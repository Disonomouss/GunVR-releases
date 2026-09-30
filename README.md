# GunVR

A VR mod for **Gun** (2005, PC). Play it in a headset with your hands: aim
and shoot with the controllers, draw from holsters on your body, load rounds
by hand, swing melee weapons and draw the bow.

> Work in progress: playable from start to finish in VR, still being tuned.

## Download

Get the latest zip from the **[Releases](../../releases/latest)** page. The
full guide (controls, the in-headset menu, settings, troubleshooting) is the
`README.md` inside the zip.

## What you need

- **Gun for PC.** The Steam release works as it comes; GunVR runs it at 60 fps
  by itself, in memory. GunVR does not include any game files.
- **An ASI loader** in the game folder, such as
  [Ultimate ASI Loader](https://github.com/ThirteenAG/Ultimate-ASI-Loader).
  One way that works with Gun: rename the game's `binkw32.dll` to
  `binkw32Hooked.dll` and put the loader in as `binkw32.dll`.
- **A PC VR headset with an OpenXR runtime** (Virtual Desktop, SteamVR,
  Meta / Oculus, Windows Mixed Reality) set as the active OpenXR runtime.
  Developed on a Quest 3 through Virtual Desktop.
- Windows 10 or 11.

Turn off ReShade and any widescreen fix for Gun while you play in VR.

## Install

1. Unpack the zip anywhere.
2. Double-click **`Install GunVR.bat`**. It finds the game folder (or asks
   for it) and copies the mod in.
3. Start your OpenXR runtime, put the headset on, and start Gun.

**`Install GunVR with 4 GB.bat`** does the same and also lets the game use
4 GB of memory instead of 2 GB, which helps on long sessions. It keeps your
original Gun.exe as `Gun.exe.before-4gb`.

To remove the mod, double-click **`Uninstall GunVR.bat`**.

## Controls at a glance

| | |
|---|---|
| **Aim / fire** | point the controller, pull the trigger |
| **Move / turn** | left stick moves, right stick turns |
| **Weapons** | reach to a holster on your body and squeeze the grip |
| **Reload** | squeeze at your chest with the gun hand, or bring rounds to the gun |
| **A** | jump |
| **B** | scope (rifles and the Sharps) |
| **Y** | action: use, mount, pick up |
| **Right stick click** | Dead Eye |
| **Left menu button** | tap: pause; hold: the GunVR menu |

## Problems

The game folder has a `GunVR.log` after each session. If something goes
wrong, open an issue here and attach that log: it says what the mod saw.
