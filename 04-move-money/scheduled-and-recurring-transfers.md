# Scheduled & Recurring Transfers

_Summerville Mobile › Move Money › Scheduled & Recurring Transfers_

## Move Money: Scheduled & Recurring Transfers

> Recurring transfers are the set-once, forget-forever workflow — 8 frequencies with end-date control, a confirmation preview, and a cancel-anytime sheet.

### Step-by-Step Workflow

#### Step 1: Open Repeat Transfer and Pick Frequency

From the transfer form, tap **Repeat Transfer** to open the frequency sheet. Pick one: **Daily, Weekly, Bi-Weekly, Bi-Monthly, Monthly, Quarterly, Semiannually, Annual**.

![Step 1: Open Repeat Transfer and Pick Frequency](../.gitbook/assets/Screenshot_1776963158.png)

#### Step 2: Pick End Condition

Back on the Repeat Transfer form, tap **End on** — the dropdown offers two options: **End Date** (you pick a specific stop date) or **Until I Cancel** (no end date, runs indefinitely). Most recurring transfers use **Until I Cancel** because that matches the realistic intent.

![Step 2: Pick End Condition](../.gitbook/assets/Screenshot_1776963161.png)

#### Step 3: Confirm the Schedule

The Confirm screen previews the full schedule: **From / To accounts**, **amount**, **Scheduled: Weekly, until I cancel** (or whatever cadence + end rule), and a human-readable line like *"Transfers will be made every week on Thursday"*. **Edit** returns to the form, **Cancel** discards, **Confirm transfer(s)** commits.

![Step 3: Confirm the Schedule](../.gitbook/assets/Screenshot_1776963214.png)

#### Step 4: Success — Transfer Summary

On commit, the **Transfer Summary** screen appears: big checkmark icon, *"Transaction Scheduled Successfully"*, the amount (e.g., **$10.00**), From / To cards, schedule line, and the next-occurrence date. **Done** returns to the Move Money hub.

![Step 4: Success — Transfer Summary](../.gitbook/assets/Screenshot_1776963222.png)

#### Step 5: Cancel a Scheduled Transfer

From the **Scheduled Transfers** list later, tap **Delete** on any row; the **Confirm** dialog asks *"Are you sure you want to cancel this scheduled transfer?"* — **OK** cancels the series, **Cancel** keeps it active. Cancelling one instance cancels the entire series — per-occurrence skip isn't supported.

![Step 5: Cancel a Scheduled Transfer](../.gitbook/assets/Screenshot_1776963604.png)

### Summary

Recurring transfers serve the two most common repeat patterns — payroll-day savings splits and fixed-amount household transfers — with a frequency list that covers everything from daily overdraft sweeps to annual tax top-ups. The **Until I Cancel** default (no end date) matches how most recurring needs actually run. The explicit confirm-to-cancel dialog prevents fat-finger cancellation of a mission-critical auto-transfer, which is the most reported regret-action for this feature.

### Key Use Cases

* Weekly paycheck savings split: Weekly frequency, Until I Cancel, Retail Checking → Retail Savings, fixed amount.
* Rent auto-transfer with known end date: Monthly, End Date = lease end.
* Member wants to pause one month: current behavior is cancel-and-re-create; there's no built-in pause.
