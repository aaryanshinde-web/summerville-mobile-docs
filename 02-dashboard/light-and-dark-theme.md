# Light & Dark Theme

_Summerville Mobile › Dashboard › Light & Dark Theme_

## Dashboard: Light & Dark Theme

> Member-controlled visual preference. The Side Menu lists **Settings** as the entry; the theme picker lives within Settings. System-, Light-, and Dark-mode options are all supported, with System as the default.

### Step-by-Step Workflow

#### Step 1: Open Side Menu → Settings

Tap the hamburger icon to open the Side Menu, then tap **Settings** to enter the preference tree. The theme picker is one of the Display rows inside Settings.

![Step 1: Open Side Menu → Settings](../.gitbook/assets/Screenshot_1776963761.png)

#### Step 2: Pick Theme Mode (Destination Screen)

The theme picker offers three modes: **System** (follows iOS/Android theme), **Light**, or **Dark**. Selection applies immediately without an app restart; brand colors (navy header, signature blue accents) are preserved across both surfaces so the Summerville identity doesn't flip with theme. The destination picker is not included in this capture set — coverage will be added once captured.

![Step 2: Pick Theme Mode — TODO: capture theme picker destination](TODO-theme-picker.png)

### Summary

Theme is a local preference stored on the device, not on the server — a member's choice on their phone doesn't propagate to tablet or web, and reinstalling the app resets to **System**. The three-mode control (with System as the default) matches how iOS and Android natively expose theme preference; respecting the OS-level choice is the right default for members who run system-wide dark mode at night.

### Key Use Cases

* Member on system-wide dark mode: no action needed — the app picks up dark automatically on first launch.
* Accessibility preference for high contrast: set Dark explicitly to pin the theme regardless of system setting.
* Member switches phones: new device defaults to System; re-pin only if they used Light or Dark explicitly.
