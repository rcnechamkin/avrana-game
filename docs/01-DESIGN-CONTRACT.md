---
project: Avrana Game
source: https://linear.app/avranakern/document/01-design-contract-d2790c42e4f5
source_updated_at: 2026-09-29T01:45:56.452Z
status: MIXED
---

# Design Contract

## LOCKED: Product identity

* Phone-native multiplayer game.
* Private player screens are mechanically important.
* Server-authoritative state.
* Standalone from the Avrana Party device during design/prototyping.
* In-person play is a first-class mode.
* Remote/text-only play is a separate communication mode.

## LOCKED: Desired experience

Players should feel like a crew barely keeping a complicated ship functioning while:

* making real resource tradeoffs;
* coordinating under incomplete information;
* deciding what evidence to trust;
* interacting with an AI whose goals may overlap imperfectly with theirs;
* occasionally discovering that human incentives differ.

A positive play signal is somebody naturally saying:

> "Wait. Read exactly what your phone says."

## LOCKED: Accessibility

* Premise and core loop should be learnable quickly.
* One clear decision at a time is better than a giant dashboard.
* Explain unfamiliar mechanics in context.
* Translate technical language into plain player-facing language.
* Software enforces legality.
* Forecast important consequences when possible.

## LOCKED: Social constraints

* A human traitor is not guaranteed.
* Some games can begin with zero divergent humans.
* Players can consciously change motives through bargains/recruitment.
* Suspicious behavior is not proof of betrayal.
* Do not let the design collapse into "find the traitor."

## LOCKED: AI constraints

* AI is not simply good or evil.
* AI motive != AI integrity.
* A reliable AI can be strategically misaligned.
* A cooperative AI can be sincerely wrong.
* AI deception must be bounded and counterable.
* The AI must not arbitrarily erase the value of evidence.

## LOCKED: In-person communication

Players may always speak aloud.

Do not create mechanics that require pretending otherwise.

## LOCKED: Outcome philosophy

* Primary Objective determines personal victory.
* Score is a separate performance measure.
* A loser may outscore a winner.
* Score cannot convert a failed Primary Objective into a win.
