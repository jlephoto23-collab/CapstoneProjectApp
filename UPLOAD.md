# Upload the full app files

The GitHub Actions APK build expects these files under `web/`:

- `web/index.html` (already in repo)
- `web/lms.html` (full EduFlow LMS)
- `web/portfolio.html` (portfolio site)

## Quick upload (GitHub website)

1. Open https://github.com/jlephoto23-collab/CapstoneProjectApp
2. Click **Add file** → **Upload files**
3. Upload from the zip you downloaded in chat:
   - Rename/copy `lms.html` → path `web/lms.html`
   - Rename/copy `portfolio.html` → path `web/portfolio.html`
4. Commit to `main`.

## Build the APK

1. Go to **Actions** tab
2. Select **Build Android APK**
3. Click **Run workflow** → **Run workflow**
4. When green, open the run → **Artifacts** → download **EduFlow-debug-apk**

Install the APK on your Android phone (enable Install unknown apps).

## Demo logins

- Admin: `admin@eduflow.co` / `admin123`
- Student: register a new account
