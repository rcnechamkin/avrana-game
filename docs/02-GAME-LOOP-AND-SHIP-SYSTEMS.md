---
project: Avrana Game
source: https://linear.app/avranakern/document/02-game-loop-and-ship-systems-d8c923670c83
source_updated_at: 2026-09-29T01:45:58.401Z
status: MIXED
---

# Game Loop & Ship Systems

## PROVISIONAL: Round structure

Preferred direction: synchronous rounds with simultaneous action commitment.

1. **Ship Phase** — failures worsen, delayed consequences resolve, events occur.
2. **Information Phase** — each player receives their available telemetry/private information.
3. **Planning Phase** — crew discusses priorities.
4. **Action Phase** — each player commits a small number of actions.
5. **Resolution** — simultaneous actions and resource changes resolve.
6. **AI Phase** — AI acts, recommends, bargains, requests authority, or communicates.
7. **Forecast** — show the most important likely next-round consequences.

Early prototype assumptions:

* 4 players
* 8–10 rounds
* 2 actions per player per round
* 15–20 minutes
* all provisional

## LOCKED: Cooperative depth

Four loyal humans plus a cooperative AI must still have an interesting game.

Do not use deception to cover a weak ship puzzle.

## Candidate resources — PROVISIONAL

* Power
* Coolant
* Oxygen
* Hull Integrity
* Time / distance to destination
* System/Data Integrity only if it earns its place

## Candidate systems — PROVISIONAL

### Reactor

Produces power. Depends on coolant. Higher output creates risk.

### Life Support

Consumes power. Maintains oxygen.

### Propulsion / Navigation

Consumes major power. Advances Mission progress.

### Communications

Affects information and private-channel mechanics.

### Computer Core / Security

Supports authentication, authorization, logs, diagnostics, and AI control.

### Hull

Absorbs external damage. Breaches can create oxygen loss and cascades.

## LOCKED: Maintenance philosophy

Avoid:

> Spend 2 actions -> system fixed.

Prefer:

* temporary patch;
* expensive root-cause repair;
* emergency workaround;
* resource reroute;
* AI delegation;
* deliberate risk acceptance.

## Example cascade

Coolant damage -> reactor heat -> reduced reactor output -> power shortage -> communications shutdown -> information game changes.

Ship mechanics and social mechanics should affect each other.

## Candidate player verbs

* Repair
* Reroute
* Diagnose
* Authorize
* Communicate
* Investigate
* Assist
* Transfer
* Isolate
* Sacrifice
* Negotiate
* Consult AI
* Delegate to AI

## OPEN

* Whether physical movement/location exists.
* Exact shared resource count.
* Exact system count.
* Exact simultaneous-action conflict rules.
