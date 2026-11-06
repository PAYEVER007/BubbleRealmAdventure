# Bubble Realm Adventure — Android test APK

This repository builds a shareable **debug APK** of Bubble Realm Adventure v1.0.0 using GitHub Actions. No PC needed.

## Upload the game source from a phone

1. In ChatGPT, download **BubbleRealmAdventure_v1_0_0_GitHub_APK_BuildReady.zip**.
2. On this repository's **Code** tab, choose **Add file → Upload files** (use your browser's Desktop site mode if needed).
3. Select the downloaded ZIP. Upload it as a file **to the repository root**, without extracting it. Do **not** rename to `.apk`.
4. Choose **Commit changes** on branch `main`.

An Android test APK build will start automatically once the ZIP is committed.

## Download and install the APK

1. Open this repository's **Actions** tab.
2. Choose **Build Android test APK** and open the newest successful run.
3. In **Artifacts**, download `BubbleRealmAdventure-v1.0.0-APK`.
4. Extract the downloaded artifact ZIP; inside is `BubbleRealmAdventure-v1.0.0-test.apk`.
5. Share this APK to an Android phone and install it. Android may ask you to approve installing apps from the file manager.

This is a **debug APK for mobile testing**, not a signed release AAB for publishing on Google Play.

**Privacy:** This is a PUBLIC repository. Uploading the game ZIP here makes the game's source and assets public. Change repository visibility to private first if needed.
