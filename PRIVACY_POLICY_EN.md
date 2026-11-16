# StreamCat Privacy Policy

**Effective Date**: November 16, 2026  
**Developer**: LEE SEOKHUI (`Seoki0903-forest`)  
**Contact**: https://github.com/Seoki0903-forest/StreamCat/issues

StreamCat ("the App") is designed with a local-first architecture. We value your privacy and do not operate remote tracking servers.

---

## 1. Information We Do Not Collect
StreamCat **does not require user accounts, does not display ads, and does not include third-party analytics or tracking SDKs**. We do not collect, sell, or upload personally identifiable information (such as your name, email address, phone number, contacts, or location) to developer-operated servers.

## 2. Permissions & Local Device Processing
All control data stays strictly between **your mobile device and your own Windows PC** over USB or your local Wi-Fi network:

1. **Local Network & Wi-Fi Discovery (`INTERNET`, `ACCESS_NETWORK_STATE`, `ACCESS_WIFI_STATE`)**
   - Used exclusively to connect to your Windows PC running StreamCat over USB (`127.0.0.1`), USB tethering, or your local Wi-Fi subnet (`port 8080` / local LAN discovery beacon).
2. **Camera (`CAMERA` — Optional, Wi-Fi QR Pairing Only)**
   - Used solely when you tap the QR scanner button to read the connection QR code displayed by your own PC's StreamCat desktop application.
   - Camera frames are decoded strictly on-device in real time and are **never recorded, saved, or transmitted** to any external server.
3. **Photos & Backup Files (System File Picker / Storage Access Framework)**
   - Accessed only when you explicitly choose an image/GIF for a custom key icon, split background theme, or when you import/export a configuration backup (`.json`).
   - Configurations are stored locally in your mobile WebView storage (`localStorage`) and your PC's local configuration directory.
4. **PC Program List, Active Window Title & Audio Sessions (Local PC Only)**
   - Used locally on your Windows PC to show app icons, switch pages automatically when active apps change, and control the Windows Volume Mixer. None of this data leaves your local network.
5. **Stock Ticker Widget (Optional User Action)**
   - Only when you place a Stock Widget on your deck does the PC server fetch public market quote data for the requested ticker symbol.

## 3. Third-Party Sharing
StreamCat does not sell or share user data with third parties.

## 4. Data Retention & Deletion
All layouts, icons, and preferences are stored only on your own devices. You can delete them at any time by clearing app storage or uninstalling the App and removing the local PC configuration folder (`%LOCALAPPDATA%\StreamCat`).

## 5. Children's Privacy
StreamCat does not knowingly collect personal information from anyone, including children under 13.

## 6. Changes to This Policy
Updates to this Privacy Policy will be published directly in this repository (`PRIVACY_POLICY_EN.md`) with an updated effective date.
