# TargetCalendar

Track daily GBP targets and actuals in a month-view calendar. A tick marks a met positive target. Entries stay on your device, and new installations start empty. The app works offline without an account or network permission. Uninstalling or clearing app data removes local records and preferences.

## Release candidate: 1.2.0-rc.1

This is a public **testing pre-release** for Android 8.0 (API 26) and later. The installed package identifies as **TargetCalendar 1.2.0 / build 4**; the release tag is `targetcalendar-v1.2.0-rc.1`. Stable 1.1.0 remains the latest stable release.

- [Download the signed 1.2.0 candidate (APK)](https://github.com/segunorija/app-releases/releases/download/targetcalendar-v1.2.0-rc.1/TargetCalendar-1.2.0.apk)
- [Candidate release notes](https://github.com/segunorija/app-releases/releases/tag/targetcalendar-v1.2.0-rc.1)
- [Candidate SHA-256 checksum](https://github.com/segunorija/app-releases/releases/download/targetcalendar-v1.2.0-rc.1/TargetCalendar-1.2.0.apk.sha256)
- [APK verification metadata](https://github.com/segunorija/app-releases/releases/download/targetcalendar-v1.2.0-rc.1/verification.json)
- [Source, merge and validation provenance](releases/1.2.0-rc.1.json)
- [Sample CSV](https://github.com/segunorija/app-releases/releases/download/targetcalendar-v1.2.0-rc.1/TargetCalendar-sample.csv)

The candidate keeps the familiar calendar, editor, logo and original light/green appearance. It adds:

- A stationary header with Settings beside Today, plus a separate scrolling Settings screen.
- A saved daily default and explicit month application, preserving actuals and existing targets unless replacement is confirmed. Saving a default or browsing months never rewrites records.
- Monday/Sunday week start, Light/Dark/System themes and Original green/Ekelola indigo accents.
- CSV export across all saved dates, native Save/Share, and validated CSV import with a conflict preview and explicit confirmation. Existing conflicts are kept by default; replacement includes deliberate blanks.
- Purple Overtime for positive actuals against a zero target. Zero-target/zero-actual days remain saved but are excluded from recorded-day averages.
- Offline Help, release notes and installed version/build information.

CSV replaces workbook export in 1.2.0. Use UTF-8, commas, `Date,Target,Actual` headers (optional `Status`), ISO dates and non-negative GBP decimals. Blank differs from zero. Import limits are 5 MiB and 50,000 records. Native `.xlsx`/`.xls` files must be saved as CSV first. CSV contains daily records only, not settings or appearance, and is not a full app backup. [Format guidance](https://github.com/segunorija/targetcalendar/blob/main/docs/CSV_FORMAT.md).

The exact signed candidate passed automated logic/browser/CSV checks and Android builds/lint, plus physical Pixel 6a checks on the device-reported Android 17/API 37 and WebView 156.0.8078.47. Native file exchange, offline restart, Gboard, process-death recovery, Excel desktop CSV round-trip and a signed 1.1.0 upgrade were exercised with disposable data. [Detailed evidence and remaining coverage](https://github.com/segunorija/targetcalendar/blob/main/docs/PIXEL_ACCEPTANCE.md). Google Sheets, other Android versions and provider-specific access errors remain additional manual coverage.

Export a copy of important records before updating. Install over the existing TargetCalendar app; do not uninstall or clear app data. The candidate uses the permanent signing identity, and an upgrade in a disposable Pixel profile retained its saved target/actual pair. Promotion to stable is a separate decision. Any changed build distributed after build 4 must use a higher Android version code.

Candidate APK SHA-256:

```text
90e0a62c54e108ae82613b7cbb610dbc2e23bad0fe679b9e50e917ba3f20df45
```

Permanent signing-certificate SHA-256:

```text
fd9fe59a1c0d9db426bf67f5dcecaaa377780c95d525514265d481cc5560acdd
```

## Latest stable: 1.1.0

Stable 1.1.0 supports Android 8.0 (API 26) and later. Its data exchange is **Export to Excel**, which saves/shares recorded months as a workbook; the candidate's Settings/CSV features are not part of 1.1.0. Each release has its own versioned tag and checksum.

- [Download TargetCalendar 1.1.0 (APK)](https://github.com/segunorija/app-releases/releases/download/targetcalendar-v1.1.0/TargetCalendar-1.1.0.apk)
- [Release notes for 1.1.0](https://github.com/segunorija/app-releases/releases/tag/targetcalendar-v1.1.0)
- [SHA-256 checksum](https://github.com/segunorija/app-releases/releases/download/targetcalendar-v1.1.0/TargetCalendar-1.1.0.apk.sha256)

[Browse releases](https://github.com/segunorija/app-releases/releases) · [Ekelola App Library](https://ekelola.com/app-library/)
