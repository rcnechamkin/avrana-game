---
doc_type: open_questions
status: open
canonical: true
---

# Open Design Questions

These are unresolved. Agents should not silently invent answers and then treat them as canonical.

## Core loop

- What is the ideal final session length?
- Are 8 to 10 rounds correct?
- Are 2 actions per player correct?
- How long should the planning phase be?
- Should some actions resolve immediately while others resolve at round end?

## Ship systems

- Exact number of shared resources?
- Exact core systems?
- Does System/Data Integrity need to exist as a resource?
- How severe should cascading failures become?
- How much randomness should external events contain?
- Are there positive events or only crises?
- Does physical location on the ship matter?
- Is there ever a map?

## Simultaneous actions

- What happens when two players repair the same system?
- Can combined actions produce a stronger result?
- Can actions conflict?
- Should actions be editable until the phase ends?
- Can some actions be visible before resolution?

## Specialties

- Are specialties permanent?
- Are they unique?
- Can players gain or lose capabilities?
- Do specialties create enough cooperation without creating hard-role dependency?

## AI

- How are AI motives represented mechanically?
- Are AI motive weights selected from authored templates or generated?
- Can motives change mid-game?
- How visible is AI integrity?
- Can the AI knowingly lie in Standard mode?
- What limits AI deception?
- Does the AI have a resource/budget for intervention?
- Can players permanently destroy or isolate the AI?
- How much control can be delegated to it?

## Information and investigation

- Is there a dedicated flight recorder / black box system?
- What can it verify?
- What does an audit query cost?
- How are logs repaired or destroyed?
- What evidence remains trustworthy under severe system compromise?
- How many communication-security concepts belong in first-release Standard play?

## Objectives

- How often should a divergent Primary Objective exist at setup?
- What is the maximum number of divergent humans in a four-player game?
- How often can Primary Objectives change?
- Can a player hold multiple mandatory Primary conditions?
- When does adding conditions become too cognitively heavy?
- How are impossible objectives detected and avoided?
- How are objective difficulty values assigned?

## Social systems

- How is formal player recruitment initiated?
- Does recruitment consume an action?
- Can a player recruit more than once?
- Does rejection remain secret?
- Should false acceptance exist?
- Can AI or players expose prior offers?
- Can alliances expire?

## Death / escape

- What does a dead player do?
- Can a dead player still win?
- Does death end active play or transition to a new role?
- When do escape pods become available?
- Can escaped players continue interacting?
- Can a player leave before the public Mission is resolved?

## Scoring

- Which actions generate score?
- Should score reward team contribution if the player's Primary was anti-team?
- How should goal difficulty weighting work?
- Can score be gamed by low-value repetitive actions?
- Should score be visible during play or only afterward?

## Interface

- How much ship state should every player see?
- How much should be role-specific?
- How should consequence forecasting be presented?
- How should the UI explain security concepts without jargon?
- How much post-game data is useful before it becomes forensic soup?

## Implementation

- Should AI behavior be fully deterministic/rule-driven for MVP?
- Does any generative model belong in runtime gameplay?
- What state must be authoritative server-side?
- What state can remain client-local?
- How should session replay / post-game reconstruction be stored?
- How should a game seed work for reproducible testing?
