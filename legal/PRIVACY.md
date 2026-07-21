# MONARCH Privacy Policy

DRAFT - for attorney review; not legal advice.

Last updated: July 1, 2026

This Privacy Policy explains what information MONARCH handles when you install, activate, and use the software. MONARCH is designed first as a local show-control application: your show files, stems, lyrics, charts, and most operational data stay on your computer unless you choose to sync or send them elsewhere.

## 1. Information Stored Locally

MONARCH stores show state, song metadata, library indexes, preferences, logs, cached media, generated cue audio, and package/export artifacts on your computer. Local files may include song titles, artist names, lyrics, chart names, audio file paths, routing choices, MIDI settings, performance history, license status, and crash or diagnostic logs.

Local files are not sent to us automatically.

## 2. License Activation

MONARCH uses Keygen or a similar license service to activate and verify licenses. License requests may include:

- the license key or account identifier you enter;
- a machine fingerprint or machine identifier;
- license id, activation id, product id, policy id, entitlement, tier, expiry, and status;
- app version, operating system, request time, and network metadata needed by the license provider.

This data is used to validate licenses, enforce activation limits, support offline verification, prevent abuse, and provide support.

## 3. MONARCH Cloud

If you configure MONARCH Cloud, the app may send and receive cloud account, organization, library, show, song, setlist, preparation, and sync metadata. This may include names, email addresses, rig display names, show names, song titles, song metadata, set order, notes, and timestamps.

MONARCH Cloud is not intended to store raw multitrack audio, chart PDFs, or other large performance media unless a future cloud feature explicitly says it does. Audio and chart files are generally expected to remain local or in storage services you configure.

If MONARCH Cloud is not configured, the desktop app does not connect to it.

## 4. Optional Integrations

If you configure or use optional integrations, MONARCH may exchange data with those services:

- Dropbox library sync may read folder names, song metadata sidecars, audio/chart file metadata, and sync tokens needed for your Dropbox account.
- LRCLIB lyric lookup may send song title, artist, album, or duration to search for lyrics.
- GitHub links may open release pages, documentation, or issue forms in your browser.
- If you explicitly enable anonymous crash reports, a configured Sentry endpoint receives the limited crash-occurrence payload described below. As with any web request, the provider may process transport metadata such as the source IP address.
- Operating-system services may handle file pickers, crash logs, networking, audio devices, MIDI devices, and URL opening.

Those services are governed by their own privacy policies.

## 5. Diagnostics and Bug Reports

MONARCH writes local logs and crash markers. Automatic crash reporting is off by default and requires an explicit preference. When enabled and a reporting endpoint is present in the signed build, the next launch sends only the app version, operating-system name, and the fact that a crash occurred. The report payload does not include the crash log, stack trace, show/song names, paths, lyrics, audio, device names, or machine identifiers. The app may also help you reveal a local log file or open a pre-filled GitHub issue; anything you share manually may contain machine names, file paths, device names, show/song names, plugin state, error messages, and other troubleshooting details.

Review diagnostics before sharing them publicly.

## 6. Analytics

MONARCH does not currently include product analytics, advertising trackers, or third-party marketing SDKs. We do not currently collect automatic usage analytics from local app sessions.

If analytics are added in the future, this policy should be updated before that build is shipped.

## 7. Data Retention

Local MONARCH data remains on your computer until you delete it. Cloud, license, issue tracker, or integration data is retained according to the relevant service, account, legal, support, and backup requirements.

## 8. Security

We use reasonable safeguards appropriate for a beta-stage product, but no software, network, or storage system is perfectly secure. You are responsible for protecting your computer, your show content, your Dropbox account, your GitHub account, license keys, and any exported packages.

## 9. Children

MONARCH is a professional production tool and is not intended for children under 13. Do not provide children's personal information to MONARCH Cloud or support channels.

## 10. Changes

We may update this Privacy Policy as MONARCH changes. The current policy should be included with release packages and linked from the app or release site.

## 11. Contact

For privacy or support questions, use the public MONARCH release issue tracker:

https://github.com/johnconradmusic/monarch-releases/issues
