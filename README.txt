CALCSPACE ANDROID PROJECT

This project wraps the finished CalcSpace calculator in a native Android WebView.
The calculator HTML and background image are bundled locally, so the app works offline.

PHONE-ONLY BUILD:
1. Create/sign in to a GitHub account in your phone browser.
2. Create a new repository named calcspace-android.
3. Upload the CONTENTS of this ZIP (not the ZIP itself) to the repository's main branch.
   Make sure the .github/workflows/build-apk.yml file is included.
4. Open the repository's Actions tab.
5. Select "Build CalcSpace APK", tap "Run workflow", then "Run workflow".
6. When the run finishes successfully, open it and download the "CalcSpace-APK" artifact.
7. Extract the downloaded ZIP, tap app-debug.apk, and install it.
   Android may ask you to allow installs from that browser or file manager.

This is a debug APK for personal installation, not a Play Store release.
