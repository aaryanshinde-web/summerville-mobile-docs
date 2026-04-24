# Update Address

_Summerville Mobile › Profile & Preferences › Update Address_

## Profile & Preferences: Update Address

> Read-then-edit pattern — the current address is shown in a summary card, and the **Edit** button is the only way to enter the modification form.

### Step-by-Step Workflow

#### Step 1: Open the Side Menu

Tap the **☰** hamburger icon at the top-right of any screen.

![Step 1: Open the Side Menu](../.gitbook/assets/Screenshot_1776963761.png)

#### Step 2: Tap Settings → Personal Information

In the Side Menu, tap **Settings**, then tap **Personal Information**.

![Step 2: Tap Settings → Personal Information](../.gitbook/assets/Screenshot_1776963778.png)

#### Step 3: Tap Mailing Address (or Residential Address)

On the Personal Information menu, tap **Mailing Address — Update mailing address** (or **Residential Address — Update residential address** for the separate residential record).

![Step 3: Tap Mailing Address](../.gitbook/assets/Screenshot_1776963778.png)

#### Step 4: Review Current Address

The summary card shows the full structured address on file: **House number**, **City**, **State**, **ZIP Code**, **Country** (e.g., 3049 INDEPENDENCE DR, LIVERMORE, California, 94551, United States). Verify this matches your records; if it's already correct, back out without editing.

![Step 4: Review Current Address](../.gitbook/assets/Screenshot_1776963826.png)

#### Step 5: Edit and Save

Tap **Edit** to open the structured-field edit form. Fields: **House number**, **Street address**, **Country**, **City**, **State** (dropdown), **ZIP Code**. The screen carries a plain-language note *"Please allow one business day for your address change to be processed."* Update the fields and tap **Save** to commit.

![Step 5: Edit and Save](../.gitbook/assets/Screenshot_1776963828.png)

### Summary

Address updates propagate slowly by design — the core takes a few minutes, and downstream services (card reissuance mailing, statement mailing) can take days to pick up the change. Because of that cascade, members changing address just before a card reissuance should confirm with support that the card mail goes to the new address. The structured-field design (house number / city / state / ZIP / country) forces clean data entry instead of a free-text address that would need parsing downstream.

### Key Use Cases

* Member moves within the same state: Edit → change house number, city, ZIP → Save → new statements mail to the new address next cycle.
* Member realizes their card is at the old address: call support from the Help menu to expedite reissuance to the correct address.
* Address is already correct on file: back out — no action needed, and no-op edits still trigger core syncs so avoid them.
