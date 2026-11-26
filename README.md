# ZXH OFFICIAL LUDO

**Original FTGM LUDO — Perfect Edition**, packaged as a full-screen Android game.

**Brand:** ZXH OFFICIAL  
**Creator:** ZULQARNAIN X HAIDER

## Original game features retained
- Original 15×15 Ludo board and four home yards
- Computer and local Friends modes
- 2, 3 or 4 player setup, player names and avatars
- Player color selection and human/CPU controls
- Animated 3D dice and extra rolls
- Token movement, home lanes, safe squares and captures
- CPU move scoring, reactions/emojis and animated win celebration
- Original board composition and token artwork, bundled locally for offline use

## Android APK
1. Open the repository **Actions** tab.
2. Select **Build Android APK** and run the workflow on `main`.
3. Download the `ZXH-OFFICIAL-LUDO-APK` artifact from the successful run.
4. Extract it and install `app-debug.apk` on Android.

The workflow builds a debug APK. A signed release APK/AAB needs a private signing keystore and signing configuration.

## Offline behaviour
Gameplay, board artwork, tokens and sound effects run locally. Sound effects are synthesized with the device audio engine, so there are no remote audio dependencies. The Android build bundles the artwork; the web version caches the local assets with its service worker. No ads, analytics, account, backend or online multiplayer service is included.

**Powered by ZXH OFFICIAL**  
**ZULQARNAIN X HAIDER**


## ZXH OFFICIAL LUDO V2 — New standalone build

A newly built, self-contained mobile-first edition is available in `/v2`.

- Classic 52-space Ludo loop and four home lanes
- 2-player (Red vs Yellow), 3-player and 4-player matches
- Local pass-and-play or CPU opponents with difficulty settings
- Animated dice, legal token selection, captures and safe squares
- Four tokens per player and win detection
- No ads, account, subscription, analytics or backend
- Installable PWA with a local service worker and offline cache
- All gameplay code, styling and artwork are local; no external fonts or CDNs

Open the new version: [ZXH OFFICIAL LUDO V2](./v2/)

Creator: **ZULQARNAIN X HAIDER**  
Powered by **ZXH OFFICIAL**
