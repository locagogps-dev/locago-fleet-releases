# LOCAGO Fleet releases

Public download page for LOCAGO Fleet Android updates (APK files).

Each version is a plain file under `apks/` (for example
`apks/locago-fleet-v9.apk`), served by raw.githubusercontent.com.
The app checks the published version in Firestore and downloads the
matching file when an update is available.

The app itself is login-gated: an account created by the LOCAGO admin is
required to use it. The source code lives in a separate private repo.
