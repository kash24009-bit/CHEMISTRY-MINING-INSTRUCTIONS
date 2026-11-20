# Port progress · Chemistry (043), from the Physics (042) instructions

Each step is committed and pushed when it is done, so a usage stop loses nothing. A new session continues from the first open line.

- [x] 1. Tools ported and tested: `pyqkit.py` (subject blocks: question types, step kinds, registers R01–R08, mock section types, blueprint class), `che_code_env.py` (Batch 0 `--init`, refused when any vault exists), `che_gate.py`, `che_marks.py`, `che_s6.py`. All compile; a fresh vault passes validate 16/16; the setup with `--init` starts a vault at batch 0, and without it stops as before.
- [ ] 2. Instruction documents: subject content in CLAUDE.md, CHE-00, CHE-02, CHE-04, CHE-07, CHE-08, CHE-10, RULE-CARD and the reader agent.
- [ ] 3. CHE-03 mistakes ledger: every lesson carried from Physics, marked as carried.
- [ ] 4. CHE-05 syllabus from the official 2026-27 syllabus.
- [ ] 5. CHE-06 draft pattern seed; the kit seeds and validates it.
- [ ] 6. CHE-09 work plan, CHE-11 teaching handoff, README.
- [ ] 7. Final checks, then the pull request.
