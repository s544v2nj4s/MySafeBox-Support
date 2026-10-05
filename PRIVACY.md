# MySafeBox Privacy Policy

_Last updated: October 5, 2026_

MySafeBox is designed so that your data stays yours. The developer does not collect, store, or have access to any of your personal data.

## Summary

- **No data collection.** MySafeBox has no accounts, no analytics, no advertising, and no tracking.
- **Your vault stays on your device**, encrypted.
- **Backups and shared items are encrypted** before they leave your device.
- The developer runs **no servers** and receives none of your data.

## Data stored on your device

Items you add (passwords, cards, IDs, banking details, Wi-Fi networks, notes, photos, and attachments) are stored only on your device. They are encrypted with AES-GCM, using a key kept in the iOS Keychain that never leaves the device. Your master passcode is never stored. Only a salted PBKDF2 hash of it is kept, to check the passcode when you unlock.

**Face ID / Touch ID** is handled entirely by iOS. MySafeBox only receives a yes/no result and never has access to your biometric data.

**Clipboard.** When you copy a value, it's kept on this device only and cleared automatically after 60 seconds.

## Backups

When you export a backup, the file is encrypted with a key derived from your master passcode. It's saved wherever you choose, such as iCloud Drive. The developer has no access to backup files, and they can't be opened without your passcode.

## Sharing with trusted contacts

If you use sharing, MySafeBox uses Apple's iCloud (CloudKit) to connect you with the people you invite:

- **Shared items are end-to-end encrypted** on your device for each recipient. Apple and the developer can't read them.
- **Your contact card** contains the display name you choose and public encryption keys. It's visible only to the contacts you connect with.
- **Invitations.** The email address you enter is used to look up the person's Apple Account through iCloud and to prepare the invitation. Your list of contacts is stored encrypted on your device.

This data is stored in your iCloud account and your contacts' iCloud accounts, under Apple's [privacy policy](https://www.apple.com/legal/privacy/). Stopping a share deletes that item's shared copies. Removing a contact or erasing your vault ends the connection, removing both people's access to everything shared through it.

## Purchases

Purchases (the Full Version and optional tips) are processed by Apple through the App Store. The developer doesn't receive your payment details or personal information.

## Children

MySafeBox doesn't knowingly collect any information from anyone, including children.

## Deleting your data

- **Erase Vault** (More (…) → Erase Vault…) deletes all items and sharing data from your device and ends sharing in iCloud.
- **Deleting the app** removes the vault from your device.
- Backup files you exported stay where you saved them until you delete them.

## Changes to this policy

If this policy changes, the updated version will be posted here with a new "Last updated" date.

## Contact

Questions about privacy? [Open an issue](https://github.com/s544v2nj4s/MySafeBox-Support/issues/new). Please don't include any private data.
