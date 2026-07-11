# Privacy Policy

**Last updated:** June 22, 2026

Remember Who ("we", "our", or "us") is committed to protecting your privacy. This policy explains how we collect, use, and safeguard your information.

## Information We Collect

### Information You Provide

- **Contact Information:** Names, phone numbers, emails, and other details you enter about your contacts
- **Notes & Interactions:** Notes, meeting records, and conversation summaries you create
- **Photos:** Profile photos you add to contacts
- **Voice Recordings:** Audio recordings you make for voice notes (processed on-device or via OpenAI Whisper API if cloud transcription is enabled)
- **Business Card Scans:** Images of business cards you scan (processed on-device using Google ML Kit OCR)
- **Account Information:** Email address when you create a cloud account (optional)

### Information Collected Automatically

- **Location Data:** When you enable location-based reminders (optional)
- **Calendar Data:** When you connect calendar integration (optional)
- **Crash Reports:** Anonymous crash data to improve app stability

## How We Use Your Information

- **Core Functionality:** Store and display your contacts and notes
- **Voice Transcription:** Convert voice recordings to text (on-device or cloud)
- **Business Card Scanning:** Extract contact details from business card images (on-device only)
- **Calendar Prep:** Match calendar attendees to your contacts for meeting preparation
- **Reminders:** Send birthday and follow-up notifications
- **Cloud Backup:** Sync your data across devices (if enabled)
- **App Improvement:** Fix bugs and improve performance

## Data Storage & Security

### Local Storage

- All data is stored locally on your device by default
- Local data is encrypted using industry-standard encryption

### Cloud Storage (Optional)

- Cloud backup is optional and requires account creation
- Cloud data is encrypted in transit (TLS) and at rest
- We use Supabase for secure cloud storage

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
  - **Supabase** — cloud storage for optional account backup
  - **Sentry** — anonymous crash reporting to improve app stability
  - **RevenueCat** — in-app purchase processing and subscription management
  - **OpenAI** — cloud voice transcription only (if you enable cloud mode and grant consent; see "Third-Party AI Services" above)
  - **Google** — calendar integration (Google Sign-In is used solely for calendar access, not for account creation or login) and on-device OCR (Google ML Kit, no data leaves the device)
  - **Microsoft** — calendar integration only (Microsoft OAuth is used solely for Outlook calendar access)
- **Legal Requirements:** If required by law

## Your Rights

You can:

- **Access** your data anytime within the app
- **Export** your data from Settings
- **Delete** your account and all cloud data
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
