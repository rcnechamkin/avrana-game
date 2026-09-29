---
doc_type: gameplay_loop
status: provisional
canonical: true
---

# Core Game Loop

## Current direction

### PROVISIONAL

Use synchronous, round-based play with simultaneous action commitment.

Conventional one-player-at-a-time turns are currently disfavored because they:

- create downtime;
- reduce the crisis-management feel;
- make private choices easier to socially audit before resolution;
- feel more like a board game turn structure than a crew responding together.

## Round structure

### PROVISIONAL

1. **Ship Phase**
   - Existing failures worsen.
   - Previous delayed consequences resolve.
   - External events may occur.

2. **Information Phase**
   - Each player receives their available telemetry.
   - Private messages, warnings, objective updates, or AI contact may arrive.
   - Information can differ between players.

3. **Planning Phase**
   - Crew discusses priorities.
   - In-person players may speak freely.
   - Remote mode may route communication through the game.

4. **Action Phase**
   - Each player selects a small number of actions.
   - Current prototype assumption: 2 actions per player per round.

5. **Resolution Phase**
   - Avrana resolves simultaneous actions.
   - Resource changes occur.
   - Conflicts, cooperation, and cascading consequences are applied.

6. **AI Phase**
   - AI may act on systems it controls.
   - AI may communicate, bargain, recommend, warn, recruit, conceal, or deceive according to its current rules and motives.

7. **Forecast Phase**
   - The most important likely next-round consequences are shown.

## Target session shape

### PROVISIONAL

- 4 players for the first prototype.
- 8 to 10 rounds.
- 2 actions per player per round.
- 15 to 20 minutes for the earliest test.
- These values must be tuned through playtesting.

## Core player verbs

### PROVISIONAL

- Repair
- Reroute
- Diagnose
- Authorize
- Communicate
- Investigate
- Assist
- Transfer
- Isolate
- Sacrifice
- Negotiate
- Consult AI
- Delegate to AI

## Action design rules

### LOCKED

Actions should present understandable tradeoffs.

Prefer:

> Increase Reactor Output  
> +3 Power next round  
> Reactor temperature rises significantly  
> Coolant failure risk increases

Avoid requiring players to understand hidden arithmetic before acting.

## Simultaneous-action design opportunity

### PROVISIONAL

Multiple players may:

- unknowingly target the same system;
- coordinate a stronger joint action;
- waste actions through duplication;
- interfere with one another;
- create conflicts that the server resolves authoritatively.

Exact resolution rules are still open.
