A+MENTOR ANDROID APK BUILD STARTER

This is a source package plus a GitHub Actions workflow. It is NOT itself an APK.
It builds a debug APK in GitHub Actions after you upload the files to a GitHub repository and run the workflow.

IMPORTANT
- This app is a visual/demo prototype. Student login and payments are not connected to a real backend and must not be used for real credentials or money.
- This does not change your live Netlify website. It is a separate project.
- Keep this repository private if you do not want to publish your source files.

MOBILE-FRIENDLY STEPS
1. Sign in at https://github.com/ and create a new repository named aplusmentor-android-app.
2. Do not add a README or license during repository creation (the ZIP already includes files).
3. On a computer, extract this ZIP. Upload the CONTENTS of the aplusmentor-android-build folder to the repository root. Make sure .github/workflows/build-apk.yml is included. GitHub's web uploader may hide dot-folders; if it does, use GitHub Desktop or upload through a computer browser that shows hidden files.
4. Commit the files to the main branch.
5. In the repository, open Actions -> Build A+Mentor Android APK -> Run workflow.
6. Wait for the run to finish successfully. Open the completed run and download the APlusMentor-debug-apk artifact. GitHub downloads it as a ZIP; extract it to get app-debug.apk.
7. Transfer app-debug.apk to your Android phone and open it to install. You may need to allow installation from that source in Android settings. Install only APKs built from your own repository.

If GitHub asks you to enable Actions, enable it for this repository. No passwords, API keys, or payment credentials are needed for this demo build.
