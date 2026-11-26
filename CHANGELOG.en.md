# Release notes

Download from the [website](https://zimuai.top/download/Ant-Clean-Mac-latest-arm64.dmg) (`Ant-Clean-Mac-1.3.2-arm64.dmg` is the current installer file name). This file records version changes only; it does not include the installer or source code.

## 1.3.2 (build 14)

November 26, 2026

- Fixes in-app update checks that could incorrectly report you are on the latest version.
- Website download always serves the current public build; the in-app feed uses a separate manifest URL with less caching interference.
- Includes the 1.3.0 large-file scan and list improvements and pre-delete dependency review.
- Signed, notarized Developer ID build on the website. This repository does not include the installer or source code.

## 1.3.1 (build 13)

November 26, 2026

- Improves update manifest fetching to reduce false negatives from HTTP caching.

## 1.3.0 (build 12)

November 26, 2026

- Large files: folder tree scan scope with remembered selection; parallel multi-volume scanning with stop.
- Row-wide selection; sort by size, then by modification date when sizes match.
- View dependencies before delete; Trash or permanent delete.
- Signed, notarized Developer ID build on the website. This repository does not include the installer or source code.

## 1.2.0 (build 11)

November 24, 2026

- Before deleting a large file, the app lists apps and related files that may be affected.
- Delete confirmation no longer describes moving an item to the Trash as always recoverable.
- The installer is Developer ID signed and Apple notarized, and is hosted on the website. This repository does not include the installer or source code.

## 1.1.0 (build 10)

November 21, 2026

- The installer is Developer ID signed, uses Hardened Runtime, and is Apple notarized. The stapled DMG is hosted on the website.
- The home screen and sidebar are redesigned. Click the sidebar mark to collapse it to icons.
- System information is grouped text. Process monitoring shows CPU or memory figures centered under the list only while sorting by CPU or memory.
- Settings is an unboxed list and no longer includes an appearance theme switch.
- App uninstall no longer offers an unused sort or badge.
- In-app updates now read the version manifest on the website.

## 1.0.2 (build 9)

November 18, 2026

- The installer is Developer ID signed, uses Hardened Runtime, and is Apple notarized. The notarization ticket is stapled to the DMG.
- The sidebar shows the current version. This build checks GitHub for a newer official release. Installers are now hosted on the website, so this build will not receive an update prompt from GitHub.
- Selecting or clearing all system-junk and large-file results now updates once, instead of freezing the interface on large results.
- The process page initially shows only the list. Each row has a marker that opens its details, and clicking again closes them.
- Sorting and search are labeled separately. Search matches the name, PID, or path under every sort order.
- Uninstall confirmation states that the app and its related files are deleted directly and are not moved to the Trash.

## 1.0.1 (build 2)

November 16, 2026

- The public installer is free, without login, activation, or device registration.
- It is Developer ID signed and Apple notarized.

## 1.0

November 15, 2026

- First public Apple Silicon release.
- It includes a trial or activation and device binding. This is a historical installer, not the current download.
