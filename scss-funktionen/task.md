Aufgaben:

1. SCSS Mixin: (Unter tools in mixins.scss)

- Schreibe ein Mixin Namens BUTTON
- das Mixin gibt dir eine Schriftfarbe zurück
- das Mixin gibt dir eine Hintergrundfarbe zurück
- gib eine Size zurück (padding): small oder large
- der Button kann eine Border haben: true oder false
- binde das Mixin an einer Button Komponente ein

2. Z-Layer Funktion: (Unter tools in mixins.scss)

- Lass dir eine Map mit den unterschiedlichen z-index Werten in eine Funktion übergeben
- Die Funktion gibt den Value des Z-Index zurück

3. Utility für Spacings: (Unter utilities in u-spacings.scss)

- Schreibe ein Loop für Spacings. Klassen sollten wie folgt aussehen: u-mt-l (margin-top: large value).
- die Variablen deiner Spacings sollte in einem Objekt geschrieben sein
- loope über dieses Objhekt und lass dir die Keys und Values zurück geben.
- Tipp: Kürze ein String - https://sass-lang.com/documentation/modules/string/#slice
- deine Utilitys sollten durch die Loop Methode automatisch erzeugt werden

4. Mixin für einen Tooltip: (Unter tools in mixins.scss)

- ein Tooltip kann oben, rechts, unten, links positioniert werden.

5. Breakpoints: (Unter tools in mixins.scss)

- Schreibe ein Mixin in SCSS welches mindestens drei Breakpoint Punkte berücksichtigt:
  Desktop > 1025px
  Tablet < 1024px
  Mobil < 720px
- nutze map & mixin, @each, @if
