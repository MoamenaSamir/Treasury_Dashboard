# Treasury & Bank Balance Dashboard

Power BI dashboard for tracking multi-bank cash positions in real time — built for a real-estate brokerage's finance team to replace manual spreadsheet reconciliation.

**Note:** Data is anonymized. Company name, logo, banks, and figures are fictional. The model and logic are real.

## What it does

- Tracks opening/closing balance across 9+ bank accounts
- Separates EGP and USD views (no currency mixing)
- Breaks down revenue, expenses, and net income per account
- Cross-checks against backoffice categories (commissions, fees, cash)
- Date-range slicer for any period, no model changes needed

## Built with

Power BI Desktop · Power Query · DAX · Data Modeling

## Key insight

One account can hold a disproportionate share of total balance — a useful flag for treasury to diversify rather than rely on a single bank. Expense-to-revenue ratio stays consistent across accounts, which helps forecast next period's cash needs.

## What's next — previewed in the deck

The case study includes mockups (built on the same demo data) showing how three upcoming features would look once added:

- **Cash flow forecast** — 90-day projection from trailing closing balances
- **Automated low-balance alerts** — flags any account under its minimum threshold
- **Same-day reconciliation** — matches backoffice categories against bank totals, surfaces mismatches immediately

Together these turn the dashboard from a balance tracker into a full treasury command center.
