# DevVault privacy policy

_Last updated: 16 October 2026_

DevVault is a personal app used only by its author. It has no servers and
collects no data.

## Google Drive

When you connect Google Drive, DevVault asks for the `drive.file` permission.
With it the app can see and change only the files it created itself. It
stores one file, `devvault-sync.dvault`, in your Drive. The file is encrypted
on your device with your master password (Argon2id + AES-256-GCM) before it
is uploaded, so neither Google nor anyone else can read its contents.

DevVault does not read any other files in your Drive, does not share data with
third parties and does not use it for advertising or analytics.

## Data on your devices

Everything else stays on your devices in the same encrypted form. The sign-in
token for Google is kept in the operating system's secure storage. You can
disconnect Google Drive in the app at any time, and revoke access at
https://myaccount.google.com/permissions.

## Contact

Questions: open an issue at https://github.com/Nekbakht-M or write to the
email address on that profile.
