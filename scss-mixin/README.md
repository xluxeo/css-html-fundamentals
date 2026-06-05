# SCSS Mixins — Beispielprojekt

Kurzbeschreibung:

Dieses kleine Projekt zeigt SCSS-Mixins für Flexbox und Breakpoints.

Schnellstart:

- Abhängigkeiten installieren:

```bash
npm install
```

- Dev-Server starten (Vite):

```bash
npm run dev
```

SCSS-Struktur

- Mixins befinden sich in: [src/assets/scss/02-tools/_mixins.scss](src/assets/scss/02-tools/_mixins.scss#L1)
- Tokens (Breakpoints etc.) in: [src/assets/scss/01-tokens/_breakpoints.scss](src/assets/scss/01-tokens/_breakpoints.scss#L1)
- Die `02-tools/index.scss` forwardet die Mixins, daher kannst du sie per `@use` einbinden.

Wie Mixins einbinden

Beispiel 1 — namespaced `@use`:

```scss
@use "02-tools" as tools;

.my-flex {
  @include tools.flexbox(row, true, wrap);
}
```

Beispiel 2 — global import (kein Namespace):

```scss
@use "02-tools" as *;

.my-flex {
  @include flexbox(column, false, nowrap);
}
```

Breakpoint-Mixin verwenden

```scss
.my-box {
  width: 100%;

  @include breakpoints('m') {
    width: 50%;
  }
}
```