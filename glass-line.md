---
title: "GlassLine — Privacy Policy"
description: "How the GlassLine teleprompter app for Android handles your data."
---

# GlassLine — Privacy Policy

**Application:** GlassLine
**Package:** `com.togetherontheroad.telepromter`
**Platform:** Android
**Publisher:** Together On The Road
**Effective date:** 8 September 2026
**Contact:** together.on.the.road.team@gmail.com

GlassLine is a teleprompter that scrolls your script by listening to you read it aloud.
This policy explains what the app does with data, and what it does not.

## The short version

- GlassLine has no accounts and no sign-in. We never ask you who you are.
- Your scripts stay on your device, and we never upload them and never see them. If you
  use Android's own backup, Android may copy them to your Google Drive so you can
  restore them on a new phone — that copy is yours, not ours.
- The microphone is used only while a reading session is running, only to follow your
  place in the script, and only after you allow it. The audio goes to your device's
  speech recognition service, which on most phones is Google's and may process it over
  the network.
- There is an optional accessibility service that keeps voice scrolling working while
  another app is recording video. It is off unless you turn it on yourself, and
  everything else works without it.
- The app shows rewarded video ads, and those ads use an advertising identifier.
- We collect anonymous usage and crash statistics so we can fix what breaks.

## Scripts you write

Scripts you create in GlassLine are stored in the app's own storage on your device.
They are never sent to us and never synced to any server of ours.

If you have Android's own backup switched on, Android may include GlassLine's data —
including your scripts — in **your** Google Drive backup, so that you can restore them
when you set up a new phone. That backup belongs to your Google account and is not
visible to us. You can turn it off, or delete it, in Android's
**Settings → Google → Backup**.

Deleting a script in the app, or uninstalling the app, removes it from the device. A
copy may remain in your own Google backup until that backup is deleted or replaced.

## Microphone and speech recognition

Voice-controlled scrolling is the point of the app, so GlassLine needs to hear you.

- The app asks for microphone permission the first time you press Play — never at
  launch — and will not listen until you grant it.
- Audio is captured only while a reading session is running — that is, between Play and
  Pause. Stopping playback or leaving the teleprompter ends the session. If you have
  enabled the optional accessibility service described below, a session continues while
  you are in your camera app, so that the script can keep following your voice while you
  film; it still ends when you stop playback or leave the teleprompter.
- GlassLine does not save or transmit audio. Depending on the mode, either Android's own
  speech recognition service opens the microphone directly, or GlassLine captures the
  audio itself and passes it straight to that recognition service. Either way the audio
  is never written to a file, never kept once it has been recognised, and never sent to
  a server belonging to GlassLine. The recognised words come back to the app, are
  matched against your script in memory, and are then discarded.
- On most Android devices that recognition service is provided by Google, and it may
  process the audio on Google's servers. What happens to the audio there is governed by
  the privacy policy of the recognition service on your device (on Google devices, the
  [Google Privacy Policy](https://policies.google.com/privacy)), not by this one. Which
  service handles recognition is a device setting you control.

## Voice control while recording (optional accessibility service)

GlassLine includes an optional Android **accessibility service**, shown in Android's
settings as "GlassLine voice scrolling". It is switched off when you install the app,
GlassLine cannot switch it on, and everything else in the app works without it.

**Why it exists.** When a camera app records video, Android gives that app the
microphone and gives GlassLine silence instead, so the script stops following your voice
at the moment you need it most. An enabled accessibility service listening for speech is
the one arrangement Android allows for keeping voice control working while another app
records. Your video keeps its own sound.

**What it does.** While a reading session is running, it receives microphone audio so
your speech can be recognised and used to scroll the script, and it shows a small
"GlassLine is listening" badge over whatever app you are filming with. The badge does
not take touches; the app underneath keeps every tap. While the service is on, it also
checks which other apps are using the microphone, so that GlassLine can tell you when a
camera has taken it — this is read from Android's audio system, by audio source, and
never by looking at which apps you have or what you are doing in them.

**What it does not do.** It cannot read what is on your screen. It receives no
accessibility events, cannot tap, type or act in other apps, and has no capabilities
beyond capturing audio. It captures nothing unless you have pressed Play in GlassLine.

**The audio is handled exactly as described above** — passed straight to your device's
speech recognition service, never written to a file, never kept once recognised, and
never sent to a server belonging to GlassLine. On most phones that recognition service
is Google's and may process the audio on Google's servers.

**Turning it off.** Open Android's **Settings → Accessibility → GlassLine voice
scrolling** and switch it off. You can do this at any time.

## Advertising

GlassLine is free and supported by **rewarded video ads** — full-screen videos you
choose to watch. There are no banners and no interstitials. From time to time the app
asks whether you would like to watch one; the video plays only if you choose to watch
it.

Ads are delivered through the **Appodeal** mediation SDK, which in this app serves ads
from **Google AdMob** only. To select and measure ads, these SDKs may process:

- your device's advertising identifier (Android Advertising ID);
- coarse device and app information (device model, OS version, app version, language,
  country);
- your IP address, from which an approximate location is derived;
- ad events — that an ad was requested, shown, clicked or completed.

These partners act as independent controllers of that data. See:

- [Google AdMob / Google advertising privacy](https://policies.google.com/technologies/ads)
- [Appodeal privacy policy](https://www.appodeal.com/privacy-policy/)

**Your choices.** In the European Economic Area, the United Kingdom and Switzerland, the
app asks for your consent before any personalised advertising, using Google's consent
form. In US states with applicable privacy laws, the app offers the opt-out required by
those laws. On any Android device you can also reset or delete your advertising ID in
**Settings → Privacy → Ads**, which limits the ad personalisation described above.

## Analytics and crash reporting

GlassLine uses **Google Firebase** for:

- **Analytics** — anonymous, aggregated usage events (for example: a session started, a
  script was created, a prompt was shown). These events describe actions, not content:
  the text of your scripts is never included, and neither is anything you have said.
- **Crashlytics** — crash and error reports, including the device model, OS version, app
  version and a stack trace, so that failures can be diagnosed and fixed.
- **Remote Config** — settings fetched from our servers to adjust app behaviour. This is
  a download; nothing about you is sent up.

Firebase processes this data on Google's infrastructure under the
[Google Privacy Policy](https://policies.google.com/privacy) and the
[Firebase privacy documentation](https://firebase.google.com/support/privacy).

If Firebase is unreachable, or the device has no network at all, GlassLine continues
to work normally.

## Data we do not collect

We do not collect your name, email address, phone number, contacts, photos, files,
precise GPS location, or the content of your scripts. We do not sell personal
information. We do not build user profiles ourselves.

## Children

GlassLine is not directed at children and we do not knowingly collect personal
information from children. If you believe a child has provided personal information
through the app, contact us at the address above and we will act on it.

## Permissions the app requests

| Permission | Why |
| --- | --- |
| `RECORD_AUDIO` | Voice-controlled scrolling. Requested on first Play, used only during a reading session. |
| `INTERNET`, `ACCESS_NETWORK_STATE` | Speech recognition — your device's recognition service may recognise over the network — and loading ads, analytics, crash reports and remote settings. |
| Accessibility service (`BIND_ACCESSIBILITY_SERVICE`) | Optional. Lets voice control keep working while another app records video. Off unless you enable it in Android's settings. |
| `com.google.android.gms.permission.AD_ID` | Merged in by the Google Mobile Ads SDK; gives access to the advertising identifier used for ads. |

## Your rights

Depending on where you live, you may have the right to access, correct, delete or
export personal data about you, to object to or restrict its processing, and to withdraw
consent. Because GlassLine holds no account and stores your content only on your
device, most of this is exercised directly: uninstalling the app removes the data it
keeps. For data held by our advertising and analytics partners, use the links above, or
write to us and we will help.

## Changes to this policy

If this policy changes materially we will update this page and the effective date at the
top of it. The version published here is always the current one.

## Contact

together.on.the.road.team@gmail.com
