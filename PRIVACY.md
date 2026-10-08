# MySafeBox Privacy Policy

Effective 8 October 2026

MySafeBox is a password and private-information vault. It is built so that your vault stays on your device and the developer never has access to it. This policy explains what the app does with your information.

## The short version

- Your vault is stored only on your device, encrypted with a key that never leaves it.
- The developer runs no servers and collects no data about you: no accounts, no analytics, no advertising, and no tracking.
- A few optional features use services from Apple or Have I Been Pwned. They are described below, along with exactly what they receive.

## Your vault

Everything you save in MySafeBox — logins, notes, cards, IDs, bank details, Wi-Fi networks, photos, and attachments — is encrypted with AES-256 and stored on your device. The encryption key is kept in your device's Keychain and is never sent anywhere. Your master passcode itself is never stored; only a slow, salted PBKDF2 hash used to check it.

The developer cannot see, recover, or reset your vault or your master passcode. If you forget your passcode or lose your device without a backup, your data cannot be recovered.

When you copy a value, it stays on this device only and is cleared from the clipboard automatically after 60 seconds.

## Backups

When you export a backup, MySafeBox creates an encrypted folder protected by your master passcode, and saves it wherever you choose, such as iCloud Drive or another location in the Files app. The developer never receives your backups.

## Face ID, camera, and photos

- **Face ID or Touch ID** is handled by iOS. MySafeBox only learns whether it succeeded.
- **Camera and photo library** access is used only when you choose to add a photo to an item. Photos are encrypted and stored in your vault like everything else.

## AutoFill

If you turn on MySafeBox for AutoFill, iOS can fill your saved logins in other apps and websites. To show suggestions above the keyboard, MySafeBox gives iOS each login's website and username. Passwords are never given to iOS's suggestion list; they're filled in only after you unlock MySafeBox. You can turn suggestions off in MySafeBox's AutoFill settings.

## Sharing with trusted contacts

Sharing is optional and uses Apple's iCloud (CloudKit) in your own iCloud account. When you use it:

- To invite someone, MySafeBox passes their email address to Apple's iCloud so the invitation can reach them.
- Each person's sharing name and public encryption keys are stored in the shared iCloud space between the two of you, so you can verify each other with a safety code.
- Shared items are end-to-end encrypted on your device for each recipient. Apple and the developer cannot read them; only your contact's device can.

This information is stored by Apple under Apple's privacy policy, not by the developer. Removing a contact, or erasing your data, ends the connection: the person who sent the invitation deletes the shared space, and the person who accepted it leaves it.

## Leaked password check

If you choose to check for leaked passwords, MySafeBox uses the Pwned Passwords service from Have I Been Pwned (haveibeenpwned.com). For each password, only the first 5 characters of a scrambled (SHA-1 hashed) form are sent. The service replies with a list of leaked password hashes that start the same way, and the match is made on your device. Your passwords, usernames, and other details are never sent.

The results are saved in your vault, encrypted, so warnings stay visible until you check again.

## Purchases

The Full Version and tips are purchased through Apple's App Store. Apple processes the payment; the developer receives no payment details and only learns, through Apple, that a purchase was made.

## Children

MySafeBox is not directed at children and does not knowingly collect information from anyone.

## Your rights and deleting your data

Because the developer does not collect or hold your personal information, there is nothing held by the developer to access, correct, or delete. You stay in control of everything MySafeBox stores:

- **Erase All Data** (More → Erase All Data…) deletes every item and all sharing data on your device, and ends sharing in iCloud.
- **Deleting the app** removes the vault from your device.
- Backups you exported stay where you saved them until you delete them.
- Data stored in iCloud for sharing is managed by Apple and your iCloud account settings.

## Changes to this policy

If this policy changes, the new version will be included in the app and published with a new effective date.

## Contact

MySafeBox is published by the developer shown as the seller on its App Store page. For questions about this policy, open an issue at github.com/s544v2nj4s/MySafeBox-Support. Please never include passwords or other private data, because issues are public.
