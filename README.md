# StarSide Station — builds

Downloads for **StarSide Station**, a cozy station-life game in the rings of a gas giant. This repo only holds finished builds.

## Play it on Windows

1. Download **[StarSide-Launcher-windows.zip](https://github.com/Daytacorp/StarSide-Station-builds/raw/main/StarSide-Launcher-windows.zip)**.
2. Unzip it anywhere and run **StarSide Launcher.exe**.
3. Windows may say *"Windows protected your PC"* because the launcher isn't code-signed yet. Click **More info**, then **Run anyway**. You only see this the first time.
4. Click **Install**, then **Play**.

## Play it on a Mac

1. Download **[StarSide-Launcher-macos.zip](https://github.com/Daytacorp/StarSide-Station-builds/raw/main/StarSide-Launcher-macos.zip)**. Safari unzips it to **StarSide Launcher.app**; drag that into Applications.
2. Open it. macOS will say it can't check the app for malware, because it isn't from a registered Apple developer yet. Click **Done**.
3. Open **System Settings → Privacy & Security**, scroll down, and click **Open Anyway** next to "StarSide Launcher". Confirm, and it opens. You only do this once.
   (On older macOS: right-click the app, choose **Open**, then **Open**.)
4. Click **Install**, then **Play**.

## After that

Just open the launcher. It checks for new builds every time, shows what's new, and downloads only what changed.

- **Windows:** the game lives in `%APPDATA%\StarSide Launcher\game`; saves in `%APPDATA%\Godot\app_userdata\StarSide Station`.
- **Mac:** the game lives in `~/Library/Application Support/StarSide Launcher/game`; saves in `~/Library/Application Support/Godot/app_userdata/StarSide Station`.
- The launcher's **Game folder** button opens the game's folder. Updates and reinstalls never touch your saves.

## Found a bug?

Tell Weston. Say which version the launcher shows, what you were doing, and what happened.
