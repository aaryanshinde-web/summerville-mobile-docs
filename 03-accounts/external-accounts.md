# External Accounts

_Summerville Mobile › Accounts › External Accounts_

## Accounts: External Accounts (Linked Non-Summerville Accounts)

> A dedicated section at the bottom of the Accounts tab that aggregates accounts you've linked from other banks and institutions (Chase, IQ Bank, your credit card, your mortgage, etc.) — one unified view of your financial life. Link new ones through the MX aggregator, see groupings, drill into details with charges/credits tables, and use the per-row overflow menu to manage.

**How to get here:** Bottom navigation → **Accounts** → scroll to the **External Accounts** section

### Step-by-Step Workflow

#### Step 1: Find the External Accounts Section

Open the **Accounts** tab. Scroll past your Summerville holdings (Retail Checking, Retail Savings) — the **External Accounts** section starts with an underlined header. You'll see a row of institution logos (US Bank, AmEx, Citi, Chase, USAA) and a **+ Add an Account** button. If you've already linked accounts, they appear in grouped cards.

![Step 1: Find the External Accounts Section](../.gitbook/assets/Screenshot_1776962804.png)

#### Step 2: View Grouped Externals

When externals are grouped, each group (e.g., **Other**) has a total amount and individual rows beneath it — like **Line of Credit — Tyfone Test — $10,000.00**, **Mortgage — $215,000.00**, **Used Automobile — $15,000.00**, **Visa Classic A+ — $9,573.02**. The section header and group total make it easy to see your full exposure at a glance.

![Step 2: View Grouped Externals](../.gitbook/assets/Screenshot_1776962824.png)

#### Step 3: Tap + Add an Account to Link a New External

Tap **+ Add an Account**. The **Add Accounts** screen asks *"Select your institution"* with a search bar and suggestions (e.g., **MX Bank**). Type the bank or card issuer's name or pick from the grid.

![Step 3: Tap + Add an Account to Link a New External](../.gitbook/assets/Screenshot_1776962846.png)

#### Step 4: Authenticate With the External Institution (MX Handoff)

After picking the institution, the MX aggregator's authentication screen loads: *"MX Bank — mx.com — Enter your credentials"* with **Username** and **Password** fields and a **Data access by MX** footer. This is the OAuth-style handoff where MX establishes the read-only link on your behalf. Enter the external institution's credentials (not your Summerville credentials) and submit. MX verifies and returns control to Summerville Mobile once the link is established.

![Step 4: Authenticate With the External Institution (MX Handoff)](../.gitbook/assets/Screenshot_1776962854.png)

#### Step 5: Open the External Accounts Filter

Tap the **filter icon (funnel)** above the External Accounts list to open the filter sheet. Tick categories (ALL / CHECKING), specific external institutions, and tap **Apply** to narrow; **←** returns to the full list.

![Step 5: Open the External Accounts Filter](../.gitbook/assets/Screenshot_1776962829.png)

#### Step 6: Drill Into a Single External Account — Charges / Credits

Tapping an external account opens its detail card — e.g., **Line of Credit — Other** with **Current Balance**. A **MONTH / CHARGES / CREDITS** table summarizes activity by month (e.g., *Apr — $0 charges — $0 credits*). If the aggregator returned transactions, a transaction list appears; if not, the empty state shows. Some products (straight lines of credit, closed accounts) don't expose transaction history, so the empty state is expected.

![Step 6: Drill Into a Single External Account — Charges / Credits](../.gitbook/assets/Screenshot_1776962870.png)

#### Step 7: Per-Account Overflow Menu

Tap the **⋯** (three-dot) menu on any external account card to open the quick-action sheet:
- **Edit Details** — update nickname or category.
- **Mark as Business** — flag the account for business-view filtering.
- **Mark as Duplicate** — hide it from totals if the aggregator returned it twice.
- **Mark as Closed** — archive an account that's been closed externally.
- **Hide Account** — remove from default views without deleting the link.
- **Close Menu** — dismiss.

![Step 7: Per-Account Overflow Menu](../.gitbook/assets/Screenshot_1776962866.png)

### Summary

External Accounts is the aggregation layer — it turns Summerville Mobile into a "see everything in one place" app. Balances contribute to Dashboard Net Worth; externals can be picked as source or destination in the Transfer Funds picker (showing up automatically after you link them). The MX aggregator handles the credential exchange (Step 4) — Summerville never sees or stores your external bank's username and password. The per-row overflow menu handles real-world cleanup cases: aggregator duplicates (mark duplicate), legacy closed accounts (mark closed), and accounts you don't want cluttering your main view (hide). Summerville never moves money out of a linked external account without an explicit transfer you initiate; the link is read-only for the aggregator.

### Key Use Cases

* Consolidate a multi-bank setup: link each external, see all balances in one place alongside your Summerville accounts.
* Set up regular transfers from an external: link it first, then the external appears as a transfer source in Move Money.
* Aggregator returned a duplicate row: **⋯** on the duplicate → **Mark as Duplicate** — it disappears from totals.
* Account closed at the external bank but still showing: **⋯** → **Mark as Closed** — archives the row.
* MX authentication fails on first link: wrong credentials or external bank requires a 2FA step — retry from **+ Add an Account** with the correct credentials.
