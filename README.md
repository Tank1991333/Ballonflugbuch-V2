# Ballonflugbuch V2

Eine einfache, offline-fähige Web-App zur Erfassung und Dokumentation von Ballonfahrten.

## Funktionen

- Flüge erfassen, bearbeiten und löschen
- Automatische Berechnung der Flugdauer
- GPS-Flugaufzeichnung
- Berechnung der GPS-Strecke
- Erfassung der maximalen Höhe
- Flugbuch mit Suchfunktion
- Filterung nach Jahr
- CSV-Export für Excel
- JSON-Datensicherung
- Wiederherstellung einer JSON-Sicherung
- Druckansicht und PDF-Ausgabe
- Lokale Speicherung im Browser
- Offline-Unterstützung durch einen Service Worker

## Datenspeicherung

Die Flugdaten werden im LocalStorage des verwendeten Browsers gespeichert.

Dadurch gilt:

- Die Daten werden nicht automatisch zwischen Geräten synchronisiert.
- Die Daten sind nur im jeweils verwendeten Browser vorhanden.
- Beim Löschen der Browserdaten können die Flüge verloren gehen.
- Deshalb sollte regelmäßig eine JSON-Sicherung erstellt werden.

## GitHub Pages aktivieren

1. Repository auf GitHub öffnen.
2. Zu `Settings` wechseln.
3. Links `Pages` auswählen.
4. Unter `Build and deployment` die Option `Deploy from a branch` auswählen.
5. Als Branch `main` einstellen.
6. Als Verzeichnis `/ (root)` auswählen.
7. Auf `Save` klicken.

Die Web-App ist anschließend unter folgender Adresse erreichbar:

```text
https://DEIN-BENUTZERNAME.github.io/DEIN-REPOSITORY/
