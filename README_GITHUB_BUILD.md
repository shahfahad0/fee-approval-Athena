# Fee Approval App - GitHub Build

Upload these project files to the root of your private GitHub repository.

Required root files/folders:

- `.github/workflows/main.yml`
- `app/`
- `build.gradle`
- `settings.gradle`
- `gradle.properties`

Then open **Actions → Build Fee Approval APK → Run workflow**.

When successful, download the artifact named **FeeApproval-APK**. It contains `FeeApproval.apk`.

Do not upload the Firebase Admin SDK service-account JSON to GitHub. Keep it only on the server under `data/firebase-service-account.json`.
