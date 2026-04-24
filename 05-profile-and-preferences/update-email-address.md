# Update Email Address

_Summerville Mobile › Profile & Preferences › Update Email Address_

## Profile & Preferences: Update Email Address

> Multi-email profile with per-email edit and a uniqueness validation that rejects duplicate addresses — similar pattern to phone numbers but with email-specific delivery implications.

**How to get here:** Side Menu (☰) → Settings → Personal Information → **Email Address**

### Step-by-Step Workflow

#### Step 1: Edit Email With Uniqueness Check

The **Update Email Address** screen shows one or more stored emails (e.g., *Email address 1 — prashant.karpe@tyfone.com*) with an **Edit** button per row. The contextual text reads *"Update the email address you would like to receive alerts and notifications on."* A **Refresh** link pulls fresh core data. When editing, if the new address matches another email already on file, the app throws an **Alert** dialog: *"Please ensure that both email addresses are unique."* — tap **OK** to dismiss and correct the entry.

![Step 1: Edit Email With Uniqueness Check](../.gitbook/assets/Screenshot_1776963812.png)

### Summary

Email is the fallback delivery channel for alerts and eStatement notices, so the uniqueness check isn't cosmetic — allowing duplicates would let a single address double-up on delivery and create compliance ambiguity when the member later claims they didn't receive the notice. The pattern (list + edit + uniqueness validation) matches the phone-number screen because both are identity-verified contact channels; the difference is email bounces don't immediately block sign-in, where a bad phone number blocks OTP.

### Key Use Cases

* Member moves from personal to work email: edit Email address 1, save, old one removed, new one receives alerts.
* Member wants two emails for redundancy (personal + work): add both as separate entries, both receive the same alert categories.
* Member attempts to save a duplicate: alert fires, no save — correct the entry before retrying.
