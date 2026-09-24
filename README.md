# Amalgam releases

Public downloads of Amalgam, a VPN client over olcRTC.

Every version has its own release: what changed, the files themselves, and their SHA-256
hashes (also in `SHA256SUMS`, for `shasum -a 256 -c SHA256SUMS`). Take the newest one from the
[releases list](https://github.com/YolisStormbreaker/amalgam-releases/releases).

- **macOS** (Apple silicon, macOS 14 or later): `Amalgam-<version>.zip`, signed with Developer ID
  and notarized. Unzip it and move Amalgam to Applications. The app updates itself.
- **Android** (arm64, Android 6.0 or later): `Amalgam-<version>-arm64-v8a.apk`, package
  `com.yolisstorm.amalgam`. Install it by hand the first time; after that the app updates itself.
- **iPhone and iPad**: through TestFlight, by invitation.

How to check the signatures is at the end of each release's notes.

The `files` release is where the update feeds pointed before per-version releases; it stays for
the versions that still fetch from it.
