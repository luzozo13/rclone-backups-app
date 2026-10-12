# rclone backups app

A personal backup app. [rclone](https://rclone.org) uses this Google client to copy the owner's encrypted backups (made with [restic](https://restic.net)) to the owner's own Google Drive.

- Used only by its owner. It is not offered to anyone else, and nobody else can sign in to it.
- It asks for one permission: Google Drive `drive.file`, which lets it see and change only the files and folders it created itself. It cannot see the rest of the Drive.
- The backups are encrypted before they leave the owner's server, so Google stores only unreadable data.

Privacy policy: [PRIVACY.md](PRIVACY.md)
