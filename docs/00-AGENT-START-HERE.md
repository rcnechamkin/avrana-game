---
doc_type: agent_entrypoint
project: avrana-game
status: discovery
canonical: true
version: 0.1
updated: 2026-09-28
---

# Agent Start Here

## Purpose

This folder captures the current design state for Avrana Game, developed as an independent game project.

The working project name is **Avrana Game**; the final game title remains open.

Agents should treat these files as a **working design contract**, not as a finished specification.

## Standalone scope

Treat the runtime as an authoritative multiplayer game server plus private phone/browser clients. Pi hardware, Party Home, appliance networking, captive portals, .avrgame packaging, and device deployment are not prerequisites. Avrana Party may consume the proven game through a later integration.

Read [REPO-NOTES.md](REPO-NOTES.md) for provenance and unresolved source status ambiguity. Read 10-DECISION-REGISTER.md after the ordered topic docs.

## Core premise

A phone-native cooperative starship crisis game where:

- the ship-maintenance game is strategically meaningful on its own;
- all players use private phone screens;
- players make decisions under incomplete or asymmetric information;
- an AI acts as a fifth participant with its own motives, limits, bargains, and possible deceptions;
- human Primary Objectives may sometimes diverge from the public Mission;
- players may consciously change alignment or objectives during play;
- some sessions may contain no hostile humans at all;
- victory and score are separate concepts.

## Read order

1. `01-DESIGN-CONTRACT.md`
2. `02-GAME-LOOP.md`
3. `03-SHIP-SYSTEMS.md`
4. `04-MISSION-AND-OBJECTIVES.md`
5. `05-AI-AND-SOCIAL-SYSTEMS.md`
6. `06-COMMS-TRUST-AND-DECEPTION.md`
7. `07-SCORING-AND-ENDGAME.md`
8. `08-MVP-ROADMAP.md`
9. `09-OPEN-QUESTIONS.md`

## Agent behavior rules

When proposing implementation or design changes:

- Preserve all `LOCKED` decisions unless explicitly asked to revisit them.
- Treat `PROVISIONAL` decisions as current direction, not permanent truth.
- Treat `OPEN` items as unresolved.
- Prefer the smallest playable experiment that tests one uncertain assumption.
- Do not add systems merely because they are thematically appropriate.
- New mechanics should create meaningful player decisions.
- The cooperative ship game must remain interesting without betrayal.
- Do not assume a human traitor exists in every session.
- Do not make in-person play depend on players being forbidden to speak.
- Do not convert technical concepts into jargon-heavy player UI.
- Do not make the AI omniscient by default.
- Do not let points override whether a player's Primary Objective succeeded.

## Design shorthand

**Deep state, shallow interface.**

The simulation may be complex internally, but the player should usually face a small number of legible choices with understandable consequences.

**Uncertainty should be investigable, not arbitrary.**

Players can lack certainty, but should have actions, evidence, redundancy, logs, repairs, or other means to improve confidence.

**The ship game comes first.**

Do not use hidden motives, deception, AI behavior, or social deduction to rescue a weak cooperative resource-management loop.
