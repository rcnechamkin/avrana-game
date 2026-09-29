---
project: Avrana Game
source: https://linear.app/avranakern/document/06-mvp-roadmap-and-open-questions-b21f055647d1
source_updated_at: 2026-09-29T01:46:07.973Z
status: MIXED
---

# MVP Roadmap & Open Questions

## Prototype 0 — Cooperative Ship Puzzle

Goal: prove four loyal humans can have an interesting game.

Include:

* Standard Mission
* 4 players
* 4–6 ship systems
* 3–5 resources
* synchronous rounds
* simultaneous actions
* cooperative/trustworthy AI
* consequence forecasting

Exclude:

* divergent human Primaries
* AI deception
* recruitment
* communication warfare
* escape pods
* advanced scenarios

## Prototype 1 — AI Fifth Participant

Add AI recommendations, limited authority, self-preservation, and explicit authority requests.

## Prototype 2 — Private Information & Trust

Add asymmetric telemetry, private AI contact, limited integrity faults, and diagnostics/evidence.

## Prototype 3 — Divergent Objectives

Add occasional lore-backed Primary Objectives that differ from the Mission.

Do not guarantee one every game.

## Prototype 4 — Bargains & Recruitment

Add AI offers, objective changes, player recruitment, and objective history.

## Prototype 5 — Communication Warfare

Primarily Remote/Text mode:

* interception;
* spoofing;
* delay/loss;
* one-way channels;
* authentication/encryption mechanics;
* bounded audit tools.

## Later

* escape pods;
* Emissary;
* Cargo;
* Quarantine;
* Rescue;
* AI Core;
* post-death roles.

# Open Questions

## Core loop

* Ideal session length?
* Correct round count?
* Correct action count?
* Planning timer?
* Immediate vs. delayed action resolution?

## Ship

* Exact resources?
* Exact systems?
* Does physical player location matter?
* How much randomness belongs in events?

## AI

* How are motives represented?
* Can motives change?
* What bounds deception?
* Does the AI have an intervention budget?
* How visible is integrity?

## Information

* Does a black box exist?
* What can it verify?
* What does investigation cost?

## Objectives

* How often does a divergent Primary exist?
* Maximum number of divergent humans?
* How many Primary changes are tolerable?
* How is impossible objective generation prevented?

## Death / escape

* What does a dead player do?
* Can a dead player still win?
* When do escape pods become available?

## Scoring

* Exact point sources?
* Difficulty weighting?
* Is score visible during play?

## Implementation

* Rule-driven AI for MVP?
* Any need for a runtime generative model?
* What state must remain authoritative?
* How are session replay and post-game reconstruction stored?
