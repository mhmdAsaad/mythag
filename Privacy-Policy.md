# Privacy Policy

**Last Updated:** July 5, 2026

This Privacy Policy explains how **jibalapps** ("we", "us", or "our") collects, uses, stores, processes, and protects your information when you use our mobile application, **Mythaq** (also known as **ميثاق** / **Mithaq**, hereinafter referred to as the "App"), and the choices you have associated with that data.

We are committed to protecting and respecting your privacy. The App is designed primarily for educators and teachers to build, organize, and manage educational portfolios, lesson reports, and evaluations.

Please read this Privacy Policy carefully to understand our practices regarding your personal data and how we treat it. By downloading, installing, or using the App, you agree to the collection and use of information in accordance with this policy.

---

## 1. Information Collection and Use

We collect several different types of information for various purposes to provide and improve our services to you.

### A. Personally Identifiable Information (PII)
While using our App, we may ask you to provide us with certain personally identifiable information that can be used to contact or identify you. Personally Identifiable Information includes:

1. **Authentication Credentials & Profile Info:** When you sign in using Google Sign-In or Apple Sign-In, we receive information from the respective provider including your unique User Identifier (UID), email address, display name, and profile picture URL (where applicable).
2. **Teacher Profile Details:** To generate personalized reports and portfolios, you may provide profile information which is stored locally and synced to our secure cloud database. This information includes:
   * Full Name
   * Academic Specialization
   * Grade Level
   * School Name (Educational Institution)
3. **User-Generated Content:** We process and store files and data you create or upload, including:
   * Performance Reports
   * Strategy Reports (including text, lesson topics, goals, tools used, and implementation steps)
   * Academic Years configuration
   * Educational Portfolios
   * Semester Roadmap / Plans (خطة الفصل الدراسي)
   * Selected photos, screenshots, or documents attached as "implementation evidence" (شواهد التنفيذ)

### B. Google Drive Integration & File Access

> [!IMPORTANT]
> **Why we use your personal Google Drive instead of our own storage:** > In strict compliance with Ministry of Education (MOE) privacy regulations, third-party applications are not permitted to host or store sensitive school media, including photos of students or the interior of school facilities, on external commercial servers. To ensure full compliance with MOE policies, our App requires all evidence photos (شواهد التنفيذ) and documents to be saved exclusively to your personal Google Drive. This guarantees that you retain 100% ownership, control, and privacy over all sensitive educational media.

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

* **Internet Access (`android.permission.INTERNET`):** Required for all cloud interactions, authentication, syncing data, fetching subscription status, loading ads, and communication with third-party service providers.
* **Device Storage / Media Permissions (`android.permission.READ_EXTERNAL_STORAGE` / `android.permission.READ_MEDIA_IMAGES` / iOS Photo Library & Files Access):** Required to let you select and upload image files or PDF documents from your device's gallery or file system to attach as implementation evidence (شواهد التنفيذ) to your reports.

---

## 3. Third-Party Service Providers

We employ third-party companies and SDKs to facilitate our App, perform service-related operations, or assist us in analyzing how our App is used. These third parties have access to your personal data only to perform these tasks on our behalf and are bound by strict contractual obligations not to disclose or use it for any other purpose.

The App integrates and shares limited data with the following third-party service providers:

* **Cloud Infrastructure & Authentication (Google Firebase):** We use Firebase Services (including Firebase Authentication and Cloud Firestore) to handle user account sign-ins, host our secure backend functions, and maintain real-time syncing of profile metadata and text reports.
* **Subscription Management (RevenueCat):** We use RevenueCat to process, track, and validate in-app purchases and subscription states securely across iOS and Android platforms.
* **Advertising Networks (Google AdMob):** We use Google AdMob to display advertisements within the free tier of the App. AdMob may process temporary device identifiers (like IDFA or GAID), cookies, and network location data to deliver relevant ads.
* **Edge Computing & Serverless Functions:** We use secure cloud hosting providers to execute serverless environment configurations, validate user referral codes, and process premium milestone checks.

---

## 4. Data Storage, Retention, and Location

* **Local Storage:** The App caches settings, teacher profile details, reports, and portfolio metadata locally on your device using local secure storage mechanisms, Shared Preferences, and Key-chain/Secure Storage.
* **Cloud Storage:** Account profile data, portfolio metadata, reports, academic year records, and semester roadmap plans are securely stored on our cloud databases in a database partitioned by your unique User ID (UID).
* **Google Drive Storage:** Your uploaded assets (
