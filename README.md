<img src="icon.png" width="96" align="right" alt="YT Skipper icon">

# YT Skipper

An Android app that taps YouTube's **Skip** button for you as soon as an ad can be skipped.

Made so you don't have to look for a tiny button on your phone, for example while driving.
Still, the safest option is to start your playlist before you set off and not touch the phone on the road.

**[⬇ Download the latest version](https://github.com/GNarek/yt-skipper/releases/latest)**. On that page tap **YT-Skipper-x.y.z.apk**.

## What it does and doesn't do

- Works only inside the official **YouTube** app. It ignores every other app.
- Taps **Skip** only on ads that have a Skip button. Ads that can't be skipped still play.
- Never taps anything else, such as "Visit advertiser".
- Doesn't use the internet, collect data, or show its own ads.
- Works on **Android 8.0 and newer**.

## Install

1. On your phone, download **YT-Skipper-x.y.z.apk** from the [Releases page](https://github.com/GNarek/yt-skipper/releases/latest) and open it.
2. If Android asks, allow your browser or Files app to **install unknown apps**.
3. If **Google Play Protect** warns about an unknown app, tap **More details → Install anyway**.
   (The app isn't on the Play Store, so Play Protect doesn't know it.)

## Set up (about 1 minute)

Open **YT Skipper**. It shows a checklist; each step has a button that opens the right screen:

1. **Turn on YT Skipper in Accessibility**: tap **Open settings → YT Skipper**, turn it on and confirm.
   - **Switch greyed out** or "Restricted setting" (Android 13+)? Go to **Settings → Apps → YT Skipper → ⋮ (top right) →
     Allow restricted settings**, then try again.
2. **Allow unrestricted battery use**: tap **Allow** in the dialog, so Android never stops YT Skipper.

When the top of the app turns **green: Working**, you're done. You can close the app; it keeps working in the
background and after a restart.

## The floating button

While YT Skipper runs, a small round button sits on the edge of the screen:

| Button | Meaning |
|---|---|
| 🟢 Green | Working, ads are skipped |
| 🟠 Orange | Running, but a setup step is missing (open the app) |
| ⚪ Grey | Paused |
| No button | YT Skipper is off |

**Tap** it to pause or resume, **hold** it to open the app, **drag** it to move it. It can be hidden in the app.

## Troubleshooting

- **It stopped working / the button disappeared:** open YT Skipper and follow the checklist again.
  Don't use **Force stop** on YT Skipper: that switches it off.
- **A red round accessibility button appeared:** that's Android's accessibility shortcut, and tapping it turns
  YT Skipper off. Remove it: **Settings → Accessibility → YT Skipper → YT Skipper shortcut → off**.
- **Advanced Protection (Android 17):** with Advanced Protection turned on, Android blocks accessibility apps like
  this one.
- **An ad wasn't skipped:** YouTube sometimes changes its app. Let me know which YouTube version you have.

## Updating

Download the new APK from the [Releases page](https://github.com/GNarek/yt-skipper/releases) and install it over
the old one. Your settings stay.

---

Not affiliated with YouTube or Google. Personal project, shared as-is.
