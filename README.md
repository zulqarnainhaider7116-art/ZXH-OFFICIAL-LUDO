# ZXH OFFICIAL LUDO

Premium, ad-free offline Ludo game and Android wrapper.

**Brand:** ZXH OFFICIAL  
**Creator:** ZULQARNAIN X HAIDER

## Included
- CPU and local pass-and-play modes
- 2–4 player setup with player names
- Dice roll animation and sound toggle
- Token movement, captures, safe squares and win state
- Responsive premium interface and branded app icon
- Capacitor Android project generation through GitHub Actions

## Build the Android APK
1. Open the repository's **Actions** tab.
2. Select **Build Android APK**.
3. Tap **Run workflow** and confirm the main branch.
4. Wait for the workflow to finish successfully.
5. Open the run's **Artifacts** section and download **ZXH-OFFICIAL-LUDO-APK**.
6. Extract the artifact and install `app-debug.apk` on your Android device.

The workflow creates the Android wrapper and builds a debug APK. A signed release APK/AAB requires a private signing keystore and a separate signing configuration.

## Offline & privacy
The bundled game assets and gameplay run locally. No ads, analytics SDK, account, remote multiplayer service or backend is included. Google Fonts are optional; system fonts are used when offline.

## Current scope
This repository contains a fresh ZXH Ludo implementation. It is not a byte-for-byte port of the earlier FTGM LUDO source, which was not present in the repository supplied for this build.
