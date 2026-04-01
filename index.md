# Privacy Policy

**FlipFlow**
**Last Updated:** April 1, 2026
**Effective Date:** April 1, 2026

---

## 1. Introduction

FlipFlow ("we," "us," or "our") is operated by Mehmet Nuri Ozdemir, based in Germany. This Privacy Policy explains how we collect, use, and protect your information when you use the FlipFlow mobile application (the "App").

By using FlipFlow, you agree to the practices described in this Privacy Policy. If you do not agree, please do not use the App.

**Contact:** ozdemirtradesolutions@gmail.com

---

## 2. Information We Collect

### 2.1 Information You Provide

- **Age range** -- Provided during onboarding to personalize your experience.
- **App selection preferences** -- The social media apps you choose to monitor (e.g., Instagram, TikTok, YouTube, Snapchat, Reddit, X/Twitter).
- **Onboarding survey responses** -- Screen time habits, frequency of use, emotional awareness preferences, and personal goals.
- **Feedback** -- If you submit feedback through the in-app feedback form, we receive the text you provide. No personal identifiers are attached unless you voluntarily include them.

### 2.2 Information Processed on Your Device

The following data is processed and stored **exclusively on your device** and is never transmitted to our servers:

- **Screen Time data** -- We use Apple's Screen Time API (FamilyControls, DeviceActivity, ManagedSettings) to monitor usage of your selected apps. This data is processed entirely on your device by Apple's frameworks.
- **Camera data** -- During the hydration reset flow, your device camera captures a short video to verify that you are drinking water. Video frames are analyzed on-device using Apple's Vision framework. No video or images are saved, uploaded, or transmitted to any server. No facial recognition is performed. No biometric data is collected or stored.
- **Usage statistics** -- Daily reset counts, hydration timestamps, streak data, weekly reset history, and monitoring state are stored locally on your device using UserDefaults within the App Group (`group.com.mehmetnuriozdemir.FlipFlow`).
- **Insights data** -- The App generates personalized insight cards based on your local usage data (reset counts, streaks, time patterns). All insight generation occurs on-device.
- **Secure counters** -- Daily limit counters are stored locally with HMAC-based tamper protection. The HMAC signing key is stored in the iOS Keychain and never leaves your device.
- **Encrypted local data** -- Certain sensitive fields stored in UserDefaults are encrypted using ChaChaPoly (256-bit) with a symmetric key stored in the iOS Keychain. Encryption and decryption occur entirely on-device.

### 2.3 Product Analytics

To understand onboarding completion, subscription conversion, permission failures, monitoring reliability, and reset-flow performance, we use **Mixpanel**, a third-party product analytics provider.

The analytics data we may send to Mixpanel includes:

- **Pseudonymous app and device metadata** -- Such as an anonymous app instance identifier, app version, build number, iOS version, device model family, and general locale or country derived from device settings.
- **Subscription and paywall analytics** -- Such as paywall views, selected plan, offering or package identifiers, purchase attempts, restore attempts, trial status, and entitlement status.
- **Onboarding and feature funnel events** -- Such as onboarding step views and completions, permission request outcomes, app-selection counts, monitoring start outcomes, block trigger reasons, reset flow starts, reset outcomes, and whether skip or discrete reset modes were used.
- **Coarse product metrics** -- Such as whether onboarding or monitoring has been completed, the count of selected apps or categories, and hydration amount buckets.

We configure our implementation to avoid sending camera recordings, video frames, raw Screen Time activity, exact selected app tokens or names, free-form feedback text, exact reset timestamps, or precise location to Mixpanel.

### 2.4 Subscription Information

Subscription purchases are managed through RevenueCat, a third-party subscription management platform, which communicates with Apple's App Store. RevenueCat receives an anonymous app user identifier to manage your subscription status. RevenueCat does not receive your name, email, or other personal identifiers from the App. RevenueCat's handling of data is governed by [RevenueCat's Privacy Policy](https://www.revenuecat.com/privacy/).

Apple processes all payment transactions. We do not collect, process, or store your payment information, credit card details, or billing address. Apple manages all billing under [Apple's Privacy Policy](https://www.apple.com/legal/privacy/).

### 2.5 Local Notifications

The App sends local notifications to your device to inform you about hydration resets, reward milestones, focus achievements, and behavioral improvement reminders. These notifications are generated and delivered entirely on your device. No notification data is sent to any server.

### 2.6 Information We Do Not Collect

- We do **not** collect biometric data or perform facial recognition.
- We do **not** store, upload, or transmit your camera recordings.
- We do **not** collect your name, email address, phone number, or precise location through the App (unless you voluntarily provide contact information via feedback).
- We do **not** send raw Screen Time contents, exact app selections, FamilyControls tokens, or camera data to Mixpanel.
- We do **not** track you across other apps or websites.
- We do **not** sell any data to third parties.
- We do **not** use third-party advertising SDKs.

---

## 3. How We Use Your Information

We use the information described above solely to:

- Provide, operate, and maintain the App's core functionality.
- Monitor your selected apps and trigger hydration resets when usage thresholds are reached.
- Verify hydration resets through on-device camera analysis.
- Track your daily resets, hydration log, streaks, and personal progress.
- Generate personalized insights and analytics based on your local usage data.
- Send local reward notifications for focus achievements and habit improvements.
- Personalize your experience based on onboarding preferences.
- Manage your subscription status through RevenueCat and Apple StoreKit.
- Analyze onboarding, subscription, permission, monitoring, and reset funnels using limited pseudonymous product analytics through Mixpanel.
- Improve app performance and fix bugs.

We do not use your data for advertising, cross-app tracking, or any purpose unrelated to the App's functionality.

---

## 4. Data Storage and Processing

- **On-device processing** -- All Screen Time monitoring, camera analysis, insight generation, and usage tracking is performed entirely on your device. FlipFlow does not operate backend servers for processing user data.
- **Local storage** -- Your preferences, monitoring state, hydration logs, and usage data are stored locally using UserDefaults within the App Group.
- **Keychain storage** -- Encryption keys and HMAC signing keys are stored securely in the iOS Keychain, protected by the operating system's hardware-backed security.
- **Encrypted storage** -- Sensitive local data is encrypted using ChaChaPoly with 256-bit keys before being written to UserDefaults.
- **Camera recordings** -- Processed in real time and discarded immediately after analysis. No recordings are persisted.
- **Third-party analytics processing** -- Limited pseudonymous product analytics events are transmitted to Mixpanel and processed on Mixpanel's infrastructure rather than only on-device.
- **No cloud sync** -- Your data is not synced to any cloud service operated by us.

---

## 5. Data Sharing and Disclosure

We do **not** sell, trade, or rent your personal information to third parties.

We may share information only in the following limited circumstances:

- **Mixpanel** -- We share limited pseudonymous product analytics events and device or app metadata with Mixpanel so we can understand onboarding conversion, paywall performance, permission denial recovery, subscription issues, monitoring reliability, and reset flow outcomes. We do not configure Mixpanel to receive camera recordings, raw Screen Time contents, or exact app selections.
- **RevenueCat** -- An anonymous app user identifier is shared with RevenueCat to manage your subscription status. No personally identifiable information is shared. RevenueCat processes this data under [RevenueCat's Privacy Policy](https://www.revenuecat.com/privacy/).
- **Apple** -- Subscription billing and payment processing is handled by Apple through the App Store. Apple processes your payment data under its own privacy policy.
- **Legal requirements** -- If required by applicable law, regulation, court order, or governmental request.
- **Safety** -- To protect the rights, property, or safety of FlipFlow, our users, or the public as required by law.

---

## 6. Third-Party Services

The App uses the following services:

- **Mixpanel** -- For pseudonymous product analytics, funnel measurement, and app improvement. Mixpanel receives the limited event and property data described in Section 2.3 and processes it under [Mixpanel's Privacy Policy](https://mixpanel.com/legal/privacy-policy/).
- **RevenueCat** -- For subscription management, entitlement verification, and offering configuration. RevenueCat receives an anonymous identifier and subscription transaction data. Subject to [RevenueCat's Privacy Policy](https://www.revenuecat.com/privacy/).
- **Apple StoreKit 2** -- For processing in-app purchases and subscriptions. Subject to [Apple's Privacy Policy](https://www.apple.com/legal/privacy/).
- **Apple Screen Time API (FamilyControls, DeviceActivity, ManagedSettings)** -- For monitoring and managing app usage. All data remains on-device per Apple's framework design.
- **Apple Vision Framework** -- For on-device analysis of hydration verification video. No data leaves your device.
- **Apple CryptoKit** -- For on-device encryption (ChaChaPoly) and HMAC-based integrity verification. All cryptographic operations occur locally.

We do not use third-party advertising services. We may add or remove service providers over time, and we will update this Privacy Policy when those changes materially affect data processing.

---

## 7. Permissions

| Permission | Purpose | Data Handling |
|---|---|---|
| **Camera** | Record a short video during hydration verification | Processed locally in real time using Apple Vision; never saved, uploaded, or transmitted |
| **Screen Time / FamilyControls** | Detect app usage and temporarily block selected apps | Processed and stored on-device only; data never leaves your device |
| **Notifications** | Inform you about hydration resets, focus rewards, and habit improvement milestones | Delivered locally; no data sent to servers |

You can revoke any permission at any time in your device's Settings app. Revoking Camera or Screen Time permissions will limit the App's core functionality.

---

## 8. Children's Privacy

FlipFlow is intended for users aged 18 and older. We do not knowingly collect personal information from anyone under 18 years of age. In compliance with the Children's Online Privacy Protection Act (COPPA) and equivalent regulations, we do not direct our services to children under 13.

If you believe someone under 18 is using the App, please contact us at ozdemirtradesolutions@gmail.com, and we will take appropriate action to delete any associated data.

---

## 9. Your Rights

### 9.1 Rights for All Users

- **Access** -- You can view most core usage data directly within the App (dashboard, insights, settings, statistics). For analytics data processed through Mixpanel or subscription data processed through RevenueCat, you may also contact us.
- **Deletion** -- You can delete local App data by uninstalling FlipFlow. Keychain items may persist after uninstallation; reinstalling and then uninstalling will clear them. If you want us to delete analytics data processed through Mixpanel that we control, contact us and we will handle the request subject to our ability to identify the relevant records.
- **Revoke permissions** -- You can revoke Camera, Screen Time, or Notification permissions at any time through your device's Settings.

### 9.2 European Economic Area -- GDPR

If you are in the European Economic Area (EEA) or the United Kingdom, you have the following rights under the General Data Protection Regulation:

- **Right of access** (Article 15) -- Request confirmation of whether we process your personal data.
- **Right to rectification** (Article 16) -- Request correction of inaccurate data.
- **Right to erasure** (Article 17) -- Request deletion of your personal data.
- **Right to restriction of processing** (Article 18).
- **Right to data portability** (Article 20).
- **Right to object** (Article 21).
- **Right to withdraw consent** at any time without affecting the lawfulness of prior processing.

**Legal basis for processing:** Your consent (Article 6(1)(a) GDPR), which you provide by granting Camera and Screen Time permissions where applicable, our legitimate interests (Article 6(1)(f)) in measuring onboarding, subscription, reliability, and feature performance through limited pseudonymous analytics, and the performance of a contract (Article 6(1)(b)) when you use the App's services.

**Data controller:** Mehmet Nuri Ozdemir, Germany. Contact: ozdemirtradesolutions@gmail.com

Most core behavioral data is stored locally on your device. Limited pseudonymous analytics and subscription-related records may also be processed by Mixpanel and RevenueCat, and you may contact us to exercise applicable rights relating to that data.

You have the right to lodge a complaint with a data protection supervisory authority in your member state.

### 9.3 Turkey -- KVKK

If you are in Turkey, you have rights under the Personal Data Protection Law (KVKK, Law No. 6698), including the right to:

- Learn whether your personal data is being processed.
- Request information about the purpose of processing and whether data is used in accordance with its purpose.
- Know the third parties to whom personal data has been transferred.
- Request rectification of incomplete or inaccurate data.
- Request deletion or destruction of personal data.
- Object to any result that is to your detriment arising from analysis of processed data exclusively by automated means.

Contact us at ozdemirtradesolutions@gmail.com to exercise these rights.

### 9.4 California -- CCPA

If you are a California resident, you have the following rights under the California Consumer Privacy Act:

- **Right to know** what personal information is collected, used, and shared.
- **Right to delete** your personal information.
- **Right to opt out** of the sale of your personal information.
- **Right to non-discrimination** for exercising your privacy rights.

**We do not sell your personal information or share it for cross-context behavioral advertising.** Core FlipFlow behavior data remains on-device, while limited pseudonymous analytics and subscription-related records may be processed by Mixpanel and RevenueCat. You can delete local App data by uninstalling the App and contact us regarding third-party records we control.

---

## 10. International Data Transfers

Core FlipFlow behavioral data remains stored and processed locally on your device. However, pseudonymous product analytics sent to Mixpanel and anonymous subscription identifiers handled by RevenueCat may be processed outside your country of residence. Mixpanel stores customer data in the United States by default unless a different regional data residency option is configured for the project, and RevenueCat may also process subscription identifiers in the United States. Subscription payment data is handled by Apple under Apple's own data transfer policies and applicable legal frameworks.

---

## 11. Data Retention

- **Camera recordings** -- Not retained. Processed in real time and discarded immediately after analysis.
- **App preferences and statistics** -- Stored locally on your device for as long as the App is installed. Uninstalling the App removes all UserDefaults data.
- **Mixpanel analytics events** -- Retained by Mixpanel according to our workspace retention settings and operational needs, unless deleted sooner through configuration or applicable requests.
- **Keychain data** -- Encryption keys and HMAC keys stored in the iOS Keychain may persist after app deletion. Reinstalling and uninstalling the App will clear these items.
- **Subscription records** -- Managed and retained by RevenueCat and Apple per their respective data retention policies.

---

## 12. Security

We implement privacy-by-design principles, including:

- **On-device-only processing** for all camera analysis, Screen Time monitoring, and insight generation.
- **Keychain-stored encryption keys** using iOS hardware-backed security for sensitive data protection.
- **ChaChaPoly encryption** (256-bit) for sensitive fields stored in UserDefaults.
- **HMAC-based integrity verification** (SHA-256) for tamper-resistant counters.
- **Data minimization for analytics** so Mixpanel receives limited pseudonymous product telemetry rather than camera data, raw Screen Time contents, or exact app selections.
- **Local-only storage** with no cloud backend or remote database.

Your device's built-in security features (encryption, passcode, biometric lock) provide additional protection for your locally stored data. However, no method of electronic storage is 100% secure, and we cannot guarantee absolute security.

---

## 13. Changes to This Privacy Policy

We may update this Privacy Policy from time to time. We will notify you of material changes by updating the "Last Updated" date at the top of this document and, where appropriate, through an in-app notification. The current version of this Privacy Policy is accessible at any time within the App through Settings. Your continued use of the App after changes constitutes acceptance of the updated Privacy Policy. We encourage you to review this policy periodically.

---

## 14. Contact Us

If you have any questions about this Privacy Policy or wish to exercise your data rights, please contact us:

**Developer:** Mehmet Nuri Ozdemir
**Location:** Germany
**Email:** ozdemirtradesolutions@gmail.com
