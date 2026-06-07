## IPO Mailbox Manager v1.0.0

Initial private release of **IPO Mailbox Manager**, a Windows utility for reviewing and cleaning Avaya/IP Office CLP mailbox files.

This tool was originally developed during the development of our **Speech2Mail transcription services** to help inspect voicemail mailbox exports, identify file types correctly, and safely clean up old voicemail data while preserving protected system audio.

Learn more about Speech2Mail at [https://Speech2Mail.ca](https://Speech2Mail.ca).

## Highlights

- Review CLP mailbox files in a searchable, sortable grid.
- Separate **Voicemails**, **Auto Attendants**, **Greetings**, **Announcements**, **All Files**, and **Backups** into dedicated tabs.
- Delete all voicemails for a selected user.
- Delete voicemails older than a selected number of days.
- Preserve protected Auto Attendant, Greeting, and Announcement files during cleanup.
- Move deleted voicemail files into a backup folder instead of permanently deleting them.
- Restore individual backup files.
- Restore all backup files for a selected user.
- Restore all files from the backup folder.
- Clear backup folders when they are no longer needed.
- Play CLP voicemail audio directly from the app.
- Right-click voicemail actions for play and delete.
- Double-click voicemail playback.
- Multi-select support for deleting multiple voicemail files.
- Export parsed mailbox data to JSON.

## Requirements

- Windows x64
- Microsoft .NET 8 Windows Desktop Runtime

## Release Package

Download and extract the release zip, then run:

`IPO Mailbox Manager.exe`

This release package contains the compiled app only. Source code is not included in the release zip.
