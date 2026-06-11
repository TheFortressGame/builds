# The Fortress - QA Builds

Playtest builds of **The Fortress**, a medieval fantasy idle tower defense game. This page is for invited testers.

## How to install (Windows)

1. Go to [Releases](https://github.com/TheFortressGame/builds/releases) and open the newest one (top of the list).
2. Download the `TheFortress-win-...zip` file under Assets.
3. Unzip it anywhere (right-click -> Extract All).
4. Run **TheFortress.exe**.
5. First launch only: Windows SmartScreen will warn you because the game isn't signed yet. Click **More info**, then **Run anyway**. This is expected for unsigned playtest builds.

## Why are there two exe files?

- **TheFortress.exe** - the game, exactly as real players will get it. Play this one.
- **TheFortressQA.exe** - the same game plus the QA cheat panel (state snapshots, version readout). Use this one when a test script asks you to open the CHEAT panel or load a snapshot.

## Reporting bugs and crashes

The game writes a log file as it runs. If you hit a bug or crash:

1. Open any folder window, paste this into the address bar, and press Enter: `%APPDATA%\Godot\app_userdata\The Fortress\logs`
2. Grab the newest file in that folder.
3. Post in the Discord bug-reports channel with: what you were doing, what you expected, what happened instead, the log file, and a screenshot if you can.

Join the Discord here: https://discord.gg/NpH6fJKY

## Good to know

- The game runs in a tall, narrow window - it's designed for phones in portrait orientation. A full-screen / desktop-ratio version for PC is planned.
- Each release lists **What's in this build** so you can see what changed.
- Your save data lives on your machine and survives installing a new build over the old one.
- The "Source code" links GitHub adds to each release contain only this download page's readme - they are not the game's source code.

## Other platforms

Windows is the first QA platform. Android is coming soon, and iOS is planned after that.
