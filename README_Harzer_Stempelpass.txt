Harzer Stempelpass – Prototyp mit GPS-Kartenmarkern

Dateien:
- harzer_stempelpass.html: App-Oberfläche und Funktionen
- manifest.json: Metadaten für Installation als Web-App

Enthalten:
- 222 reguläre Stempelstellen
- Suche nach Nummer, Name und Ort
- Erledigt/offen, Favoriten, Fortschrittsanzeige
- lokal gespeicherter Fortschritt (localStorage)
- Sonderstempel manuell hinzufügen, abhaken und löschen
- Export/Import der persönlichen Sammlung
- OpenStreetMap-Karte mit GPS-Markern für reguläre Stempelstellen
- Standortfreigabe und Navigation über Apple Karten/Google Maps
- GPS-Daten werden beim Öffnen der Karte aus einer öffentlich verfügbaren GPX-Sammlung geladen und lokal gespeichert; alternativ ist GPX-Import möglich

GPS-Quelle:
https://github.com/MichaelRoeder/hwn (hwn.gpx; Datenstand der veröffentlichten HWN-GPS-Daten: 23.04.2025)
Offizielle GPS-Seite:
https://www.harzer-wandernadel.de/stempelstellen/gps-download/

Hinweise:
- Die offizielle Website weist darauf hin, dass GPS-Koordinaten abweichen können. Bitte beim Wandern zusätzlich auf Wegweiser und Karten achten.
- Wenn der automatische Download auf dem iPhone nicht funktioniert, auf der GPS-Seite die GPX-Datei laden und in der Kartenansicht der App über „GPX importieren“ auswählen.
- Für „Zum Home-Bildschirm“ müssen HTML-Datei und manifest.json gemeinsam auf einer HTTPS-Webadresse gehostet werden. Der Download allein veröffentlicht die App nicht.
- Sonderstempel werden vorerst manuell gepflegt; die offizielle Sonderstempelliste ist noch nicht vollständig eingebaut.
