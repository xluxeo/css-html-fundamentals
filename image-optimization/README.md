# Image Optimization

Ein einfaches Vite-Projekt in Vanilla JavaScript mit SCSS, das Bildoptimierungstechniken demonstriert.

## Inhalt

- Darstellung von `picture`-Elementen mit `srcset` und verschiedenen Breakpoints
- WebP- und JPG-Quellen für Bilder
- Lazy Loading für optimierte Ladezeit
- CSS-Modifier für Bildfokus-Positionen
- SCSS-Setup mit `sass` und `sass-mq`

## Installation

1. Node.js installieren (empfohlen: aktuelle LTS-Version)
2. Abhängigkeiten installieren:

```bash
npm install
```

## Entwicklung

Starte den lokalen Entwicklungsserver mit:

```bash
npm run dev
```

Öffne anschließend die angezeigte URL im Browser.

## Produktion

Build für die Produktion:

```bash
npm run build
```

Vorschau des Produktions-Builds:

```bash
npm run preview
```

## Projektstruktur

- `index.html` – Hauptseite mit Beispielbildern und `picture`-Elementen
- `src/main.js` – Einstiegspunkt, importiert SCSS
- `src/assets/scss/` – SCSS-Quellcode und Komponenten
- `src/assets/images/` – Beispielbilder im JPG- und WebP-Format
- `vite.config.js` – Vite-Konfiguration für SCSS mit modernem Compiler