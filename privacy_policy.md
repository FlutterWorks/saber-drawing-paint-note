# Saber's Privacy Policy

Saber is an application developed by Adil Hanney that
facilitates the user in creating and organising handwritten notes.

This privacy policy may be updated from time to time.
You can view the latest privacy policy at
[saber.adil.hanney.org/privacy-policy](https://saber.adil.hanney.org/privacy-policy),
and you can view the history of changes to the privacy policy on
[GitHub](https://github.com/saber-notes/saber/commits/main/privacy_policy.md).

## What data does the application use?

The application seeks to access the least amount of data possible
and uses a zero-trust approach to cloud storage.

Data the application uses includes the user's:
- Notes (including images and backgrounds): Used for the main functionality of the application
- In-app settings: Used to customise the application to the user's preferences
- Online cloud service (referred to as "the cloud") credentials including the server URI, username, and passwords: Used to enable syncing between devices

## Ads

Saber has been ad-free since September 2024.
If you are using a version of the application older than v0.4.7,
please update to the latest version.

## How is the cloud used?

The cloud is used to store and sync the user's notes and settings
between the user's devices but is not necessary for the application to function.

To use this feature, users need to make an account on a Nextcloud server
of their choice to use as a cloud service.
For users who don't want to choose a custom Nextcloud server,
the official Saber server — run by Adil Hanney — is hosted at
[nc.saber.adil.hanney.org](https://nc.saber.adil.hanney.org).

To maintain privacy, all notes are encrypted before being sent to the cloud.
A randomly generated key is used to encrypt the notes.
This key and password are stored on the user's device in secure storage,
and an encrypted form of the key is uploaded to the cloud.

### My notes are private, right?

With any cloud storage, the server owners can see and read any files you upload.
This is why Saber encrypts your notes before uploading them to the cloud,
so they're unreadable to the server owner.

### So what data can the server owners see?

- All information provided during the sign-up process, including but not limited to your username and email address.
- Information about any device that connects to the server, including but not limited to the device's operating system, browser, and IP address.
- An encrypted (scrambled) form of your notes. The server owner cannot read the notes, but they can see metadata like:
  - The size of each note.
  - The number of notes you have.
  - The encrypted names of your notes.
  - The last time you edited a note, when it was created, and when you last synced.
- An encrypted (scrambled) form of your encryption key. This is required to enable cross-device syncing.
- Nextcloud is general-purpose software, so the server owner can see any other files you upload
  to the server and information you provide outside of Saber.

## “Talk is cheap. Show me the code.”

The source code is free and open to the public under the
[GPLv3 license](https://github.com/saber-notes/saber/blob/main/LICENSE.md)
and is available on [GitHub](https://github.com/saber-notes/saber).

## How can I delete my data?

How you can delete your data will vary based on which cloud provider you use.
1. If you don't use a cloud provider, your data is only stored on your device.
  If you delete the app, your data will be deleted with it. Desktop users will
  also need to delete the `Saber` folder in your Documents folder.
2. If you use the default cloud provider, you can head to the
  [account deletion page](https://nc.saber.adil.hanney.org/index.php/settings/user/drop_account)
  by going to Settings then "Delete account". You'll get an email with a link to confirm
  the deletion of your account. Once you click the link, your account will be deleted after
  a 1 week grace period. If you change your mind, contact me at
  [adilhanney@disroot.org](mailto:adilhanney@disroot.org) and I'll cancel the deletion.
3. If you use a third-party Nextcloud server, there may be a "Delete account" option in the Settings.
  If not, you may need to contact the server administrator to delete your account.
  You should see the server's privacy policy for more information.

## Privacy point of contact

This application is developed by Adil Hanney.
You can contact me at [adilhanney@disroot.org](mailto:adilhanney@disroot.org) for any enquiries,
or [create an issue](https://github.com/saber-notes/saber/issues/new/choose)
on this repo (requires a GitHub account).
