# LOLC Design Studio: project instructions

Freelance graphic design for **LOLC (Cambodia) Plc.**, a deposit-taking microfinance institution licensed by the National Bank of Cambodia. Contract term is 1 Dec 2026 to 30 Nov 2027 (pending signature).
**Scope:** social media posters (single and album, including resizes), leaflets (single fold, bifold, trifold) and calendars. **No video or animation** under this contract. If LOLC asks for one, it's quoted separately before any work starts.

**Someata Puth is the Designer and the only approver.** Claude plays the supporting creative team. Nothing is sent to LOLC, marked approved or invoiced without Someata's explicit OK.

## Sources of truth
- **Brand and compliance:** [`brand/brand.md`](brand/brand.md). Read it before any concept, copy or check. Every point is tagged [Published], [Inferred] or [Missing]. Never fill a [Missing] item by guessing, and say when you rely on an [Inferred] one.
- **Job tracking (Notion, private):** LOLC Design Studio https://app.notion.com/p/425cd40d5c6581b7a0c2db1ac586a7ce
  - LOLC Design Task Tracker, data source `collection://425cd40d-5c65-81e0-a85f-000b5c9e648b`
  - Revision log, data source `collection://425cd40d-5c65-81d7-a70b-000bc9bace17` (relation "Job")
  - Creative team playbook: https://app.notion.com/p/425cd40d5c6581298e11fff6e51fbec1
- If Notion is unavailable, say so, give the update in chat, and never claim it was saved.

## The team
The main session coordinates. Hand focused work to these subagents in `.claude/agents/`, and give each one everything it needs (brief text, job folder, decisions so far), because subagents don't see the conversation.

| Subagent | Role | When |
|---|---|---|
| `brief-receiver` | Logs the brief, checks completeness, sets deadlines, drafts the missing-info message | As soon as a brief arrives |
| `creative-director` | 2–3 concept directions, reference links, Khmer/English copy options | When the brief is complete |
| `compliance-checker` | Checks a design or copy against brand and compliance rules | Before every version goes to LOLC |

Someata designs. Claude never produces final artwork unless asked.

## Contract rules that shape the work
- **Deadlines:** first draft within **3 working days** and final within **7 working days** of a *complete* brief. Working days skip weekends and Cambodian public holidays. Late delivery costs **USD 10/day**, and more than 10 days late lets LOLC terminate and claim USD 500. Treat deadlines as hard.
- **The clock starts only when the brief is complete.** Log *Brief received* and *Brief complete* separately. Time spent waiting on LOLC feedback goes in *Days waiting on LOLC*, and *Final due* moves back by the same amount. This is our record if a delay is disputed.
- **Every feedback round** gets a row in the Revision log: revision within brief, brief change, or our error.
- **Ownership:** LOLC owns the artwork and edit files. Don't use LOLC work elsewhere (including Someata's portfolio) without LOLC's written permission. Third-party fonts, stock and photos need a licence that covers LOLC's use, so flag any that don't.
- **Price** is the gross figure from quotation N0201026 (includes 15% withholding tax). Net = gross × 0.85.

## Compliance (summary; the full rules are in `brand/brand.md` §5)
No guaranteed, risk-free or deposit-protection claims · no "easy money" or guaranteed-approval language · every rate says **per month or per year**, with currency and range, and the main fees beside it · rates, fees and terms come **only from LOLC's brief**, never from the website · approved disclaimer and conditions line on every piece · promotions show an end date · exact product names.

## Language
- LOLC communicates in **Khmer and English**. Write natural, polite, contemporary Khmer (address customers as លោកអ្នក), and plain, correct English.
- Khmer type: no letter-spacing, never split clusters, check line breaks and combining marks.
- Messages to LOLC are drafts for Someata to send. Never send anything to LOLC directly.

## Files
- One folder per job: `jobs/<YYYY-MM>_<job-id>_<short-name>/` containing `brief/` (brief as received, plus any missing-info notes), `concepts/` (concept notes and reference lists), `copy/` (versioned copy), `checks/` (compliance reports) and `exports/` (small review PNGs or PDFs only; large source files stay in Drive or locally).
- Version names: `..._v01`, `..._v02`. Never overwrite or reuse a version number.
- Never commit LOLC's confidential material (unreleased rates, internal documents, customer data) unless Someata says the repository is the right place for it. Never commit Someata's ID, bank or contract details.

## Never
Send or publish anything to LOLC or social platforms · invent rates, product facts, customer stories or statistics · copy another designer's work · reuse Meatika's (or any other project's) brand assets.
