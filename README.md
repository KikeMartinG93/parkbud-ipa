# ParkBud for SideStore

Compiled ParkBud IPA for SideStore to sign and install. This repo is the IPA and source listing only — not the app source.

Current IPA: **ParkBud 2.0.1 (build 11)**.

## Add in SideStore

1. Open SideStore → Sources → +
2. Paste this URL:

```
https://raw.githubusercontent.com/KikeMartinG93/parkbud-ipa/main/apps.json
```

Or tap this link on a device with SideStore installed:

[Add ParkBud to SideStore](sidestore://source?url=https://raw.githubusercontent.com/KikeMartinG93/parkbud-ipa/main/apps.json)

Then install **ParkBud** from the source and let SideStore re-sign it.

If you already have 1.0 installed, refresh the source and install 2.0.1 as an update.

## IPA

- App: ParkBud 2.0.1 (build 11)
- Bundle ID: `us.marting.parkbud`
- Minimum iOS: 17.0
- Direct download: [ParkBud.ipa](https://github.com/KikeMartinG93/parkbud-ipa/releases/download/v2.0.1/ParkBud.ipa)

## Notes

- SideStore re-signs with your Apple ID. A free developer certificate needs a refresh about every 7 days.
- This IPA is unsigned so SideStore can sign it on install.
- The Lock Screen widget, Apple Watch app, and App Group may not survive every SideStore signing setup. The iPhone app is the install target.
