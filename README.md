# CS4 Robotic Arm Fault Detection

**Status: planning and setup. No hardware, firmware, tests, or purchases are asserted complete.**

## Goal
Build a robotic arm as a machine under test and identify abnormal operating conditions from sensor measurements. The **first engineering milestone** is one safely operated motor/joint, vibration and temperature readings, and basic computer-side telemetry. Do not start with the whole arm or an ML model.

## Team
- **Nana:** software/electrical integration lead (VS Code + Codex).
- **Tiago:** CAD, mechanical assembly and physical hardware lead (VS Code + Claude Code); software integration work to be assigned by issue.
- Other teammates are not confirmed in Nana's November 6 master handoff.

## Working agreements
- GitHub is the approved code, decisions and interface source of truth.
- `docs/` is the planned Obsidian notes vault. Pull before editing; commit and push after editing.
- Each task gets one owner, acceptance criteria and evidence of tests.
- Read `AGENTS.md`, `CLAUDE.md`, `docs/02_AI_CONTEXT.md`, `docs/03_DECISIONS.md`, and `docs/04_INTERFACES.md`.
- **Caution:** The two uploaded handoffs disagree on motors: Nana's master handoff proposes NEMA 17 steppers/TMC2209; an earlier conversation summary describes an all-servo EEZYbotARM MK2. Neither is independently reconfirmed as the final selection. Do not commit hardware-specific implementation until Nana and Tiago resolve this.

## Repository layout
`docs/` notes and decisions; `firmware/` ESP32; `backend/` Python; `dashboard/` UI; `hardware/` CAD and electrical records; `tests/` test plans and test code; `data/` tiny illustrative data only.

## First steps (proposed, not done)
1. Confirm Tiago's access, printer, motor choice and physical stop review.
2. Agree on a telemetry schema and module ownership.
3. Make mock sensor packets run through Python validation/logging/dashboard (no powered hardware needed).
4. Plan first powered test **only after** electrical and physical stop review with teacher/qualified supervisor.

## Sources
November 6, 2026: `CS4_Robotic_Arm_Master_Handoff.pdf` and `PROJECT_INSTRUCTIONS_FOR_CHATGPT.txt` (provided to shared ChatGPT Project). Three original technical documents are referenced in the handoff but not bundled here. This starter is a newly constructed template, **not the original 27-file ZIP**.
