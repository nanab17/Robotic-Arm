# Decision Log
Entries marked **PROPOSED** are not accepted engineering decisions.

| Date | Topic | Status | Decision / next owner |
|---|---|---|---|
| 2026-11-06 | Goal | DOCUMENTED | Fault detection on a robotic arm; first milestone one joint |
| 2026-11-06 | Collaboration stack | PREFERRED PLAN | Shared ChatGPT, GitHub, Git-backed Obsidian, VS Code + Codex/Claude Code; installations not verified |
| 2026-11-06 | Motor/arm platform | OPEN CONFLICT | NEMA 17 stepper in Nana handoff vs all-servo MK2 in other handoff; Nana and Tiago to confirm |
| 2026-11-06 | Communications | OPEN | WebSockets vs MQTT |
| 2026-11-06 | ADXL345 interface | OPEN | I2C for basic checkout vs SPI for high-rate acquisition |
| 2026-11-06 | Hardware safety | OPEN, REQUIRED BEFORE POWER | Qualified review of independently effective physical stop and power arrangement |
| 2026-11-06 | Telemetry format | PROPOSED | See 04_INTERFACES.md; do not code as if frozen |

For a new decision, record: date, options, who approved, evidence, affected files, verification test.
