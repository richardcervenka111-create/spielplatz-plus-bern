# Spielplatz plus

Die Stadt kennt ihre Spielplätze. Eltern brauchen aber die Kombination: Spielplatz, Wasser, WC. Diese Karte rechnet die Distanzen aus drei Datensätzen vor.

Live: **https://richardcervenka111-create.github.io/spielplatz-plus-bern/**

Zwei Sprachen (DE/EN), „nächster Punkt“ mit Fussroute, kein Tracking, Standort bleibt im Gerät.

## Daten

Spielplätze der Stadt Bern aus OpenStreetMap (leisure=playground, Mittelpunkte der Flächen), je mit Luftlinien-Distanz zum nächsten Trinkbrunnen (drinking_water=yes) und zum nächsten WC aus denselben OSM-Daten. Distanzen sind Luftlinie, der Fussweg ist länger.

`data.js`: 372 Punkte, OpenStreetMap-Stand 2026-07-15T15:22:01Z, gebaut am 2026-09-25 mit `_tools/make_map_app.py` (Overpass API, Bounding Box Stadt Bern 46.90–46.99 / 7.37–7.50). Lizenz ODbL, © OpenStreetMap-Beitragende. Karte: OSM-Kacheln, Leaflet 1.9.4 (cdnjs, mit Integritätsprüfung).

## Ehrlich gesagt

OpenStreetMap ist so gut wie die Leute, die es pflegen. Fehlt ein Punkt oder stimmt ein Detail nicht: in OpenStreetMap korrigieren, davon haben alle etwas. Diese Seite ersetzt keine offizielle Auskunft der Stadt.

## Lokal

`index.html` im Browser öffnen. Kein Build.

## Lizenz

Code MIT. Daten ODbL (OpenStreetMap).
