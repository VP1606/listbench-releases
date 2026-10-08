# Listbench releases

Installers and update files for **Listbench**, a macOS app for drafting and publishing eBay car-parts listings with AI assistance.

This repository holds release builds only. There is no source code here. Installed copies of Listbench check this repository for updates automatically.

## Installing

1. Open the [latest release](https://github.com/VP1606/listbench-releases/releases/latest) and download the `.dmg` file.
2. Open the `.dmg` and drag **Listbench** into **Applications**.
3. Open Listbench. macOS will say it can't verify the developer. Click **Done**.
4. Open **System Settings → Privacy & Security**, scroll down, and click **Open Anyway** next to the Listbench message. Confirm with your password or Touch ID.

You only do this once. Later versions install themselves from inside the app.

**Requirements:** a Mac with Apple silicon (M1 or later) running macOS 26 or later.

## Releases

| Type | Version example | Who gets it |
|---|---|---|
| Release | `0.2.0` | Everyone |
| Pre-release (dev) | `0.2.0-dev.1` | Test installs only |

Pre-releases are work in progress and are not meant for everyday use.

## Why the "Open Anyway" step?

Listbench is signed with its own certificate rather than one issued by Apple, so macOS asks you to confirm it the first time. Updates are signed with the same certificate, and the app only installs updates that match it.

## Support

Listbench needs an account to work. Contact the developer for access or help.
