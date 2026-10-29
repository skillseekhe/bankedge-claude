# BankEdge AI - Android app

Offline-first mobile app (HTML/JS, no external libraries) wrapped as a native Android app. AI features use Google Gemini.
The Android project is generated during the build by `make_project.sh`, so the repo needs only:

- `index.html`
- `make_project.sh`
- `.github/workflows/build-apk.yml`

## Build the APK
Actions > Build APK > Run workflow. Download `BankEdgeAI-debug-apk` from Artifacts, unzip, install `app-debug.apk`.

## First run
Settings > paste a free Gemini key from https://aistudio.google.com/apikey > Test connection.
