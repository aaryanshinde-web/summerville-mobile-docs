# Zelle Send Money

_Summerville Mobile › Move Money › Zelle Send Money_

## Move Money: Zelle — Send Money

> The Zelle integration verifies the member's phone before every send — it's the fraud control that makes person-to-person instant payments reversible-proof enough to run on mobile.

### Step-by-Step Workflow

#### Step 1: Enter 6-Digit Verification Code

After tapping Send in Zelle, the app sends a one-time code to the phone number on file (last 4 shown, e.g., `******9061`) and requires the member to enter it before the payment commits. **Resend Code** is available if the SMS doesn't arrive; **Verify** is the commit. The fine print at the bottom is the required Zelle SMS-consent notice.

![Step 1: Enter 6-Digit Verification Code](../.gitbook/assets/Screenshot_1776962977.png)

### Summary

Zelle in the Summerville app is a per-transaction step-up flow, not a one-time pairing — every send re-verifies via SMS OTP, by design, because Zelle payments are effectively irrevocable once sent. If the member repeatedly fails to receive the code, route them to Profile → Update Phone Number before any more send attempts, because a stale phone number on file is the most common failure mode and it locks them out of Zelle specifically.

### Key Use Cases

* Member sending rent to a roommate: enter amount, pick recipient, receive OTP, enter code, Verify.
* Member's phone number recently changed but not updated in-app: OTP won't land; update phone number first, re-attempt send.
* Fraudster gains app access but not phone: Zelle step-up blocks the send because they can't receive the OTP.
