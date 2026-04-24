# Skip A Pay

_Summerville Mobile › Move Money › Skip A Pay_

## Move Money: Skip A Pay

> The member-self-service loan-payment deferral — pick an eligible loan, accept the fee and terms, and the system moves the due date out by one payment cycle. Limited to twice in any 12-month period.

### Step-by-Step Workflow

#### Step 1: Select Which Loan to Skip

The **Skip A Pay** landing shows three tabs — **Skip A Payment**, **History**, **More** — with Skip A Payment active. The loan selector dropdown defaults to **All Loans**; eligible loans are listed with **Due Date** and **Payment Due** amounts (e.g., *Line of Credit (******9991L0006) — Due May 18, 2026 — Payment Due $300.00; Used Automobile (******9991L0004) — Due Apr 25, 2026 — Payment Due $450.00*). **Disqualified Loans** appear in a separate section with the disqualification reason stated (e.g., *Monthly Loan Payment is below the minimum allowed limit of $50.00*).

![Step 1: Select Which Loan to Skip](../.gitbook/assets/Screenshot_1776964170.png)

#### Step 2: Confirm Skip and Fees

After picking a loan, the Confirm screen shows the contact-info reminder (*"The credit union does not have an email address on file..."*), the loan detail, and a side-by-side **Current Due Date** vs **Advanced Due Date** comparison (e.g., May 2026 / 18 moving to June 2026 / 18). Below: *"NOTE: You have the option to skip loan payment two times within a 12 month period"* plus the **Transaction Fee** ($35.00 in the capture).

![Step 2: Confirm Skip and Fees](../.gitbook/assets/Screenshot_1776964176.png)

#### Step 3: Pick Fee Payment Method and Accept Terms

Choose where the $35 fee comes from: **Credit Union Account** (with account dropdown — default retail checking), **Charge my Credit Card**, or **Add to Loan Balance**. Below is the full **Terms & Conditions** block — the member must tick *"I agree to the terms and fees as stated above"* before Finish is enabled. Note block calls out scheduled-payment implications for members on auto-pay.

![Step 3: Pick Fee Payment Method and Accept Terms](../.gitbook/assets/Screenshot_1776964185.png)

#### Step 4: View Skip History

Tap **History** tab to see every Skip A Pay request. Each entry shows status (**Pending** or **Completed**) with the loan reference and *"Requested: date at time"* timestamp. Support uses this tab to answer *"did my skip go through"* questions without opening a core-system ticket.

![Step 4: View Skip History](../.gitbook/assets/Screenshot_1776964185.png)

### Summary

Skip A Pay is a one-click relief valve for members who need to push a loan payment out by a month — most common use cases are cash-flow squeezes, a big expense elsewhere, or life events. The two-per-year limit is policy-enforced server-side; the fee is non-negotiable and is the real monetization lever. The Terms & Conditions block is deliberately long because consumer-lending regs require specific disclosure, and the tick-to-agree captures the ESIGN consent trail. Disqualified loans are surfaced upfront so the member doesn't waste time clicking into loans they can't skip.

### Key Use Cases

* Member with an unexpected vet bill: pick the car loan, accept the $35 fee, due date moves a month.
* Member already skipped twice this year: loans show in Disqualified with the limit reason, no further action.
* Finance support troubleshooting: History tab → confirm status is Completed, reference the timestamp in the ticket.
