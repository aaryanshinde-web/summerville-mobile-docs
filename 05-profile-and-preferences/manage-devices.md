# Manage Devices

_Summerville Mobile › Profile & Preferences › Manage Devices_

## Profile & Preferences: Manage Devices

> The trusted-devices list — every phone, tablet, or browser that has logged into the account — with a one-tap **Forget** control and the Remember Device / Trust Device tab split.

**How to get here:** Side Menu (☰) → **Settings** → **Personal Information** → **Manage Devices**

### Step-by-Step Workflow

#### Step 1: Open the Side Menu

Tap the **☰** hamburger icon at the top-right of any screen.

![Step 1: Open the Side Menu](../.gitbook/assets/Screenshot_1776963761.png)

#### Step 2: Tap Settings → Personal Information

In the Side Menu, tap **Settings**, then tap **Personal Information**.

![Step 2: Tap Settings → Personal Information](../.gitbook/assets/Screenshot_1776963778.png)

#### Step 3: Tap Manage Devices

On the Personal Information menu, tap **Manage Devices — Update your linked devices** (the last row). The devices list loads.

![Step 3: Tap Manage Devices](../.gitbook/assets/Screenshot_1776963778.png)

#### Step 4: Review and Forget Devices

The top of the screen shows tabs **Remember Device** and **Trust Device**. Each linked device row shows platform icon, OS version, last-accessed timestamp, and a **Forget** action. Examples: *Google sdk_gphone64_arm64, Android Version 16, Last Accessed 4/23/26 9:51 AM*; *iPhone, iOS Version 26.3.1*; *Online or Desktop, OS X Version 10_15_7*. Tap **Forget** on any device you no longer use or don't recognize.

![Step 4: Review and Forget Devices](../.gitbook/assets/Screenshot_1776963832.png)

### Summary

Remembered devices skip the OTP step on login but still require password; trusted devices can biometric-log without OTP. The split lets you fine-tune the trade-off between friction and security per device — a personal phone gets Trust, a shared home tablet gets Remember only. **Forget** immediately revokes the device from both lists and forces full credential entry + OTP on the next attempt from that device.

### Key Use Cases

* Member loses their phone: Forget that device from another device immediately; full login required for re-enrollment.
* Member wants to downgrade a shared family tablet from Trust → Remember: Forget, then re-pair as Remember-only on next login.
* Security audit: periodically review the list — any device you don't recognize is a Forget + password-change immediately.
