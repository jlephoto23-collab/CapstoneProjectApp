# Building the Android APK

EduFlow is a web app wrapped for Android using a WebView (Cordova-style layout in CI).

## Option A — GitHub Actions (recommended)

1. Push to `main` (already set up with `.github/workflows/build-apk.yml`).
2. Open the repo → **Actions** → run **Build Android APK**.
3. When the job finishes, download the **apk** artifact (debug APK).

## Option B — Local (Android Studio)

1. Install Android Studio and SDK.
2. Create a new Empty Activity project.
3. Put `web/` assets in `app/src/main/assets/www/`.
4. Load `file:///android_asset/www/index.html` in a WebView with JavaScript enabled.
5. Build → Build APK(s).

## Install on phone

- Enable **Install unknown apps** for your file manager.
- Open the downloaded `.apk` and install.
