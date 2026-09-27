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
3. **Allow notifications** (recommended, Android 13+): tap **Allow**, so YT Skipper can show its status notification.

When the top of the app turns **green: Working**, you're done. You can close the app; it keeps working in the
background and after a restart.

## The status notification

While YT Skipper runs, it shows a silent notification:

| Notification | Meaning |
|---|---|
| ▶\| **On · skipping YouTube ads** | Working; shows how many ads were skipped |
| ❚❚ **Paused · ads are not skipped** | Paused; tap **Resume** |
| ! **Setup not finished** | A step is missing; tap to open the app |
| No notification | YT Skipper is off |

Use **Pause / Resume** right in the notification. Tap the notification to open the app.
If you swipe it away, it comes back the next time you open YouTube. You can turn it off in the app.

## Troubleshooting

- **It stopped working / the notification disappeared:** open YT Skipper and follow the checklist again.
  Don't use **Force stop** on YT Skipper: that switches it off.
- **A red round accessibility button appeared:** that's Android's accessibility shortcut, and tapping it turns
  YT Skipper off. Remove it: **Settings → Accessibility → YT Skipper → YT Skipper shortcut → off**.
- **Advanced Protection (Android 17):** with Advanced Protection turned on, Android blocks accessibility apps like
  this one.
- **An ad wasn't skipped:** YouTube sometimes changes its app. Let me know which YouTube version you have.

## Updating

Download the new APK from the [Releases page](https://github.com/GNarek/yt-skipper/releases) and install it over
the old one. Your settings stay.

**Updating from 1.0.0:** the round floating button is replaced by the status notification. Open the app once and
tap **Allow** under "Allow notifications".

---

Not affiliated with YouTube or Google. Personal project, shared as-is.
