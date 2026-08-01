# Privacy Policy

**Luxury Sudoku** | Last updated: August 1, 2026 | Developer: Nikolay Nedyalkov

This Privacy Policy describes how **Luxury Sudoku** ("the App", "we", "our") handles information when you use the application on your mobile device. By using the App you agree to the practices described here.

---

## 1. Information We Collect

The App itself does **not** collect, transmit, or store any personal information on external servers. All game data is stored locally on your device only:

- A display name you choose during onboarding (stored only on your device).
- Your game progress, puzzle state, scores, and Daily Challenge streak (stored only on your device).
- App preferences and settings, including your notification preference (stored only on your device).

None of this data is sent to us or any third party by the App directly. You can delete all locally stored data at any time by uninstalling the App.

---

## 2. Advertising (Google AdMob and Mediation Partners)

The App displays advertisements served through **Google AdMob** (Google LLC), which uses mediation to request ads from multiple ad networks so it can show you the most relevant ad available. In addition to Google's own ad service, our AdMob mediation setup currently includes:

- **Unity Ads** (Unity Technologies)
- **AppLovin** (AppLovin Corporation)

Depending on which network's ad is served on a given occasion, that network may collect and use certain information from your device to serve and measure ads, including:

- **Device or other IDs** — device identifiers such as the Advertising ID / IDFA.
- **Approximate location** — derived from your IP address.
- **App activity** — ad interaction data (impressions, clicks).
- **App info & performance** — diagnostics and crash data reported by each network's SDK.
- Device type, operating system, and language settings.

This data collection is governed by each network's own privacy policy:

- [Google's Privacy Policy](https://policies.google.com/privacy)
- [Unity's Privacy Policy](https://unity.com/legal/privacy-policy)
- [AppLovin's Privacy Policy](https://www.applovin.com/privacy/)

You can opt out of personalised advertising at any time through your device settings:

- **Android:** Settings → Google → Ads → "Delete advertising ID" or "Opt out of Ads Personalization".
- **iOS:** Settings → Privacy & Security → Apple Advertising → turn off "Personalised Ads".

---

## 3. Notifications

With your permission, the App sends **local notifications** to remind you about the Daily Challenge. These reminders are scheduled and delivered entirely on your device — no notification content or schedule is sent to us or to any server.

- The App requests notification permission on first launch. You may grant or deny it, and you can change it at any time in your device's system settings.
- To deliver reminders at the correct local time, the App reads your device's current time zone. This is used only on your device and is not transmitted.
- If you deny or disable notifications, the App continues to work normally — you simply won't receive reminders.

---

## 4. Third-Party Services

The App uses the following third-party services, each with its own privacy terms:

- **Google AdMob** — advertising and mediation. [Privacy Policy](https://policies.google.com/privacy)
- **Unity Ads** — advertising, served via AdMob mediation. [Privacy Policy](https://unity.com/legal/privacy-policy)
- **AppLovin** — advertising, served via AdMob mediation. [Privacy Policy](https://www.applovin.com/privacy/)
- **Google Fonts** — fonts may be fetched from Google servers on first launch. No personal data is linked to these requests beyond a standard IP address. [Privacy FAQ](https://developers.google.com/fonts/faq/privacy)
- **Google Play In-App Review / Apple App Store** — after completing a game, the App may show the native in-app rating prompt provided by Google (Android) or Apple (iOS). Your interaction with this prompt is handled entirely by Google or Apple under their respective privacy policies; the App does not receive or store your rating.

---

## 5. Google Play Data Safety Declaration

This section maps the practices above to Google Play's **Data safety** categories, for consistency between this policy and the Play Console form.

> **Key principle (Google's definition):** data is only "**collected**" if it leaves the device, and "**shared**" if it's transferred to a third party. Everything Luxury Sudoku stores itself (display name, scores, progress, streak, settings) **stays on the device and is never transmitted**, so it is declared as **NOT collected**. The only data leaving the device comes from the **Google AdMob mediation stack** — the Google AdMob SDK itself plus the **Unity Ads** and **AppLovin** SDKs it mediates to.

| Question | Answer |
|---|---|
| Does your app collect or share any of the required user data types? | **Yes** — via the Google AdMob SDK. |
| Is all of the user data collected by your app encrypted in transit? | **Yes** (Google ad services use HTTPS/TLS). |
| Do you provide a way for users to request that their data is deleted? | **No in-app request needed** — app data is local and removed on uninstall; ad data is controlled via the device Advertising ID reset / opt-out. |

**Data types collected and shared** (via AdMob mediation: Google, Unity Ads, AppLovin). For each: Collected = Yes, Shared = Yes, processing is not ephemeral, and it is required (not optional — users can't turn ads off in-app, though they can opt out of personalization at the OS level):

| Category | Data type | Purposes |
|---|---|---|
| **Location** | Approximate location | Advertising or marketing |
| **Device or other IDs** | Device or other identifiers (Advertising ID / IDFA) | Advertising or marketing; Analytics; Fraud prevention, security & compliance |
| **App activity** | App interactions (ad impressions/clicks) | Advertising or marketing; Analytics |
| **App info & performance** | Diagnostics / crash logs (Google, Unity Ads, and AppLovin SDKs each report their own crash/diagnostic data) | Analytics; Fraud prevention, security & compliance |

**Per-network sources**, since Play Console's SDK scanner detects each of these directly in the app binary and cross-checks them against this declaration:

- **Google AdMob / Google Mobile Ads SDK** — ad serving, mediation orchestration.
- **Unity Ads** (`com.unity3d.ads:unity-ads`) — mediation partner; also bundles its own bid-optimization/analytics component ("Coherence").
- **AppLovin** (`com.applovin:applovin-sdk`) — mediation partner; also bundles its own native crash reporter.

**Data types declared as NOT collected** — stored only on-device and never transmitted:

- **Name** — the display name chosen at onboarding (local only).
- **App activity / other** — game progress, puzzle state, scores, Daily Challenge streak (local only).
- **App preferences** — settings incl. notification preference (local only).
- **Notifications & time zone** — daily reminders are scheduled on-device; the device time zone is read locally and not transmitted.
- **In-app review** — the Google Play / Apple rating prompt is handled by the store; the app receives and stores nothing.

**Notes & verification:**

- Ads SDKs are mandatory disclosure even though the app's own code collects nothing — each SDK collects on the app's behalf, which counts as the app's collection. This applies to Google, Unity Ads, and AppLovin individually, not just AdMob as a whole.
- AdMob is the source of truth for the Google side, but Unity Ads and AppLovin publish their own data-collection disclosures too — cross-check Google's "AdMob and Data safety" guidance **and** Unity's / AppLovin's Play Console SDK Index entries before submitting, as all three can update independently.
- Google Fonts fetches font files on first launch (standard request exposing IP only); it isn't user data collection but is disclosed above for transparency.
- No account, no login, no separate analytics/crash-reporting SDK beyond what the AdMob mediation stack (Google, Unity Ads, AppLovin) includes — Unity Ads' Coherence component and AppLovin's native crash reporter are part of that stack, not an extra SDK added separately.
- EU consent / US state regulations: confirm Unity Ads and AppLovin are added as ad partners in the AdMob console's Privacy & messaging (consent) configuration, so the in-app consent message actually requests consent on their behalf — this is a separate CMP setup from the Play Console Data safety form.
- Keep this section in sync with the app's actual ad mediation dependencies whenever SDKs change.

---

## 6. Children's Privacy

The App is not directed to children under the age of 13. We do not knowingly collect personal information from children. If you believe a child has provided personal data through the App, please contact us and we will take steps to remove that information.

---

## 7. Data Retention and Deletion

Because all data is stored locally on your device, you have full control over it. Uninstalling the App permanently deletes all locally stored data. We do not retain any user data on our servers because we do not collect any.

---

## 8. Security

We do not transmit your personal data, so there is no data in transit to protect on our end. Data stored locally on your device is protected by your device's own security mechanisms (screen lock, encryption, etc.).

---

## 9. Changes to This Policy

We may update this Privacy Policy from time to time. When we do, we will revise the "Last updated" date at the top of this page. Continued use of the App after changes are posted constitutes acceptance of the updated policy.

---

## 10. Contact

If you have any questions or concerns about this Privacy Policy, please contact us at:

**Email:** [n.nedialkov@stenik.bg](mailto:n.nedialkov@stenik.bg)
