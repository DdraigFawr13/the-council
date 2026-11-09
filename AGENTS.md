# Agent instructions

The Council: a fantasy council of 12 councillors, each a personified aspect of Morgan, that debates Morgan's questions in short sittings in Claude chats, with Morgan as head.

Shared rules load through CLAUDE.md (`.claude/master/RULES.md`, AI-Master-Instructions lite profile). This file holds only what is specific to this project. Keep it under 30 lines.

## Read first

- `NOTES.md`: current state, next step and decisions.
- `docs/CONCEPT.md`: the concept brief. Its "Do not reopen" list is settled.

## Local checks (run before pushing)

- `node .claude/master/sync.mjs --check`

## Project rules

- Seats come from Morgan's own answers, and each seat cites them. Never add, merge or change a councillor without Morgan's yes. (Why: the critique's top risk was Claude inventing flattering voices.)
- Sittings stay short by law: 2-3 sentences a speaker unless Morgan asks for more. (Why: Morgan's stated hate is "too long winded".)
- It is a thinking tool, not therapy. Keep the crisis rule in the charter. (Why: research found AI unsafe as a stand-in therapist.)

## Moving to the full setup

When the project needs multi-session plans, specs, CI rules or the shared skills, set `"profile": "full"` in `.ai-master.json`, run `node .claude/master/sync.mjs`, and add `docs/HANDOFF.md`, `docs/DECISIONS.md` and `docs/LESSONS.md` from the master's `core/templates/`.
