# Canopy Kernel Patch Protocol v0.1

Purpose: ensure changes to the kernel remain auditable, reversible, and aligned with safety posture.

## Patch Types
- PATCH: wording/clarity; no behavioral change
- MINOR: new contract/artifact; no breaking change
- MAJOR: changes constraints, invariants, or authority boundaries (requires explicit sign-off)

## Required Patch Contents (template)
1) Patch ID: KP-YYYYMMDD-###
2) Summary: what changed
3) Rationale: why
4) Scope: files affected
5) Risk analysis:
   - safety impact
   - governance impact
   - privacy/export impact
6) Backward compatibility:
   - breaking? yes/no
7) Test/verification:
   - what was checked (at minimum: life safety text policy constraints unaffected)
8) Decision:
   - accept / reject / revise
9) Sign-off:
   - Founder/Principal (internal)

## Patch Workflow
1) Create branch: `patch/KP-YYYYMMDD-###`
2) Apply edits
3) Update a `CHANGELOG.md` entry (if present) or add patch notes in PR description
4) Review against:
   - Safety Constitution (BT)
   - Life-safety invariants (AW)
   - Non-anthropomorphic language rules
5) Merge to main
6) Tag internal milestone if meaningful

## Automatic Reject Conditions
- Any language implying consciousness/agency
- Any weakening of life-safety override
- Any addition of tactical incident instructions
- Any removal of auditability requirements
