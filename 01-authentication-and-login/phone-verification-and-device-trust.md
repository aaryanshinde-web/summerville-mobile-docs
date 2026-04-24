# Phone Verification & Device Trust

_Summerville Mobile › Authentication & Onboarding › Phone Verification & Device Trust_

## Authentication & Onboarding: Phone Verification & Device Trust

> A silent outbound SMS from the member's own phone proves the device is the one tied to the account on file — this is the trust signal that unlocks lighter-weight step-up later in the session.

### Step-by-Step Workflow

#### Step 1: Verify Your Phone Number

The app explains why it's asking for SMS permission — to confirm the SIM matches the number on record. Make sure the member grants phone and SMS permissions and that cellular data (not just Wi-Fi) is enabled so the verification text can actually send from the device.

![Step 1: Verify Your Phone Number](../.gitbook/assets/Screenshot_1776962642.png)

### Summary

Device trust is the difference between a one-touch biometric login and a full OTP step-up on every session, so getting through this verification cleanly the first time saves friction for every subsequent login. The two common failure modes are denied SMS permissions and Wi-Fi-only devices that can't send the outbound text — both are surfaced on this single screen so support doesn't need to guess.

### Key Use Cases

* First-time enrollment on a personal phone: grant SMS permission, complete verification, device becomes trusted for biometric login.
* Member swaps SIMs or gets a new phone: Verify Your Phone Number runs again automatically on first launch and re-trusts the device.
* Tablet or Wi-Fi-only device: verification will fail by design — direct the member to enroll on their primary phone first.
