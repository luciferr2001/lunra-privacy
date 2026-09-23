# Privacy Policy - Lunra

**Draft - the developer must review and fill in the contact email below
before submitting to Play Console.**

---

Last updated: 2026-09-24

Lunra ("the app") is a menstrual cycle and period tracker developed by
[fill in developer contact email before publishing]. This policy explains
what data the app collects, how it's used, and the choices you have.

## Summary

Lunra is built local-first: your cycle, symptom, mood, and note entries
are stored encrypted on your device, and no account is required to use
the app. Signing in with Google is entirely optional and exists for one
reason - to back up your data to your own Google account and restore it
if you reinstall the app or switch devices. If you never sign in, nothing
you log ever leaves your device.

Because this app handles menstrual cycle data - a sensitive health
category - this policy is deliberately explicit about exactly what is
and isn't collected, and who can see it.

## Data stored locally, always

Whether or not you sign in, the app stores the following on your device
only, encrypted at rest:

- Period start/end dates
- Flow intensity, symptoms, mood, and an optional energy rating you log
- Free-text notes you write
- Cycle length preferences and app settings (reminders, app lock,
  appearance)

This local data is never transmitted anywhere unless you explicitly sign
in (see below). Uninstalling the app deletes it permanently.

## Optional: Google sign-in and cloud backup

If you choose to sign in with Google (Settings -> Backup), the app uses
Firebase Authentication to identify you, and mirrors the data listed
above to Google Firestore, scoped to your account and readable only by
you - no other user or the developer can read another user's data.
Signing in requires Google's own account and consent flow, governed by
Google's Privacy Policy: https://policies.google.com/privacy.

Once signed in:

- Every entry you log is also written to your private Firestore backup.
- Reinstalling the app and signing in again with the same Google account
  restores your data automatically.
- You can delete your cloud backup at any time from Settings ("Delete
  cloud backup") without affecting what's stored on your device.
- Signing out stops further syncing but does not delete data already
  backed up - use "Delete cloud backup" for that.

## No other data collection

This app does not:

- Show ads or use any advertising SDK.
- Use analytics, crash reporting, or any tracking SDK.
- Access your device's camera, microphone, precise location, or contacts.
- Share, sell, or otherwise disclose your data to any third party.
- Use your data for any purpose other than providing the app's own
  features to you.

## App lock

If you enable "App lock" in Settings, the app requires your device's own
PIN, pattern, or biometric unlock (via Android's system authentication)
before it opens. This authentication happens entirely on-device through
Android's own APIs - the app never receives or stores your PIN,
password, or biometric data itself.

## Data retention and deletion

- Local data persists until you delete an entry in-app or uninstall the
  app.
- Cloud backup data persists until you delete it via Settings, or
  request deletion by contacting the developer.

## Children's privacy

Lunra is intended for users who menstruate and is not directed at
children. The app does not knowingly collect data from children.

## Changes to this policy

If the app's data practices change (for example, if a new feature adds
new data collection), this policy will be updated and the "Last updated"
date above will reflect the most recent revision.

## Contact

For privacy questions about this app, contact the developer at:
[fill in developer contact email before publishing]

---

_Developer note: this draft is provided as a starting point only. Host
this file at a public URL before submitting to Google Play - required by
the Health apps declaration and Data Safety form for any app handling
menstrual/reproductive health data._
