# Gabicce Mare – Reiseführer v0.6

Alle Dateien und Ordner ins Root des GitHub-Pages-Repositories laden.

## Neue Bilddateien
Sieben vom Benutzer bereitgestellte Restaurantfotos sind in `assets/photos/*.jpg` gespeichert und werden von den Restaurantkarten direkt geladen. Keine Screenshot-Dienste mehr für diese Karten.

**Noch offen:** Hotel-Hero und Hotelkarten (Originalfotos fehlen), Sonntag-Hero Gradara (konkretes Foto fehlt). Diese Stellen sind bewusst als gestaltete Platzhalter markiert und nicht durch erfundene Aufnahmen ersetzt. Samstag und übrige Tages-Heros nutzen noch die bisherigen externen Atmosphärenfotos.

## Technik
Sonntags-Höhenprofil: im HTML eingebettete GPX-Werte als SVG, funktioniert ohne Netzwerk. Streckenkarte: Leaflet und OSM benötigen Internet. Wetter: Open-Meteo benötigt Internet.

Sitz- und Fahrradplätze bleiben, Buchungscodes sind nicht enthalten.
