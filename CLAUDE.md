# CLAUDE.md — Avrana Game

## Scope and authority

Work on the standalone Avrana Game. Treat the runtime as an authoritative multiplayer game server with private phone/browser clients. Keep game design, prototyping, balancing, and tests independent of the Avrana Party appliance and any sibling repository.

Do not introduce Pi, Party Home, captive portal, appliance networking, `.avrgame` packaging, device deployment, or hardware requirements. Future platform integration must not become an MVP prerequisite.

## Required read order

Read README.md, then:

1. docs/00-AGENT-START-HERE.md
2. docs/01-DESIGN-CONTRACT.md
3. docs/02-GAME-LOOP.md
4. docs/03-SHIP-SYSTEMS.md
5. docs/04-MISSION-AND-OBJECTIVES.md
6. docs/05-AI-AND-SOCIAL-SYSTEMS.md
7. docs/06-COMMS-TRUST-AND-DECEPTION.md
8. docs/07-SCORING-AND-ENDGAME.md
9. docs/08-MVP-ROADMAP.md
10. docs/09-OPEN-QUESTIONS.md
11. docs/10-DECISION-REGISTER.md

Also read docs/REPO-NOTES.md before resolving ambiguities. Use docs/manifest.json for source archive hashes and machine-readable order. Follow the active task's relevant sections after this initial read.

## Preserve design distinctions

- LOCKED: preserve unless Cody explicitly revisits the decision.
- PROVISIONAL: use as a testable assumption, not a permanent rule.
- OPEN: label proposed answers explicitly; do not present them as approved design.
- FUTURE: defer until requested or its roadmap gate is met.
- EXAMPLE: illustrative only; do not automatically generate canonical content from it.

Document-level frontmatter is metadata; section labels govern decisions. Preserve compound source labels such as FUTURE / PROVISIONAL, LOCKED CONCEPT, LOCKED FOR MVP, and LOCKED PRINCIPLE. Do not silently upgrade or downgrade source decisions. If docs conflict, identify both statements and record the ambiguity; obtain a design decision when implementation depends on resolving it.

## Non-negotiable design invariants

- The cooperative ship game must work without betrayal; never assume a human traitor exists.
- Private player screens matter mechanically; the server owns authoritative game state.
- In-person players may always speak aloud. Communication Mode and Scenario are separate concepts.
- AI motive and integrity are different. Reliable actors may be misaligned; cooperative actors may be sincerely wrong.
- Bound deception and provide counterplay. Evidence must remain useful and uncertainty investigable.
- Mission is public, fixed, and Scenario-defined. Primary Objective determines personal victory.
- Objective changes require conscious player choice and explicit UI disclosure. Manipulation alone does not change objectives.
- Secondary and Tertiary Objectives affect score/narrative. Score cannot turn a failed Primary into victory; a loser may outscore a winner.
- Deep state, shallow interface. Complex consequences, simple choices. Explain costs, risks, and important consequences in plain player language.
- Every mechanic must create a meaningful decision.

## Development sequence

Follow the documented roadmap and the standalone Linear milestones M0–M8. Begin with M0 design contract, then M1 cooperative prototype. Validate the ship puzzle with loyal humans and a trustworthy AI before advancing social complexity.

Treat four players, synchronous rounds, simultaneous commitments, roughly two actions per round, 8–10 rounds, 15–20 minutes, 4–6 systems, and 3–5 resources as provisional. Candidate systems/resources are not a settled schema. A runtime generative model is not required by the design.

Prefer the smallest experiment that tests the uncertain assumption. Record playtest evidence and proposed decisions separately from approved decisions. When an approved decision changes, update affected docs, the decision register, and manifest as needed; explain the reason and status transition.

## Repository workflow

This repository is documentation-only. No implementation stack, build, or test commands exist yet. Do not invent claims that software has been built, tested, or playtested.

Before editing, inspect repository state and applicable instructions. Keep changes scoped to the current task and preserve existing work. Validate local Markdown links, manifest paths, read order, and status consistency after documentation changes. For later implementation, add appropriate run/test instructions when the stack is selected and test meaningful behavior: server authority, private information, objective transitions, action resolution, and outcome separation.

Report what changed, how it was verified, and unresolved design questions. Never hide unresolved tuning or conflict behind a confident default.
