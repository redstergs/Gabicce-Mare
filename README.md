# Gabicce Mare – persönlicher Reiseführer (v0.1)

Statische Webseite für GitHub Pages, ohne Build-Prozess.

## Veröffentlichung
1. Neues öffentliches GitHub-Repository anlegen, z. B. `gabicce-reise`.
2. Den **Inhalt dieses Ordners** (index.html, styles.css, app.js, assets/) in das Repository-Root hochladen.
3. In **Settings → Pages → Build and deployment**: `Deploy from a branch`, Branch `main`, Ordner `/ (root)` wählen.
4. Die veröffentlichte Adresse steht danach unter Settings → Pages.

## Lokal testen
Im Ordner `python -m http.server 8000` starten und `http://localhost:8000` öffnen. Direktes Öffnen von index.html per `file://` blockiert je nach Browser das Laden der GPX-Daten.

## Hinweise
- Kartenkacheln und Leaflet werden über das Internet geladen.
- Wetterdaten werden live von Open-Meteo abgefragt; bei noch nicht verfügbarer Prognose erscheint ein entsprechender Hinweis.
- Das Headerbild ist eine eigens per CSS gestaltete Küstenillustration und kein Foto eines konkreten Ortes.
- Montag und Dienstag sind noch nicht vollständig redaktionell ausgearbeitet.
- Die Seite enthält Buchungscodes: Ein öffentliches GitHub-Pages-Repository ist **nicht privat**. Vor dem Teilen der URL oder Hochladen in ein öffentliches Repository Buchungscodes aus `index.html` entfernen, wenn diese nicht öffentlich sein sollen.
