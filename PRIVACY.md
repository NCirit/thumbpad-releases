# Thumbpad Privacy Policy

_Last updated: 5 October 2026_

Thumbpad lets you control your own Windows PC from your Android phone over your local network. Your remote-control activity stays on your own devices. The app also shows ads through Google AdMob, which is the only feature that involves data leaving your device, and offers optional purchases through Google Play to remove those ads. This policy explains all of these.

## Summary

- Your remote-control activity (mouse, keyboard, media, volume) stays on your local network and is sent only to your paired PC, encrypted. We never receive it.
- We have no servers and no accounts, and we do not run our own analytics.
- The app shows ads through Google AdMob. To serve those ads, Google may collect your device's advertising identifier and related information. This is the only data that leaves your device to a third party.
- You can optionally pay to remove ads. Payment is handled entirely by Google Play; we never see your payment details.

## Your remote-control data (stays local)

Thumbpad has no servers of its own. All control happens between your phone and your PC.

- **Pairing credentials**: a cryptographic key pair and your PC's identity are generated and stored **only on your phone**, in the Android Keystore / encrypted storage. They are used solely to authenticate to your own PC and never leave the device otherwise.
- **Input and media commands**: mouse movement, keystrokes, media controls, and volume changes are sent **directly to your paired PC** over an encrypted (TLS) connection on your local network. They are not recorded and are not sent anywhere else. We, the developer, never receive them.

## Advertising

Thumbpad displays ads provided by **Google AdMob**: one full-screen ad when you open the app (shown at an idle moment, never over a gesture in progress), and native ads styled to match the app on the Keyboard and Media screens. Ads are never placed over the trackpad.

- To provide and measure ads, Google may collect and process information such as your device's **advertising ID**, IP address, approximate (coarse) location derived from the IP address, device information, and ad interactions. For this, Google acts as an independent controller of that data.
- **Consent**: where required (for example in the EEA, the UK, and Switzerland), the app shows a consent form before serving personalized ads, using Google's User Messaging Platform. You can choose non-personalized ads.
- **Your controls**: you can reset your advertising ID or opt out of ad personalization at any time in **Android Settings → Google → Ads**.
- **Ad-free**: if you buy ad removal (see below), the app does not initialize AdMob, show the consent form, or request any ads.
- Google's handling of this data is described in Google's Advertising and Privacy policies:
  - https://policies.google.com/technologies/ads
  - https://support.google.com/admob/answer/6128543

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
- **Internet**: used to reach your PC on the local network and to load ads.
- **Google Play billing**: used to offer and verify the optional ad-free purchases.

## Data sharing

We do not sell or share your data. The only third party involved is **Google**: through AdMob for the advertising described above, and through Google Play for optional purchases.

## Data the app involves (for reference)

- **Device or other identifiers** (advertising ID): collected by Google AdMob for advertising.
- **Purchase history** (which ad-free products you own): read from Google Play to decide whether to show ads. It stays on your phone and is not sent to us.
- No other personal data is collected by the app. Your input, keystrokes, and media activity are never collected or transmitted to us or to Google.

## Data retention and deletion

- Pairing information is stored locally on your phone. Removing a paired PC in the app, or uninstalling the app, deletes it.
- The cached ad-free status is stored locally and deleted when you uninstall the app. Your purchase itself stays with your Google account, so reinstalling restores it.
- Advertising data processed by Google is subject to Google's own retention policies. You can reset your advertising ID in Android settings to disassociate future ad data.

## Children

Thumbpad is not directed at children and does not knowingly collect personal data from anyone.

## Changes to this policy

If this policy changes, the updated version will be posted here with a new date.

## Contact

Questions? Contact: n.cirit.n@gmail.com
