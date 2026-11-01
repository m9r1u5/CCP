# CCP Dose Calculator

Offline drug dose calculator built from the Cornell CCP CPG booklet (v1.5).

## Install
- **Android:** download `CCP-Dose-Calculator.apk` from the latest **Release** and open it.
- **iPhone / iPad:** open the GitHub Pages link in Safari → **Share** → **Add to Home Screen**. Works offline.
- **iOS app file:** each release also has an unsigned `.ipa`. Installing it needs an Apple Developer account
  (for signing / TestFlight) or a sideloading tool.

## Builds
Every push to `main` runs **Actions → Build Android + iOS** and publishes a new release with both files.

## Updating
Change the files, bump `VERSION` in `sw.js`, push. Web users tap **Update**; APK users install the newest APK.
