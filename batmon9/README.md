# Batmon 9

Diese Instanz von **Batmon** überwacht ein separates BMS-Gerät über Bluetooth.

## Eigenschaften

- **Instanznummer:** 9
- **Add-on Name:** `batmon9`
- **WebUI-Port:** `http://[HOST]:8088`
- **Repository:** [MadPlayer87/batmon-multi](https://github.com/MadPlayer87/batmon-multi)

## Beschreibung

Dieses Add-on basiert auf [fl4p/batmon-ha](https://github.com/fl4p/batmon-ha) und wurde angepasst, um mehrere Instanzen parallel betreiben zu können.  
So können bis zu 10 verschiedene BMS-Geräte gleichzeitig überwacht werden.

## Hinweise

- Stelle sicher, dass jede Instanz ein **eigenes BLE-Gerät** oder Interface verwendet.
- Ports und Interfaces lassen sich in der Add-on-Konfiguration individuell anpassen.
