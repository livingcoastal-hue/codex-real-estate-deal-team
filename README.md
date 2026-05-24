# Real Estate Deal Team

A reusable Codex skill that turns Codex into an eight-role commercial real estate deal team for acquisitions, underwriting, diligence, investor communications, asset management, and disposition analysis.

## What It Does

This skill routes real estate work to specialized AI roles:

- **Sage**: Deal sourcer and broker email triage
- **Atlas**: Underwriter and assumptions builder
- **Echo**: Market researcher
- **Vertex**: Capital stack architect
- **Argus**: Due diligence lead
- **Ledger**: LP communicator
- **Forge**: Asset manager
- **Nova**: Disposition and refi-vs-sale analyst

It is designed for tasks involving OMs, rent rolls, T-12s, broker emails, acquisition screens, IC memos, lender matrices, due diligence trackers, LP updates, quarterly asset reviews, and exit decisions.

## Installation

Copy this folder into your Codex skills directory:

```bash
~/.codex/skills/real-estate-deal-team
```

Restart Codex or refresh the session so the skill metadata is reloaded.

## Usage

Invoke the skill directly:

```text
Use $real-estate-deal-team to screen this multifamily deal.
```

Target one or more roles:

```text
Use $real-estate-deal-team. Act as Atlas and Vertex. Build underwriting assumptions and a debt sizing matrix from this OM.
```

Create an investor-facing memo:

```text
Use $real-estate-deal-team. Act as Ledger and write an LP update from these quarterly actuals.
```

## Included Templates

- `assets/templates/acquisition-screen.md`
- `assets/templates/dd-tracker.md`
- `assets/templates/lender-matrix.md`
- `assets/templates/lp-update.md`
- `assets/templates/refi-vs-sale.md`

## Included References

- `references/role-playbooks.md`
- `references/deal-screening.md`

## Notes

This skill is not legal, tax, securities, or investment advice. It helps organize analysis and decision support. Final decisions should be reviewed by qualified professionals.
