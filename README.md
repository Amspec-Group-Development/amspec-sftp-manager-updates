# AmSpec SFTP Manager - update files

Current version: **0.1.3**

This repository is written by the AmSpec SFTP Manager release pipeline. It contains the installers and the
signed update manifest that installed copies of AmSpec SFTP Manager check. It contains no source code and no
configuration. Do not edit it by hand: installed copies only accept a `latest.json` whose signature
(`latest.json.sig`) was made with the release key, so a manual change simply stops updates.

Both installers need WinFsp 2.1 or later on the PC; it is not part of these files.

| File | Purpose |
|---|---|
| `AmSpec-SFTP-Manager-0.1.3-x64-user.msi` | Installer for a single user (no administrator rights). Auto-update uses this one. |
| `AmSpec-SFTP-Manager-0.1.3-x64.msi` | Installer for all users of a PC (needs administrator rights / Intune). |
| `latest.json` / `latest.json.sig` | Update manifest and its signature. |
