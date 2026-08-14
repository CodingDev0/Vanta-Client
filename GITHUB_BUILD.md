# Build Vanta without Android Studio

## 1. Upload this folder to GitHub

Create a new empty GitHub repository, then upload the contents of this folder.

## 2. Wait for GitHub Actions

Open the repository's **Actions** tab.

The workflow named **Build Vanta Android APK** will build the debug APK automatically.

## 3. Download the APK

Open the completed workflow run and find the **Vanta-debug-apk** artifact.

Download it, unzip it, and install `app-debug.apk` on Android.

## 4. Phone-only workflow

You can do the GitHub steps from your phone browser. No Android Studio is required for the cloud build.

## 5. Minecraft pack

The Bedrock pack is in:

`bedrock/VantaResourcePack/`

A ready-to-import `.mcpack` is also supplied separately with the project download.

## Important

The GitHub build produces a debug APK. Android may require you to allow installation from the browser/file manager used to open the APK.

Vanta does not bypass Minecraft's private renderer or falsely claim an unsupported FPS cap is unlocked.
