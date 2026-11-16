# video-analysis

Import-ready packaging of the **video-analysis** skill, copied from
[`Starchild-ai-agent/official-skills`](https://github.com/Starchild-ai-agent/official-skills)
(path `video-analysis/`). All credit goes to the original author. The upstream
repository is unchanged; this repo only repackages the skill so it can be
imported directly (SKILL.md at the repository root).

## Layout

- `SKILL.md`, `analyze.py`, `config.yaml`, `exports.py` — the original skill files (see the trailing-newline packaging note below)

## License

The upstream repository contains **no LICENSE file** (checked at the repo root
and in the `video-analysis/` folder), so no license is included here and none
was invented. Usage terms are whatever the upstream author grants.

## Packaging note

The published SKILL.md has one extra trailing newline from GitHub's text editor.
All other skill-file bytes are unchanged. This is the original Starchild skill;
its host-tool references and optional transcription dependencies are unchanged.
Importing it does not install those dependencies or validate runtime compatibility.
