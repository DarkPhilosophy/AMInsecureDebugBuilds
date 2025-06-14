# App Manager Insecure Debug Builds

This repository contains an [App Manager](https://muntashirakon.github.io/AppManager/) build that is generated automatically by [a GitHub Action](https://github.com/MuntashirAkon/AppManager/blob/master/.github/workflows/debug_build.yml) that is triggered whenever something is pushed to the [AppManager repository](https://github.com/MuntashirAkon/AppManager).

The APK file is signed by a debug signing key that is publicly available and contains debug flags such as debug and test-only. Therefore, it is HIGHLY INSECURE and NOT RECOMMENDED for daily use. By downloading and installing the APK file, you agree that the maintainers and contributors of App Manager are NOT responsible for any damages made to your device or any theft of personal information (including but not limited to personally identifiable info) for YOUR negligence. We recommend that you only use the build provided here for testing or retrieving debug logs, and uninstall it immediately after you are finished.

Each build has a unique build identifier appened to the version string as well as APK name. The name of the app, after it is installed, will show up as "AM Debug" instead of the regular "App Manager". You can install both builds side-by-side, but an ADB user may not use ADB on both builds at the same time. If you encounter an issue, please make sure you are currently running the latest build before reporting it, and also please include the build identifier with your report.

