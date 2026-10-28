# STRATA for Poweramp 3

STRATA 0.1.0 is an early preview skin with paired dark and light themes, a quiet background, and native Poweramp skin options. The companion app supports English and Russian. Poweramp itself is required: https://powerampapp.com/.

## Download and install

Download `STRATA-0.1.0-release.apk` from this repository's Releases page. Android 6.0 (API 23) or newer is required. Install the APK, open STRATA, tap Apply in Poweramp, and select STRATA in Poweramp's skin picker. The separate STRATA Light entry is also available; Poweramp's Follow Day/Night Mode switches the paired variants.

If you installed the earlier local-test APK, uninstall that STRATA app first. The public preview uses a different, permanent signing key, so Android cannot install it as an update to the test-key build.

## Poweramp verification — approval pending

This release is **not yet allowlisted by Poweramp**. On Poweramp builds with skin verification, it appears as unverified, skin options do not persist across host restarts, and Poweramp automatically deselects the skin after 48 hours. The companion app can open the native options page. Permanent use depends on the developer accepting the release certificate and shipping it in a Poweramp update. Publication alone does not grant verification.

Package: `com.strata.poweramp.v3.skins`  
Version: `0.1.0` / versionCode `3`  
APK signing certificate SHA-256:

```text
55306D0E141E4E3202EDDE00731D1D63A67F2C1F0CE7D99352935856B39156D0
```

The release assets include `SHA256SUMS.txt` (APK file integrity) and `strata-release-certificate.pem` (public certificate). The signing certificate fingerprint and APK file checksum are different identifiers.

## Validation and privacy

The production APK builds successfully, passes the resource contract check, and verifies with APK Signature Schemes v1 and v2. Release lint reports 0 errors and 23 warnings. The same app code and resources were previously exercised on an Android 16 emulator with Poweramp build 1034. The newly signed APK has not been tested on a physical device; other Android versions and OEM firmware remain unverified.

STRATA requests no Android permissions and includes no accounts, advertising, analytics, or network access. Poweramp remains responsible for music playback and its own data handling. STRATA is an independent third-party skin.

Poweramp API/SDK notice: [POWERAMP-SDK-LICENSE.txt](POWERAMP-SDK-LICENSE.txt). Official skin verification documentation: https://github.com/maxmpz/powerampapi/blob/master/poweramp_skin_sample/readme.md#skin-verification.
