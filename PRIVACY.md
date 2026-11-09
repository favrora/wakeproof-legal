# WakeProof Privacy Policy

Effective date: November 6, 2026

WakeProof ("WakeProof", "we", "us") is provided by **David Voskanyan**. Send questions and privacy requests to **Team Beauty AI App** at [team@beautyai.app](mailto:team@beautyai.app). This policy describes WakeProof 1.0.8.

## Local alarm and code data

WakeProof stores alarm times, labels, repeat and cycle settings, date exceptions, saved places, wake-check settings, wake-up history, drafts, profiles, and app preferences on your device. This data supports alarms, scan missions, recovery, and local progress views. No WakeProof account is required.

Camera frames and scanned QR or barcode contents are processed on the device. WakeProof stores a cryptographic hash for a code you scan, rather than retaining its raw scanned value. It does not record or upload camera photographs or video.

If you ask WakeProof to generate a printable QR code, the generated code's raw value is saved locally with the place so the app can display or print it again. Generated QR codes, hashes, place labels, camera images, and configured alarm times are not included in the app's analytics uploads or sent to RevenueCat. Printing or sharing a generated QR PDF uses the destination you choose; shared files and printouts can contain the code and place label you selected.

Native scheduling data and a limited technical journal are also stored locally. On Android, native scheduling records and this journal use device-protected storage to support alarm recovery before the first unlock after a restart. The mission hashing secret and the app's private QR/place database are not moved into that storage. Widgets and Live Activities use a local summary of upcoming alarms and their status.

## App usage analytics

WakeProof uses Amplitude for manually defined app usage and diagnostic events. These can include onboarding and permission steps, screen names, alarm setup outcomes, scan success or failure, mission and wake-check outcomes, feature use, paywall interactions, app and OS versions, device model, language, subscription tier, event timestamps, durations, error codes, and technical identifiers.

Amplitude and RevenueCat identifiers are pseudonymous: they can link events to an installation or purchase profile without requiring a WakeProof account. Usage and purchase events may be connected through these identifiers. Pseudonymous data is not the same as fully anonymous data.

The app keeps a bounded local journal of native alarm operations and structured errors. When app usage analytics is enabled, journal entries may be uploaded to Amplitude when the app runs and a connection is available. The upload contains technical stages, timestamps, identifiers, and error codes, rather than QR values or hashes, camera images, alarm or place labels, or your configured alarm schedule. This journal is not a complete record of every crash or alarm outcome.

The app's Amplitude configuration disables advertising identifiers, IP-address tracking, and location tracking. Autocapture and session replay are disabled; WakeProof does not send screen recordings through Amplitude. Network services still process connection data needed to receive requests under their applicable terms.

## Purchases and server analytics

Apple App Store or Google Play processes WakeProof Pro purchases. RevenueCat manages purchase validation, subscription status, entitlement checks, and restoration. It may process store receipts or purchase tokens, transaction and product identifiers, purchase and renewal times, country or currency, amounts, refund or cancellation information, a pseudonymous app user identifier, and app or device metadata needed for these functions. WakeProof does not receive your full payment-card details from the stores.

RevenueCat's Amplitude integration is enabled. Subscription and purchase events, including purchases, renewals, cancellations, expirations, and applicable financial adjustments, are sent from RevenueCat to Amplitude for purchase and revenue analysis. This server-to-server processing can occur while the app is closed and is separate from the device's app usage analytics setting. It does not include your camera images, QR contents, alarm labels, or local wake-up history.

## Your choices and permissions

You can switch off app usage analytics in WakeProof Settings. This stops new usage and diagnostic uploads from that app/device; queued native journal entries are discarded rather than uploaded while that setting is off. It does not cancel a subscription, stop store or RevenueCat purchase processing, stop RevenueCat's server-sent purchase analytics, or automatically delete previously received analytics records. Contact us for questions or requests about records already held by service providers.

Camera access is used for scanning. Notification, AlarmKit, exact-alarm, full-screen alert, vibration, wake-lock, and foreground-service capabilities are used as applicable to deliver alarms and wake-checks. You can manage permissions in your device settings. The app does not require microphone access or enable advertising.

## Sharing and service providers

WakeProof does not sell personal information. Data is processed with Apple or Google for store purchases and platform services, RevenueCat for purchases and entitlements, and Amplitude for the analytics described above. A print, share, or export action sends the selected file to the service or recipient you choose. Service providers may process information in countries other than your own. We may also disclose information when required by applicable law.

Further provider information:

- [Apple Privacy Policy](https://www.apple.com/legal/privacy/)
- [Google Privacy Policy](https://policies.google.com/privacy)
- [RevenueCat Privacy Policy](https://www.revenuecat.com/privacy/)
- [Amplitude Privacy Notice](https://amplitude.com/privacy)

## Retention and deletion

You can delete alarms and saved places and reset the app's local alarm, place, history, draft, and preference database in Settings. Diagnostic queues are bounded; journal entries are removed as acknowledged or discarded, or as older entries are replaced. Resetting the local database does not delete store purchases, provider records, or files you have exported or shared.

Uninstalling normally removes the app's storage container. Operating-system backups, secure-storage behavior, and copies in other apps or printouts can have different retention. A device-only hashing secret may not transfer to a different device, so restored scan missions may require rebinding.

Apple, Google, RevenueCat, and Amplitude retain server-side records under their applicable service arrangements and retention practices, including purchase restoration, support, fraud prevention, and legal requirements. Turning off usage analytics does not automatically erase records already received. Contact us about access or deletion requests; locating pseudonymous records may require an app or purchase identifier.

## Security

WakeProof uses operating-system storage controls and a device-only mission hashing secret in Keychain- or Android Keystore-backed secure storage. Online service communications use encrypted network connections. No security measure is absolute; keep your device and operating system updated.

## Children and privacy requests

WakeProof is not directed to children under 13. If you believe a child has provided information to us, contact **Team Beauty AI App** at [team@beautyai.app](mailto:team@beautyai.app).

Depending on your location, you may have rights to access, correct, delete, restrict, or object to processing, or to complain to a regulator. Contact the address above for questions or to exercise applicable rights.

## Changes

We update the effective date when this policy changes and provide additional notice where required.
