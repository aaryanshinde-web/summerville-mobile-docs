# Approval Settings

_Summerville Mobile › Business Banking › Approval Settings_

## Business Banking: Approval Settings

> The Approvals Settings screen — set the total number of approvals required for each transaction type (ACH — Payment, ACH — Collection, ACH — Payroll, Domestic Wires). Two info blocks explain how transactions behave when the count is set to 1 vs. more than 1.

**How to get here:** Side Menu (☰) → **Business Settings** → **Approval Settings**

### Step-by-Step Workflow

#### Step 1: Open Approval Settings

From Side Menu (☰) → **Business Settings**, scroll to **Manage** and tap **Approval Settings — Manage settings for transactions requiring approvals**. The **Approvals Settings** screen opens with **Select business** showing the active business, the line *"There are 4 approver(s) with approval permission in this business"*, and the heading *"Select the total number of approvals required for a transaction to process."*

![Step 1: Open Approval Settings](../.gitbook/assets/Screenshot_1777271132.png)

#### Step 2: Pick the Approval Count per Transaction Type

Each transaction type has a numeric stepper: **ACH - Payment**, **ACH - Collection**, **ACH - Payroll**, **Domestic Wires**. Tap a stepper to open the count picker.

![Step 2: Pick the Approval Count per Transaction Type](../.gitbook/assets/Screenshot_1777271132.png)

#### Step 3: Set the Approval Count

A picker shows numeric options (**1**, **2**, **3**, **4** — capped at the *"There are N approver(s)"* count). Tap the desired count to set it for that transaction type.

![Step 3: Set the Approval Count](../.gitbook/assets/Screenshot_1777271134.png)

#### Step 4: Read the Rules and Save

A note explains: *"When number of approvals is set to 1 — Transactions initiated by an approver will be auto-approved. Transactions initiated by an anybody else in the business can be approved by any approver."* A second note adds *"When number of approvals is set to more than 1 — Transactions initiated by an approver will count as one of the required approvals. Other approval(s) will be required to process the transaction. Transactions initiated by someone who's not an approver need to be approved by the chosen number of approvers."* Tap **Save** to commit or **Cancel** to discard.

![Step 4: Read the Rules and Save](../.gitbook/assets/Screenshot_1777271137.png)

### Summary

Approval Settings is the per-transaction-type guardrail for outgoing money. **1** means the role with approval permission acts unilaterally; **more than 1** means the initiator's approval counts as one and N additional approvers are required, so a single user can never push a transaction through alone. Different counts for ACH Payments, ACH Collection, ACH Payroll, and Domestic Wires let the business set higher friction on higher-risk rails (a wire can require two approvers while a payroll batch stays at one).

### Key Use Cases

* Tighten domestic wire risk: set **Domestic Wires — 2** while keeping ACH at 1.
* Dual-control ACH payroll: set **ACH - Payroll — 2**.
* Loosen back to single-approver after audit: change each row to **1** and **Save**.
* Audit current rules before adding a new approver: open Approval Settings, read counts, tally with the *"There are N approver(s)"* line.
