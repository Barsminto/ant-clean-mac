# Release notes

Download the installer from the [website](https://zimuai.top/download/Ant-Clean-Mac-1.1.0-arm64.dmg). This page records version changes and does not include the installer.

## 1.1.0 (build 10)

November 18, 2026

- When a newer version is available, the sidebar can download the installer, replace the running app and reopen it. The update manifest is hosted on the website.
- Process sampling runs only while Overview or Processes is in front. Switching pages or sending the app to the background pauses sampling and lowers CPU use.
- A Battery page has been added, and Overview also shows charge, maximum capacity and cycle count. Values come from the system battery controller. Per-app energy use is not estimated.
- The installer is Developer ID signed, uses Hardened Runtime, and is Apple notarized. The notarization ticket is stapled to the DMG.

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
