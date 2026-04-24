# Account Alerts

_Summerville Mobile › Profile & Preferences › Account Alerts_

## Profile & Preferences: Account Alerts

> Self-service alert configuration per account — balance thresholds, periodic balance snapshots, deposits, and withdrawals — with a contact-information nudge at the top for members whose alerts aren't landing.

### Step-by-Step Workflow

#### Step 1: Account Alerts Home

The top of the screen shows the info note *"Have you not been receiving your alerts? check your contact information."* — that link is the operational escape hatch when alerts exist but aren't delivering. **Balance Alerts** shows a count of active alerts per account (e.g., **Retail Checking (#0001) — Balance Less than $1000.00**); tap **Add** on any row to create a new alert for that category.

![Step 1: Account Alerts Home](../.gitbook/assets/Screenshot_1776963856.png)

### Summary

Alert categories are intentionally grouped by event type (Balance, Periodic Balance, Deposit, Withdrawal) rather than by account — this matches how members think about notifications ("tell me when deposits hit" rather than "tell me everything about checking"). The contact-information nudge at the top is the single most important piece of UX on this screen because silent-alert failures are the most common alerts support ticket, and 90% of those are caused by an outdated email or phone number on file.

### Key Use Cases

* Freelancer who wants a ping on every deposit: Deposit Alerts → Add → Retail Checking → any amount.
* Low-balance protection: Balance Alerts → Add → set threshold = minimum-balance policy, e.g., $1000.
* Monthly cashflow snapshot: Periodic Balance Alerts → Add → schedule weekly or monthly.
