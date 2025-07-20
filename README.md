# Batmon Multi-Instanz Add-on

Dieses Repository enthält **10 getrennte Instanzen** des Home Assistant Add-ons **Batmon**, jeweils zur parallelen Überwachung verschiedener BMS-Geräte per Bluetooth oder CAN.

## Add-on Instanzen

| Instanz | Slug      | WebUI Port | Beschreibung                     |
|---------|-----------|------------|----------------------------------|
| 1       | `batmon1` | `8080`     | BMS Monitoring Instanz 1
| 2       | `batmon2` | `8081`     | BMS Monitoring Instanz 2
| 3       | `batmon3` | `8082`     | BMS Monitoring Instanz 3
| 4       | `batmon4` | `8083`     | BMS Monitoring Instanz 4
| 5       | `batmon5` | `8084`     | BMS Monitoring Instanz 5
| 6       | `batmon6` | `8085`     | BMS Monitoring Instanz 6
| 7       | `batmon7` | `8086`     | BMS Monitoring Instanz 7
| 8       | `batmon8` | `8087`     | BMS Monitoring Instanz 8
| 9       | `batmon9` | `8088`     | BMS Monitoring Instanz 9
| 10       | `batmon10` | `8089`     | BMS Monitoring Instanz 10

## Verwendung

1. Repository in Home Assistant hinzufügen:
   - Einstellungen → Add-on Store → Drei Punkte (⋮) → Repository hinzufügen
   - Gib die GitHub-URL dieses Repos ein.

2. Installiere eine oder mehrere `batmonX` Instanzen.

3. Konfiguriere jede Instanz individuell (BLE-Adresse, MQTT-Ziel, Port etc.).

## Hinweise

- Jede Instanz nutzt denselben Code, aber unterschiedliche `slug` und Ports.
- Stelle sicher, dass Geräteadressen oder Interfaces **pro Instanz getrennt** sind.
