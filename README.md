# Exit Sentinel private releases

This repository and the source repository are private. Signed Apple Silicon macOS builds and their updater manifest are available only to authorized users.

The app uses the local GitHub CLI login in its native backend to read private release assets. No credential is embedded in the app or sent to its frontend. Run `gh auth login` with an account that has repository read permission before checking for updates.

Actions → Publish signed release → Run workflow builds a source ref. There is no scheduled run; publish only by manual dispatch. Source checkout uses a read-only deploy key; signing keys are Actions secrets.

The app is ad-hoc signed and has not been notarized by Apple.
