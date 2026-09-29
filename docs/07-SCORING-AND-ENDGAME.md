---
doc_type: scoring_endgame
status: mixed
canonical: true
---

# Scoring, Victory, and End Game

## Core rule

### LOCKED

Victory is categorical.

Score is numerical.

A player can:

- win with a lower score;
- lose with a higher score;
- succeed at several side objectives while failing their Primary Objective.

## Personal victory

### LOCKED

A player wins if their current Primary Objective is satisfied at game end.

Multiple players can win.

A player's final victory state may differ from the public Mission outcome.

Examples:

- Mission succeeds, Player 2 still loses because their Primary required destroying the AI.
- Mission fails, Player 3 wins because their Primary required escaping with classified data.

## Score

### PROVISIONAL

Score represents accomplishments and performance.

Candidate scoring sources:

- Secondary Objectives;
- Tertiary Objectives;
- critical repairs;
- resource efficiency;
- crew rescues;
- successful investigations;
- alliance/recruitment success;
- survival/escape;
- objective difficulty;
- high-impact actions.

## Primary Objective difficulty

### PROVISIONAL

Primary Objectives will not all be equally difficult.

Do not force artificial equality.

Possible approach:

- keep victory binary/categorical;
- weight score rewards based on difficulty;
- do not claim a harder Primary means someone "won more."

## Results hierarchy

### LOCKED

The first results page should answer, in this order:

1. What happened to the public Mission?
2. Did this player win or lose?
3. Did the Primary Objective succeed?
4. Which Secondary Objectives succeeded?
5. Which Tertiary Objectives succeeded?
6. What was the player's score?
7. Where did the player place on the score leaderboard?

## Example

```text
MISSION
SHIP REACHED DESTINATION

YOUR RESULT
VICTORY

PRIMARY OBJECTIVE
✓ Ensure the ship reaches its destination

SECONDARY
✗ Keep Player 3 alive

TERTIARY
✓ Preserve the AI core
✓ Restore communications

SCORE
1,240

SCOREBOARD
2nd
```

## Scoreboard rule

### LOCKED

The scoreboard ranks score, not "who won most."

It is valid for a losing player to rank above a winning player.

## Detailed post-game page

### LOCKED CONCEPT

A deeper post-game page should reveal the hidden structure of the session.

Candidate data:

- final objectives for every participant;
- objective histories;
- accepted AI deals;
- accepted/rejected player recruitment;
- AI motive profile;
- AI integrity problems;
- AI lies;
- AI sincere errors;
- important communication failures;
- system sabotage/access history;
- deaths and escapes;
- critical ship events;
- timeline of turning points.

## Post-game quality target

Players should think:

> "Damn, it all makes sense now."

Avoid outcomes that feel like:

> "The game randomly decided we lose."
