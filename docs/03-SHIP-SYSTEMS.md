---
doc_type: ship_systems
status: provisional
canonical: true
---

# Ship Systems and Cooperative Strategy

## Design goal

### LOCKED

The ship-maintenance layer must be a real cooperative strategy game.

Four loyal players with a cooperative AI should still face:

- scarcity;
- tradeoffs;
- cascading failures;
- uncertainty;
- timing pressure;
- non-obvious choices.

If perfect cooperation makes victory automatic, the ship game is not deep enough.

## Strategic target

### LOCKED

Aim for:

> Pandemic-level decision pressure with much lower interface friction.

This describes the desired relationship between depth and usability, not a request to copy Pandemic's mechanics.

## Candidate shared resources

### PROVISIONAL

Keep the final resource count small.

Current candidates:

- Power
- Coolant
- Oxygen
- Hull Integrity
- Time / distance-to-destination
- System/Data Integrity, only if needed

A resource should exist only if it creates meaningful tradeoffs.

## Candidate ship systems

### PROVISIONAL

### Reactor
- Produces power.
- Depends on coolant.
- High output may create heat or failure risk.

### Life Support
- Consumes power.
- Maintains oxygen.
- Failure directly threatens crew survival.

### Propulsion / Navigation
- Consumes substantial power.
- Advances the ship toward the Mission destination.

### Communications
- Supports private communication and information reliability mechanics.
- Losing power here may change the social/information layer.

### Computer Core / Security
- Supports authentication.
- Supports authorization.
- Supports diagnostics and logs.
- May mediate AI control.

### Hull
- Absorbs external damage.
- Breaches may reduce oxygen or damage other systems.

## System-state philosophy

### LOCKED

A broken system should rarely mean:

> Spend 2 actions -> fixed.

Prefer:

- causes;
- symptoms;
- temporary patches;
- permanent repairs;
- emergency workarounds;
- resource tradeoffs;
- downstream effects.

## Example reactor problem

### EXAMPLE

State:

- Reactor output: 62%
- Coolant loop: damaged
- Temperature: rising

Possible responses:

1. Reduce reactor output
   - safer;
   - creates power shortage.

2. Repair coolant loop
   - expensive;
   - fixes underlying cause.

3. Emergency vent
   - stops immediate overheating;
   - permanently loses coolant.

4. Authorize AI regulation
   - saves player actions;
   - gives AI additional system authority.

5. Ignore it
   - risky;
   - may be rational under greater pressure elsewhere.

## Cascading systems

### LOCKED

Ship systems should interact.

Example chain:

`Coolant damage -> reactor heat -> reduced reactor output -> power shortage -> comms shutdown -> information game changes`

This coupling is valuable because ship maintenance and social mechanics become one game instead of parallel minigames.

## Pressure

### PROVISIONAL

Candidate pressure sources:

- finite rounds;
- worsening failures;
- external events;
- shared resource scarcity;
- mission progress requirements;
- crew injury/death/isolation;
- AI actions;
- loss of access or permissions.

## Event design

### LOCKED

Events should preferably create decisions.

Weak:

> Lose 2 Hull.

Better:

> Hull breach.  
> Seal Deck 4 now and remove Player 3's Engineering access, or lose 2 Oxygen each round until repaired.

## Player specialties

### PROVISIONAL

Soft specialties may reduce option overload and create natural cooperation.

Candidates:

- Engineer
- Security
- Navigator
- Medical / Life Support specialist

Do not assume rigid RPG classes are required.

## Player location

### OPEN

It is not yet decided whether players have physical positions on a ship map.

Do not add movement until it proves mechanically necessary.
