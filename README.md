# IPO Mailbox Manager

IPO Mailbox Manager is a Windows utility for managing Avaya/IP Office CLP mailbox files.

It was originally developed during the development of Speech2Mail transcription services to help inspect voicemail exports, identify protected audio files, and safely clean up mailbox data.

Learn more at [Speech2Mail.ca](https://Speech2Mail.ca).

## Features

- Review CLP mailbox files in a searchable, sortable grid.
- Separate Voicemails, Auto Attendants, Greetings, Announcements, All Files, and Backups.
- Play voicemail audio directly from the app.
- Delete all voicemails for a selected user.
- Delete voicemails older than a selected number of days.
- Preserve auto attendant, greeting, and announcement files during cleanup.
- Move deleted voicemail files into a backup folder instead of permanently deleting them.
- Restore individual backup files.
- Restore all backup files for a selected user.
- Restore all files from the backup folder.
- Clear backup folders when they are no longer needed.
- Export parsed mailbox data to JSON.

## Requirements

- Windows x64
- Microsoft .NET 8 Windows Desktop Runtime

## Running The App

Download and extract the release zip, then run:

```text
IPO Mailbox Manager.exe
```

## Basic Instructions

1. Safely remove the SD card from the Avaya/IP Office system.
2. Insert the SD card into a card reader connected to your Windows PC.
3. Open IPO Mailbox Manager.
4. Click **Browse**.
5. Browse to the voicemail folder on the SD card:

```text
SYSTEM\DYNAMIC\LVMAIL
```

6. Click **Refresh** if the files do not load automatically.
7. Review the files using the Voicemails, Auto Attendants, Greetings, Announcements, All Files, and Backups tabs.
8. Use the cleanup options to delete voicemails by user or by age.

Protected system audio files, such as auto attendants, greetings, and announcements, are separated from regular voicemails so they are not removed during voicemail cleanup.

## Privacy

The compiled release package does not include source code. Source access and distribution are controlled by Speech2Mail.

## Copyright

Copyright ©2026 By: [S2M Developments](https://Speech2Mail.ca)
