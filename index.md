---
layout: default
title: Moliboard Support
---

# Moliboard Support

Moliboard turns your Mac keyboard into a real piano for small kids — a 37-key grand-piano sound, an animated Ocean or Space world that reacts to every note, and 34 play-along nursery and classical songs.

This page is where to come for help, FAQ, and contact info. The [privacy policy](./PRIVACY.html) is on its own page.

## Contact

- **Email:** [yang.qi@opcify.ai]
- **Typical response time:** within two working days.
- When writing, it helps us a lot if you include the app version (visible in *Moliboard → About*), your macOS version, and — for bugs — a short description of what you were doing right before the issue.

## What Moliboard does

- Turns every letter, number, and punctuation key on your Mac keyboard into a piano note. 37 keys in total, laid out like a real piano.
- Plays a real grand-piano sound using the audio sampler built into macOS. No tinny beeps.
- Renders an animated background (Ocean or Space) that reacts to every note you play — fish and bubbles in Ocean, stars and galaxies in Space.
- Includes 34 play-along songs — nursery rhymes like *Twinkle Twinkle*, folk tunes like *Oh Susanna*, and classical pieces like *Für Elise* and *Canon in D*. A bouncing arrow shows the next key; kids play at their own pace.
- Tracks stars, levels and a Feed counter as simple rewards for practice. No timer, no penalty for wrong notes.

## System requirements

- macOS 26.4 or later.
- Any Mac with a keyboard — built-in on a laptop, or external (wired or wireless) on a desktop. Apple Magic Keyboard, third-party mechanical keyboards, and the on-screen keyboard all work.
- Speakers or headphones.
- A MIDI keyboard is **not** required and is not currently supported — the whole point of Moliboard is that your kid needs no extra hardware.

## Supported languages

The app interface is fully localised in:

- English
- 简体中文 (Simplified Chinese)
- 繁體中文 (Traditional Chinese)

Moliboard uses your Mac's system language. To change it, open *System Settings → General → Language & Region*, set Moliboard's preferred language, and relaunch the app.

## Quick start

1. Open Moliboard — the app starts in its own window.
2. Press any letter, number or punctuation key. That's a piano note.
3. The bottom row of your Mac keyboard is bass, the top row is treble, and **Middle C sits on the H key**.
4. Tap the song card at the top to pick a song and play along.
5. The very first time you open the app, an in-app tutorial guides you through the above in under a minute.

## Frequently asked questions

### I don't hear any sound when I press a key.

Three things to check, in order:

1. **System volume and output device.** Make sure your Mac isn't muted and the output device is the one you expect (built-in speakers, Bluetooth headphones, etc.).
2. **App focus.** Moliboard only listens to the keyboard while its window is the active window. Click on the Moliboard window and try again.
3. **Relaunch.** Quit Moliboard (*⌘Q*), reopen it, and the audio engine is rebuilt from scratch. Almost every "no sound" report we get is resolved by this.

If none of that works, email us with your macOS version — we'll help figure it out.

### How do I change the background — Ocean, Space, or the galaxy version of Space?

- Press **` (the backtick key, top-left of your keyboard)** to switch between Ocean and Space.
- When Space is showing, press **\\ (backslash)** to flip between the galaxy and cartoon styles.
- Your choice is remembered the next time you open the app.

### Can I use a MIDI keyboard or external piano controller?

No — Moliboard is specifically designed around the built-in Mac keyboard. That's the whole point: your kid doesn't need any extra hardware to start playing.

### How do I play a song?

Open the song picker at the top of the screen, pick any of the 34 songs, and press **Play it!**. A bouncing arrow will appear above the next key your kid needs to press. Kids play at their own pace — there is no timer and no "wrong note" penalty.

### My child is struggling with the full songs. Is there an easier mode?

About half of the included songs are "starter" arrangements (short, simple, one hand). The longer arrangements have `(Full)` in the title — skip those for smaller kids until they're ready.

### What age is Moliboard designed for?

Moliboard is built with 3–6 year olds in mind, but plenty of older kids (and a few adults) enjoy it too. There is no reading required and the first interaction — "press a key, hear a note" — needs zero instruction.

### Does Moliboard need an internet connection?

No. Moliboard is fully offline. After install, you can use it on a Mac that has no network connection at all. See the [privacy policy](./PRIVACY.html) for detail.

### Does Moliboard collect any data about my child?

No. Moliboard has no accounts, no analytics, no network access, and no third-party SDKs. See the [privacy policy](./PRIVACY.html) for the full statement.

### What macOS versions are supported?

macOS 26.4 or later. Older versions of macOS are not supported.

### The app is too loud / too quiet.

Moliboard follows your system output volume. Use the volume keys on your Mac keyboard, or the volume slider in Control Center. The app itself does not have a separate volume slider on purpose — one fewer thing for a small child to accidentally change.

### How do I quit or go full-screen?

Moliboard is a normal macOS windowed app.

- **Quit:** press *⌘Q*, or click the red traffic-light button in the top-left corner.
- **Full-screen:** click the green traffic-light button for big-screen concerts. *Esc* or *⌃⌘F* returns to windowed mode.

### How do I reset the app — clear progress, stars and theme preference?

Moliboard stores a small set of preferences (selected theme, current song, keyboard layout, progress counters) in the standard macOS user-defaults store. To reset:

1. Quit Moliboard.
2. Open Terminal and run:
   ```
   defaults delete ai.opcify.Moliboard
   ```
3. Reopen Moliboard. It will start fresh as if newly installed.

Uninstalling the app (dragging it to the Trash) also removes this data.

### Can I use Moliboard with Screen Time, Focus modes, or guided access on macOS?

Yes. Moliboard is a regular sandboxed app and respects all system parental-control and Focus-mode settings. You can add it to your child's approved apps in *Screen Time → Content & Privacy Restrictions → App Store, Media, Web & Games → Apps* on the parent's Mac.

### Accessibility notes

- Moliboard does not require the mouse. Everything in the game loop runs from the keyboard.
- All interactive visuals also produce audio feedback, and all audio events also produce visual feedback.
- The app does not rely on colour alone to convey information (the bouncing arrow that guides song playback is a shape and a motion, not just a colour).
- If you have specific accessibility needs we haven't covered, please email — we take those requests seriously.

## Reporting a bug

Email [yang.qi@opcify.ai]with:

1. **App version** — visible in *Moliboard → About*.
2. **macOS version** — visible in  → *About This Mac*.
3. **Your Mac model** — also in  → *About This Mac*.
4. **What you were doing** — one or two sentences is fine. ("Playing *Old MacDonald*, pressed H repeatedly, the screen froze on the third verse.")
5. **Screenshot or screen recording** if the issue is visual. *⇧⌘5* on macOS captures a screen recording.

## Refunds and billing

Refunds for App Store purchases are handled by Apple, not by us. To request one, use [reportaproblem.apple.com](https://reportaproblem.apple.com) and pick the Moliboard purchase. If you think the reason for the refund is a bug we should know about, please also email us — even if you've already filed with Apple.

## Known issues

Nothing open right now. If you hit something, please let us know.

## Release notes

Every shipped version's notes appear on Moliboard's App Store listing under *What's New in Version X*. This page will be updated if we ever introduce a behavioural change worth flagging to existing users outside the App Store notes.

## Privacy

See the [privacy policy](./PRIVACY.html).
