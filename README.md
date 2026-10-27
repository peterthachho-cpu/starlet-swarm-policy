# Starlet Swarm privacy policy

Static GitHub Pages site for Starlet Swarm (`com.neaura.starletswarm`). No build, dependencies, JavaScript, or external fonts.

## Review before publication

- Confirm the privacy contact. `index.html` currently uses `Seidelin2@hotmail.com`, copied from the game's SettingsManager.cs; ownership has not been confirmed.
- This policy describes the current repository's AdMob integration, not a future ad-free build. Update the policy and Play Console Data safety declaration if the released build changes.
- Verify that the production binary matches these data practices, including any third-party SDKs, retention practices, and target audience. Repository inspection alone cannot verify the installed production binary or external account settings.
- Confirm the developer identity shown on the store. The page names the game and Neaura, as in the project settings.

## Publish to the repository shown in the task

1. Open `https://github.com/peterthachho-cpu/starlet-swarm-policy`.
2. Select **uploading an existing file** and upload `index.html` and this README.md at the repository root. Commit to `main`.
3. Open **Settings > Pages**.
4. Select **Deploy from a branch**, choose **main** and **/ (root)**, then save.
5. Wait for GitHub Pages deployment to succeed. The expected URL is:
   `https://peterthachho-cpu.github.io/starlet-swarm-policy/`
6. Open the URL in a signed-out/private window and verify that the policy loads before using it in Play Console. This URL has not been deployed or verified by this task.
7. Update the app's Privacy Policy URL in Play Console and save.

## Follow-up in the Unity client

`KawaiiSurvivor/Assets/Scripts/Managers/SettingsManager.cs`, method `PrivacyPolicyButtonCallback`, still opens `https://nowherevps.com/policy`. Update this to the verified Pages URL when preparing the next client build. This task does not modify the Unity project.

## Sources used for the draft

- Google Play User Data policy: https://support.google.com/googleplay/android-developer/answer/10144311
- AdMob Unity data disclosure: https://developers.google.com/admob/unity/privacy/play-data-disclosure
- Project settings, AdsManager.cs, SettingsManager.cs and the local Sijil save system in KawaiiSurvivor.
