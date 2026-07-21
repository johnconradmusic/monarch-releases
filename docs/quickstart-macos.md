# MONARCH macOS Quickstart

This is the shortest path from a fresh download to a phone-connected stage view.

## Install

1. Download the latest `MONARCH-*-macOS-universal.dmg` from the MONARCH releases page.
2. Open the DMG and drag `MONARCH.app` to `Applications`.
3. Launch MONARCH from `Applications`.
4. If the build is signed and notarized, macOS should open it normally. If you are testing an unsigned beta, right-click `MONARCH.app`, choose `Open`, then confirm once.

## Activate

1. In MONARCH, open `About MONARCH` or click the license chip.
2. Choose `ENTER LICENSE KEY...`.
3. Paste the beta, trial, or paid license key.
4. Confirm the registration panel shows `Trial` or `Licensed`.

Editing and authoring require an active license or trial. Playback surfaces remain focused on show operation.

## Load A Demo Show

1. On first launch, choose `Load Demo Show`.
2. If you are already in the workstation, open the command palette and run `Load Demo Show`.
3. Open the setlist and confirm songs, tracks, lyrics, sections, and charts are present.
4. Open `Audio Device Settings`, pick the show interface, then run the bus test buttons before pressing play.

## Connect A Phone Or Tablet

1. Keep the Mac and viewer device on the same network.
2. Open the launcher shown by MONARCH, or browse to:

   ```text
   http://monarch.local:8790
   ```

   If Bonjour is unavailable on the network, use the Mac's IP address instead:

   ```text
   http://<mac-ip-address>:8790
   ```

3. Open the QR sheet from the workstation and scan the `Confidence Monitor`, `Charts`, `Timer`, or `Controller` QR code.
4. On iPad or iPhone, use Safari's Share button and `Add to Home Screen` for a full-screen stage icon.

## Panic Button Tour

Before rehearsal, practice the safety path:

1. Press `GO` and confirm the confidence strip moves from `STANDBY` to `LIVE`.
2. Press `STOP` to stop at the saved song start.
3. Press `PANIC` to stop playback and block accidental restart.
4. Use `Recover From Panic` only after audio, MIDI, and the band are ready.
5. Confirm the current song has no missing files or unavailable outputs.

For show-critical use, keep a backup plan: a second rig, exported show package, printed setlist, and a manual audio fallback.
