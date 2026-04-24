# Trust This Device

_Summerville Mobile › Authentication & Onboarding › Trust This Device_

## Authentication & Onboarding: Trust This Device (Post-Login Prompt)

> After you log in on a new phone, the app asks whether to promote it from "Remembered" to "Trusted." Trusted devices skip the OTP step on future logins and high-value actions.

### Step-by-Step Workflow

#### Step 1: Trust This Device Prompt

After successful login on a previously untrusted device, the Dashboard loads and an overlay modal appears: shield icon with a checkmark, heading *"Enhance Security by Trusting This Device"*, body text *"You can now trust this device to ensure quick and secure logins without One-Time Passcode and approve/deny transactions. Safety Tip: Trust only your personal devices. Avoid using public or shared devices for added security."* Two buttons: **Not now** and **Trust this device**.

![Step 1: Trust This Device Prompt](../.gitbook/assets/Screenshot_1776962622.png)

#### Step 2: Alternate Prompt — "Not Everything's Unlocked Yet!"

On a different part of the onboarding, the same idea surfaces with a different framing — a gold shield icon and the text *"Not Everything's Unlocked Yet! To protect your account, some actions may require extra verification. Trust this device for full access and skip future extra verifications on this device."* with an **Ok** button. Tap **Ok** to trust the device.

![Step 2: Alternate Prompt — "Not Everything's Unlocked Yet!"](../.gitbook/assets/Screenshot_1776962732.png)

### Summary

"Remembered" and "Trusted" are two distinct security postures on the same device. Remembered skips the member-ID prompt on repeat login but still requires OTP for sensitive actions. Trusted additionally skips OTP step-up for everyday actions, giving you the smoothest login experience on a known personal device. These prompts are surfaced right after login when you're most likely to act; dismissing with **Not now** is fine — the device stays Remembered and you can promote later via Manage Devices.

### Key Use Cases

* First login on your primary personal phone: **Trust this device** — biometric login works without OTP next time.
* First login on a borrowed or shared device: **Not now** — device stays Remembered only, OTP required on every login.
* Accidentally trusted a shared device: Profile → Personal Information → Manage Devices → Forget, re-trust next time on your own phone.
