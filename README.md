# XI Deck Android

Android WebView wrapper for `xi_deck.html`.

## Build automatically on GitHub
1. Create a new GitHub repository.
2. Upload all files from this project, preserving folders.
3. Open **Actions** and run **Build Android APK**, or push to `main`.
4. Download the `xi-deck-apk` artifact from the completed workflow run.

Publishing a GitHub Release also attaches `app-debug.apk` to the release.

## Build locally
Requires JDK 17 and Gradle 8.9:

```bash
gradle assembleDebug
```

Output: `app/build/outputs/apk/debug/app-debug.apk`
