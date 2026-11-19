# Changelog

Every Andromon release, newest first. Written by the build; don't edit by hand.

## v1.0.4 (build 2) · 2026-11-19

### Desktop and web

- Release from the automation branch; the release branch is gone (`9863b7e`)
- Publish a release when a new version is pushed to the automation branch (`ff51d2c`)
- Remove the GitHub Actions build; releases are built in Andromon_Releases (`cfd3511`)
- Publish releases in Andromon_Releases, built from the release branch (`1e88e2f`)
- Let the release manifest link downloads and commits to separate repositories (`8d9f412`)
- Build a new release by itself when the version in package.json changes (`65d136a`)
- Keep the release manifest and notes in build/ out of git (`0d9650d`)
- List the phone app and web build in the release manifest and changelog (`b685db9`)
- Offer the 32-bit Windows build its own installer in the update check (`7099546`)
- Keep web build zips in build/ out of git (`9671407`)
- Release 1.0.4 with companion 1.0.4 (`96203a4`)
- Keep the installers release.py makes in build/ (`06139ee`)
- Bundle companion 0.35.0 (`330c10d`)

### Phone app 0.29.0

- Check and build the app with GitHub Actions (`6df021b`)
- Point the hints to Droid Desk's Shizuku page (`52c7ebd`)
- Add a user guide with screenshots (`af538d8`)
- Replace the launcher icon with the robot artwork (`f332c50`)
- Add accessibility options to Settings: text size, high contrast, bold text, reduce motion (`bc2f92e`)
- Add the Freezer and Battery saver tools (`c3ff0c1`)
- Add privileged access through Shizuku (`fd10aa1`)
- Dock the bottom bar, simplify the PC link screen, add a design guide (`bc80fa1`)
- Switch the app's icons to Lucide outlines (`ca4138d`)
- Droid Desk Companion: Android helper app for Droid Desk (`5cd2077`)

The list shows the phone app's latest commits, not everything before it.

### Downloads

- Linux x64 (deb): [Andromon-1.0.4-amd64.deb](https://github.com/Deshan555/Andromon_Releases/releases/download/v1.0.4/Andromon-1.0.4-amd64.deb), 104.4 MB
- Linux arm64 (AppImage): [Andromon-1.0.4-arm64.AppImage](https://github.com/Deshan555/Andromon_Releases/releases/download/v1.0.4/Andromon-1.0.4-arm64.AppImage), 129.9 MB
- Linux arm64 (deb): [Andromon-1.0.4-arm64.deb](https://github.com/Deshan555/Andromon_Releases/releases/download/v1.0.4/Andromon-1.0.4-arm64.deb), 99.3 MB
- macOS arm64 (dmg): [Andromon-1.0.4-arm64.dmg](https://github.com/Deshan555/Andromon_Releases/releases/download/v1.0.4/Andromon-1.0.4-arm64.dmg), 125.1 MB
- macOS x64 (dmg): [Andromon-1.0.4-x64.dmg](https://github.com/Deshan555/Andromon_Releases/releases/download/v1.0.4/Andromon-1.0.4-x64.dmg), 132.3 MB
- Linux x64 (AppImage): [Andromon-1.0.4-x86_64.AppImage](https://github.com/Deshan555/Andromon_Releases/releases/download/v1.0.4/Andromon-1.0.4-x86_64.AppImage), 128.7 MB
- Android (apk): [Andromon-Companion-1.0.4.apk](https://github.com/Deshan555/Andromon_Releases/releases/download/v1.0.4/Andromon-Companion-1.0.4.apk), 1.5 MB
- Windows arm64 (exe): [Andromon-Setup-1.0.4-arm64.exe](https://github.com/Deshan555/Andromon_Releases/releases/download/v1.0.4/Andromon-Setup-1.0.4-arm64.exe), 117.8 MB
- Windows ia32 (exe): [Andromon-Setup-1.0.4-ia32.exe](https://github.com/Deshan555/Andromon_Releases/releases/download/v1.0.4/Andromon-Setup-1.0.4-ia32.exe), 101.9 MB
- Windows x64 (exe): [Andromon-Setup-1.0.4-x64.exe](https://github.com/Deshan555/Andromon_Releases/releases/download/v1.0.4/Andromon-Setup-1.0.4-x64.exe), 123.7 MB
- Windows (exe): [Andromon-Setup-1.0.4.exe](https://github.com/Deshan555/Andromon_Releases/releases/download/v1.0.4/Andromon-Setup-1.0.4.exe), 240.7 MB
- Web (zip): [Andromon-Web-1.0.4.zip](https://github.com/Deshan555/Andromon_Releases/releases/download/v1.0.4/Andromon-Web-1.0.4.zip), 2.2 MB

The web build runs in Chrome or Edge: unzip it and upload the files to any static host.

Every build of the `release` branch, newest first. Written by the build; don't edit by hand.

## v0.1.0 (build 4) · 2026-11-19

- Add a Memory page: RAM in use, apps in memory, Stop and Free memory (`008937d`)
- Use less memory in long sessions (`15eee26`)
- Save screen recordings and files from the phone straight to disk (`566f534`)
- Bundle the companion with the new welcome tour look (`319b7c3`)
- Bundle the companion with the chart Dashboard (`c73ab24`)
- Bundle the companion with the Tools tabs (`cba6585`)
- Bundle companion 0.34.0 (`87442c3`)
- Add a web build ready to upload to a static host (`cfcfd70`)
- Retake the user guide screenshots on a real phone (`a9c8793`)
- Leave the PC link off when it was stopped on the phone (`b29f5dc`)
- Show a start-up splash with the logo and a progress bar (`2683498`)
- Show screenshots full screen (`6f01905`)
- Add a media player for videos and music (`fa7ce6e`)
- Blur personal data in phone screenshots (`362c0c9`)
- Blur personal data in the Andromon window (`cf4a192`)
- Add app zoom, smaller buttons and icon-only buttons to Accessibility (`e0842b5`)
- Add a Repair desk for phone repair shops (hidden for now) (`d8a3a5f`)
- Find photos that look alike (`705ff4e`)
- Add Folder sync between this computer and the phone (`732517e`)
- Add a Battery health page (`de5a728`)
- Add a Storage map page (`aab1ac4`)
- Lock backups with a password (`b962ae5`)
- Share the clipboard both ways while a phone is connected (`5c3f312`)
- Add keyboard shortcuts for the mirror's controls (`6656782`)
- Mirror extra phones in small windows of their own (`74d3b7e`)
- Install apps and copy files dropped on the mirrored screen (`71ff101`)
- Tell the phone which computer it is linked to (`1bbc9b1`)
- Add a script that builds, signs and checks the installers (`e1bd2b3`)
- Show a code the phone can scan to find this computer (`78976d8`)
- Put the mirror controls around the phone's screen, with Auto quality (`ed7c828`)
- Pin the sidebar to the window's left edge (`211745f`)
- Show what to set up first when running as a web page (`d3ffbad`)
- Connect phones by themselves and keep other adb programs off them (`0f1c99b`)
- Add an SD card recovery page (PhotoRec) (`5a85b5b`)
- Show an app's screenshots on the F-Droid page (`7b0ddcd`)
- Add accessibility settings (`c38cc5a`)
- Rename the app to Andromon (`ff8c7b6`)
- Show a progress bar while files are copied, uploaded or downloaded (`2f155d9`)

## v0.1.0 (build 3) · 2026-11-15

- Say in the README where to download the builds (`feddcf1`)
- Show Connect phone and Connect over Wi-Fi as icon buttons (`1d98db9`)
- Pick the fake location on a map, with place search (`e0d319f`)
- Move the options to Settings and rebuild the Files, Screenshot and Shell pages (`0e94d14`)
- Replace the system's select menus with the app's own dropdown (`09c6254`)
- Use icon buttons to call or text a number in Contacts (`ae40116`)
- Show the optional tools this computer has, and offer them at install (`1c5c41b`)
- Show nearby devices on a radar on the Wi-Fi transfer page (`4c8871f`)
- Give backup & restore and Shizuku their own pages (`41305b1`)

## v0.1.0 (build 2) · 2026-11-15

- Add an update check: find a newer build, download its installer and open it (`8c8adca`)
- Use the changes since the previous build as the release's description (`6751db4`)

## v0.1.0 (build 1) · 2026-11-15

- Build macOS, Windows and Linux installers on pushes to the release branch (`fd4d69c`)
- Add a user guide with screenshots (`c78b7a9`)
- Update the app icon (`0f4805c`)
- Keep the API tester's side panel below the fixed header (`6cfc7d1`)
- Add a Settings page: appearance, mirror defaults, save folders, downloads and sources (`f4bfcb3`)
- Add a download manager: progress, speed, cancel and history from a header button (`12d82da`)
- Brand the installers: app icon, DMG background, Windows setup pictures (`5ae0326`)
- Add an F-Droid page: browse and install free and open-source apps (`b8d2ec4`)
- Add a ReVanced page: patch an app on the computer and install it (`a181a70`)
- Add a Start Shizuku card to the Overview (`ed72bed`)
- Bundle Droid Desk Companion 0.29.0 (`40c921e`)
- Redesign the window: brand colours, new Overview and Screen mirror, Lucide icons (`4da8db7`)
- Droid Desk: Android phone manager for Windows and macOS (`5c67842`)

First build recorded here: the list shows the latest commits, not everything before it.
