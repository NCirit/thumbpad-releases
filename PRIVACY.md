# Thumbpad Privacy Policy

_Last updated: 7 October 2026_

Thumbpad lets you control your own Windows PC from your Android phone over your local network. Your remote-control activity stays on your own devices. The app also shows ads through Google AdMob, measures anonymous app usage with Google Analytics for Firebase (you can turn this off), and offers optional purchases through Google Play to remove ads. This policy explains all of these.

## Summary

- Your remote-control activity (mouse, keyboard, media, volume) stays on your local network and is sent only to your paired PC, encrypted. We never receive it.
- We have no servers and no accounts.
- The app shows ads through Google AdMob. To serve those ads, Google may collect your device's advertising identifier and related information.
- The app measures how it is used (for example, whether pairing succeeded and why a connection failed) with Google Analytics for Firebase. It never records what you type, what you control, or anything about your PC. You can turn it off in Settings.
- You can optionally pay to remove ads. Payment is handled entirely by Google Play; we never see your payment details.

## Your remote-control data (stays local)

Thumbpad has no servers of its own. All control happens between your phone and your PC.

- **Pairing credentials**: a cryptographic key pair and your PC's identity are generated and stored **only on your phone**, in the Android Keystore / encrypted storage. They are used solely to authenticate to your own PC and never leave the device otherwise.
- **Input and media commands**: mouse movement, keystrokes, media controls, and volume changes are sent **directly to your paired PC** over an encrypted (TLS) connection on your local network. They are not recorded and are not sent anywhere else. We, the developer, never receive them.
- **Screen view (optional, off by default)**: when you turn it on, your PC streams its screen (or the area around the cursor) **directly to your phone** on your local network, end-to-end encrypted with a key created for each session. The picture is shown live and is never recorded, stored, or sent to us, to Google, or to any server. Usage statistics never include anything from your screen.

## Advertising

Thumbpad displays ads provided by **Google AdMob**: one full-screen ad when you open the app (shown at an idle moment, never over a gesture in progress); native ads styled to match the app on the Keyboard and Media screens, and in the screen view preview while you are idle; and an optional video ad that you can choose to watch to unlock full screen view for 15 minutes. Ads are never placed over the trackpad.

- To provide and measure ads, Google may collect and process information such as your device's **advertising ID**, IP address, approximate (coarse) location derived from the IP address, device information, and ad interactions. For this, Google acts as an independent controller of that data.
- **Consent**: where required (for example in the EEA, the UK, and Switzerland), the app shows a consent form before serving personalized ads, using Google's User Messaging Platform. You can choose non-personalized ads.
- **Your controls**: you can reset your advertising ID or opt out of ad personalization at any time in **Android Settings → Google → Ads**.
- **Ad-free**: if you buy ad removal (see below), the app does not initialize AdMob, show the consent form, or request any ads.
- Google's handling of this data is described in Google's Advertising and Privacy policies:
  - https://policies.google.com/technologies/ads
  - https://support.google.com/admob/answer/6128543

## Usage statistics (Google Analytics for Firebase)

To understand whether people manage to set up and use Thumbpad, the app sends a small set of anonymous usage events to **Google Analytics for Firebase**:

- **Setup and connection milestones**: the app was opened for the first time, setup or pairing was started, a PC was found, pairing completed, and the first time (and later, once per day) a command reached your PC.
- **Connection problems**: when connecting fails, a short reason from a fixed list (for example "timeout", "PC not found", or "pairing rejected") and the step where it happened.
- **Kind of use**: only whether a command was a mouse, keyboard, or media command.

What is **never** sent: the text you type, the keys or shortcuts you press, mouse movements, media titles, your PC's name or network address, or anything on your PC's screen.

Firebase also collects standard information to count and group these events: an **app instance ID** (a random identifier for this installation), device model, Android version, app version, language, and approximate country derived from the IP address. Google processes this data on our behalf as a service provider.

- **Consent**: where consent is required (for example in the EEA, the UK, and Switzerland), analytics storage stays off until you agree through the consent form; without consent only cookieless, identifier-free signals are sent.
- **Your controls**: turn off **Settings → Privacy → Share usage statistics** at any time. Collection stops immediately.
- **Retention**: analytics data is kept for up to 14 months and then deleted automatically by Google.
- Google's handling of this data: https://policies.google.com/privacy and https://firebase.google.com/support/privacy

## In-app purchases (remove ads)

Thumbpad offers optional purchases that remove all ads, sold through **Google Play**: a one-time purchase and/or a yearly subscription, depending on what is currently offered in the app.

- **Payment** is processed entirely by Google Play under your Google account. We do not receive your name, card, or other payment details.
- **Purchase status**: the app asks Google Play which ad-free purchases your Google account owns, and stores only the result (whether ads are removed, and which kind of purchase) on your phone. Nothing about your purchase is sent to us.
- **Subscriptions** renew automatically every year until you cancel. You can cancel at any time in the Google Play app under **Payments & subscriptions**; ads return when the paid period ends.
- Google's handling of payment data is described in the Google Privacy Policy: https://policies.google.com/privacy

## Permissions

- **Camera**: used only to scan the pairing QR code shown by the PC agent. Frames are processed on-device and are not stored or transmitted.
- **Local network / Wi-Fi state**: to discover and connect to your PC on the same network.
- **Notifications & foreground service**: to run the optional “sync phone volume to PC” feature and show its ongoing status.
- **Internet**: used to reach your PC on the local network, to load ads, and to send usage statistics.
- **Google Play billing**: used to offer and verify the optional ad-free purchases.

## Data sharing

We do not sell or share your data. The only third party involved is **Google**: through AdMob for the advertising described above, through Google Analytics for Firebase for usage statistics, and through Google Play for optional purchases.

## Data the app involves (for reference)

- **Device or other identifiers** (advertising ID): collected by Google AdMob for advertising. App instance ID: collected by Google Analytics for Firebase for usage statistics.
- **App activity and diagnostics** (setup and connection milestones, connection failure reasons): collected by Google Analytics for Firebase, can be turned off in Settings.
- **Purchase history** (which ad-free products you own): read from Google Play to decide whether to show ads. It stays on your phone and is not sent to us.
- No other personal data is collected by the app. Your input, keystrokes, and media activity are never collected or transmitted to us or to Google.

## Data retention and deletion

- Pairing information is stored locally on your phone. Removing a paired PC in the app, or uninstalling the app, deletes it.
- The cached ad-free status is stored locally and deleted when you uninstall the app. Your purchase itself stays with your Google account, so reinstalling restores it.
- Usage statistics are kept by Google Analytics for up to 14 months.
- Advertising data processed by Google is subject to Google's own retention policies. You can reset your advertising ID in Android settings to disassociate future ad data.

## Children

Thumbpad is not directed at children and does not knowingly collect personal data from anyone.

## Changes to this policy

If this policy changes, the updated version will be posted here with a new date.

## Contact

Questions? Contact: n.cirit.n@gmail.com
