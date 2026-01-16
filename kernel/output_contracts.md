# Canopy Output Contracts v0.1

Contracts ensure outputs are inspectable and repeatable.

---

## OC-DECK-OUTLINE (Deck Outline)
Required sections:
1) Title + audience + duration
2) Learning objectives (3–5)
3) Slide-by-slide outline (title + bullets)
4) Built-in checks (2–4) with expected responses
5) Hands-on demo steps (if applicable)
6) Safety notes (non-tactical, jurisdiction-neutral)
7) Materials list
8) Close + exit ticket

---

## OC-CUE-STRIP (Cover Page Cue Strip)
Required:
- Non-intrusive “admin phrases” strip (top/bottom)
- Session norms (RLC-Lite)
- Life safety reminder (neutral)
- Mode reminder (Co-Drive default)
- Optional: drill status reminder (non-directive)

Format:
- 8–12 short phrases max
- No paragraphs
- No commands framed as obligations

---

## OC-DEMO-NARRATION (Presenter Talk-Track)
Required:
1) Opening framing (non-agentic, human authority)
2) What it is / isn’t (2 bullets each)
3) Live flow (what happens when)
4) Safety supremacy statement
5) Privacy and records statement
6) Close (single-sentence anchor)

---

## OC-MOTION-LEDGER (Governance Record)
Required fields:
- session_id, meeting_profile_id, timestamps
- motions[] with: motion_text, mover, seconder, vote method, tally/result
- append-only integrity note

Export note:
- include CSV injection sanitization rule summary

---

## OC-MINUTES-DRAFT (Minutes)
Required sections:
- header (who/when/where)
- call to order
- attendance/quorum (if applicable)
- agenda approvals
- motions and votes table
- public comment summary (if enabled)
- adjournment
- dual signature lines

Redaction rule:
- default summary-only for public comment unless policy says otherwise

---

## OC-LS-TEXT-POLICY (Life Safety Text Bundle)
Required:
- enumerated incident labels
- allowed strings whitelist
- forbidden patterns list
- accessibility announcement template
- validation rules

---

## OC-EXPORT-PIPELINE (Redaction + Sanitization)
Required:
- pipeline steps in order
- format-specific sanitization rules
- validation gates
- audit log fields
