# Privacy Policy - Lunra

Last updated: 2026-09-25

Lunra ("the app") is a menstrual cycle and period tracker developed by
Rutik Rathod (contact: rathodrutik05@gmail.com). This policy explains
what data the app collects, how it's used, and the choices you have.

## Summary

Lunra is built local-first: your cycle, symptom, mood, and note entries
are stored encrypted on your device, and no account is required to use
the app. Signing in with Google is entirely optional and exists for one
reason - to back up your data to your own Google account and restore it
if you reinstall the app or switch devices. If you never sign in, none
of what you log ever leaves your device.

Because this app handles menstrual cycle data - a sensitive health
category - this policy is deliberately explicit about exactly what is
and isn't collected, and who can see it.

## Data stored locally, always

Whether or not you sign in, the app stores the following on your device
only, encrypted at rest:

- Period start/end dates
- Flow intensity, symptoms, mood, and an optional energy rating you log
- Basal body temperature, cervical mucus, and medications/supplements
  you log
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

## App usage and crash diagnostics

The app uses Firebase Analytics, Firebase Crashlytics, and Firebase
Performance Monitoring to understand how the app is used and to fix
bugs and crashes. This is separate from - and never merged with - your
cycle/health data described above. Specifically:

- **Analytics**: a small set of event names (e.g. "a period was logged,"
  "a PDF export was completed," "onboarding finished") and coarse
  counts (e.g. how many fields were filled in on a log entry). Event
  data never includes symptom text, notes, dates you logged, or any
  other cycle content.
- **Crashlytics**: if the app crashes, a stack trace and basic device/OS
  information (model, Android version, app version) is sent so the
  crash can be diagnosed and fixed. Crash reports do not include your
  cycle data.
- **Performance Monitoring**: app start-up time and how long a PDF
  export takes to generate, to catch and fix slowness.

These tools use Google's Firebase Analytics/Crashlytics infrastructure
and are tied to an anonymous installation identifier, not your name,
email, or Google account. This data is never used to personalize the
ads shown in the app (see below) and is never sold or shared with
advertisers.

## Advertising

The app shows non-personalized ads via Google AdMob. Ad requests are
explicitly marked non-personalized, so they are not based on your
activity in this app or elsewhere. See Google's AdMob policies for how
ad delivery itself works: https://policies.google.com/technologies/ads.

## No other data collection

This app does not:

- Access your device's camera, microphone, precise location, or
  contacts.
- Share, sell, or otherwise disclose your cycle/health data to any
  third party.
- Use your cycle data for any purpose other than providing the app's
  own features to you.

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
- Analytics/Crashlytics/Performance data follows Firebase's standard
  retention periods and is not retrievable per-user since it isn't tied
  to your identity.

## Children's privacy

Lunra is intended for users who menstruate and is not directed at
children. The app does not knowingly collect data from children.

## Changes to this policy

If the app's data practices change (for example, if a new feature adds
new data collection), this policy will be updated and the "Last updated"
date above will reflect the most recent revision.

## Contact

For privacy questions about this app, or to request deletion of your
cloud-backed-up data without using the app, contact the developer at:
rathodrutik05@gmail.com
