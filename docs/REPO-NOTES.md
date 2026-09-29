# Repository import notes

## Provenance

The canonical design docs now come from the user-supplied Avrana_First_Party_Game_Agent_Docs.zip, version 0.1, dated 2026-09-28. All eleven Markdown documents and the original document structure have been imported. The manifest records the archive SHA-256 and original document hashes for reproducible provenance.

The earlier eight-document Linear import is superseded as the repo's canonical doc set and remains available in Git history. Linear itself was not edited by this update. The standalone project remains [Avrana Game](https://linear.app/avranakern/project/avrana-game-2a67ee269acb).

## Scope adaptation

The archive predates the explicit standalone-project request and identifies the game as an Avrana Party game. The user's standalone requirement governs this repository. Only 00-AGENT-START-HERE.md, 01-DESIGN-CONTRACT.md, and 10-DECISION-REGISTER.md were adapted: project identity, working title, server authority, appliance independence, and repository reading guidance. The other eight Markdown documents are unchanged from the archive. The manifest uses the standalone project identifier and adds provenance and repo entrypoints while preserving source statuses and read order.

No mechanics, balance values, examples, or design status distinctions were promoted or settled during import. Frontmatter such as discovery, provisional, mixed, or canonical describes a document; section-level LOCKED/PROVISIONAL/OPEN/FUTURE/EXAMPLE labels retain their meaning. Compound labels such as LOCKED FOR MVP and LOCKED PRINCIPLE are preserved.

## OPEN: Source status ambiguity

- 04-MISSION-AND-OBJECTIVES.md labels divergent starting Primaries PROVISIONAL.
- 10-DECISION-REGISTER.md lists occasional setup divergence under LOCKED.

The original archive contains both statements, so it does not eliminate this ambiguity. Both are preserved. Do not silently decide whether the lock covers only the capability while frequency/content remain provisional, or a broader commitment. The cooperative first prototype still excludes divergent human Primaries in 08-MVP-ROADMAP.md. Resolve the distinction explicitly when implementation depends on it.

## Reading guidance

09-OPEN-QUESTIONS.md is the dedicated unresolved-question register. 08-MVP-ROADMAP.md includes prototype success criteria. Later roadmap features remain deferred even when their underlying design concepts are LOCKED. No stack, numeric balance, probability, objective catalog, or exact action-conflict resolution was approved by this import.
