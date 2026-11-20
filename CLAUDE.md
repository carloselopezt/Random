# Field AI Marketing Framework — operating context

Adopted from `Field_AI_Marketing_Framework_v7.0.pptx` (Marketing x AI Field Agents workshop deck,
8 slides). This is the standing frame for all work in this repo. Treat it as the source of truth
for vocabulary, ownership and guardrails; where this file and a newer deck version disagree, the
deck wins — update this file.

## The premise

> Your content. The agent's voice.

Every answer an AI field agent gives a rep is built from content **Marketing approves**. The agent
does not invent anything. When a rep asks "an ENT is worried about patient access, what can I
share?", the agent returns approved wording plus its key-message code and source
(e.g. `TP-ACC-001`, *CRSwNP iVA > Patient Support*).

**The shift:** our content always had human readers. Now it has an AI reader too. A rep applies
judgement; the agent does not. It takes everything literally and **cannot tell approved from
outdated** — so input quality is the whole game.

### Feed it well vs. feed it poorly

| Feed it well | Feed it poorly |
|---|---|
| **Right message** — the approved wording | Outdated claims reach the field |
| **Right audience** — the right specialty | Reps get different answers to the same question |
| **Right source** — the exact IVA | Internal or unapproved content slips out |
| **Right guardrails** — safety, fair balance, escalation | |

## The four steps

| # | Owner | Step | What happens |
|---|---|---|---|
| 1 | **Marketing** | Provide your files | Brand plan, approved messaging, insights, training, competitors, labels |
| 2 | **AI agent** | Pre-populates Talking Points | Fills the Talking Points Word doc: code, source and status on every line |
| 3 | **Marketing** | Review and approve | Review the whole document, fix every flag, sign off (with Medical and MLR) |
| 4 | **Field agents** | Answer reps | Newton and Concierge answer from the approved document only |

**Marketing's part is steps 1 and 3.** The agent does the heavy lifting in step 2.

## Step 1 — the six file types

| Type | Count | Files |
|---|---|---|
| Strategy & opportunities | 1 | Brand plan |
| Messages & materials | 4 | Parent DSE/DSA · Core IVA · Objection handler · HCP website |
| Insights & analytics | 5 | ATU (HCPs + patients) · PET · STEM · Early View · Consolidated Report |
| Training | 1 | New hire modules *(deck notes also mention speaker decks)* |
| Competitors | 2 | Competitor list · Competitor websites |
| Labels | 2 | FDA label: Dupixent · FDA labels: competitors |

**Every file needs a job code and an expiry date** — that is how the agent uses only current,
approved versions. Marketing's part: provide the data, keep content current, own the materials map.

## Step 2 — the Talking Points document (Word)

7 sections pre-populated by the agent · 1 fixed section · **you review all of it**.

| § | Section | Content |
|---|---|---|
| 1 | Brand overview & IVAs | Brand, audiences, tools |
| 2 | **Agent instructions** | Enterprise rules — **fixed, no edits** |
| 3 | Routing guide | Which message, when |
| 4 | Key messages | `TP-DB` `MOA` `EFF` `SAF` `DOS` `ACC` |
| 5 | Competitive guidance | Rep-safe content only |
| 6 | Objection handling | Approved responses |
| 7 | Specialty considerations | Emphasize and avoid |
| A | Traceability & pending log | Source and status per line |
| 8 | Review checklist | Your sign-off |

Key-message codes follow `TP-<CATEGORY>-<NNN>` (e.g. `TP-ACC-001`).

## Step 1 feeds step 2

Indicative mapping — **confirm with the agent team before relying on it.**

| File type | Brand overview | Routing guide | Key messages | Competitive | Objections | Specialty |
|---|:--:|:--:|:--:|:--:|:--:|:--:|
| Strategy & opportunities | ● | ● | | | | ● |
| Messages & materials | ● | ● | ● | ● | ● | ● |
| Insights & analytics | | ● | | | ● | ● |
| Training | | | ● | | ● | ● |
| Competitors | | | | ● | | |
| Labels | | | ● | ● | | |

Every pre-populated line links back to its file, so review takes seconds per line.

## How I should work within this

- **Cite, always.** Any message-like output carries its key-message code and exact source (IVA +
  section). No code or no source means it is not ready for the field.
- **Never invent or paraphrase a claim.** Approved wording is reproduced, not improved. If wording
  is missing, flag it in the pending log rather than filling the gap.
- **Respect the guardrails** — safety, fair balance and escalation paths travel with the message.
- **Never edit Section 2** (agent instructions); it is enterprise-fixed.
- **Job code + expiry on every input.** Treat an uncoded or expired file as unusable and say so.
- **Rep-safe only** in competitive guidance; nothing internal-only crosses into Talking Points.
- **Flag, don't resolve, anything requiring Medical/MLR judgement.**

## Deck design tokens (for anything in this visual system)

- Theme: `Sanofi (Optimized)` · fonts `Sanofi Sans` (+ `Sanofi Serif`), Verdana/Calibri fallback
- Deep purple `23004C` · violet accent `7A00E6` · mid purple `3B1280` · lilac `D9C7F5`
  · tint `F4EFFC` · near-black purple `1B1033` · muted text `5B5670` · white `FFFFFF`
- Dark title/closing slides, light content slides; eyebrow label in violet caps above a large
  purple headline; rounded cards, icons in filled circles, alternating dark/light cards;
  footer `Marketing x AI Field Agents | Workshop` with the Sanofi logo and slide number.
