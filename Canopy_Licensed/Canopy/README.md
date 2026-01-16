# Canopy

**Canopy** is a structured environment that holds learning, meetings, and life-safety states together—without replacing human authority.

## What this repo is (Bootstrapped / Temporary)
This repository supports the **Kernel-Driven Human Presentation Mode (KD-HPM)** bootstrap loop:
1) Generate/iterate decks & artifacts using the Canopy kernel (in ChatGPT)
2) Present as a human operator (Co-Drive)
3) Upload outcomes back into the kernel for the next iteration

## What Canopy is not
- Not a decision-maker
- Not a teacher/chair/clerk
- Not an emergency instruction system

## Repo layout
- `docs/` — specs, demos, runbooks
- `schemas/` — JSON schemas (district profile, policy bundles) *(placeholder)*
- `policy/` — example policy bundles *(placeholder)*
- `examples/` — sample exports (minutes/ledger) *(placeholder)*
- `scripts/` — helper scripts (validation stubs) *(placeholder)*
- `licenses/` — license texts & licensing notes

## Quick start
- Read: `docs/BOOTSTRAP_KD-HPM.md`
- Use the demo script: `docs/DEMO_NARRATION_SCRIPT.md`
- Create a GitHub repo from this zip: `docs/CREATE_REPO_STEPS.md`

## Licensing (recommended layered model)
This zip ships with **Apache-2.0** as the default repository license for open governance artifacts and specs.
If you later split the kernel prompts or hosted runtime into separate packages, consider source-available licensing for those layers.
See: `licenses/LICENSING_NOTES.md`.
