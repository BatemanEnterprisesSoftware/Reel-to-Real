# Reel to Real

Turn Facebook and Instagram reels, videos, and walkthroughs into prompts for improving the software you're building. Reel to Real is a native Windows desktop app. Speech and screen analysis run on your computer after a one-time setup.

## Install on Windows

1. Open the [latest release](https://github.com/BatemanEnterprisesSoftware/Reel-to-Real/releases/latest).
2. Under **Assets**, download the `Reel-to-Real-<version>.zip` file. GitHub's automatic **Source code** archives are not the Windows app.
3. Right-click the ZIP, choose **Extract All**, open the extracted folder, and double-click **Install for Windows.cmd**.
4. Open **Reel to Real** from your desktop. Use **Local engine** if prompted to finish setup.

First-time setup downloads the speech, video, and AI tools. It requires internet access and several gigabytes of space.

## Use it

Paste reel links (one per line), add videos, or paste a transcript. Enter what you want to improve, choose **Quick read** or **Deep read**, then select **Create prompts**. A batch can hold up to 20 sources and continues in the background. Review the evidence and edit or copy each completed prompt.

Public reel links may stop working when the platform requires login. Download the video yourself and add the file in that case. The app does not log into your social accounts. Uploaded videos are limited to 10 minutes and 250 MB each.

## Updates and privacy

Open **Updates** in the app to read past changes or check for a newer release. Updates are verified with a signed manifest and a SHA-256 checksum. Saved prompts, project details, model downloads, and media evidence stay on each computer and are preserved by app updates. Reel links and first-time setup use the internet; video analysis itself does not require a paid AI API.

This repository distributes releases and their signed update files. The Windows ZIP contains the app; the auto-generated source archives do not.
