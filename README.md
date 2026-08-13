# Aurora Player

Aurora Player is a modern, feature-rich local desktop music player built with Python and PySide6. It offers a simple interface, queue management, and seamless Discord Rich Presence integration. 

## ✨ Features

*   **Broad Audio Support:** Play your local audio files, including MP3, WAV, FLAC, OGG, M4A, AAC, and many more.
*   **Discord Rich Presence (RPC):** Show off what you are listening to on Discord in real-time.
*   **Smart Cover Art Fetching:** Automatically searches for missing cover art via YouTube Music (no API key required) or TIDAL (custom API key supported).
*   **Discord Cover Art Uploads:** If no online cover art is found, the app automatically extracts embedded metadata images and uploads them temporarily to services like Catbox or 0x0.st to display on your Discord profile.
*   **Customizable Theming:** Tailor the UI to your liking with Dark/Light modes, customizable accent colors, and dynamic blurred backgrounds that adapt to your currently playing album art.
*   **Session Persistence:** Never lose your spot; Aurora Player remembers your queue, last played track, and exact playback position upon exit.
*   **Advanced Queue Management:** Supports drag-and-drop file loading, playlist shuffling, alphabetical sorting, and single-track or full-queue looping.
*   **Uninterrupted Playback:** Minimize or close the application straight to your system tray to keep the music playing in the background.
*   **Single-Instance Engine:** Opening an audio file from your OS file explorer will seamlessly append it to your running queue instead of launching multiple application windows.

![Aurora Player Preview](https://i.imgur.com/d1puQto.png)

> **This application is still in a work-in-progress state.**

## 🚀 Installation

This application is provided as a baked portable executable. **You do not need to install Python, dependencies, or any requirements to run this.** 

1. Download the latest release from the [Releases page](https://github.com/Arikizu/Aurora-Player/releases).
2. Move the downloaded application to your preferred location. (App creates config file in "Aurora Player" folder placed in user documents.)
3. Launch `Aurora_Player.exe` file.
4. Drag and drop audio files directly into the window, or use the **+ Files** / **+ Folder** buttons to create your queue.

> **Note on Antivirus/Windows Defender:** Because this is a compiled `.exe` file without a paid publisher certificate, Windows SmartScreen or your antivirus software might flag it as an unrecognized app. If this happens, click **"More info"** and then **"Run anyway"**.

## ⚙️ Configuration

You can access the **Settings** menu by clicking the gear icon "⚙" on the main interface. From there, you can configure:
*   **Appearance:** Toggle dark mode and input custom HEX codes for your accent and background colors.
*   **System Behavior:** Enable auto-play on startup, toggle the system tray icon, and configure whether external files should immediately play or queue.
*   **Integrations:** Enable or disable Discord RPC and select your preferred cover art lookup methods - YouTube Music and TIDAL.

> **YouTube covers are ready to use without any configuration, while TIDAL requires configuration such as an App ID and a secret key.**


You can support me on:

[![buycoffee.to](https://buycoffee.to/img/brand/bc-logo.svg)](https://buycoffee.to/arikizu)

## 📝 License

Distributed under the Creative Commons Attribution-NonCommercial 4.0 International License (CC BY-NC 4.0). See `LICENSE` for more information.
