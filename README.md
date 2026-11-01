# Kultur am Wegesrand

Ein einzelner HTML-Prototyp, um Kulturorte in der Umgebung eines Kartenpunkts zu entdecken.

## Online öffnen

Die App wird über GitHub Pages veröffentlicht:
https://henningralf.github.io/kultur-am-wegesrand/

Jeder Push auf `main` aktualisiert die Seite nach etwa einer Minute.

## Lokal starten

Öffne `index.html` in einem aktuellen Browser. Für Karte, Suche und Ergebnisdaten ist eine Internetverbindung erforderlich.

## Datenquellen

- QLever für die primäre Wikidata-Umkreissuche
- Wikidata Query Service als Fallback, wenn eine QLever-Abfrage fehlschlägt
- Photon für die Orts- und Adresssuche
- OpenStreetMap für die Kartenkacheln

Die öffentlichen Dienste können zeitweise ausfallen und haben eigene Nutzungsgrenzen. Der Prototyp benötigt keine API-Schlüssel und keinen Build-Schritt.
