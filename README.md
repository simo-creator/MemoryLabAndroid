# Memory Lab Android

Offline Android WebView wrapper for the Memory Lab learning app.

## Build APK with GitHub Actions
1. Create a GitHub repository and upload the contents of this folder.
2. Open Actions and run **Build Memory Lab APK** (or push to `main`).
3. Open the completed workflow run and download the `Memory-Lab-APK` artifact.
4. Extract the ZIP and install `app-debug.apk` on your Android phone.

The app loads `app/src/main/assets/index.html` locally. JavaScript and DOM storage are enabled so the lesson progress and streak can persist on the device. No internet permission is requested.
