---
doc_type: communications_and_trust
status: mixed
canonical: true
---

# Communications, Trust, and Deception

## Fundamental constraint

### LOCKED

In-person players can always speak aloud.

Do not create mechanics that require players to pretend they cannot hear someone sitting next to them.

## Communication modes

### LOCKED CONCEPT

### In-person mode

Assume free spoken communication.

Useful mechanics:

- conflicting telemetry;
- selective private information;
- permissions;
- authorization;
- AI private messages;
- secret objectives;
- system access;
- evidence quality.

### Remote / text-only mode

Avrana controls the communication channel.

Additional mechanics can include:

- message delay;
- message loss;
- interception;
- one-way channels;
- sender spoofing;
- altered messages;
- stale/replayed messages.

Remote mode allows deeper communications warfare than in-person mode.

## Security concepts

### LOCKED CONCEPT

The game can use real concepts, but player UI should translate them.

| Internal concept | Player-facing meaning |
|---|---|
| Authentication | Verified sender |
| Encryption | Private / exposed |
| Integrity | Message intact / may be altered |
| Authorization | Access allowed / denied |
| Freshness | Current / stale |
| Auditability | Recorded / unverified |

## Important semantic rule

### LOCKED

Authentication proves identity, not truth.

Example:

> FROM: SHIP AI  
> VERIFIED SENDER

This proves the AI sent the message.

It does not prove the AI's claim is correct.

## AI integrity

### LOCKED

AI integrity is not a "trust meter."

It describes whether the AI can reliably process reality.

Possible internal dimensions:

- Perception
- Memory
- Reasoning
- Communication
- Identity

Do not expose all dimensions to players unless they create meaningful decisions.

Possible player-facing states:

- Stable
- Unstable
- Unknown
- specific fault warning

## Sources of false information

### LOCKED

The game should distinguish:

### Deception
An actor knowingly lies or frames information dishonestly.

### Corruption
Information was altered in transit or storage.

### Error
An actor sincerely believed false information.

This distinction is valuable because not every contradiction should imply a traitor.

## Detectability requirement

### LOCKED

Deception must have counterplay.

Players need ways to improve confidence through:

- redundant telemetry;
- diagnostics;
- logs;
- repairs;
- authentication;
- direct comparison;
- audit queries;
- independent evidence.

## Trusted subsystem / black box

### PROVISIONAL

A limited independent subsystem may verify narrow facts.

Possible functions:

- confirm that Player 2 accessed Life Support;
- confirm that the AI authored a message;
- confirm that a control action occurred;
- record a time-stamped event.

It should **not** automatically answer strategic questions such as:

> Was the AI telling the truth?

Queries should likely have cost or limitations.

Potential costs:

- actions;
- time;
- power;
- system access;
- limited query count.

## AI deception constraints

### LOCKED PRINCIPLE

If every signal can always be fake, players stop reasoning.

Therefore:

- AI deception must be bounded;
- some channels/evidence can become more trustworthy;
- system repair should improve epistemic certainty;
- players should sometimes be able to prove facts.

## In-world communication examples

### EXAMPLE

Instead of showing:

> AUTHENTICATION FAILURE

Prefer:

> Sender could not be verified.

Instead of:

> ENCRYPTION DISABLED

Prefer:

> This channel is no longer private. Messages may be intercepted.

Teach the underlying concept when needed, not before.
