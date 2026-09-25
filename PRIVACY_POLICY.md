# CoreFast Privacy Policy

_Last updated: September 25, 2026_

CoreFast is an intermittent fasting tracker for iOS and Android. This policy explains what data the app handles and, just as importantly, what it does not.

## Summary

CoreFast does not collect, transmit, or sell your personal data. CoreFast has no backend server, no user accounts, and no analytics. Everything you enter stays on your device.

## What CoreFast stores

CoreFast stores the following locally on your device only:

- Your selected fasting plan and settings (schedule, notification preferences, units)
- Your fasting session history (start/end times, status, optional notes)
- Your daily hydration log
- If you use the optional Sunrise to sunset plan, the location coordinates it needs — see "Location" below
- If the app crashes, a local error log (the error message and a stack trace) so it can show you what happened on your next launch

Your plan, sessions, hydration log, and saved location are encrypted at rest (AES-256-GCM) using a key held in the iOS Keychain or Android Keystore, marked device-only so it is never copied to iCloud Keychain, Android auto-backup, or transferred between devices. The crash log is kept unencrypted in local app storage — it exists only so the app can show you what happened after a crash, and it is cleared as soon as you dismiss that message. None of this data is synced to any server, because CoreFast has no server.

## What CoreFast does not do

- It does not require an account, sign-in, or email address.
- It does not use cloud sync or a remote database.
- It does not use advertising identifiers or show ads.
- It does not use third-party analytics, crash reporting, or tracking SDKs of any kind.
- It does not access your contacts, camera, or photo library.
- It does not read or write Apple HealthKit or Android Health Connect data (this app does not currently integrate with either).
- It does not access your location unless you specifically choose the optional Sunrise to sunset fasting plan — see "Location" below.

## Location

CoreFast only requests your device location if you choose the optional Sunrise to sunset fasting plan, which needs it to calculate that day's sunrise and sunset. The app asks for a single, low-accuracy location reading (not continuous or background tracking) each time you select that plan, and saves the resulting coordinates on-device — encrypted alongside your other settings, the same as everything else CoreFast stores — so the calculation can run each day without asking again. This location is never transmitted to any server or shared with any third party. Choosing any other plan never requests or uses your location, and you can clear a saved location at any time via "Delete all local data" in Settings.

## Notifications

If you enable local reminders, CoreFast schedules notifications directly on your device using the operating system's notification framework. These reminders are generated and delivered entirely on-device; no reminder content is sent to or through any server.

## Backup and export

CoreFast lets you export a backup of your data as a plain JSON file, which you control (for example, saving it to Files or a cloud drive of your choice through your device's own share sheet). Unlike the copy CoreFast keeps encrypted on your device, the exported file itself is not encrypted, so anyone who gets hold of it can read its contents. CoreFast does not upload this file anywhere itself. Because you choose where the exported file goes, you are responsible for the privacy of that destination.

## Data deletion

You can permanently delete all app data from Settings at any time by choosing "Delete all local data." This removes your sessions, preferences, and hydration history from the device and destroys the on-device encryption key. This cannot be undone. Uninstalling the app also removes its local data.

## Children's privacy

CoreFast does not knowingly collect any information from anyone, including children, because it does not collect information at all. The app includes a health and safety disclaimer and is not intended to provide medical advice to any user.

## Changes to this policy

If CoreFast's data practices change (for example, if an optional, opt-in integration such as Apple HealthKit or Android Health Connect is added in a future version), this policy will be updated to describe exactly what is read or written and will remain opt-in only, with no automatic upload to any server operated by us.

## Contact

Questions about this policy can be sent to: corefast.support@icloud.com
