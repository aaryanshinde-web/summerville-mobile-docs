# Zelle Send Money

_Summerville Mobile › Move Money › Zelle Send Money_

## Move Money: Zelle — Send Money

> Zelle is a per-transaction step-up flow with OTP verification before every send — the fraud control that makes instant P2P irreversible-proof enough to run on mobile.

### Step-by-Step Workflow

#### Step 1: Zelle Splash — Move Money in the Moment

The first time a member taps Zelle, the branded splash loads: Zelle logo at the top, hero image, tagline *"Move money in the moment — Simply and securely — with people and businesses you know."*, and **Get Started** at the bottom. Once enrolled, this splash is skipped on subsequent launches.

![Step 1: Zelle Splash — Move Money in the Moment](../.gitbook/assets/Screenshot_1776962953.png)

#### Step 2: Choose How to Receive Money

On first-time setup the member picks a receive endpoint — an email or US mobile number from the on-file list (e.g., *(470) 461-9061, (224) 698-9201, prashant.karpe@tyfone.com, summerville@tyfone.com*). Only one endpoint can be the Zelle identity. Tap **Continue** to proceed.

![Step 2: Choose How to Receive Money](../.gitbook/assets/Screenshot_1776962959.png)

#### Step 3: Enter 6-Digit Verification Code

After tapping Send, the app sends an OTP to the phone on file (last 4 shown, e.g., `******9061`). Enter the code, tap **Verify**. **Resend Code** is available if SMS doesn't arrive. The fine print at the bottom is the required Zelle SMS-consent notice.

![Step 3: Enter 6-Digit Verification Code](../.gitbook/assets/Screenshot_1776962977.png)

### Summary

Zelle in the Summerville app is a per-transaction step-up flow — every send re-verifies via SMS OTP, by design, because Zelle payments are effectively irrevocable. If the member repeatedly fails to receive the code, route them to Profile → Update Phone Number first; a stale phone number on file is the most common failure mode and it locks them out of Zelle specifically. The receive-endpoint choice in Step 2 is a one-time enrollment decision — it can be changed later in Zelle settings but only one endpoint is active at a time.

### Key Use Cases

* Member sending rent to a roommate: enter amount, pick recipient, receive OTP, enter code, Verify.
* First-time Zelle enrollment: splash → pick receive endpoint → continue, ready to send and receive.
* Phone number changed but not updated in-app: OTP won't land; update phone number first, re-attempt send.
