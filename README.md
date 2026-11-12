# Imkerjahr Planer

Kleine Web-App, um die Aufgaben im Imkerjahr zu planen. Einfach `index.html` im Browser öffnen – keine Installation nötig.

## Königinnenzucht

Zuchtmethode wählen:

- **Pflegevolk** – Königin wird ca. 2 h vor dem Umlarven entnommen, dann Zuchtrahmen einsetzen
- **Anbrüter + Pflegevolk** – 24 h im weisellosen Anbrüter, danach ins Pflegevolk
- **Königin aus Volk entfernt** – Pflegevolk 9 Tage vorher entweiselt

Dann optional das **Datum der Auffuhr auf die Belegstelle** eingeben:

- **Ohne Belegstellendatum** startet der Plan heute (oder an einem gewählten Starttag). Die App zeigt, wann die Auffuhr frühestens und spätestens möglich ist.
- **Mit Belegstellendatum** zeigt die App den frühesten und spätesten Starttag mit Wochentag. Du wählst aus, wann du tatsächlich startest. Vergangene Tage sind gesperrt.

Die Auffuhr ist von Tag +13 (nach 3 Tagen Kellerhaft) bis Tag +16 nach dem Umlarven möglich (`AUFFUHR_FRUEH` / `AUFFUHR_SPAET` in `index.html`).

- Wochenenden sind farblich markiert, der heutige Termin bekommt ein «heute»-Abzeichen.
- Erledigte Aufgaben abhaken (wird im Browser gespeichert).
- Export als Kalenderdatei (`.ics`) für Handy-/Outlook-Kalender, oder ausdrucken.

Weitere Bereiche des Bienenjahres lassen sich in `index.html` im Array `MODULES` ergänzen.
