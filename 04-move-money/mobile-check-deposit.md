# Mobile Check Deposit (RDC)

_Summerville Mobile › Move Money › Mobile Check Deposit_

## Move Money: Mobile Check Deposit — Remote Deposit Capture

> The Deposit tab of the bottom navigation — pick the destination account, enter the amount, capture the front and back of the check, endorse correctly, and submit. Holds may apply per the credit union's funds-availability policy.

**How to get here:** Bottom navigation → **Deposit**

### Step-by-Step Workflow

#### Step 1: Open the Deposit Tab

From the bottom navigation, tap **Deposit**. The Check Deposit form loads.

![Step 1: Open the Deposit Tab](../.gitbook/assets/Screenshot_1776963667.png)

#### Step 2: Pick Destination Account and Enter Amount

At the top of the Check Deposit screen, the **Select an account to deposit into** dropdown defaults to your primary checking (e.g., *Retail Checking Account #0001 - #0000060071 $145,131.22*). Change if needed. Below, the **Enter amount** field takes the exact dollar amount of the check you're depositing.

![Step 2: Pick Destination Account and Enter Amount](../.gitbook/assets/Screenshot_1776963664.png)

#### Step 3: Capture Front and Back

Two capture cards appear side-by-side — **CHECK Front** and **CHECK Back** — each with a camera icon that launches the native camera with auto-capture framing. Align the check inside the frame and hold still; the camera auto-detects edges and captures. **Clear** wipes both captures so you can retake; **Deposit Check** submits.

![Step 3: Capture Front and Back](../.gitbook/assets/Screenshot_1776963664.png)

#### Step 4: Endorse and Retain

The on-screen instruction reads: *"Endorse the back of your check with your signature, and 'for mobile deposit only at Summerville.'"* The restrictive endorsement is the fraud control that prevents double-deposit. *"Please retain your check in a secure place until it is reflected in your account balance"* is the reminder to hold the paper check through any hold window. The **Holds may apply** notice at the top is the member-facing surface of the FI's Reg CC funds-availability rules.

![Step 4: Endorse and Retain](../.gitbook/assets/Screenshot_1776963667.png)

#### Step 5: Quick Actions — Set Default / History / Stop Payment

Below the capture panel, three row actions persist across every visit to the Deposit tab: **Set Default Account** pre-selects the deposit destination for future submissions, **Check Deposit History** opens the audit list of past RDC submissions and their statuses, and **Stop Check Payment** is the entry point for stopping an outbound check you wrote (co-located here because it's the other major check-related action).

![Step 5: Quick Actions — Set Default / History / Stop Payment](../.gitbook/assets/Screenshot_1776963667.png)

### Summary

RDC is the highest-ROI self-service feature for a community FI — it eliminates a branch trip for every paper check — and the friction in the experience is the fraud-control layer, not the tech. The restrictive-endorsement instruction, the retain-the-check reminder, and the funds-availability hold notice are all calibrated to match Reg CC and the FI's risk posture. Stop Check Payment sits on the same screen because members who are in "thinking about checks" mode are the ones most likely to realize they need to stop one. The **Long press to set as default page** hint at the bottom is a power-user shortcut that pins this screen as the default landing.

### Key Use Cases

* Business owner depositing a vendor rebate check on a Saturday: capture, endorse, submit, funds available per posted hold policy.
* Member asks why their deposit hasn't cleared: **Check Deposit History** shows per-item status (Submitted / In Review / Posted / Held) and the specific hold reason.
* Member realizes they wrote a check to the wrong payee: Stop Check Payment from the Deposit tab routes into the stop-payment flow without navigating away.
