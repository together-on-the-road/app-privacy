# Privacy policies — Together On The Road

Privacy policies for the mobile applications published by Together On The Road.

- [Telepromter (Android)](#telepromter-android)

---

## Telepromter (Android)

**Application:** Telepromter
**Package:** `com.togetherontheroad.telepromter`
**Platform:** Android
**Publisher:** Together On The Road
**Effective date:** 7 September 2026
**Contact:** together.on.the.road.team@gmail.com

Telepromter is a teleprompter that scrolls your script by listening to you read it
aloud. This policy explains what the app does with data, and what it does not.

### The short version

- Telepromter has no accounts and no sign-in. We never ask you who you are.
- Your scripts stay on your device. We never upload them and never see them.
- The microphone is used only while you are recording, only to follow your place in
  the script, and only after you allow it.
- The app shows rewarded video ads, and those ads use an advertising identifier.
- We collect anonymous usage and crash statistics so we can fix what breaks.

### Scripts you write

Scripts you create in Telepromter are stored in the app's own storage on your device.
They are not sent to us, not synced to any server, and not backed up by us. Deleting a
script in the app, or uninstalling the app, removes them from the device.

### Microphone and speech recognition

Voice-controlled scrolling is the point of the app, so Telepromter needs to hear you.

- The app asks for microphone permission the first time you press Play — never at
  launch — and will not listen until you grant it.
- Audio is captured only while a reading session is running. Stopping playback, leaving
  the screen or backgrounding the app ends the session.
- Telepromter does not record, store or transmit audio itself. It hands the microphone
  to **Android's own speech recognition service** and receives back recognised words,
  which it matches against your script in memory and then discards.
- On most Android devices that recognition service is provided by Google, and it may
  process the audio on Google's servers. What happens to the audio there is governed by
  the privacy policy of the recognition service on your device (on Google devices, the
  [Google Privacy Policy](https://policies.google.com/privacy)), not by this one. Which
  service handles recognition is a device setting you control.

### Advertising

Telepromter shows **rewarded video ads** — full-screen videos you choose to watch in
exchange for continued use. There are no banners, no interstitials and no ads that
appear without you opting in.

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

### Analytics and crash reporting

Telepromter uses **Google Firebase** for:

- **Analytics** — anonymous, aggregated usage events (for example: a session started, a
  script was created, a prompt was shown). These events describe actions, not content:
  the text of your scripts is never included.
- **Crashlytics** — crash and error reports, including the device model, OS version, app
  version and a stack trace, so that failures can be diagnosed and fixed.
- **Remote Config** — settings fetched from our servers to adjust app behaviour. This is
  a download; nothing about you is sent up.

Firebase processes this data on Google's infrastructure under the
[Google Privacy Policy](https://policies.google.com/privacy) and the
[Firebase privacy documentation](https://firebase.google.com/support/privacy).

If Firebase is unreachable, or the device has no network at all, Telepromter continues
to work normally. Following a voice does not need the internet.

### Data we do not collect

We do not collect your name, email address, phone number, contacts, photos, files,
precise GPS location, or the content of your scripts. We do not sell personal
information. We do not build user profiles ourselves.

### Children

Telepromter is not directed at children and we do not knowingly collect personal
information from children. If you believe a child has provided personal information
through the app, contact us at the address above and we will act on it.

### Permissions the app requests

| Permission | Why |
| --- | --- |
| `RECORD_AUDIO` | Voice-controlled scrolling. Requested on first Play, used only during a reading session. |
| `INTERNET`, `ACCESS_NETWORK_STATE` | Loading ads, analytics, crash reports and remote settings. |
| `com.google.android.gms.permission.AD_ID` | Merged in by the Google Mobile Ads SDK; gives access to the advertising identifier used for ads. |

### Your rights

Depending on where you live, you may have the right to access, correct, delete or
export personal data about you, to object to or restrict its processing, and to withdraw
consent. Because Telepromter holds no account and stores your content only on your
device, most of this is exercised directly: uninstalling the app removes the data it
keeps. For data held by our advertising and analytics partners, use the links above, or
write to us and we will help.

### Changes to this policy

If this policy changes materially we will update this page and the effective date at the
top of it. The version published here is always the current one.

### Contact

together.on.the.road.team@gmail.com
