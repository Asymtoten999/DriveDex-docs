# Privacy Policy for DriveDex

**Effective Date:** 1.Sep 2026
**Last Updated:** 1.Sep 2026

This Privacy Policy explains how Aasim Nawaz Sheik ("**DriveDex**," "**we**," "**us**," or "**our**") collects, uses, and shares information when you use the DriveDex mobile application (the "**App**").

---

## 1. Information We Collect

### 1.1 Account Information
When you create an account, we collect your **email address**, a **password** (stored securely by our authentication provider and never visible to us in plain text), and the **username** you choose. Your username is shown publicly to other users on leaderboards and friends lists.

### 1.2 Photos and Camera Data
DriveDex's core feature requires access to your device's camera. When you scan a car:

- We capture a **photo you take of a vehicle**, which is sent to a third-party AI service (see Section 2) to identify the make, model, and estimated value, and to read the license plate.
- If the scan is successful, the **photo and the extracted vehicle details (make, model, year, estimated value, and license plate number) are stored** in your account so the car appears in your in-app "Garage."
- **Important:** Because the App is used to photograph real vehicles in public places, photos you take may incidentally include **visible license plates, other people, other vehicles, or property that is not yours**. Please be mindful of your surroundings and applicable local laws when scanning. Do not use the App to photograph people without their awareness in situations where they have a reasonable expectation of privacy.
- License plate numbers are used to detect duplicate scans on your own account and are not intentionally shared with other users, though your scanned car's make, model, and value may appear on leaderboards under your username.

### 1.3 Gameplay and Usage Data
We collect data related to your use of the App's features, including: points balance, daily scan counts, streak history, badges/achievements earned, collection ("Dex") progress, raffle entries, and friend connections you create.

### 1.4 Advertising Data
The App displays ads and rewarded video ads through **Google AdMob**. AdMob and its partners may collect device identifiers (such as your advertising ID), IP address, and other technical data to serve and measure ads, and — subject to your consent — to personalize them. See Section 2.3 and Section 6 for more on your choices.

### 1.5 Automatically Collected Information
Like most apps, we and our service providers may automatically collect certain technical information, such as device type, operating system, app version, and crash/error logs, to keep the App running reliably.

---

## 2. How We Use Your Information and Who We Share It With

We use the categories of data above to operate, maintain, and improve the App. We share data with the following categories of third parties, each acting as an independent processor or controller of the data they receive:

### 2.1 Supabase (Backend, Database & Storage)
We use Supabase to host our database and to store your account data, gameplay data, and uploaded car photos. Supabase processes this data on our behalf to operate the App.

### 2.2 AI Image Analysis Provider (OpenAI)
When you scan a car, the photo is sent to OpenAI's Vision API to identify the vehicle and read the license plate. This transmission happens through our backend (a Supabase Edge Function) — the image is not sent directly from your device to OpenAI. OpenAI processes this image to return the identification result; please refer to OpenAI's own privacy practices for how they handle API data.

### 2.3 Google AdMob (Advertising)
We use Google AdMob to serve banner ads and rewarded video ads (used to grant bonus scans and raffle entries). Where required (for example, under the EU/UK GDPR), we present a consent form (via Google's User Messaging Platform) before showing personalized ads or collecting related data, and honor the choices you make there. You can review Google's own privacy policy at https://policies.google.com/privacy and their partners at https://www.google.com/about/company/publisher-partners/.

### 2.4 Other Users
Your **username**, **badges**, **streak**, and **garage value / collection completion percentage** may be visible to other users through the Leaderboard feature, and to users you add as friends. You can change your username at any time, but historical leaderboard snapshots may not update retroactively.

### 2.5 Legal and Safety
We may disclose information if required by law, or if we believe in good faith that disclosure is necessary to protect our rights, your safety, or the safety of others.

We do **not sell** your personal information to third parties for their own independent marketing purposes.

---

## 3. Data Retention

We retain your account data, garage photos, and gameplay data for as long as your account is active. If you delete a car from your Garage, we also delete the associated stored image from our storage provider. If you delete your account (see Section 7), we will delete or anonymize your personal data within 30 days, except where retention is required for legal, tax, fraud-prevention, or raffle-recordkeeping purposes (for example, keeping a record of raffle entries for the current draw).

---

## 4. Children's Privacy

DriveDex is not directed to children under the age of 16, and we do not knowingly collect personal information from children under that age. Furthermore, participation in paid or rewarded raffles within the App is restricted to users aged 18 and older. If you believe a child under 16 has provided us with personal information, please contact us at aasim.sheik.988@gmail.com so we can delete it.

---

## 5. Your Rights and Choices

Depending on where you live, you may have rights to access, correct, delete, or export your personal data, or to object to or restrict certain processing (for example, under the EU/UK GDPR or the Swiss FADP). California residents may have similar rights under the CCPA/CPRA, including the right to opt out of the "sale" or "sharing" of personal information (which, under California law, can include certain advertising data shared with ad partners like AdMob).

To exercise any of these rights, contact us at aasim.sheik.988@gmail.com. We will respond within the timeframe required by applicable law.

You can also manage certain choices directly:
- **Ad personalization / tracking:** manage your device's Advertising ID settings, and (on iOS) your App Tracking Transparency permission for this App, in your device settings.
- **Consent (GDPR/UK users):** you can update your ad-consent choices via the in-app consent form the next time it appears, or by contacting us to reset it.
- **Account deletion:** see Section 7.

---

## 6. Advertising Identifiers and Tracking

On iOS, the App will request your permission via Apple's App Tracking Transparency (ATT) framework before accessing your device's advertising identifier for tracking purposes, in addition to the separate AdMob/UMP consent flow shown to users in applicable regions. You can change your choice at any time in your device's Settings.

---

## 7. Account Deletion and Data Retention

You have the right to request the complete deletion of your DriveDex account and all associated personal data at any time.

* **In-App Account Deletion:** You can delete your account directly inside the app by navigating to the **Shop / Rewards** tab, scrolling to the bottom footer, and selecting **Delete Account**. Confirming this action triggers an immediate and permanent removal process.
* **Scope of Deletion:** Executing an account deletion permanently wipes:
  * Your authentication credentials and account profile (`profiles`).
  * All logged vehicle scans and uploaded vehicle photos from storage (`scans`, `user_cars`).
  * Your earned Spotter Points, streaks, unlocked badges, and active raffle entries (`raffle_entries`).
* **Manual Request Option:** If you are unable to access the app, you may submit a formal deletion request by emailing **aasim.sheik.988@gmail.com** from the email address registered to your DriveDex account. Manual requests are processed within 30 days in accordance with the Swiss Federal Act on Data Protection (revDSG).
* **Data Persistence:** Once deleted, your account and associated garage records cannot be restored. Any anonymous or aggregated operational metrics (such as non-identifying system logs) may be retained for system stability and abuse prevention.
---

## 8. Data Security

We use commercially reasonable technical and organizational measures — including row-level security policies on our database and encrypted connections — to protect your information. However, no method of transmission or storage is 100% secure, and we cannot guarantee absolute security.

---

## 9. International Data Transfers

Our service providers (including Supabase, OpenAI, and Google) may process and store data in countries other than your own, including the United States. Where required, we rely on appropriate safeguards (such as Standard Contractual Clauses) for such transfers.

---

## 10. Changes to This Policy

We may update this Privacy Policy from time to time. We will indicate the "Last Updated" date above and, for material changes, provide additional notice (such as an in-app notification) where required by law.

---

## 11. Contact Us

If you have questions about this Privacy Policy or how we handle your data, contact us at:

Aasim Nawaz Sheik

Eggbergstrasse 5, 8193 Zurich, Switzerland

aasim.sheik.988@gmail.com
