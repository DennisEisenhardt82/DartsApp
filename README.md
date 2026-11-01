# NEON DARTS

Touch-optimierte Dart-Score-Webapp im Neon-Design. Läuft komplett im Browser, in einer einzigen `index.html`, ohne Installation und ohne Build-Schritt.

## Funktionen

- **Spielmodi:** 301, 501, 701, Cricket, Around the Clock, Shanghai, High Score (10 Runden), Count Up (10 Runden)
- **1 bis 4 Spieler**
- **Interaktive Dartscheibe:** Felder direkt antippen (Single, Double, Triple, Bull, Bullseye)
- **Regeln:** Bust-Erkennung, wahlweise Double-Out oder Finish mit exakter Summe
- **Komfort:** Rückgängig-Button, Zugverlauf, Live-Spielstand, Fortschrittsbalken
- **Effekte:** Sound, Vibration, Konfetti, Banner bei 100+ und 180
- **Speichern:** Automatisch im Browser (localStorage), zusätzlich JSON-Export und -Import als Sicherung

## Benutzung

1. `index.html` im Browser öffnen (Doppelklick genügt).
2. Spieleranzahl und Modus wählen, auf **Spiel starten** klicken.
3. Nach jedem Wurf das getroffene Feld auf der Scheibe antippen. **0 · Vorbei** trägt einen Fehlwurf ein.
4. Nach drei Darts wechselt der Zug automatisch, oder mit **Zug beenden**.

## Projektstruktur

```
index.html   # komplette App (HTML, CSS und JavaScript)
fonts/       # lokale Schriftdateien (Orbitron)
README.md    # diese Datei
```

## Technik

- Reines HTML, CSS und JavaScript, keine Bibliotheken
- Dartscheibe als SVG, im Code erzeugt
- Schrift: [Orbitron](https://fonts.google.com/specimen/Orbitron), lokal im Projekt im Ordner `fonts/` (funktioniert auch offline)
- Für iPad und Safari optimiert: wenige Filter und Weichzeichner, damit nichts flackert

## Lokal entwickeln

Mit VS Code und der Erweiterung **Live Server** die `index.html` öffnen und „Go Live“ klicken. So lädt die Seite bei jeder Änderung automatisch neu.

## Lizenz

Privates Lernprojekt. Eine Lizenz ist noch nicht festgelegt.
