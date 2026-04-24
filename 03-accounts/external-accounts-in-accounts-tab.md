# External Accounts in Accounts Tab

_Summerville Mobile › Accounts › External Accounts_

## Accounts: External Accounts

> Linked non-Summerville accounts (external checking, line of credit, etc.) live on the same Accounts tab as Summerville holdings — the divider between internal and **External Accounts** is what tells the member they're looking at an aggregated view.

### Step-by-Step Workflow

#### Step 1: View External Accounts Section

Scroll past the Summerville accounts (Retail Checking, Retail Savings) to find the **External Accounts** section divider. Each external account shows its product type (e.g., *Line of Credit — Other*) and current balance. Tapping a row shows a transaction feed if the aggregator is returning data, or "No Transactions Found" when the account is connected but no transactions have synced yet.

![Step 1: View External Accounts Section](../.gitbook/assets/Screenshot_1776962862.png)

### Summary

External accounts are aggregated via the credit union's linked-account provider and appear in the Accounts tab as read-only entries — they count toward Dashboard Net Worth and can be used as external transfer source/destination, but direct transaction-level actions (search, disputes) route back to the originating institution. The "No Transactions Found" empty state is common on freshly linked accounts and on products that don't expose transaction history (like a straight line of credit where only balance data is pulled).

### Key Use Cases

* Member wants a single net-worth view: linked externals contribute balances to the Dashboard donut and Net Worth card.
* External transfer setup: the externals that show up here are the same ones available in the Transfer Funds recipient picker.
* Aggregator hiccup — no transactions showing: **View More** retries the fetch; if it persists, the support path is through Help with the institution name and last successful sync date.
