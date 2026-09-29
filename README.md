# Avrana Game

Standalone phone-native starship crisis strategy game: an authoritative multiplayer server and private phone/browser clients.

This repository is independent from the Avrana Party device/appliance and from its game catalog. Pi hardware, Party Home, captive portals, appliance networking, `.avrgame` packaging, and device deployment are not prerequisites. A later integration may consume a proven game.

## Start here

Read [CLAUDE.md](CLAUDE.md), then the canonical docs in this order:

1. [00-AGENT-START-HERE.md](docs/00-AGENT-START-HERE.md)
2. [01-DESIGN-CONTRACT.md](docs/01-DESIGN-CONTRACT.md)
3. [02-GAME-LOOP-AND-SHIP-SYSTEMS.md](docs/02-GAME-LOOP-AND-SHIP-SYSTEMS.md)
4. [03-MISSION-AND-OBJECTIVES.md](docs/03-MISSION-AND-OBJECTIVES.md)
5. [04-AI-COMMS-AND-TRUST.md](docs/04-AI-COMMS-AND-TRUST.md)
6. [05-SCORING-AND-ENDGAME.md](docs/05-SCORING-AND-ENDGAME.md)
7. [06-MVP-ROADMAP-AND-OPEN-QUESTIONS.md](docs/06-MVP-ROADMAP-AND-OPEN-QUESTIONS.md)
8. [07-DECISION-REGISTER.md](docs/07-DECISION-REGISTER.md)

[docs/manifest.json](docs/manifest.json) provides the machine-readable read order and source metadata. [docs/REPO-NOTES.md](docs/REPO-NOTES.md) records provenance and unresolved source ambiguity.

## Design status

- **LOCKED**: preserve unless Cody explicitly revisits it.
- **PROVISIONAL**: current preferred direction; validate through playtesting.
- **OPEN**: unresolved; do not silently invent a canonical answer.
- **FUTURE**: deliberately deferred.
- **EXAMPLE**: illustrative, not canonical content.

Document-level `MIXED` frontmatter means individual sections retain their own statuses. Candidate lists and examples are not blanket commitments.

## First proof

Prove that four loyal humans with a trustworthy AI can have a tense, interesting cooperative ship game before adding divergent objectives, deception, recruitment, communication warfare, escape pods, or advanced scenarios.

This initial repository contains design documentation only. No implementation stack, build command, runtime generative model, or gameplay tuning values have been selected by this import.

[Standalone Linear project](https://linear.app/avranakern/project/avrana-game-2a67ee269acb)
