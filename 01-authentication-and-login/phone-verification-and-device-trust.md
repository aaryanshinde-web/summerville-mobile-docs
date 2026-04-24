# Phone Verification & Device Trust

_Summerville Mobile › Authentication & Onboarding › Phone Verification & Device Trust_

## Authentication & Onboarding: Phone Verification & Device Trust

> The two-part first-login security flow on a new phone. First Summerville confirms the SIM in your phone matches your account's phone-on-file (Phone Verification), then it asks whether to promote this device from "Remembered" to "Trusted" so future logins and transactions skip the OTP step (Device Trust).

### Step-by-Step Workflow

#### Step 1: Verify Your Phone Number — Send Verification Message

After your first login on a new phone, the **Verify Your Phone Number** card appears: *"We will send a secure text message from this phone to confirm it matches the phone number on our records. Click 'Send Verification Message' to get started."* Below is an Attention block explaining that phone and SMS permissions are required, and cellular data (not just Wi-Fi) must be enabled. Tap **Send Verification Message**; **Cancel** exits without verifying.

![Step 1: Verify Your Phone Number — Send Verification Message](../.gitbook/assets/Screenshot_1776962625.png)

#### Step 2: Sending Text…

The app initiates the outbound SMS and shows a **"Sending text…"** loading indicator. This usually completes in a few seconds. If the SMS fails (Wi-Fi only, no SIM, permissions denied), the flow surfaces an error.

![Step 2: Sending Text…](../.gitbook/assets/Screenshot_1776962642.png)

#### Step 3: Trust This Device Prompt

Once verification succeeds, your Dashboard loads and an overlay modal invites you to trust the device. The shield icon and heading read *"Enhance Security by Trusting This Device"* with body text *"You can now trust this device to ensure quick and secure logins without One-Time Passcode and approve/deny transactions. Safety Tip: Trust only your personal devices. Avoid using public or shared devices for added security."* Two buttons: **Not now** (keeps the device as Remembered only) and **Trust this device** (promotes to Trusted).

![Step 3: Trust This Device Prompt](../.gitbook/assets/Screenshot_1776962622.png)

#### Step 4: Alternate Prompt — "Not Everything's Unlocked Yet!"

A second trust prompt may appear later in the session: a gold shield icon with *"Not Everything's Unlocked Yet! To protect your account, some actions may require extra verification. Trust this device for full access and skip future extra verifications on this device."* with a single **Ok** button. This is the same idea as Step 3, framed as a call-to-action when you try a high-value action on an untrusted device.

![Step 4: Alternate Prompt — "Not Everything's Unlocked Yet!"](../.gitbook/assets/Screenshot_1776962732.png)

### Summary

Phone Verification is the first layer of device security — it proves the physical phone has your account's SIM on it. Device Trust is the second layer, and the member controls it: trust turns off the OTP step-up on future logins and lets you approve high-value actions without extra verification. Always trust your personal phone; never trust a shared or borrowed device. If you accidentally trust a device you later want to revoke, go to Profile → Personal Information → Manage Devices → Forget.

### Key Use Cases

* First-time setup on a new personal phone: verify phone → trust device → skip OTP on every subsequent login.
* First-time setup on a borrowed or shared device: verify phone → tap **Not now** on the trust prompt → device stays Remembered only.
* Swapping SIMs or moving to a new phone: verification runs again automatically, reset the device trust on the new phone.
* Trusted a shared device by mistake: Profile → Personal Information → Manage Devices → Forget to revoke.
