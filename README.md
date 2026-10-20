# Ride Intercom for Android: tester download

Signed APKs for testers of **Ride Intercom by Plyntr** (app id `com.plyntr.rideintercom`).
This repo holds only release files. It has no source code.

## Install
1. Open the [latest release](https://github.com/joeprosynergy/ride-intercom-releases/releases/latest) on your Android phone and download `ride-intercom-<version>.apk`.
2. Open the file. If Android asks, allow installs from your browser or file app.
3. Open Ride Intercom, then tap Create or Join. The app asks for the microphone at that point.

## Updates are manual
The app doesn't update itself. When a new release appears here, download it and install it over the old one. Your settings are kept because every release is signed with the same key.

## Check the download (optional)
Each release has a matching `.sha256` file. To check the APK, run `sha256sum -c ride-intercom-<version>.apk.sha256`.
Signing certificate SHA-256:
`FA:E2:3C:05:B5:86:71:E3:09:3C:83:A8:5E:A5:CF:D3:9E:94:ED:23:59:E2:BC:D1:43:9D:F3:AF:70:C8:C7:14`
