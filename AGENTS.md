# Working rules for coding agents (Codex, Claude and any other AI)

This public repository only holds ScanStation's signed installers, published as GitHub releases by
the ScanStation release train. There is no source code here. It belongs to the ScanStation app
project (DLM Innovations LLC).

- Never upload, edit, re-tag or delete a release by hand. Releases come only from the release train
  in DLM-Innovations/ScanStation (`docs/RELEASE-ENGINEERING.md`, `docs/UPDATES.md`), after David
  approves and signs.
- Changes to this repository's own files (README, this file) go through a `dwr/*` PR, and are
  merged only between releases, with the ScanStation release lead's OK.
- Never commit secrets, signing material or private keys.

## QA: run Quinn

**Quinn** is the DLM QA kit. The installers published here are qualified by the ScanStation app's
Quinn setup: `docs/qa/quinn/SKILL.md` and `docs/qa/quinn/profile.md` in DLM-Innovations/ScanStation.
This repository has no copy of its own, because nothing here is built or tested.
