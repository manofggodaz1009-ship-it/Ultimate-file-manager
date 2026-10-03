# Ultimate File Manager — GitHub APK Build

Package: `com.antonydaniel.filemanager`

This project is configured for GitHub Actions to build a debug APK.

## Build on GitHub

1. Create a new GitHub repository.
2. Upload all files/folders from this project to the repository root.
3. Commit to the `main` branch.
4. Open the repository's **Actions** tab.
5. Select **Build Android APK**.
6. Click **Run workflow** if you want to start it manually.
7. When the workflow finishes, open the workflow run and download the artifact named `UltimateFileManager-debug-apk`.

## Important

The app requests broad storage access because it is designed as a local file manager. Android and Google Play impose restrictions on broad storage access, so review platform requirements before publishing to Google Play.
