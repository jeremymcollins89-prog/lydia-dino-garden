# Dino Garden

A calm puzzle, music, learning and art game for little kids. Made by Coll Business Solutions LLC.

**Play it:** https://jeremymcollins89-prog.github.io/lydia-dino-garden/

- No accounts, no ads, no tracking.
- Everything (the child's name, progress, paintings) is saved only on the device.
- Works offline after it has been opened once.

## For parents

1. Open the link above in **Safari** (iPad/iPhone) or **Chrome** (Android).
2. Tap **Share → Add to Home Screen** (iPad/iPhone) or **⋮ → Add to Home screen** (Android).
3. Open Dino Garden from the home screen.
4. Tap the **⚙️ settings bubble** (top right), answer the grown-ups question, type your child's name, and tap **Save**.

## Files in this repository

All files sit at the top level of the repository (not inside a folder):

```
lydia-dino-garden/          <- the repository
├── index.html              <- the game
├── sw.js                   <- offline helper (saves the game on the device)
├── manifest.json           <- app name and icons for "Add to Home Screen"
├── apple-touch-icon.png    <- home screen icon (180×180)
├── icon-512.png            <- large icon (512×512)
└── README.md               <- this file
```

## Updating the game

Run the PowerShell publish script with the new `lydia-dino-garden.zip` in Downloads, or upload the changed files on GitHub with **Add file → Upload files**. Devices pick up the new version the next time they open the game online.

## Locking a device into the game

iPad/iPhone: Settings → Accessibility → Guided Access → On. In the game, triple-click the top (or side) button to start; triple-click again and enter the passcode to exit.
