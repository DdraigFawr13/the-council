# Notes

Updated: 2026-11-09. Keep this file short: a fresh session reads it first.

## Now

The Council is built (charter and 12 sheets, #2 and #3) and passed its kill test on Morgan's call (see Decisions). Sittings run in threads of this Claude Code project, following `council/CHARTER.md` and `council/MEMBERS.md`. Next development steps are proposed to Morgan, who picks before anything substantial is built.

Pages:
- Brainstorm: [open questions](https://claude.ai/artifact/JRRFM9rYWv1Gbkc7cKrRym), [concepts](https://claude.ai/artifact/E57hx6ZSBmzf15F45XUtot), [round 1](https://claude.ai/artifact/Drq7sEeVNgVW3YJD4Uy3xQ).
- Design: [round 1](https://claude.ai/artifact/7Bg2x2vWhFDfeJpDAva5Pn) (`design1`, answered), [round 2](https://claude.ai/artifact/S3dJWfzsBi75dTDCyqvjXW) (`design2`): confirm 8 aspects in 4 pairs (Steward/Reveller, Face/Tide, Healer/Sovereign, Hearth/Hermit, each citing Morgan's words), pick 4 challengers (recommended: Elder, Reckoner, Stranger, Fool), and decide whether the "eat my feelings" line goes on any sheet. Answered in chat 2026-11-09.
- Design [round 3](https://claude.ai/artifact/SjtDBZmLGK7MkE1J6JunqG) (`design3`): confirm the 12, and names, races and looks for each (new titles for the Face and the Tide). Answered 2026-11-09.
- Built: `council/CHARTER.md` (Project instructions), `council/MEMBERS.md` (12 sheets), `docs/SETUP.md`, `docs/sample-sitting.md`. Dry runs fixed 3 unclear rules, then added law 8 (Speak plainly) after Morgan found the speech unclear, and renamed the fourth voice the opposer.
- Design agent cost measured (seat review $0.31, dry runs $0.28 and $0.15). Brainstorm: $0.64.

## Next

- Hold about 3 sittings with the new cross-talk (#3), then check the voices are distinct and revisit the Sovereign and the Hermit.
- After each sitting, add its decree to `council/DECREES.md`.
- Revisit the Sovereign and the Hermit after a few sittings. Then: voices; the charter (procedure, length law, crisis rule); the home.
- Keep watching the other kill criteria (brief): at least 4 sittings in the 4 weeks from 2026-11-09, speeches not skimmed, councillors not just agreeing with Morgan's opening view, and the councillors distinguishable by voice after 3 sittings.
- Brainstorm trial (D-048, master): measure 2 is "design round 1 asks nothing the brief answered"; measure 3 is "after design, Morgan says the concept survived unchanged". Report both to a master session for `decisions/benchmarks/brainstorm-trial.md`.

## Decisions

- 2026-11-09 Concept chosen: A+B+C merged, with D's decree line and E's copyable charter (brief, Concepts dropped). Morgan: "Do what you recommend".
- 2026-11-09 12 councillors plus Morgan as leader: 13, Morgan's favourite number.
- 2026-11-09 Design round 1 (Morgan took every recommendation): 8 aspects in 4 opposed pairs + 4 outside challengers; Herald and Scribe are officers, not seats; 2-3 sentences a speaker; a mix of fantasy races and humans; a Claude Project with the charter and 12 sheets.
- 2026-11-09 Design round 2 (chat): challengers are the Elder, Reckoner, Stranger and Fool. The Hearth means "people miss that I want to be friends". Retitle the Face and the Tide. The "eat my feelings" line stays off every sheet (default; Morgan didn't object).
- 2026-11-09 Design round 3: the 12 confirmed. Names: Thane Ironledger, Jinx Starlark, Ser Aldric Brightshield (the Bastion), Maren (the Heartwell), Elowen Kindleaf, Aurelian Goldmane, Hob Hearthwarm, Hush, Morrow, Sumner Brass, Grisk the Wayfarer, Motley. Officers: Corvin (Herald) and Vellum (Scribe).
- 2026-11-09 Merged as #2 (Morgan approved; caveat "the speech dialogue is a little too unclear", fixed by law 8 before the merge). No CI in this repo.
- 2026-11-09 After the first live sitting: councillors call the user "Morgan", never "Head" (Morgan: "I don't want to be called head"). Sittings get cross-talk: later speakers answer earlier ones by name, then a 2-4 line crossfire after the challenge (law 9, step 5, command `argue on`). 2-3 sentences a speaker still holds.
- 2026-11-09 Lite profile: the project is prompts and character sheets, with no code, CI or UI.
- 2026-11-09 Kill test passed on Morgan's judgement, not the formal test. After one live sitting (the AI and controls-engineering question, decree: learn the AI tools on real work and build the site judgement they can't replace), Morgan said: "Honestly I feel happy with this result and I'd say it passes the kill test." The 5-question plain-vs-Council comparison in docs/SETUP.md was not run, so this rests on one sitting and Morgan's call. If later sittings stop helping, run the formal comparison before building more.
- 2026-11-09 Morgan: "Do all" (of the proposed next steps). Added `council/DECREES.md` (decree 1 from the first sitting; the Scribe numbers new ones and councillors may cite old ones) and charter step 7, the open question: an unanswered question to Morgan is put to them before the ruling (in sitting 1, Sumner's desk-vs-site question was dropped). Portraits: pricing only, nothing spent without Morgan's yes.
- 2026-11-09 Morgan: "I want to reduce the ai isms in the writing of the councilors. I want conversation to feel more natural as well." Added law 11 (Sound like people) with a list of patterns to avoid taken from sittings 1 and 2, loosened "address Morgan by name" to now and then, and rewrote the format example. Member sheets unchanged.

