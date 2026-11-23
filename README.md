# Flipper Fernbedienung

Die Fernbedienungs-Seite für das Flipper-WLAN-Modul („Flipper WLAN-Remote“) – für den
**Fernzugriff übers Internet**. Unterwegs kann das Handy die Seite nicht vom Modul laden,
deshalb liegt sie hier (GitHub Pages).

- `index.html` ist dieselbe Datei wie im Modul (Firmware 1.25.0). Sie erkennt selbst, dass sie
  aus dem Internet kommt, und verbindet sich dann über den MQTT-Vermittler mit dem Modul –
  Ende-zu-Ende verschlüsselt.
- Hier liegt **kein Schlüssel**. Den bekommt nur das eigene Handy über den Kopplungslink
  (⚙️ → Fernzugriff übers Internet → Kopplungslink erzeugen). Der Teil hinter `#` wird nie an
  GitHub geschickt.
- Nach einem Firmware-Update `index.html` hier durch die neue Fassung ersetzen.
