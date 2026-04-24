# Update Phone Number

_Summerville Mobile › Profile & Preferences › Update Phone Number_

## Profile & Preferences: Update Phone Number

> The phone-number-of-record is used for OTP step-up across Zelle, FedNow, and login — keeping it current is the most common reason members end up on this screen.

### Step-by-Step Workflow

#### Step 1: Open the Side Menu

Tap the **☰** hamburger icon at the top-right of any screen. The Side Menu drawer slides in.

![Step 1: Open the Side Menu](../.gitbook/assets/Screenshot_1776963761.png)

#### Step 2: Tap Settings

In the Side Menu, tap **Settings — Account and security settings**.

![Step 2: Tap Settings](../.gitbook/assets/Screenshot_1776963761.png)

#### Step 3: Open Personal Information

Inside Settings, tap **Personal Information** to open the menu of contact-data actions.

![Step 3: Open Personal Information](../.gitbook/assets/Screenshot_1776963778.png)

#### Step 4: Tap Phone Number

On the Personal Information menu, tap **Phone Number — Update phone number** (the first row). The Update Phone Number screen loads with your phone numbers on file.

![Step 4: Tap Phone Number](../.gitbook/assets/Screenshot_1776963778.png)

#### Step 5: Confirm Removal (If Deleting)

Tapping **Delete** next to a stored number opens a **Confirm** dialog: *"Are you sure you want to remove this phone number?"* — tap **OK** to remove, **Cancel** to keep it. Once you tap **OK** the number is deleted immediately and any OTP routing that referenced it will fail on the next attempt.

![Step 5: Confirm Removal](../.gitbook/assets/Screenshot_1776963800.png)

### Summary

Phone number changes on this screen flow back to the core via a sync so OTPs route correctly on the next send. The **Refresh** link at the top (*"Do not see your updated contact information? Refresh"*) pulls the latest core record when a branch update hasn't propagated yet. Before removing a number, always verify at least one other Cellular number remains on file — removing the last cellular is the fastest way to lock yourself out of Zelle and FedNow step-up.

### Key Use Cases

* Member switches carriers and gets a new number: add the new one first, verify it, then delete the old.
* Branch updated the number but OTP still going to the old one: tap **Refresh** to pull the fresh core record before deleting.
* Member accidentally taps Delete: **Cancel** in the Confirm dialog reverts without change.
