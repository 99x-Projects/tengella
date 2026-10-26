# CleanFlow V2 — Operational + Growth Intelligence

This is a static, standalone **fictional prototype**, derived from root `index.html` (V1). Root V1 is not edited.

## Run
Serve repository root using `python3 -m http.server 8000` and open `http://localhost:8000/v2/`.

## Navigation
Use the top switcher to move between:
- **Layer 1 — Operational Intelligence:** all original five operational agent templates and approval interactions (V1).
- **Layer 2 — Growth Intelligence:** simulated retention, expansion and lead-qualification agents; three evidence-backed sample proposals, editable internal follow-up notes, approval/dismissal and activity log.

All entities, opportunities, numbers, confidence and commercial impacts in V2 are **fictional demonstration records**, not actual Tengella/customer intelligence or validated research ROI. Actions operate only in browser memory. No external outreach, CRM updates, invoicing or live AI execution happens.

## Research traceability (candidate alignment, not validation)
- Retention → customer retention and quality differentiation.
- Account expansion → existing-customer upsell and revenue growth.
- Lead qualification → customer acquisition and observed sales/marketing workflows.
Review priorities against `tengella-ca/docs/research/revenue-and-agentic-opportunities.md` and `executive-summary.md` before product commitment.

## Acceptance checks
- V1 root index unchanged: verify `git diff main...HEAD -- index.html` is empty.
- `v2/index.html` retains original V1 application and adds independently selectable Growth Intelligence.
- Test manual desktop/mobile layouts, keyboard tab navigation, switch both layers, activate/deactivate growth agents, edit and approve one proposal, dismiss another, and confirm no external action takes place.
- No production backend or automatic persistence is implied.

## Customer-portal cross-layer scenario
A fictional extra window-cleaning order (#PO-204) enters through a *simulated* customer portal event. Layer 1 presents a proposed staffing review; Layer 2 identifies repeated ad-hoc demand and suggests a recurring-service conversation; the account manager approves an **internal-only** follow-up. The sequence includes four stages, evidence, a reviewer note, status and reset. Nothing is booked or sent and no live Tengella portal API is used. It builds on the September 16, 2026 customer-portal announcement and should not be mistaken for already delivered AI functionality.

Smoke steps: open Layer 2, advance four stages, edit the review note, approve, confirm final disabled action and audit trace; reset and confirm the initial state. Repeat in both light and dark theme modes and at narrow mobile width.
