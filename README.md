# Exit Sentinel releases

Signed macOS Apple Silicon releases for Exit Sentinel. Download the DMG from [Releases](https://github.com/melotusme/exit-sentinel-releases/releases/latest).

`latest.json` is the public Tauri updater feed. No GitHub credentials are embedded in the app. Source and personal application data are not published here.

The app currently uses ad-hoc Apple signing (no Developer ID notarization). Update artifacts are independently signed and verified by the app.

Maintainer: Actions → Publish signed release → Run workflow builds the private source ref. An hourly scheduled check publishes when the source main branch has a new app version. The source deploy key is read-only; signing keys are GitHub Actions secrets.
