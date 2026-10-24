# Privacy Policy for Auto Cricket Scorer

**Effective Date:** October 24, 2026  
**Last Updated:** October 24, 2026  
**Developer:** Najeebullah (Najeeb Agha)  
**Package Name:** `com.aghaapps.autocricketscorer`  
**Contact:** [noormoh3@gmail.com](mailto:noormoh3@gmail.com) | Phone: +923003900182 | Website: [https://najeebagha.github.io](https://najeebagha.github.io)

---

### Introduction & Absolute Commitment to Your Privacy

Welcome to **Auto Cricket Scorer** (hereinafter referred to as "the App", "we", "us", or "our"). We understand how important personal privacy is to our users. Auto Cricket Scorer operates as a **100% Completely Offline Application with Zero Data Harvesting**. There is no online cloud database, no background remote synchronization, and no hidden server connections whatsoever.

> **Key Reassurance:**  
> **Auto Cricket Scorer is strictly offline. We do NOT collect, harvest, upload, track, sell, or share any of your personal data, match scores, player details, team information, or files with ourselves or any third party. All your cricket scoring data stays 100% locally on your device in our ultra-fast offline database (`agha_db`). You can use Auto Cricket Scorer with complete trust and confidence.**

---

### 1. Strictly 100% Offline (Powered by `agha_db`)

- **Strictly Offline Architecture:** The App has no concept of online data synchronization or remote cloud storage. There is no hidden online layer, no cloud database, and no secondary sync option.
- **Ultra-Fast Local Offline Database (`agha_db`):** Every team, player name, scorecard, ball-by-ball record, wagon wheel, tournament, and partnership chart is processed and stored exclusively within your device's private storage using our dedicated, high-speed local offline database engine (`agha_db`).
- **No Remote User Database:** We do not operate remote servers or databases to store your matches, player statistics, or team profiles.
- **No Mandatory Account or Registration:** You can use all core scoring and match management features without creating an account, providing an email address, or logging in.

---

### 2. Purpose of the Internet Permission (`android.permission.INTERNET`)

Auto Cricket Scorer requests the `android.permission.INTERNET`, `android.permission.ACCESS_NETWORK_STATE`, and `android.permission.ACCESS_WIFI_STATE` permissions strictly and transparently for the following three specific functions:

1. **Google AdMob (Free Version Only):**  
   The free version of the App displays non-intrusive advertisements served through Google AdMob to support ongoing development. Google AdMob may use device advertising identifiers (such as Google Advertising ID / GAID) in accordance with Google's own Privacy Policy. We do not have access to or store these advertising IDs.
   *(Note: Users who purchase a Pro subscription enjoy a completely 100% Ad-Free experience, disabling all advertising SDK requests).*

2. **In-App Purchases & Google Play Billing:**  
   The Internet permission is required to communicate securely with the official **Google Play Billing API** to verify and manage your Pro subscriptions (Weekly Trial, Monthly, Yearly, or Lifetime Plans).

3. **Local Wi-Fi Live Score Overlay (OBS / Prism Live Studio):**  
   The App includes an embedded local HTTP server feature that broadcasts live match scores to streaming software like OBS Studio or Prism Live Studio over your local Wi-Fi or mobile hotspot.  
   **Crucial Note:** This data transmission happens **strictly within your Local Area Network (LAN)**. No match scores or broadcast streams are ever sent to external cloud servers or the public internet.

> **Important Guarantee:** The scoring engine itself is 100% offline. At no point does the App transmit your match records, team details, or personal files over the internet to us or any third party.

---

### 3. In-App Purchases and Financial Data Security

- **Secure Google Play Billing:** All in-app purchases, recurring subscriptions, and free trial activations are handled exclusively through Google Play's native in-app billing infrastructure.
- **Zero Access to Financial Information:** We do **NOT** collect, request, process, or have access to your credit card numbers, debit card details, bank accounts, or billing addresses. All payment processing is strictly governed by Google Play’s Privacy Policy and Security Standards.

---

### 4. Device Permissions & Privacy Compliance (Google Play Compliant)

We adhere strictly to Google Play's Photo, Video, and Storage Permissions Policies:

- **No Broad Storage Permissions:** The App **does NOT** request or utilize broad storage permissions (`READ_MEDIA_IMAGES`, `READ_EXTERNAL_STORAGE`, or `WRITE_EXTERNAL_STORAGE`). All broad media read/write permissions have been permanently removed to protect your device storage.
- **Android System Photo Picker:** When choosing player photos, team logos, or broadcast watermarks, the App utilizes Android's native, privacy-preserving **System Photo Picker** (`MediaStore.ACTION_PICK_IMAGES`). The App can only access the individual photo you explicitly choose and nothing else.
- **Camera Permission (`android.permission.CAMERA`):** The camera permission is entirely optional and only requested when you choose to take a photo of a player or team logo directly within the App. Captured photos remain solely in the App's local storage and are never uploaded.
- **Backup & Restore via System File Picker (`.zkb` files):** Full database backups and restoration use Android's Storage Access Framework (SAF) / system file picker. We do not scan or read your device files; the App only touches the specific `.zkb` backup file you explicitly select to save or restore.

---

### 5. Foreground Service (`FOREGROUND_SERVICE_DATA_SYNC`)

To provide an uninterrupted live broadcast overlay for OBS and Prism Live Studio:

- The App uses the `FOREGROUND_SERVICE_DATA_SYNC` permission solely to prevent the local hotspot HTTP server from disconnecting when the App is minimized or running in the background during an ongoing live cricket match.
- A clear, non-intrusive system notification is shown while the broadcast service is running, which you can stop at any time by stopping the broadcast or closing the match.

---

### 6. User-Initiated Data Sharing (PDFs, Images & Backups)

- The App allows you to generate single-page PDF match scorecards, high-definition match summary graphic cards (1080x1920 for WhatsApp/Status), and complete `.zkb` database backups.
- **100% User-Initiated:** Sharing via WhatsApp, Bluetooth, Telegram, Email, or other platforms is **entirely manual and initiated only by you**.
- The App **never** automatically uploads, posts, or shares your match data with anyone.

---

### 7. Children's Privacy

Auto Cricket Scorer does not knowingly collect, request, or solicit any personal information from children under the age of 13. Because our App collects zero personal data from any user, it is fully safe for use by sports clubs, schools, academies, and cricket fans of all ages.

---

### 8. User Data Retention and Deletion

Because all your data is stored locally on your device:

- **Instant Deletion:** You can delete individual matches, tournaments, teams, or players at any time from within the App.
- **Complete Erasure:** Clearing the App’s storage data in your device settings or uninstalling the App will permanently delete all locally stored records and databases from your device.

---

### 9. Changes to This Privacy Policy

We may update this Privacy Policy periodically to reflect any updates in application features or Google Play policy compliance. Any revisions will be updated in the App and made available in our repository and documentation. We encourage you to review this policy periodically.

---

### 10. Contact Us & Developer Information

If you have questions, suggestions, or need assistance regarding this Privacy Policy or the App, please contact us directly:

- **Developer:** Najeebullah (Najeeb Agha)
- **Email:** [noormoh3@gmail.com](mailto:noormoh3@gmail.com)
- **Phone:** +923003900182
- **Website:** [https://najeebagha.github.io](https://najeebagha.github.io)
- **Google Play Store:** [Auto Cricket Scorer on Google Play](https://play.google.com/store/apps/details?id=com.aghaapps.autocricketscorer)

---

*You can use Auto Cricket Scorer with total peace of mind. Your cricket records belong to you and stay 100% offline on your device.*
