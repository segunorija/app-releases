# TargetCalendar Lite

Track daily GBP targets and actuals in a month-view calendar. Entries stay on your device. The app works offline without an account or network permission.

## Free download — version 1.1.1

TargetCalendar Lite **1.1.1 / build 6** updates the launcher and in-app logo with a green calendar and red LITE ribbon. It preserves Lite's calendar behaviour, storage and **Export to Excel**. Android 8.0 (API 26) and later; installed name **TargetCalendar**, package `com.ekelola.targetcalendar`.

- Daily targets and actuals in a monthly calendar.
- Status colours and ticks, plus monthly totals and averages.
- Excel workbook export for saving or sharing recorded months.

[Download TargetCalendar Lite 1.1.1 (APK)](https://github.com/segunorija/app-releases/releases/download/targetcalendar-v1.1.1/TargetCalendar-1.1.1.apk)

[Release notes](https://github.com/segunorija/app-releases/releases/tag/targetcalendar-v1.1.1) · [SHA-256 checksum](https://github.com/segunorija/app-releases/releases/download/targetcalendar-v1.1.1/TargetCalendar-1.1.1.apk.sha256) · [Verification metadata](releases/1.1.1.json)

## Updating Lite safely

Compatible Lite 1.1.0 users should **install over the existing app**. Keep a workbook export before updating. **Do not uninstall or clear app data**: that deletes local records, and Lite has no import/restore. This update preserves the permanent signing identity and application ID. Android orders updates by versionCode: 1.1.1 uses code 6, above previously distributed legacy codes 3 and 4.

**Existing 1.2.0/RC users should keep their installation and CSV exports.** Lite 1.1.1 is an artwork update to the older Lite feature set; it lacks 1.2.0's Settings, themes and CSV import/export. Its higher code does not make it a recommended update for 1.2.0. A 1.2.0-to-Lite migration has not been tested or certified safe. Do not uninstall, clear data or install Lite over it to change editions.

## Paid edition — coming soon

TargetCalendar's paid Google Play edition is planned at **£1.99, one-time purchase**, based on the accepted 1.2.0 feature set. It is not yet available on Play. It adds default-target settings, Monday/Sunday week start, Light/Dark/System appearance, accent choices, CSV import/export, overtime status and offline help.

Paid uses `com.ekelola.targetcalendar.paid`, installs separately, and does not automatically migrate records or preferences. Lite 1.1.0 and 1.1.1 export native Excel workbooks; paid imports CSV. Convert every monthly sheet to one UTF-8 comma-delimited file with `Date,Target,Actual` columns, ISO dates, numeric GBP decimals and blanks distinct from zero. Omit each source sheet's header, totals and status. Retain the original workbook and inspect the paid import preview before confirming. Existing 1.2.0 users can export CSV directly. No paid binaries are distributed here.

## Earlier releases

[Lite 1.1.0 release](https://github.com/segunorija/app-releases/releases/tag/targetcalendar-v1.1.0) is retained unchanged as an earlier release. Historical 1.2.0/RC records under `releases/` describe withdrawn distributions and are not current download guidance.

[Ekelola App Library](https://ekelola.com/app-library/)
