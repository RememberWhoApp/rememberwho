# Privacy Policy

**Last updated:** September 28, 2026

Remember Who ("we", "our", or "us") is committed to protecting your privacy. This policy explains how we collect, use, and safeguard your information.

## Information We Collect

### Information You Provide

- **Contact Information:** Names, phone numbers, emails, and other details you enter about your contacts
- **Notes & Interactions:** Notes, meeting records, and conversation summaries you create
- **Photos:** Profile photos you add to contacts
- **Voice Recordings:** Audio recordings you make for voice notes (processed on-device or via OpenAI Whisper API if cloud transcription is enabled)
- **Business Card Scans:** Images of business cards you scan (processed on-device using Google ML Kit OCR)
- **Account Information:** Email address when you create a cloud account (optional)
- **Phone Contacts:** If you import from your phone's contacts or use Contact Sync, the app reads the contacts you choose from your address book. This happens on your device; contacts are never uploaded unless you back them up

### Information Collected Automatically

- **Location Data:** When you enable location-based reminders or pin a contact on the map (optional). If you type an address and tap **Find on map**, that address is sent to your phone's built-in geocoding service (Apple on iOS, Google on Android) to place the pin; choosing **Use Current Location** or moving a map pin sends those coordinates to the same service to look up the address. Map images are loaded from OpenFreeMap, which sees the area of the map you view.
- **Calendar Data:** When you connect calendar integration (optional)
- **Crash & Performance Reports:** Crash reports and sampled performance data (via Sentry) to improve stability. We don't attach your account or contact details to them

## How We Use Your Information

- **Core Functionality:** Store and display your contacts and notes
- **Voice Transcription:** Convert voice recordings to text (on-device or cloud)
- **Business Card Scanning:** Extract contact details from business card images (on-device only)
- **Calendar Prep:** Match calendar attendees to your contacts for meeting preparation
- **Reminders:** Send birthday and follow-up notifications
- **Cloud Backup:** Keep an encrypted copy of your data you can restore on another phone or view on the web portal (if enabled)
- **App Improvement:** Fix bugs and improve performance

## Data Storage & Security

### Local Storage

- All data is stored locally on your device by default
- Phone numbers, emails, websites, social and messaging handles, notes, birthdays, family details, interaction summaries, transcripts, meeting notes and action items are encrypted on your device with AES-256 before they are stored, using a key kept in your phone's secure hardware-backed storage
- A contact's display label (usually their name), company, title, location, where you met and tags are stored unencrypted so search works; they are protected by your phone's own encryption
- Photos, business-card images and voice recordings are stored as files on your device and are protected by your phone's own security; they are not included in cloud backups

### Cloud Backup (Optional)

- Cloud backup is optional and requires creating an account (email and password)
- Before anything is uploaded, your backup is encrypted **on your device** with AES-256-GCM, using a key derived from a backup password you choose. The backup password is separate from your login password and is **never sent to us**
- We cannot read your backups, and we cannot recover your backup password — if you lose it, that backup cannot be decrypted
- Backups include your contacts, notes, interactions, meetings and action items. They are stored with Supabase and transferred over TLS, along with basic details about each backup (size, app version, date). We keep your 5 most recent manual and 3 most recent automatic backups
- Weekly automatic backup is optional and can be turned off at any time in Settings. To run it, the app keeps your backup password in your phone's secure storage
- Choose a backup password that's different from your login password

### Web Portal (Optional)

If you have a cloud backup, you can view your contacts read-only in a web browser at app.rememberwho.app. After you sign in with your Remember Who account, your most recent encrypted backup is downloaded and decrypted **in your browser** using your backup password. Your backup password and the decrypted contacts are never sent to us and are not saved; they are cleared when you sign out or close the tab. Your sign-in session is kept in that browser tab until it closes.

When you tap **Open web portal** in the app, our server uses your signed-in account (your email address) to create a single-use sign-in link for your own account. It receives no contact data and never your backup password.

The web portal is hosted by **Vercel**, which processes standard request data (such as IP address and browser type) to serve the site. The portal uses no analytics or tracking.

## Third-Party AI Services

Remember Who offers an optional cloud transcription feature powered by OpenAI's Whisper API. This feature is **disabled by default** and requires your explicit consent before any data is sent.

### What data is sent

When you enable cloud transcription, your **audio recordings** (voice notes) are sent to OpenAI's servers for speech-to-text processing. No other personal data — such as contacts, notes, or account information — is sent to OpenAI.

### Who receives the data

Audio recordings are sent to **OpenAI** ([openai.com](https://openai.com)) via their Whisper speech-to-text API.

### How we obtain your consent

Before any audio is sent to OpenAI, the app presents a consent dialog that explains what data will be shared, who it is shared with, and asks for your explicit permission. You may revoke this consent at any time by switching to on-device transcription or removing your API key in Settings.

### How OpenAI handles your data

Audio is processed by OpenAI to generate a text transcription. Under OpenAI's API data-usage policy, audio sent to the API is not used to train OpenAI's models and may be retained by OpenAI for up to 30 days for abuse monitoring before being deleted. Your OpenAI API key is stored securely on your device using hardware-backed secure storage and is never shared with us.

### On-device alternative

You can use the on-device transcription option, which processes audio entirely on your device using the Whisper AI model. When using on-device mode, **no audio data ever leaves your device**.

## Data Sharing

**We do not sell your data.**

We only share data with:

- **Service Providers:**
  - **Supabase** — account sign-in and storage for your encrypted backups (we cannot read them)
  - **Vercel** — hosting for the optional web portal (serves the site only; it never receives your backup password or decrypted data)
  - **Sentry** — crash and performance reporting to improve app stability
  - **RevenueCat** — in-app purchase processing and subscription management (receives your purchase history and, when you are signed in, your account ID)
  - **OpenAI** — cloud voice transcription only (if you enable cloud mode and grant consent; see "Third-Party AI Services" above)
  - **Google** — calendar integration (Google Sign-In is used solely for calendar access, not for account creation or login) and on-device OCR (Google ML Kit, no data leaves the device)
  - **Microsoft** — calendar integration only (Microsoft OAuth is used solely for Outlook calendar access)
  - **Apple / Google** — your phone's built-in geocoding service, when you use Find on map, Use Current Location or move a map pin
  - **OpenFreeMap** — map images (sees your IP address and the map area you view)
  - **Hugging Face** — download of the on-device transcription model, if you choose on-device transcription (no audio or personal data is sent)
- **Legal Requirements:** If required by law

## Your Rights

You can:

- **Access** your data anytime within the app
- **Export** your data from Settings
- **Delete** your account from Settings: this removes your account, all cloud backups, and that account's contacts on the phone you delete from (see [Delete Your Account](delete-account))
- **View** your backed-up contacts in a browser through the web portal
- **Use Locally:** Use the app without creating an account

## Children's Privacy

Remember Who is not intended for children under 13. We do not knowingly collect data from children.

## Changes to This Policy

We may update this policy occasionally. We'll notify you of significant changes through the app.

## Contact Us

Questions about privacy? Contact us:

**Email:** support@rememberwho.app

---

[Back to Home](./)

© 2026 [Lost Pines Creative LLC](https://lostpinescreative.com/)
