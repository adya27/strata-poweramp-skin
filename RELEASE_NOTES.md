# STRATA 0.1.0 — preview

First direct-APK preview of STRATA for Poweramp 3.

- Paired dark and light themes and native Poweramp options.
- English and Russian companion app.
- Permanent release signature; package `com.strata.poweramp.v3.skins`, versionCode `3`.
- No Android permissions, ads, analytics, or accounts.

**Poweramp allowlist approval is pending.** The 48-hour limit and non-persistent options still apply on Poweramp builds enforcing verification. An approved certificate must ship in a Poweramp update before permanent use works.

Android 6.0+ is declared. Earlier runtime QA covered an Android 16 emulator with Poweramp 1034; physical devices and other Android versions have not been validated. The production signing build passes compilation, resource checks, lint (0 errors / 23 warnings), and v1/v2 signature verification.

Users of the earlier test-key APK must uninstall that STRATA app before installing this release. Preserve `SHA256SUMS.txt` and compare the downloaded APK against it if checking file integrity. The public certificate is provided separately for the Poweramp developer.
