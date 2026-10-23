# Privacy Policy for Puja Scheduler (Archaka)

**Last Updated:** October 23, 2026

This Privacy Policy describes how **Puja Scheduler** ("Archaka", "we", "our", or "us") handles information when you use our mobile application and related services (the "App").

We are committed to protecting your privacy. **Puja Scheduler is designed with an offline-first, privacy-by-design architecture.** All your personal records, client data, booking schedules, astrological charts, and financial records remain stored locally on your device and are never uploaded to any remote server or third-party database.

---

## 1. Summary of Key Principles

* **100% Offline-First Data Storage:** We do not operate remote user account databases. Your client lists, gotras, nakshatras, booking records, fees, notes, and preferences stay strictly within your device's local sandboxed storage.
* **No Account Registration:** You do not need to register with an email, phone number, or social media account to use this App.
* **No Third-Party Advertising:** The App does not contain third-party ad networks, trackers, or commercial profiling SDKs.
* **Transparent Permission Usage:** Device permissions (such as Location and Notifications) are requested solely to perform core religious, astrological, and scheduling functions.

---

## 2. Information We Collect and How We Use It

### A. Location Information (`ACCESS_FINE_LOCATION` and `ACCESS_COARSE_LOCATION`)
* **How it is used:** 
  * Hindu calendar (Panchangam) calculations—such as Tithi, Nakshatram, Yoga, Karana, Rahu Kalam, Yamagandam, Gulika Kalam, Abhijit Muhurtham, and exact Sunrise/Sunset/Moonrise timings—are mathematically dependent on precise geographical coordinates (latitude, longitude, and elevation).
  * In addition, the traditional Hindu *Sankalpam* recitation requires determining the user's geographic context (e.g., country, state, and river basin coordinates: *Jambhu Dweepe, Bharata Varshe...*).
* **Processing & Retention:** 
  * Location information is queried only when you actively trigger Panchangam computation or location auto-detection.
  * Location coordinates are processed **ephemerally on your device**.
  * We **do not** track your location in the background, we do not monitor your movements over time, and we never transmit your location coordinates to any proprietary or marketing servers.

### B. User-Entered Client & Booking Data
* **Data Types:** Client names, phone numbers, family member details, Gotram, Nakshatram, Rashi, home addresses, puja booking dates, ceremony types, samagri (items) checklists, and fee/expense records.
* **Storage & Privacy:**
  * All of this information is saved exclusively in your device's local storage (`localStorage` / application sandbox).
  * You have the option to set an in-app security PIN to lock access to this information within the App.
  * You can manually export a complete JSON backup of your data for your personal archival or device transfer. You retain 100% ownership and control over your exported backup files.

### C. Generated Documents & PDF Exports
* **Data Types:** Generated Janma Patrika (Horoscope / Kundali), Lagna Patrika (Wedding Invitation Card), and Puja Booking Summaries.
* **Usage:** 
  * When you choose to export or share a document, the App renders a PDF or image file locally and writes it to your device's standard local application documents folder.
  * The file is passed to your operating system's native Share Sheet (e.g., WhatsApp, Email, or Print) **only upon your explicit user action**. The App does not automatically transmit or publish your generated documents anywhere.

### D. Device Notifications (`POST_NOTIFICATIONS`)
* **Usage:** 
  * The App uses local notifications to remind you of upcoming scheduled pujas and to prompt you to pack the required *Samagri* on the evening before a scheduled ceremony.
* **Processing:** 
  * All notification triggers are scheduled locally by the device's operating system alarm manager. No remote push notification server (e.g., Firebase Cloud Messaging) is used to track or message your device.

---

## 3. Third-Party Services and Network Communications

While the App operates locally, minimal external network requests may be made strictly to provide specific user-requested utilities:

1. **Reverse Geocoding (OpenStreetMap Nominatim):** When you tap to auto-detect your location for the Sankalpam generator, the App sends a secure HTTPS query containing your current latitude and longitude to OpenStreetMap's Nominatim service solely to identify your state and country for traditional regional Sankalpam phrasing. No personal identifiers or account data are passed.
2. **Optional App Version Check:** The App may check a public version manifest hosted on GitHub to notify you when an updated version of the App is available. No user data is transmitted during this check.

---

## 4. Data Retention and Deletion

Because all your data is stored locally on your device:
* **Manual Deletion:** You can delete individual pujas, clients, expenses, or bookings at any time directly through the App interface.
* **Complete Erasure:** You can permanently delete all data stored by the App at any time by:
  1. Opening your Android device **Settings** > **Apps** > **Puja Scheduler**.
  2. Selecting **Storage & Cache** > **Clear Storage / Clear Data**.
  3. Or simply uninstalling the application from your device.

Because we do not store your information on external servers, uninstalling the App or clearing its storage permanently removes all your local records. We cannot recover locally deleted data unless you created an exported backup file.

---

## 5. Security of Your Data

We take reasonable steps to help safeguard your information:
* The App provides an optional **In-App PIN Lock** feature to prevent unauthorized physical access to your records on your device.
* All external network queries (such as geocoding or version checks) are conducted exclusively over encrypted **HTTPS (SSL/TLS)** protocols.
* Your data remains confined to Android’s secure application sandbox, inaccessible to other standard applications on your device unless you explicitly export or share it.

---

## 6. Children's Privacy

Puja Scheduler is a professional and cultural utility intended for priests (*archakas*, *purohits*), astrologers, and adult organizers managing religious services. The App is not directed toward children under the age of 13 (or under the applicable age of consent in your jurisdiction), and we do not knowingly solicit or collect personal information from children.

---

## 7. Disclaimer Regarding Astrological Calculations

All astronomical, Panchangam, Muhurtham, and Janma Patrika (astrology) calculations and interpretations provided in this App are derived from classical traditional algorithms (such as Surya Siddhanta / Drik Ganitha principles) and are intended strictly for **cultural, traditional, educational, and spiritual guidance purposes**.

---

## 8. Changes to This Privacy Policy

We may update our Privacy Policy from time to time to reflect changes in our legal obligations, platform policies, or app functionality. Any updates will be posted to this page with an updated "Last Updated" date. We encourage you to review this policy periodically.

---

## 9. Contact Us

If you have any questions, concerns, or feedback regarding this Privacy Policy or the data practices of Puja Scheduler, please contact us:

* **Public Issue Tracker / Support:** [https://github.com/knarsimharao/puja-scheduler-privacy/issues](https://github.com/knarsimharao/puja-scheduler-privacy/issues)
* **GitHub Profile:** [https://github.com/knarsimharao](https://github.com/knarsimharao)
