---
doc_type: design_contract
status: discovery
canonical: true
---

# Design Contract

## 1. Product identity

### LOCKED

- The game is Avrana Game, an independent first-party Avrana game.
- It is designed around private phone screens.
- The server owns authoritative game state.
- Design, prototyping, balancing, and testing do not depend on the Avrana Party device/appliance, Pi, Party Home, captive portals, appliance networking, .avrgame packaging, or device deployment.
- It should feel native to Avrana, not like a physical board game merely rendered on phones.
- It should support in-person play.
- A remote/text-only communication mode is a future-compatible design target.

## 2. Player experience

### LOCKED

The desired experience is:

- cooperative crisis management;
- meaningful ship-system tradeoffs;
- incomplete or asymmetric information;
- coordination under pressure;
- evolving trust;
- occasional conflicting personal incentives;
- post-game reconstruction where hidden causes become understandable.

Players should sometimes naturally say:

> "Wait. Read exactly what your phone says."

That is considered a positive sign that asymmetric information is creating real social play.

## 3. Accessibility

### LOCKED

- The premise and core loop should be teachable quickly.
- Player-facing choices should be much simpler than the internal simulation.
- The UI should explain unfamiliar mechanics contextually when they first matter.
- Technical concepts should be translated into plain language.
- Legal actions should be enforced by the software.
- Players should not need to memorize large rule interaction tables.
- Important future consequences should be forecast where practical.

## 4. Complexity philosophy

### LOCKED

A mechanic is justified when it creates a meaningful decision, not merely because it adds simulation detail.

Examples:

- Good: restoring encryption consumes power needed elsewhere.
- Weak: encryption exists only as a status icon with no decision attached.

### LOCKED

The cooperative ship-maintenance layer must remain strategically interesting even when:

- all humans are loyal;
- the AI is cooperative;
- no deception mechanic is active.

## 5. Social deduction constraints

### LOCKED

- A hostile human is not guaranteed.
- A session may begin with zero divergent human objectives.
- Alignment can change during play through explicit player choices.
- A suspicious player may still be loyal.
- The game should not collapse into "find the traitor."

## 6. AI constraints

### LOCKED

- The AI is not simply good or evil.
- AI motive and AI integrity are separate concepts.
- A highly reliable AI may still have motives that conflict with the crew.
- A cooperative AI may still be sincerely wrong if its data or internal state is degraded.
- AI deception must be bounded by game rules and should leave room for counterplay.
- The AI should not be allowed to arbitrarily invalidate all evidence.

## 7. In-person communication constraint

### LOCKED

In-person players may always speak aloud.

The design must not depend on rules such as:

> "Player 3 is not allowed to talk."

Instead, the game should manipulate:

- information access;
- system permissions;
- private messages;
- telemetry;
- authentication;
- authorization;
- evidence;
- trust in data.

## 8. Outcome philosophy

### LOCKED

Victory and score are separate.

- Primary Objective success determines whether a player wins.
- Score measures accomplishments and performance.
- A loser may score higher than a winner.
- Score cannot convert a failed Primary Objective into victory.

## 9. Non-goals

### LOCKED

The game should not become:

- The Captain Is Dead with phones;
- Among Us with more menus;
- a cybersecurity certification exercise;
- a guaranteed-traitor game;
- a dashboard simulator;
- a random-information-chaos game where reasoning is pointless.
