# Exit Sentinel releases

Signed builds of [Exit Sentinel](https://github.com/melotusme/exit-sentinel) for Apple Silicon macOS, Windows x64 and Linux x86_64 (AppImage), plus the updater manifest `latest.json`.

Actions → Publish signed release → Run workflow builds a source ref. There is no scheduled run; publish only by manual dispatch. Source checkout uses a read-only deploy key; signing keys are Actions secrets.

The macOS app is ad-hoc signed and has not been notarized by Apple.
