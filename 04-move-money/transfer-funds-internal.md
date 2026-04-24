# Transfer Funds — Internal

_Summerville Mobile › Move Money › Transfer Funds (Internal)_

## Move Money: Transfer Funds — Internal (Own-Account)

> The simplest money-movement in the app — between the member's own Summerville accounts — is surfaced first so the 80% happy-path doesn't get buried under external-transfer complexity.

### Step-by-Step Workflow

#### Step 1: Transfer Funds — Select From and To

The screen defaults to the member's primary checking as the From account and shows available balance inline so they don't need to flip tabs to check funds. The To field is a search-for-accounts picker with **Recent Accounts** surfaced first — for own-account transfers, the member's savings account will typically appear at the top of Recent.

![Step 1: Transfer Funds — Select From and To](../.gitbook/assets/Screenshot_1776963185.png)

#### Step 2: Review Source and Destination

The scrollable source picker shows **Retail Checking (#0001)**, **Retail Savings (#0002)**, and any external recipients (e.g., **iq bank prime checking**) already on file. Internal transfers are instant and show no timing caveats; external transfers show ACH/FedNow timing on the confirmation.

![Step 2: Review Source and Destination](../.gitbook/assets/Screenshot_1776963639.png)

### Summary

Own-account transfers are the no-friction case: no recipient setup, no same-day cutoff warnings, no timing language. The UI still uses the same Transfer Funds shell that external transfers use, so members learn one mental model and it scales from "move $50 from checking to savings" to "send a FedNow payment to my IQ Bank account" without a separate menu.

### Key Use Cases

* Member moves their paycheck overflow into savings: From = Checking, To = Savings, amount, Transfer Funds. Done.
* Member top-ups checking from savings right before a bill clears: same flow in reverse.
* Member mistakes own-account for external transfer: the Same-day limit and timing caveats don't appear, which itself is the cue they're on the internal path.
