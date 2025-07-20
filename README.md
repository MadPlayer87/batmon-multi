# Batmon Multi-Instanz Add-on für Home Assistant

Dieses Repository enthält **10 unabhängige Instanzen** des Home Assistant Add-ons **Batmon**, jeweils zur parallelen Überwachung verschiedener **BMS-Geräte** per Bluetooth oder CAN.

Das Projekt basiert auf [fl4p/batmon-ha](https://github.com/fl4p/batmon-ha) und wurde von [@MadPlayer87](https://github.com/MadPlayer87) so erweitert, dass mehrere Instanzen **gleichzeitig** betrieben werden können – ideal für komplexe Installationen mit mehreren Batteriemodulen.

---

## 🔢 Add-on Instanzen

| Instanz | Slug       | WebUI Port | Beschreibung               |
|--------:|------------|------------|----------------------------|
| 1       | `batmon1`  | `8080`     | BMS Monitoring Instanz 1   |
| 2       | `batmon2`  | `8081`     | BMS Monitoring Instanz 2   |
| 3       | `batmon3`  | `8082`     | BMS Monitoring Instanz 3   |
| 4       | `batmon4`  | `8083`     | BMS Monitoring Instanz 4   |
| 5       | `batmon5`  | `8084`     | BMS Monitoring Instanz 5   |
| 6       | `batmon6`  | `8085`     | BMS Monitoring Instanz 6   |
| 7       | `batmon7`  | `8086`     | BMS Monitoring Instanz 7   |
| 8       | `batmon8`  | `8087`     | BMS Monitoring Instanz 8   |
| 9       | `batmon9`  | `8088`     | BMS Monitoring Instanz 9   |
| 10      | `batmon10` | `8089`     | BMS Monitoring Instanz 10  |

---

## 🧭 Verwendung in Home Assistant

### 1. Repository hinzufügen

In Home Assistant:
Einstellungen → Add-on Store → ⋮ (oben rechts) → Repository hinzufügen


GitHub-URL eingeben:

```text
https://github.com/MadPlayer87/batmon-multi
