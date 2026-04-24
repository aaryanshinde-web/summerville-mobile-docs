# Manage Recipients

_Summerville Mobile › Move Money › Manage Recipients_

## Move Money: Manage Recipients

> The system-of-record for every external person and account the member has saved — grouped by Individual vs. Business, with per-recipient account detail edits gated behind the Update Account sheet.

### Step-by-Step Workflow

#### Step 1: Manage Recipients List

The list is grouped by recipient type — **Individual** first, then Business if any exist. Each row shows a generic person icon and the recipient name (e.g., *Personal Recipient*). Tapping the chevron opens the detail view for that recipient.

![Step 1: Manage Recipients List](../.gitbook/assets/Screenshot_1776963520.png)

#### Step 2: Update Account — External Recipient Detail

Inside a recipient, tap an account to open the **Update Account** sheet. Editable fields include **Payment type** (External / Internal), **External Account Nickname**, and the routing/account-number path. The **Name on account** and institution (e.g., *DANIEL KARA — IQ Bank*) are read-only after the first save because they're keyed off the external institution's verification response — changing them requires removing and re-adding the account.

![Step 2: Update Account — External Recipient Detail](../.gitbook/assets/Screenshot_1776963536.png)

### Summary

Manage Recipients is the only place in the app where external account details can be edited without creating a new recipient — the nickname update is the most-used edit and the only one that doesn't trigger a re-verification flow with the aggregator. The read-only Name on account is a deliberate fraud control; if a member needs to correct the name, the flow is delete-and-re-add so the aggregator revalidates against the destination institution.

### Key Use Cases

* Member renames "My Chase Checking" to "Joint Savings" for clarity: Update Account → External Account Nickname → Save.
* Member realizes a saved recipient has the wrong routing number: Update Account → edit routing, Save → aggregator re-verifies; if validation fails the recipient returns to a pending state.
* Delete a stale recipient: from the Manage Recipients list, long-press or swipe to delete (implementation may vary by platform); the recipient disappears from the Transfer Funds picker immediately.
