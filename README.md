# Imkerjahr Planer

Kleine Web-App, um die Aufgaben im Imkerjahr zu planen. Einfach `index.html` im Browser öffnen – keine Installation nötig.

## Königinnenzucht

Zuchtmethode wählen:

- **Pflegevolk** – Königin wird ca. 2 h vor dem Umlarven entnommen, dann Zuchtrahmen einsetzen
- **Anbrüter + Pflegevolk** – 24 h im weisellosen Anbrüter, danach ins Pflegevolk
- **Königin aus Volk entfernt** – Pflegevolk 9 Tage vorher entweiselt

Dann Datum eingeben und auswählen, für welchen Arbeitsschritt es gilt (Standard: Umlarven = Tag 0).
Die App berechnet für jede Aufgabe Datum und Wochentag.

- Wochenenden sind farblich markiert, der heutige Termin bekommt ein «heute»-Abzeichen.
- Erledigte Aufgaben abhaken (wird im Browser gespeichert).
- Export als Kalenderdatei (`.ics`) für Handy-/Outlook-Kalender, oder ausdrucken.

Weitere Bereiche des Bienenjahres lassen sich in `index.html` im Array `MODULES` ergänzen.
