# PC Monitor

A small, no-frills hardware monitor for Windows 10 and 11. It shows **temperatures, voltages, power (watts),
clock speeds and usage %** for your **CPU, motherboard, RAM and graphics card** in a little always-on-top window
that you can put anywhere on screen.

## Download

Get **`PCMonitor.exe`** from the [latest release](https://github.com/Romoslayer/PCMonitor-Releases/releases/latest).
It's a single file: there's no installer, and you don't need to install .NET.

## Requirements

- Windows 10 or 11, 64-bit.
- **Administrator rights.** PC Monitor asks when it starts. Without them, only graphics card readings and usage %
  work.
- **The free PawnIO driver**, needed for CPU, motherboard and RAM temperatures and voltages. If it's missing,
  PC Monitor offers to open its [download page](https://github.com/namazso/PawnIO.Setup/releases/latest).

## Using it

- Double-click `PCMonitor.exe` and say **Yes** to the admin prompt.
- It lives in the notification area (system tray). **Click** the icon for settings; **right-click** it for a menu.
  On Windows 11 the icon may be tucked behind the **^** arrow; drag it onto the taskbar to keep it in view.
- It keeps running until you **right-click the tray icon and choose Quit PC Monitor**.
- In **Settings**, tick the sensors you want on the on-screen monitor. Right-click a sensor (or press F2) to rename it.
- **Drag** the on-screen monitor to move it. **Lock** it and clicks go through it to whatever is behind, and it fades
  while your mouse is over it. **Hold Ctrl** over a locked monitor to drag it or right-click it.
- Options: text size, °C/°F, opacity, theme (Match Windows, Dark or Light) and **Start with Windows**.

Settings are saved in `%AppData%\PCMonitor\settings.json`.

The on-screen monitor shows over normal windows and borderless or windowed games. It can't draw over games running in
exclusive full-screen mode.

## "Windows protected your PC"

PC Monitor isn't code-signed, so Windows SmartScreen may warn you the first time you run it. Click **More info**, then
**Run anyway**. Each release lists the file's SHA-256 checksum so you can check that your download matches.

## Licence

PC Monitor is free to download and use. Copyright © 2026 Romoslayer, all rights reserved. See [LICENSE](LICENSE).
Third-party components are listed in [THIRD-PARTY-NOTICES.md](THIRD-PARTY-NOTICES.md).
