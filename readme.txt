THE COUNTDOWN — Android installable web app

This package is an offline-capable Progressive Web App (PWA), not a compiled APK.
It contains 24 longer daily letters for November 18 through December 11, 2026.
Unlock time: 11:30 PM Chile time (America/Santiago). Previously unlocked letters remain available.

INSTALL ON ANDROID:
1. Put this folder on a static HTTPS web host (for example, a private GitHub Pages site or another HTTPS host).
2. Open the hosted address in Chrome on Android.
3. Open Chrome's menu and choose "Install app" or "Add to Home screen".
4. Launch it from the new home-screen icon. After its first successful load, the service worker caches the app for offline use.

IMPORTANT LIMITATION:
Because this is a local/offline app, unlocks use the device clock interpreted in the America/Santiago time zone. Changing the device date/time can affect unlock behavior. A tamper-proof schedule would require an online server.

An actual APK cannot be compiled in this environment because the Android SDK/Gradle build toolchain is not available. The included PWA can be installed like an app on Android without compiling an APK.
