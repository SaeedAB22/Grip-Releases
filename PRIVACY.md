# Grip Privacy Notice

Last updated: 18 September 2026

## Summary

Grip processes call state, compatible actions from the default Phone app, and motion-sensor signals locally on the Android device. Grip does not include Internet access and does not send personal data to the developer or to a remote server.

## Data Grip processes on the device

- Whether the cellular phone is idle, ringing, or in a call.
- The actions exposed by the default Phone app's active call notification, when available, so the user can answer or decline.
- Android may also provide the call notification's title or text to the notification-listener service. In the current beta this content can exist briefly in memory during the incoming call, but it is not displayed, written to storage, or transmitted.
- Accelerometer, gravity, gyroscope, and linear-acceleration signals when available, plus compatible manufacturer grip sensors on supported devices.
- Right- and left-hand calibration values and the last trusted side, stored locally in the app's private preferences.

## Data Grip does not collect or store

- Contacts or address book.
- Call history or call log.
- Phone numbers or caller identities are not retained after the call and are never transmitted.
- Audio, microphone, camera, photos, files, location, or advertising identifiers.
- Raw sensor histories.

## Network and third parties

Grip does not request Android's Internet permission. It has no account system, advertisements, analytics SDK, cloud database, or developer-operated server.

GitHub applies its own privacy practices when you visit this repository, download a release, or submit an issue. Do not include personal call information in public issue reports.

## Local storage and deletion

Calibration and app settings remain in Grip's private local storage. You can delete them by clearing Grip's app data or uninstalling Grip.

## Android permissions

Grip requests only the Android access needed to detect an incoming cellular call, show the overlay, and perform the selected call action. Access can be revoked from Android Settings, but the corresponding feature will stop working.

## Changes

Material changes to this notice will be described in the relevant GitHub release notes.

## Contact

For privacy questions, open an issue without including private information. A private contact channel will be added before a wider public release.
