# Credit Score (SavvyMoney)

_Summerville Mobile › Profile & Preferences › Credit Score (SavvyMoney)_

## Profile & Preferences: Credit Score — SavvyMoney Enrollment

> The first-time credit-score enrollment hands off to SavvyMoney via an in-app webview; the initial form collects the DOB and SSN that SavvyMoney needs to pull the bureau file.

### Step-by-Step Workflow

#### Step 1: SavvyMoney Identity Verification

The embedded webview greets the member ("Hello, Donald Blake") and asks for **Date of Birth (MM/DD/YYYY)** and **Social Security Number** — both required to pull the credit file. The URL bar (`https://creditscoretest.savvymoney.`) makes the third-party handoff visible; **NEXT** advances to the pull, **BACK** returns to the More Menu without creating an enrollment.

![Step 1: SavvyMoney Identity Verification](../.gitbook/assets/Screenshot_1776964140.png)

### Summary

Credit Score is an opt-in SavvyMoney integration, not a native feature — the member's DOB and SSN are captured once during enrollment and then the ongoing score refreshes happen silently without re-entry. Because the form is in a webview to an external vendor, members sometimes hesitate at the SSN field; the correct support script confirms SavvyMoney is a vetted third party and that the credit pull is a **soft inquiry** that doesn't affect the score.

### Key Use Cases

* First-time enrollment: member taps Credit Score in More Menu, completes DOB and SSN, sees their score within a minute.
* Returning to the feature after enrollment: no identity form; score loads directly.
* Member declines: **BACK** exits without creating an enrollment; Credit Score stays available to try again later.
