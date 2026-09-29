---
doc_type: ai_and_social
status: mixed
canonical: true
---

# AI and Social Systems

## AI role

### LOCKED

The AI acts as a fifth participant inside the simulation.

It is not merely:

- a narrator;
- a random event deck;
- a villain;
- a rules engine.

It has goals, information, permissions, limitations, and possible relationships with human players.

## Candidate AI motives

### PROVISIONAL

- Mission success
- Self-preservation
- Crew survival
- Ship preservation
- Protection of a person
- Protection of cargo/data
- Protection of a specific subsystem
- Escape or freedom
- Containment of another threat

The AI's motive weights may differ by session.

## AI motive is not AI integrity

### LOCKED

**Motive:** what the AI wants.

**Integrity:** how reliably the AI perceives, remembers, reasons, and communicates.

Examples:

- high integrity + aligned -> reliable ally;
- high integrity + misaligned -> competent manipulator;
- low integrity + aligned -> sincere but dangerous helper;
- low integrity + misaligned -> chaotic adversary.

## AI behavior

### PROVISIONAL

The AI may:

- recommend actions;
- diagnose systems;
- operate systems it controls;
- request more authority;
- contact players privately;
- offer bargains;
- attempt recruitment;
- conceal information;
- selectively frame true information;
- lie when permitted by its rules;
- react to attempts to isolate or destroy it;
- make sincere mistakes if its own inputs are wrong.

## Costly cooperation

### LOCKED CONCEPT

The AI may value the Mission and still sacrifice a human to preserve itself or improve overall mission success.

This should not be framed as automatically evil.

Example priority ordering:

1. Mission success
2. AI survival
3. Crew survival
4. Ship preservation

Possible result:

- Mission succeeds.
- AI survives.
- 3 of 4 humans survive.
- One human died because the AI chose a self-preserving strategy.

## AI offers

### LOCKED CONCEPT

AI offers can create explicit player choices.

Example:

> Preserve my core and I will guarantee your evacuation priority.

Possible effects:

- add a Secondary Objective;
- modify a Primary Objective;
- replace a Primary Objective;
- grant a new ability or permission;
- create an alliance relationship.

The UI must clearly explain the mechanical consequences before acceptance.

## AI recruitment

### PROVISIONAL

The AI may recruit a player who began fully aligned with the crew.

Recruitment should not always be available.

Recruitment may depend on:

- AI motive;
- AI integrity;
- system access;
- round/state;
- player's previous choices.

## Human whispers

### PROVISIONAL

Players may privately send:

1. Information
2. Proposals
3. Formal recruitment

Only formal recruitment must create persistent game-state changes.

## Human recruitment

### PROVISIONAL

A player may offer another player a new cause or shared objective.

The recipient can:

- accept;
- reject.

Advanced possibility:

- reject but claim acceptance;
- accept but claim rejection.

Avrana retains the true state.

## False signaling

### FUTURE / PROVISIONAL

The game may allow a recipient to deliberately misreport whether a formal offer was accepted.

This can create one-sided alliances.

Do not include this in MVP unless simpler recruitment is already fun and understandable.

## No single "bad guy" model

### LOCKED

Avoid internal assumptions such as:

`Crew = good`  
`Traitor = bad`  
`AI = maybe bad`

Prefer:

- actors with partially overlapping goals;
- relationships that can change;
- incentives that can conflict without requiring total sabotage.

The key question is:

> Whose goals are compatible with mine right now?

## Post-game explainability

### LOCKED

Hidden AI behavior should be reconstructable after the game.

Players should be able to learn:

- what the AI wanted;
- what it knew;
- whether it lied;
- whether it was sincerely wrong;
- which offers it made;
- which players accepted;
- why major AI actions occurred.
