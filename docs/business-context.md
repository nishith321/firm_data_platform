# Business Context

## The Firm
**Summit Ridge Advisors** (fictional) is a 200-person professional services firm
providing accounting, tax, and advisory services to mid-sized businesses.

- **Offices:** Sacramento, San Francisco, Los Angeles
- **Service lines:** Audit & Assurance, Tax, Advisory
- **Staff levels:** Partner, Manager, Senior, Staff
- **Clients:** ~1,500 active clients across multiple industries

## How the Business Works (Engagement Lifecycle)
1. **Engagement opened**: a client hires the firm for a specific service (e.g., 2026 tax return).
2. **Time recorded**: employees log hours against the engagement at their billing rate.
3. **Work in Progress (WIP)**: recorded time that has not been billed yet.
4. **Invoiced**: WIP is billed to the client. Some value may be written down before billing.
5. **Collected**: the client pays the invoice (fully or partially).
6. **Written off**: amounts the firm decides it will not bill or collect.

## Key Business Questions
Leadership wants to answer:
1. Are our people productively billable? (**Utilization**)
2. How much of our work's value do we actually bill and collect? (**Realization**)
3. How much money is owed to us, and how old is it? (**AR Aging**)
4. Where and why are we writing off value? (**Write-off Analysis**)
5. How much unbilled work is sitting in WIP, and for how long? (**WIP Aging**)

## Key Metrics
| Metric | Definition |
|---|---|
| Utilization % | Billable hours / Available hours |
| Billing Realization % | Billed amount / Standard value of time worked |
| Collection Realization % | Collected amount / Billed amount |
| Write-off % | Written-off amount / Standard value of time worked |
| AR Aging | Outstanding invoice balances bucketed by days past due (0-30, 31-60, 61-90, 90+) |
| WIP Aging | Unbilled time value bucketed by days since work performed |
| DSO | Days Sales Outstanding: average days to collect payment |

## Scope
**In scope:** time entry, engagements, billing, payments, write-offs, AR.
**Out of scope (for now):** payroll, general ledger, budgeting, HR.

## Data Note
All data in this project is synthetic, generated with Python. No real company data is used.
