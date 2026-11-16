# TriDesk

Free Mac app that turns VITURE Luma Ultra XR glasses into up to 5 virtual monitors, with 6DoF tracking, hand gestures and workspaces.

## What it does

- Creates 1–5 real macOS displays (drag windows onto them like normal monitors) and places them around you: **triangle/cockpit**, curved arc, flat wall, 2×2 grid, or **one big curved ultrawide** (5120×1440).
- **6DoF**: the screens stay fixed in the room, so you can turn to the side screens and lean in to read.
- **Pinch to grab** any screen and carry it somewhere else using the glasses' front camera; open palm recenters.
- **Workspaces**: save a layout plus which app windows are on which screen, then switch back in one click (it reopens the apps too).
- MacBook screen can stay as its own screen below the virtual ones, mirror, or turn off.
- Pauses when you take the glasses off, and gives you your normal screen back when you unplug.

## Requirements

 Apple Silicon Mac (M1+), macOS 14+, Luma Ultra (other Luma models may work without 6DoF). Quit SpaceWalker first: only one app can use the tracking at a time.

## Download

Get the latest `TriDesk-x.y.z.dmg` from [Releases](../../releases/latest), open it and drag TriDesk into Applications. The DMG includes a *Read Me First* file.

TriDesk isn't signed with a paid Apple developer certificate, so on first launch macOS will say it can't verify the developer. Go to **System Settings → Privacy & Security** and click **Open Anyway**. TriDesk then asks for Screen & System Audio Recording (to show your screens in the glasses), Accessibility (gestures, moving windows) and Camera (hand tracking, processed on your Mac only).

## Hotkeys (⌃⌥⌘ + key)

| Key | Action |
|---|---|
| R | Recenter |
| O | Overview of all screens |
| L | Next layout |
| M | Grab / drop the screen you're looking at |
| W | Next workspace |
| D | Lens dimming |
| H | Hand gestures on / off |
| − / = | Screens closer / farther |

## Known limitations

- 3D side-by-side mode doesn't work on Macs: macOS refuses the 3840×1200 mode the glasses switch to, so TriDesk is 2D only.
- Apple Silicon only (VITURE's SDK libraries are arm64).

## Notes

Unofficial hobby project, not affiliated with VITURE. Uses the official VITURE Glasses SDK, (c) VITURE Inc. Provided as is, without warranty.
