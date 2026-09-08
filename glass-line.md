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
- The app is supported by rewarded video ads — videos you choose to watch. They are not
  switched on for every installation from the start, and they use an advertising
  identifier.
- We collect usage and crash statistics. They never contain your scripts or your voice,
  and they are not tied to your advertising identifier — but they are not anonymous
  either, and Google may use the usage part for advertising as well as for our
  statistics.

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
  Pause, plus a few seconds afterwards while the microphone is released. Stopping
  playback or leaving the teleprompter ends the session. If you have
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
camera has taken it — **the accessibility service** reads this from Android's audio
system, by audio source, and never by looking at which apps you have or what you are
doing in them.

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

Ads are delivered through the **Appodeal** mediation SDK. In this app it serves ads from
**Google AdMob** and from Appodeal's own demand — the **BidMachine** ad exchange and the
**Bidon** bidding layer. No other advertising network's software is included in the app.
To select and measure ads, these SDKs may process:

- your device's advertising identifier (Android Advertising ID), and the **App Set ID**,
  a separate identifier that Google scopes to this developer's apps on your device;
- coarse device and app information (device model, OS version, app version, language,
  country);
- your IP address, from which an approximate location is derived;
- ad events — that an ad was requested, shown, clicked or completed.

Advertisers bidding through these exchanges may also receive this information in order
to bid. In the European Economic Area, the United Kingdom and Switzerland, which of them
receive it depends on the choices you make in the consent form described below.

The same information is also used to keep the advertising itself honest. These partners
check the advertising identifier and the ad events against invalid traffic, click fraud
and abuse, and keep what their own legal and contractual obligations oblige them to keep.
That is the **fraud prevention, security and compliance** purpose recorded beside
*advertising or marketing* for **device or other IDs** on this app's Google Play Data
safety listing. It uses the data already listed above and collects nothing further, and
GlassLine performs no checks of its own: it has no accounts, no server and nothing to
defend.

These partners act as independent controllers of that data. See:

- [Google AdMob / Google advertising privacy](https://policies.google.com/technologies/ads)
- [Appodeal privacy policy](https://www.appodeal.com/privacy-policy/)
- [BidMachine privacy policy](https://www.bidmachine.com/privacy-policy)
- [Bidon privacy policy](https://www.bidon.org/privacy-policy)

**Your choices.** In the European Economic Area, the United Kingdom and Switzerland, the
app asks for your consent before any personalised advertising, using Google's consent
form. It is shown before the app makes its first advertising request, and it lists the
partners it is asking about; you can change your answer later through the **Ad privacy**
button in the app bar of GlassLine's first screen. In US states with applicable privacy
laws, that same button is the opt-out those laws require. On any Android device you can
also reset or delete your advertising ID in **Settings → Privacy → Ads**, which limits
the ad personalisation described above.

Advertising is not switched on for every installation from the beginning, and it can be
switched off remotely. Until it is switched on for your device, GlassLine **requests no
advertising consent, loads no ad and makes no request to any advertising exchange**;
when it is switched on, the consent form described above is the first thing that
happens, before any ad is requested and before the app ever offers you a video.

One thing happens regardless, and it would be wrong to imply otherwise: parts of the ad
libraries are started by Android when the app's process starts, before any of the above
is decided. They request nothing until advertising is switched on for your device.

The analytics described in the next section do run from launch on every installation,
but they are configured **not** to read your advertising identifier, so that identifier
is used only for the advertising described here — and only once advertising is switched
on and, where consent is required, you have given it.

## Analytics and crash reporting

GlassLine uses **Google Firebase** for:

- **Analytics** — usage events (for example: a session started, a script was created, a
  prompt was shown). These events describe actions, not content: **the text of your
  scripts is never included, and neither is anything you have said or anything the
  speech recogniser returned.** They carry counts, durations, settings and outcomes.
  They are not anonymous: Firebase attaches an app-instance identifier, and Google may
  use this data for measurement and advertising as well as for our own statistics. **We
  have switched off the analytics' use of your advertising identifier**, so the usage
  statistics are not tied to it.
- **Crashlytics** — crash and error reports, including the device model, OS version, app
  version and a stack trace, so that failures can be diagnosed and fixed.
- **Remote Config** — settings the app downloads from Google's Firebase servers to
  adjust its behaviour. **We have no servers of our own.** It is mostly a download, but
  the request is not empty: it carries an app-installation identifier and basic app and
  device details (app and SDK version, language, country, time zone, platform version).
  It carries nothing you have written.

Firebase processes this data on Google's infrastructure under the
[Google Privacy Policy](https://policies.google.com/privacy) and the
[Firebase privacy documentation](https://firebase.google.com/support/privacy).

If Firebase is unreachable, or the device has no network at all, GlassLine continues
to work normally.

## Data we do not collect

We do not collect your name, email address, phone number, contacts, photos, files,
precise GPS location, or the content of your scripts. GlassLine has no location
permission of any kind, and it cannot see what other apps you have installed.

We do not sell personal information for money. Sharing an advertising identifier with
our advertising partners so that they can select and measure personalised ads may
nonetheless count as a "sale" or a "share" under some US state privacy laws; the **Ad
privacy** control described under Advertising is how you opt out of it. Beyond the
advertising and analytics services named on this page, we build no profile of you.

## Children

GlassLine is not directed at children and we do not knowingly collect personal
information from children. If you believe a child has provided personal information
through the app, contact us at the address above and we will act on it.

## Permissions in the installed app

Some of these GlassLine asks for; the rest are merged into the app by the libraries it
uses, which is why they appear in the store listing. This is the complete list of the
ones that mean anything for your privacy.

| Permission | Why |
| --- | --- |
| `RECORD_AUDIO` | Voice-controlled scrolling. Requested on first Play, used only during a reading session. |
| `INTERNET`, `ACCESS_NETWORK_STATE` | Speech recognition — your device's recognition service may recognise over the network — and loading ads, analytics, crash reports and remote settings. |
| Accessibility service (`BIND_ACCESSIBILITY_SERVICE`) | Optional. Lets voice control keep working while another app records video. Off unless you enable it in Android's settings. |
| `com.google.android.gms.permission.AD_ID` | Merged in by the Appodeal SDK; gives access to the advertising identifier, which is used for the advertising described above. The analytics are configured not to use it. |
| `ACCESS_ADSERVICES_AD_ID`, `ACCESS_ADSERVICES_ATTRIBUTION`, `ACCESS_ADSERVICES_TOPICS` | Merged in by the Google Mobile Ads SDK for Android's Privacy Sandbox. |
| `com.google.android.finsky.permission.BIND_GET_INSTALL_REFERRER_SERVICE` | Merged in by Firebase Analytics. Lets Google tell us which Play Store link an install came from, and when it was clicked. |
| `ACCESS_WIFI_STATE` | Merged in by the ad consent library, as a network-quality signal on ad and consent requests. |
| `com.amazon.privacypass.ATTEST` | Merged in by the ad measurement library that ships with BidMachine. It is used for advert-verification attestation on Amazon devices and does nothing on other phones. |

The app also contains a component from the Appodeal SDK that is told by Android when a
new app is installed on your device, so that an install resulting from an ad can be
counted. GlassLine has no permission to list the apps you have installed and does not
do so.

## Your rights

Depending on where you live, you may have the right to access, correct, delete or
export personal data about you, to object to or restrict its processing, and to withdraw
consent. Because GlassLine holds no account and stores your content only on your
device, most of this is exercised directly: uninstalling the app removes the data it
keeps — though, as above, a copy of your scripts may remain in your own Google backup
until that backup is deleted or replaced. For data held by our advertising and analytics
partners, use the links above, or write to us and we will help.

## Changes to this policy

If this policy changes materially we will update this page and the effective date at the
top of it. The version published here is always the current one.

## Contact

together.on.the.road.team@gmail.com
