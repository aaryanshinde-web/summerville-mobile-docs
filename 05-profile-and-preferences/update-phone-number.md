# Update Phone Number

_Summerville Mobile › Profile & Preferences › Update Phone Number_

## Profile & Preferences: Update Phone Number

> The phone-number-of-record is used for OTP step-up across Zelle, FedNow, and login — keeping it current is the most common reason members end up in this screen, and the delete-confirmation dialog here is the only thing that stands between a fat-finger and losing OTP access.

### Step-by-Step Workflow

#### Step 1: Confirm Removal

The member has tapped Delete next to a stored number. A **Confirm** dialog asks *"Are you sure you want to remove this phone number?"* — tap **OK** to remove, **Cancel** to keep it. If the member says **OK** the number is deleted immediately and any OTP routing that referenced it will fail on the next attempt.

![Step 1: Confirm Removal](../.gitbook/assets/Screenshot_1776963800.png)

### Summary

Phone number changes on this screen flow back to the core via a sync so OTPs route correctly on the next send — the **Refresh** link at the top (*"Do not see your updated contact information? Refresh"*) pulls the latest core record when a branch update hasn't propagated yet. Before removing a number, always verify at least one other Cellular number remains on file — removing the last cellular is the fastest way to lock the member out of Zelle and FedNow step-up.

### Key Use Cases

* Member switches carriers and gets a new number: add the new one first, verify it, then delete the old.
* Branch updated the number but OTP still going to the old one: tap **Refresh** to pull the fresh core record before deleting.
* Member accidentally taps Delete: **Cancel** in the Confirm dialog reverts without change.
