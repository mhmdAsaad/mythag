# Privacy Policy

**Last Updated:** [DATE]

This Privacy Policy explains how **[COMPANY NAME]** ("we", "us", or "our") collects, uses, stores, processes, and protects your information when you use our mobile application, **[APP NAME]** (also known as **ميثاق** / **Mithaq**, hereinafter referred to as the "App"), and the choices you have associated with that data.

We are committed to protecting and respecting your privacy. The App is designed primarily for educators and teachers to build, organize, and manage educational portfolios, lesson reports, and evaluations.

Please read this Privacy Policy carefully to understand our practices regarding your personal data and how we treat it. By downloading, installing, or using the App, you agree to the collection and use of information in accordance with this policy.

---

## 1. Information Collection and Use

We collect several different types of information for various purposes to provide and improve our services to you.

### A. Personally Identifiable Information (PII)
While using our App, we may ask you to provide us with certain personally identifiable information that can be used to contact or identify you. Personally Identifiable Information includes:

1. **Authentication Credentials & Profile Info:** 
   When you sign in using Google Sign-In, we receive information from Google including your unique User Identifier (UID), email address, display name, and profile picture URL.
2. **Teacher Profile Details:** 
   To generate personalized reports and portfolios, you may provide profile information which is stored locally and synced to our secure cloud database. This information includes:
   * Full Name
   * Academic Specialization
   * Grade Level
   * School Name (Educational Institution)
3. **User-Generated Content:** 
   We process and store files and data you create or upload, including:
   * Performance Reports
   * Strategy Reports (including text, lesson topics, goals, tools used, and implementation steps)
   * Academic Years configuration
   * Educational Portfolios
   * Semester Roadmap / Plans (خطة الفصل الدراسي)
   * Selected photos, screenshots, or documents attached as "implementation evidence" (شواهد التنفيذ)

### B. Google Drive Integration & File Access

> [!IMPORTANT]
> **Why we use your personal Google Drive instead of our own storage:** 
> In strict compliance with Ministry of Education (MOE) privacy regulations, third-party applications are not permitted to host or store sensitive school media, including photos of students or the interior of school facilities, on external commercial servers. To ensure full compliance with MOE policies, our App requires all evidence photos (شواهد التنفيذ) and documents to be saved exclusively to your personal Google Drive. This guarantees that you retain 100% ownership, control, and privacy over all sensitive educational media.

The App integrates with Google Drive using the restricted scope `https://www.googleapis.com/auth/drive.file`. 
* **Storage Ownership:** Files you upload, backup, or generate (such as reports, evidence photos, or generated QR codes) are stored directly on **your own personal Google Drive** space. We do not host these files on our company-owned central file servers.
* **Metadata Collection:** We process metadata related to these files, such as file names, file paths, file types, upload dates, Google Drive file IDs, and shareable Google Drive links, to enable in-app file syncing and organization.
* **Sharing Controls:** You control the privacy permissions of your synced folders directly within the App's settings (options include: Private to you, Public via link, or Restricted access to specific email addresses).

### C. Referral & Rewards Data
If you participate in our referral program:
* We collect and process your generated referral code, referred-by records, number of successful conversions, and referral premium history.
* This referral data is verified and processed securely using secure cloud functions.

### D. Purchase and Subscription Info
If you upgrade to our Premium tier (Mithaq PRO):
* In-app subscriptions and purchases are managed and verified through our secure subscription management provider.
* We collect transaction details, subscription status, plan ID, transaction dates, renewal configurations, and a unique subscription identifier.
* We do not collect or store your payment card numbers. All payments are processed securely by Apple's App Store or Google Play Store billing systems.

### E. Device & Usage Data
We collect information about how the App is accessed and used. This data may include:
* **App Analytics Data:** App launch counts, screen views, feature interactions (e.g., login, logout, report generation, subscription purchases, portfolio views), and overall engagement metrics.
* **Advertising Interaction Data:** Ad impressions, clicks, device identifiers (such as Android Advertising ID or iOS IDFA), and general location data (IP address) used to display and personalize advertisements.

---

## 2. Device Permissions Required

To provide standard functionality, the App requests permissions to access certain native features on your device. These are requested at runtime when needed:

* **Internet Access (`android.permission.INTERNET`):** 
  Required for all cloud interactions, authentication, syncing data, fetching subscription status, loading ads, and communication with third-party service providers.
* **Device Storage / Media Permissions (`android.permission.READ_EXTERNAL_STORAGE` / `android.permission.READ_MEDIA_IMAGES` / iOS Photo Library & Files Access):** 
  Required to let you select and upload image files or PDF documents from your device's gallery or file system to attach as implementation evidence (شواهد التنفيذ) to your reports.

---

## 3. Third-Party Service Providers

We employ third-party companies and SDKs to facilitate our App, perform service-related operations, or assist us in analyzing how our App is used. These third parties have access to your personal data only to perform these tasks on our behalf and are obligated not to disclose or use it for any other purpose.

The App utilizes the following third-party integrations:

* **Cloud Infrastructure and Backend Services:** 
  Used for authentication, real-time database storage, backend logic execution, and tracking usage statistics.
* **Advertising Networks:** 
  Used for displaying advertisements in the App. Advertising networks may collect and process device identifiers, cookies, and network location (IP address) to personalize ads.
* **Subscription Management Services:** 
  Used to manage subscription flows, verify purchases, and sync subscription states across platforms.
* **Edge Computing Services:** 
  Used for hosting secure functions that run referral logic and code validation.

---

## 4. Data Storage, Retention, and Location

* **Local Storage:** 
  The App caches settings, teacher profile details, reports, and portfolio metadata locally on your device using local secure storage mechanisms, Shared Preferences, and Key-chain/Secure Storage.
* **Cloud Storage:** 
  Account profile data, portfolio metadata, reports, academic year records, and semester roadmap plans are securely stored on our cloud databases in a database partitioned by your unique User ID (UID).
* **Google Drive Storage:** 
  Your uploaded assets (evidence files, images, etc.) remain in your personal Google Drive account and are governed by your Google account's security configuration.
* **Retention Period:** 
  We retain your data for as long as you maintain an active account with us. If you delete your account or request account deletion, we delete your remote databases and authentication profile within [NUMBER, e.g., 30] days, except where retention is legally required.

---

## 5. Security of Data

The security of your data is important to us. We employ standard technical and administrative safeguards to protect your personal information:
* All communication between the App and third-party services is encrypted using Transport Layer Security (TLS/HTTPS).
* Device-level access tokens and keys are encrypted and stored in secure native hardware storage (Secure Enclave on iOS, Keystore on Android).
* Strict database access controls ensure that your data is private and only accessible by you when logged into your account.
* You maintain absolute control over the sharing permissions of the folders created by the App in your Google Drive.

---

## 6. User Rights and Data Deletion

We believe in giving you full control over your personal data. Depending on your jurisdiction (such as GDPR in the European Union or CCPA in California), you may have specific rights regarding your personal data. Regardless of location, we provide all users with the following capabilities:

### A. Local Data Deletion
You can erase all locally cached data, settings, and profile details stored on your current device directly inside the App:
* Navigate to **Settings (الإعدادات)** -> **Data Management (إدارة البيانات)**.
* Tap **Delete all my data from the device (حذف جميع بياناتي من الجهاز)**.
* Confirm the prompt to instantly delete local Hive caches and profile information.

### B. Remote Account & Database Deletion
You can permanently delete your entire cloud account, including your authentication record, cloud database logs, reports, portfolio records, and semester plans directly from the App:
* Navigate to **Settings (الإعدادات)** -> **Data Management (إدارة البيانات)**.
* Tap **Delete Account Permanently (حذف الحساب نهائياً)**.
* Confirm the prompt to permanently delete your account and all associated cloud data.

Alternatively, you may submit a deletion request by emailing us at **[SUPPORT EMAIL]** from the email address associated with your App account. Upon verification, we will permanently purge your data from our database servers within [NUMBER, e.g., 30] days.

### C. Revoking Google Drive Permissions
Because file backups reside directly on your own Google Drive, you can revoke the App's permissions to access your Google Drive storage at any time:
1. Go to your **Google Account Settings** (https://myaccount.google.com).
2. Navigate to **Security** -> **Third-party apps with account access**.
3. Locate **[APP NAME]** and click **Remove Access**.
*(Note: Removing access will stop the cloud backup and sync features from functioning in the App, but all your previously synced files will remain intact in your Google Drive folder until you manually delete them).*

---

## 7. Children's Privacy

Our App is strictly intended for use by professional educators, teachers, and school administrators. It does not address anyone under the age of 13. We do not knowingly collect personally identifiable information from children under 13. If you are a parent or guardian and you are aware that your child has provided us with personal data, please contact us so that we can take necessary actions to remove that information.

---

## 8. Changes to This Privacy Policy

We may update our Privacy Policy from time to time. We will notify you of any changes by posting the new Privacy Policy on this page and updating the "Last Updated" date at the top of this document.

You are advised to review this Privacy Policy periodically for any changes. Changes to this Privacy Policy are effective when they are posted on this page.

---

## 9. Contact Us

If you have any questions or suggestions about this Privacy Policy or wish to request data deletion, please contact us:
* By email: **[SUPPORT EMAIL]**
* By visiting this link on our website: **[WEBSITE URL]**

---

# Apple App Store Privacy 'Nutrition Label' Mapping

To assist with your App Store submission in App Store Connect, here is a mapping of the data collected by this App to Apple's **App Privacy** categories.

In App Store Connect under the **App Privacy** section, select that the App collects the following data types and configure their usage as mapped below:

| Apple Data Category | Specific Data Collected | Data Usage / Purpose | Linked to User? | Used for Tracking? |
| :--- | :--- | :--- | :---: | :---: |
| **Contact Info** | Name (from Teacher Profile) and Email Address (from Google/Apple Sign-In) | • Product Personalization<br>• App Functionality | **Yes** | **No** |
| **Purchases** | Subscription transaction history, purchase history (via RevenueCat) | • App Functionality<br>• Product Personalization | **Yes** | **No** |
| **Identifiers** | User UID, Subscription ID, Device ID / Advertising Identifier (IDFA) | • App Functionality<br>• Analytics<br>• Third-Party Advertising | **Yes** (UID/Purchases)<br>**No** (Ad ID for ads) | **Yes** (Advertising ID) |
| **Usage Data** | Product interaction logs (e.g., clicks, screen views, report creations via App Analytics), Ad views and clicks | • Analytics<br>• Third-Party Advertising | **Yes** (Analytics logs)<br>**No** (Ad logs) | **Yes** (Ad interaction) |
| **Diagnostics** | Crash logs, performance metrics (App Store default diagnostics) | • Diagnostics | **Yes** | **No** |
| **User Content** | Photos or videos selected by user (Implementation evidence), Files / Documents generated by user | • App Functionality | **Yes** | **No** |

### Key Questions You Will Face in App Store Connect:
1. **Does the App track users?**
   * **Yes.** Because the App integrates Advertising Networks which use device advertising identifiers (IDFA) to serve and measure targeted ads, you must declare "Yes" to tracking.
2. **Is the data linked to the user?**
   * **Yes.** User accounts (Google Sign-In, User UID) link user-generated reports, purchase history, and profile data directly to the user's identity. Advertising logs are generally anonymized or linked to temporary advertising IDs, but core data is linked.
