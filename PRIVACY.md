---
layout: default
title: Moliboard Privacy Policy
---

# Moliboard Privacy Policy

**Effective date:** 2026-04-20
**Applies to:** Moliboard for macOS, all versions, all regions.
**Bundle identifier:** `ai.opcify.Moliboard`

Moliboard is a macOS app built for small children. This policy is deliberately short, blunt, and comprehensive — the less ambiguity about kids' data, the better.

## Summary (the short version)

- Moliboard collects **nothing**.
- Moliboard sends **nothing** over the internet.
- Moliboard has no accounts, no sign-up, no sign-in, no tracking, no advertising, no analytics, no crash reporting, no third-party SDKs.
- Moliboard works fully offline. You can use it on a Mac that has never been connected to the internet.
- Moliboard's App Privacy "nutrition label" on the App Store is **Data Not Collected**, matching this policy exactly.

Everything below explains the above in more detail.

## What Moliboard collects

**Nothing.**

Specifically, Moliboard does not collect, process, or transmit any of the following:

- Names, email addresses, phone numbers, postal addresses.
- Device identifiers (IDFA, IDFV, serial numbers, MAC addresses).
- Apple ID, iCloud account, or any authentication identifiers.
- Advertising identifiers or tracking identifiers of any kind.
- Location data (coarse or precise).
- Contacts, calendars, photos, videos, or files from outside the app.
- Microphone, camera, screen-recording, or accessibility input.
- Health, financial, or biometric data.
- Browsing, search, or app-usage history.
- Diagnostics, crash logs, or performance metrics.

If Apple sends a system-level crash report to itself (as it may for any app), that path is between you, Apple, and your Mac's settings — Moliboard never sees those reports and never collects them.

## What Moliboard sends over the internet

**Nothing.**

The macOS app sandbox entitlement file ships with no network entitlements. The app has no outbound or inbound network code. You can verify this with Little Snitch, Lulu, or by using Moliboard on a Mac in airplane mode — the behaviour is identical.

## What Moliboard does with the keyboard

Moliboard reads keyboard events **only while its own window is the active (key) window**, and only to turn them into piano notes in real time. Key events are not stored, not logged, not aggregated, not forwarded anywhere, and not written to disk. They exist for the few milliseconds between keypress and sound — and then they're gone.

Moliboard does not require the macOS Accessibility permission, and does not monitor the keyboard globally. Switch to any other app and Moliboard stops seeing key events entirely.

## macOS permissions Moliboard requests

**None.** Moliboard asks for no macOS permissions of any kind — no Microphone, no Camera, no Accessibility, no Full Disk Access, no Automation, no Contacts/Calendars/Photos, no Location. If a permission prompt ever appears while using Moliboard, something is wrong — please email us immediately.

## What Moliboard stores on your device

A small amount of preference data is stored locally in the standard macOS user-defaults store (`ai.opcify.Moliboard` domain) so the app remembers your choices between launches:

- The last background theme you picked (Ocean or Space), and the last Space visual style (galaxy or cartoon).
- The last song you played and how far through it you got.
- The currently-selected keyboard layout.
- Per-song progress counters (stars earned, times played).
- Whether the first-run tutorial has been completed.

This data:

- **Never leaves your Mac.** It is not uploaded, synced, backed up to the cloud by Moliboard, or shared with any third party.
- **Is owned by you.** You can read, modify, or delete it at any time.
- **Is removed when you uninstall the app.** Dragging Moliboard to the Trash deletes the preferences.
- **Can also be cleared without uninstalling** — run `defaults delete ai.opcify.Moliboard` in Terminal.

If you have iCloud Drive backup of your Mac enabled by the operating system, Apple may back up the user-defaults store as part of the system-level backup. That path is between you and Apple — Moliboard does not initiate or participate in any backup.

## Third parties

Moliboard has **no third-party components** that process user data:

- No third-party analytics SDKs (no Firebase, no Mixpanel, no Amplitude, no Sentry, no Crashlytics, no anything).
- No third-party advertising SDKs.
- No third-party authentication providers.
- No third-party content networks.
- No server backend operated by Moliboard or anyone else.

The only code that runs in Moliboard is the app itself and the audio sampler that ships with macOS (Apple's `AVAudioUnitSampler` with the system grand-piano DLS at `/System/Library/Components/CoreAudio.component/Contents/Resources/gs_instruments.dls`). No network or data-sharing code.

## Children's privacy

Moliboard is intended for use by children, including children under 13.

- **COPPA (US):** Moliboard does not collect any personal information from children (or anyone else). It therefore does not require parental consent under the Children's Online Privacy Protection Act, because there is nothing to consent to — no data leaves the device.
- **GDPR-K (EU) / UK-GDPR children's rules:** The same applies in the EU and UK. There is no collection, no processing, and no controller relationship that would trigger the child-specific provisions of the GDPR.
- **Apple Kids Category guidelines:** Moliboard meets Apple's Kids Category privacy requirements because it does not collect personal information, does not include third-party advertising, does not include third-party analytics, and does not link out to websites or services outside parental control.

## Your rights (GDPR, CCPA, and equivalents)

Because Moliboard does not collect, store on its servers, or share any personal data, most data-subject rights (access, deletion, portability, correction, objection) are satisfied trivially: there is no data held about you that we could access, delete, port, correct, or act on.

The only data associated with Moliboard — the local preferences on your Mac — is entirely under your control and can be deleted by you at any time (see *What Moliboard stores on your device* above).

If you live in California, the European Union, the United Kingdom, or another region with data-protection legislation and you would still like a formal written confirmation that no data is held about you, email us and we will reply.

## Security

Moliboard is distributed only through the Mac App Store. Builds are signed and notarised by Apple, and run inside macOS's app sandbox. Because no data ever leaves the device, the attack surface for user-data compromise is effectively zero.

## Data retention

Because Moliboard collects no data, there is nothing to retain. Local preferences on your Mac are retained on your Mac until you delete them, on your schedule.

## International data transfers

None. No data is transferred, because no data is collected.

## Changes to this policy

If Moliboard ever gains a feature that changes any of the above — for example, an optional cloud sync, an optional analytics opt-in, or anything that involves the internet at all — this page will be updated **before** that feature ships, the effective date above will change, and the update will be called out in the relevant version's App Store release notes.

We will never quietly change this policy. If the summary at the top ever stops saying "collects nothing, sends nothing," it will be because an opt-in feature has been explicitly added and documented here.

## Contact

Questions about privacy, or a request for a formal written confirmation of any of the above:

- **Email:** yang.qi@opcify.ai
- **Typical response time:** within two working days.
- **Support page:** [https://opcify.github.io/moliboard-support/](./)
