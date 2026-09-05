# Thumbpad

Turn your Android phone into a wireless **trackpad, keyboard, and media remote** for your Windows PC, over your own local network. No cloud, no account: your remote-control traffic goes only to your paired PC. The app is ad-supported (see [PRIVACY.md](PRIVACY.md)).

This repository hosts the **Windows agent** downloads. The Android app is on Google Play.

## Get it

- **Android app:** <!-- TODO: add Google Play link --> _(coming soon on Google Play)_
- **Windows agent:** [Download the latest release](../../releases/latest) → `thumbpad-agent-X.Y.Z.exe`

## Install the Windows agent

1. Download `thumbpad-agent-X.Y.Z.exe` from the [latest release](../../releases/latest).
2. Run it once. It **installs itself** to `%LOCALAPPDATA%\Programs\Thumbpad\` and adds an icon to the system tray (near the clock). You can delete the file you downloaded.
   - If Windows SmartScreen shows *“Windows protected your PC”*, click **More info → Run anyway**. The build isn't code-signed yet.
3. Optional, from the tray icon's menu:
   - **Start with Windows** launch automatically at login.
   - **Run as administrator** lets the keyboard/trackpad control elevated windows (UAC dialogs, Task Manager, admin terminals).

## Pair your phone

1. Keep the phone and PC on the **same Wi-Fi**. If Windows Firewall asks, allow Thumbpad on **Private** networks.
2. Tray icon → **Pair device…** → a QR code appears.
3. In the app, tap **Pair a PC** and scan the QR. You only pair once.

## Features

- **Trackpad** move, tap, right/middle-click, two-finger scroll, multi-finger gestures.
- **Keyboard** real typing via your phone's keyboard, special keys, and modifier chords (Ctrl/Alt/Shift/Win).
- **Media** now-playing with album art, play/pause/next/previous/seek, volume, and optional phone→PC volume sync.

## Requirements

- Windows 10 or 11 (64-bit)
- Android 8.0 (API 26) or newer
- Both devices on the same local network

## Privacy

Your remote-control activity stays on your local network: input and media commands are encrypted (TLS) and go only to your paired PC. Thumbpad has no accounts and no analytics. It is ad-supported through Google AdMob, which is the only feature that sends data (an advertising identifier) off your device. See [PRIVACY.md](PRIVACY.md).

## Uninstall the agent

1. Tray icon → turn off **Run as administrator** and **Start with Windows**, then **Quit**.
2. Delete `%LOCALAPPDATA%\Programs\Thumbpad\` and `%APPDATA%\Thumbpad\`.

## Support

Create issues under [thumbpad-releases/issues](https://github.com/NCirit/thumbpad-releases/issues) if you encounter any.
