# CloudPool

All your storage accounts, pooled into drives. CloudPool signs in to as many
cloud accounts as you own, from free Google Drive (15 GB), MEGA (20 GB) and
TeraBox (1 TB) accounts to OneDrive, Dropbox, GitHub, S3 buckets and your own
NAS (59 kinds in all), and shows them as drives you can upload to, keep in
sync both ways, share links from, open in Finder or File Explorer, and use
from your phone.

**Website, setup guide and questions: https://cloudpool.vercel.app**

This repository publishes the CloudPool installers. Get the newest one from
the [download page](https://cloudpool.vercel.app/download), which picks the
right file for your computer, or from
[Releases](https://github.com/zubairkhan778/cloudpool/releases/latest).

| System | File |
|---|---|
| Mac with Apple Silicon (M1 and newer) | `CloudPool-Mac-AppleSilicon.dmg` |
| Mac with Intel | `CloudPool-Mac-Intel.dmg` |
| Windows 10 and 11, 64-bit | `CloudPool-Windows-x64-Setup.exe` |
| Windows 10, 32-bit | `CloudPool-Windows-x86-Setup.exe` |
| Windows on ARM | `CloudPool-Windows-ARM64-Setup.exe` |
| Ubuntu, Debian, Mint (x86_64 / ARM64) | `CloudPool-Linux-amd64.deb`, `CloudPool-Linux-arm64.deb` |
| Any Linux (x86_64 / ARM64) | `CloudPool-Linux-x86_64.AppImage`, `CloudPool-Linux-arm64.AppImage` |
| iPhone and Android | the web app at https://cloudpool.vercel.app/app |

Each release lists SHA-256 checksums in `SHA256SUMS.txt`.

The installers are not signed with a paid Apple or Microsoft certificate yet,
so the first launch needs one extra click. The
[download page](https://cloudpool.vercel.app/download) shows exactly what to
click on each system.

Using CloudPool on several computers? Update all of them to the same version:
older versions keep working with your login but do not see newer drives or
kinds of accounts.

Found a problem? [Open an issue](https://github.com/zubairkhan778/cloudpool/issues)
with what you did and what happened.

The names of the storage services CloudPool connects to are trademarks of
their respective owners, who are not connected with CloudPool.
