# Medicine Mangao Android App

Android WebView wrapper for https://medicinemangao.pk/

## Configuration
- App name: Medicine Mangao
- Application ID: pk.medicinemangao.app
- Min SDK: 26 (Android 8.0)
- Target SDK: 35
- Orientation: portrait
- Website content stays live on the WordPress site.

## Build
Open this folder in Android Studio, let Gradle sync, then:
- Build > Build APK(s)
- Or run on a connected Android device/emulator.

## Notes
The launcher/splash icon is a clean vector recreation of the supplied Medicine Mangao bag/cross branding. Replace `app/src/main/res/drawable/mm_logo.xml` with the original artwork if you want the exact raster logo packaged in the APK.

Google OAuth is deliberately treated as an external browser destination because some identity providers block embedded WebViews. Normal Medicine Mangao pages remain inside the app.
