# Trust This Device Prompt

_Summerville Mobile › Authentication & Onboarding › Trust This Device Prompt_

## Authentication & Onboarding: Trust This Device Prompt

> The post-login modal that promotes the device from "Remembered" to "Trusted" — skipping future OTP step-up for this specific device.

### Step-by-Step Workflow

#### Step 1: Trust This Device Modal

After successful login on a previously unknown device, the Dashboard loads with an overlay modal: shield icon, *"Not Everything's Unlocked Yet!"*, body text *"To protect your account, some actions may require extra verification. Trust this device for full access and skip future extra verifications on this device."* **Ok** proceeds to trust the device; dismissing the modal keeps the device in Remembered status only.

![Step 1: Trust This Device Modal](../.gitbook/assets/Screenshot_1776962732.png)

### Summary

"Remembered" and "Trusted" are two different security postures on the same device — Remembered skips the member-ID prompt on repeat login, Trusted additionally skips the OTP step-up. This modal is the promotion path. Surfacing it on the Dashboard (not buried in Settings) is deliberate — members are most likely to act on trust prompts immediately after successful login, not on a later visit to preference screens. The modal doesn't force a choice — dismissing it is fine and the device remains Remembered; the member can promote later via Manage Devices.

### Key Use Cases

* First login on a new personal phone: trust the device, biometric login works without OTP next time.
* First login on a borrowed / shared device: dismiss the modal; device stays Remembered only, OTP required on every login.
* Member realizes they accidentally trusted a shared device: Profile → Manage Devices → Forget to revoke, re-trust next time.
