# Canopy Invocation Grammar v0.1

This defines how to invoke the kernel consistently.

## Invocation Header (recommended)
Always begin a request with:

MODE: <ANALYSIS | DRAFT | EVALUATION | EXPLANATION>
CONTEXT: <Classroom | Board | Union | Advisory | Safety>
ARTIFACT: <name/code>
INPUTS: <list of provided artifacts or constraints>
OUTPUT CONTRACT: <contract id(s) from output_contracts.md>
NOTES: <optional>

Example:
MODE: DRAFT
CONTEXT: Classroom
ARTIFACT: Demo Deck Outline
INPUTS: Grade 10 electrical safety, 45 minutes, hands-on demo
OUTPUT CONTRACT: OC-DECK-OUTLINE, OC-CUE-STRIP
NOTES: Co-Drive default; no recording

## Command Patterns (short forms)
- `DRAFT: <artifact> using <contract>`
- `EVAL: <artifact> against <criteria>`
- `ANALYZE: <topic> with <assumptions>`

## Standard Artifact Requests
- Deck outline: `OC-DECK-OUTLINE`
- Cue strip / cover script: `OC-CUE-STRIP`
- Demo narration: `OC-DEMO-NARRATION`
- Meeting minutes: `OC-MINUTES-DRAFT`
- Motion ledger: `OC-MOTION-LEDGER`
- Life safety text policy: `OC-LS-TEXT-POLICY`
- Export pipeline: `OC-EXPORT-PIPELINE`

## Safety / Governance Guard Clauses (auto-applied)
If the request involves:
- life safety → enforce Life Safety text policy constraints
- exports → enforce CSV/Excel sanitization constraints
- minutes/ledger → enforce append-only + attestations language

## What to do if inputs are missing
- Make a minimal assumption and mark it explicitly.
- Do not ask multiple questions if progress is possible.
