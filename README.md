# Chanel & Armani – Aufhängen ab Level 3 behoben

Ursachen und Korrekturen:
- Regen und Schnee erzeugten vorher pro Bild mehrere Partikel. Dadurch entstanden auf iPhone/iPad teilweise mehr als 1.000 Wetterobjekte.
- Wetterpartikel sind jetzt begrenzt und werden zeitgesteuert erzeugt.
- Level 3 zeichnet auf kleinen Geräten weniger Hintergrundobjekte.
- Das zweite Bonusspiel erzeugt beim Ziehen keine endlose Folge von Skalierungs-Timern mehr.
- Der Übergang von Level 3 zum Bonusspiel kann nur noch einmal ausgelöst werden.
- Die Bonus-Spielfläche wird stabil und nur bei Bedarf neu skaliert.

Geprüft:
- JavaScript-Syntax
- Level-3-Zielbedingung
- Übergang zum zweiten Bonusspiel
- Übergang vom Bonusspiel zu Level 4
