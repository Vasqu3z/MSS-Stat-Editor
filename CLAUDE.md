# MSS-Stat-Editor — Project Context

Python desktop application for editing character statistics and chemistry in Mario Super Sluggers. Part of the Comets League Baseball tooling ecosystem.

## Working Style

- This is a fork — be mindful of upstream compatibility if changes might be contributed back.
- Surgical changes only. Don't refactor working code.
- Don't break existing functionality; the tool is used for CLB character balancing.
- The editor handles game memory structures — be careful with offset calculations and data formats.

## Key Files

- `editorV3.py` — Main editor application
- `editor-vasquez-beta.py` — Beta/development version with CLB-specific modifications

## Verification

Before finalizing changes, confirm:
- Stat editing still produces valid game data
- Chemistry relationships still work correctly
- No regressions in existing features
