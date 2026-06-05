# SCSS-Funktionen Projekt

Dieses Projekt ist ein kleines Vite-basierendes Frontend-Setup mit SCSS-Struktur. Es dient als Übung für SCSS-Mixins, Utility-Generierung, Z-Index-Funktionen und responsive Breakpoints.

## Projektstruktur

- `index.html` - Einstiegspunkt der Anwendung
- `package.json` - Projektabhängigkeiten und Skripte
- `vite.config.js` - Vite-Konfiguration
- `src/main.js` - JavaScript-Einstiegspunkt
- `src/assets/scss/` - SCSS-Ordner mit modularem Aufbau
  - `01-tokens/` - Farb-, Abstand- und Layer-Variablen
  - `02-tools/` - SCSS-Mixins und Utilities
  - `03-generic/` - generelle Styles
  - `04-elements/` - Element-Styles
  - `05-objects/` - Objekt-Stilklassen
  - `06-components/` - Komponenten-Stile (Buttons, Tooltipps, Container)
  - `07-utilities/` - Utility-Klassen (z. B. Abstände)

## Installation

1. Installiere die Abhängigkeiten:

```bash
npm install
```

2. Starte den Entwicklungsserver:

```bash
npm run dev
```

3. Öffne die angezeigte lokale Adresse im Browser.

## Aufgaben und SCSS-Ziele

Im Projekt sollen folgende SCSS-Funktionen umgesetzt werden:

1. **Button-Mixin**
   - Ein Mixin namens `BUTTON`
   - gibt Schriftfarbe und Hintergrundfarbe zurück
   - unterstützt `size` als `small` oder `large`
   - unterstützt `border` als `true` oder `false`
   - wird in einer Button-Komponente eingebunden

2. **Z-Layer-Funktion**
   - Funktion nimmt eine Map mit Z-Index-Werten entgegen
   - gibt den passenden Z-Index-Wert zurück

3. **Utility für Spacings**
   - Loopt über ein Objekt mit Abständen
   - erzeugt Klassen wie `u-mt-l` automatisch
   - nutzt `@each` und String-Verkürzung

4. **Tooltip-Mixin**
   - Tooltip kann oben, rechts, unten oder links positioniert werden

5. **Breakpoints**
   - SCSS-Mixin mit mindestens drei Breakpoints:
     - Desktop > 1025px
     - Tablet < 1024px
     - Mobil < 720px
   - Verwendung von `map`, `@each` und `@if`


## Build

Für eine Produktionserstellung:

```bash
npm run build
```

Für eine Vorschau des Builds:

```bash
npm run preview
```
