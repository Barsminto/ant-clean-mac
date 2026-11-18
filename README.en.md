# Ant Clean Mac

[简体中文](README.md) · **English**

Understand what takes up space before deciding what to remove. Ant Clean Mac brings cleanup, app management and process monitoring to Apple Silicon Macs.

[Website](https://zimuai.top/) · [Download v1.0.2](https://github.com/Barsminto/ant-clean-mac/releases/download/v1.0.2/Ant-Clean-Mac-1.0.2-arm64.dmg) · [Release notes](https://github.com/Barsminto/ant-clean-mac/releases/tag/v1.0.2) · [Report an issue](https://github.com/Barsminto/ant-clean-mac/issues)

## When it helps

- Find caches, development leftovers and large files as disk space fills up.
- Sort an expanding app collection by size or usage information and inspect related files.
- Manage startup items or investigate resource-heavy processes and port connections.
- Review results locally and choose a cleanup scope rather than deleting blindly.

## Features

### System overview
See storage, memory, CPU, uptime and resource-heavy processes. These are observations of current activity, not a promise of a fixed performance improvement after cleaning.

### Processes and ports
Inspect resource usage, historical graphs, parent/child processes and network or port connections. You can terminate selected processes; termination or force termination may interrupt tasks and connections or discard unsaved work.

### System junk
Scan areas including system caches, app logs, Xcode and language-development leftovers. Review and select results before cleaning. Caches can be rebuilt, and development tools may later need to download or compile files again.

### App uninstallation
Filter and sort by size, recent installation or usage information, and inspect related configuration and leftover files. Usage, installation dates and “never used” classifications rely on Spotlight metadata and available file timestamps. Missing records do not prove an app was never opened. Related-file detection is not guaranteed to be exhaustive or exclusive to one app.

### Startup management
Inspect LaunchAgents and LaunchDaemons and batch-enable, disable or remove items. Batch operations requiring elevated access combine administrator authorization requests. Changes can affect services; an unfamiliar item is not necessarily junk.

### Large files
Find files using thresholds such as 50 MB, 100 MB, 250 MB or 500 MB. Review sizes and remove selected items without clearing every result. Confirm what a file is for first.

### Privacy cleanup
Review selected local browser traces, message attachments and related data. Confirm what you need to keep and quit relevant apps before cleaning. macOS access restrictions may prevent some files from being inspected or changed.

## Actual app screenshots

These captures show the Chinese interface. Process lists are redacted for privacy; metrics reflect capture time. Tool screens are shown before scanning.

![System overview showing storage, memory, CPU and quick tools, with process lists redacted](https://zimuai.top/assets/app-dashboard-20261116.webp)

<details>
<summary>View system junk and large-file screens</summary>

![System junk scan scope before scanning](https://zimuai.top/assets/app-system-junk-20261116.webp)

![Large-file size thresholds with no personal files shown](https://zimuai.top/assets/app-large-files-20261116.webp)

</details>

## Requirements

- Apple Silicon (M series), **arm64 only; Intel Macs are not supported**.
- macOS 15 or later.
- Current release: **1.0.2 (build 9)**. The interface supports Simplified Chinese and English. Starting with this release, the sidebar shows the version and can open a newer official download.

## Download and install

1. [Download the official DMG](https://github.com/Barsminto/ant-clean-mac/releases/download/v1.0.2/Ant-Clean-Mac-1.0.2-arm64.dmg) or read the [release notes](https://github.com/Barsminto/ant-clean-mac/releases/tag/v1.0.2).
2. Open it and drag **Ant Clean.app** to **Applications**.
3. Launch from Applications. Start by reviewing status, choosing a scan scope and checking the results.

This release is **Developer ID Application signed**, uses Hardened Runtime and a secure timestamp, and is **Apple notarized**. The DMG has a stapled notarization ticket. Signing and notarization do not guarantee that software has no defects.

To verify your download, obtain [SHA256SUMS](https://github.com/Barsminto/ant-clean-mac/releases/download/v1.0.2/SHA256SUMS) and run:

```bash
shasum -a 256 Ant-Clean-Mac-1.0.2-arm64.dmg
```

Compare the output with SHA256SUMS from the same release, not a different version.

## First use and permissions

- Choose Chinese or English and adjust the monitoring interval in Settings.
- Selected scans and cleanup run locally. The current free client requires no account, login, activation or device registration.
- macOS restricts access to some locations. Grant only permissions whose purpose you understand. Incomplete access can produce incomplete results; it does not prove files are absent.
- System-level startup changes may show a macOS administrator prompt. Review the action first and never include administrator passwords in feedback.

## Before cleaning

**Back up important data and review selected items.** Deletion behavior differs by feature: some file operations try the Trash first but may delete directly if that fails. App uninstallation, some junk-cleaning operations and system-level startup-item removal may also delete directly. Do not assume everything can be recovered from the Trash.

Related files can be shared by other apps. Browser data, attachments and development files may still be valuable. Ending processes can lose unsaved work, and startup changes can affect services. Use the tools only on devices and data you are authorized to manage.

## FAQ

**Is it free? Are there subscriptions or activation?**  
Existing v1.0.2 features are free, without login, activation or device registration. There is no automatic renewal. Donations are optional and do not unlock features or guarantee updates on a schedule.

**Does it need an internet connection?**  
Local scanning, cleanup, monitoring and built-in legal reading do not depend on an account or licensing server. GitHub, website links, downloads and feedback need network access. macOS may also perform its own security checks.

**Why can some files or startup items not be handled?**  
System protection, access permissions, files in use or administrator authorization may limit actions. Review their purpose and permissions; do not lower system security just to clean files.

**Does uninstalling remove every leftover?**  
It finds recognizable related files, but cannot guarantee every location is covered. Be careful with shared data.

**Where are the privacy policy and terms?**  
Read the [privacy policy](https://zimuai.top/privacy/) and [terms of use](https://zimuai.top/terms/). Settings also includes full offline Chinese and English documents. The website has access logs and a language preference, and historical services have separate data-handling boundaries; see the policy for details.

## Feedback

Use [GitHub Issues](https://github.com/Barsminto/ant-clean-mac/issues) and include the app version, macOS version, chip model, reproduction steps, expected and actual behavior, and only necessary **redacted** screenshots.

Do not post personal files, usernames/private paths, tokens, license keys, full logs or passwords publicly. For privacy requests, first send only a non-sensitive contact request to arrange an appropriate channel.

## Voluntary support

Stars, shares, suggestions and optional donations support maintenance. Donations do not unlock features or create a subscription.

<details>
<summary>Support via Alipay</summary>

![Alipay payment QR code, recipient antiumbo (**阳)](assets/alipay-support.png)

Choose any amount. No feature unlocks. Verify the recipient before paying.

</details>

## About this repository

This repository hosts downloads and feedback, **not the client source code**. Free use does not mean open source or grant redistribution or commercial rights that have not been expressly licensed.

© 2026 Ant Clean Mac. All rights reserved.
