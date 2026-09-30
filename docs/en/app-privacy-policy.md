# Privacy Policy

_Last updated: April 16, 2026_

## 1. Scope

This Privacy Policy applies to the LUNIA mobile application ("the App") available on iOS and Android, and all related backend services. It describes how we collect, use, store, and protect your personal data, including special category health data. The LUNIA website (lunia.health) and early access registration are governed by a separate Privacy Policy.

## 2. Data Controller

Virtuous Conviction Lda. (operating as LUNIA Health)
Rua do Porto, n.º 37, 4925-347 Viana do Castelo, Portugal
NIF: 517 193 787
Email: hello@lunia.health
Data Protection Officer (DPO): Jorge Daniel Araújo — hello@lunia.health

## 3. Data We Collect

LUNIA collects data in the following categories:

| Category | Data and purpose |
|---|---|
| **Account & Authentication** | Email, phone number (optional), user ID, JWT tokens, authentication method — for account creation and sessions. |
| **Profile & Onboarding** | Display name, age bracket, primary symptoms, emotional state, hormonal phase, check-in frequency, language preference — for service personalisation. |
| **Symptom & Health Diary** | Symptom entries (18 codes with severity), emotional state per entry, free-text notes, entry date and source — for health pattern tracking. |
| **Wearable & Biometric Data** | Sleep (total minutes, stages), heart rate, daily steps, menstrual flow, mindful minutes, hot flash and night sweat counts — via Apple HealthKit / Google Health Connect. Requires explicit consent. |
| **Conversation & AI Interaction** | Chat messages (user + AI responses), conversation mode, RAG references, red-flag detection metadata, output filter metadata — for AI companion operation. |
| **AI-Extracted Timeline** | Extracted symptoms from conversations, temporal references, contextual factors, AI confidence score, confirmation status — for automated health pattern analysis. |
| **Clinical Reports** | Report type, interview answers, AI-generated pattern narrative, AI-suggested questions, PDF export (48h expiry link) — for medical consultation preparation. |
| **Behavioral Telemetry (Tempo)** | Interaction timing, flow completion rates, screen transitions, typing speed, behavioral embedding — tracks rhythm, NEVER content. Requires opt-in consent. |
| **Community Forum** | Posts, anonymous mode, AI moderation score, automated PII redaction, reports — for peer community support. |
| **Subscription & Billing** | Subscription plan, billing dates, payment processing via Stripe — LUNIA does NOT store credit card numbers. |
| **Device & Technical Data** | Operating system, app version, locale, screen dimensions, device model, network type — requires opt-in consent. |
| **Device Identifier (Abuse Prevention)** | A single per-device identifier provided by the operating system (ANDROID_ID on Android, identifierForVendor on iOS), collected when you create an account or sign in. It is never stored as given to us: it is immediately hashed with a secret server-side key, and only that hash is kept, so the value cannot be reversed or matched against any other service's records. We use it for one purpose — to see when a suspended account returns under a new email — under our legitimate interest in keeping the community safe (GDPR Art. 6(1)(f)). It is not used for advertising, analytics or tracking you across apps, and it is not combined with device model, screen size or any other attribute to profile your device. Kept for 12 months after the device is last seen, then deleted automatically. |
| **Location** | Coarse location (country, region) derived from network — used only for region-specific health guidance and regulatory compliance. Requires explicit opt-in consent. |
| **External Research API Queries** | Search terms and queries sent to external scientific databases (PubMed, arXiv, bioRxiv, CrossRef) to retrieve peer-reviewed literature for AI responses. No personal health data is transmitted; queries are anonymised before sending. Requires opt-in consent. |
| **Nutrition API Queries** | Food and nutrition queries sent to Spoonacular for nutritional information and dietary guidance features. Queries are anonymised before sending. Requires opt-in consent. |

## 4. How We Obtain Your Consent

When you first use the LUNIA app, we ask for your explicit consent before collecting any data. Our consent system is granular — you choose exactly what data categories we may process:

- Core Health Data — symptom tracking, cycle data, AI conversations (required for app functionality)
- Analytics — anonymous usage statistics
- Adaptive Experience — behavioral tempo tracking
- Device Information — OS version, device model, screen size
- Notifications — push notification delivery and smart timing
- Wearable Health — Apple HealthKit / Google Health Connect synchronisation
- Location — coarse location for region-specific guidance and compliance
- External Research APIs — anonymised queries to PubMed, arXiv, bioRxiv, CrossRef for literature-backed AI responses
- Nutrition API — anonymised queries to Spoonacular for dietary guidance features

You can change any consent at any time in Profile → Privacy Settings. Withdrawing consent stops future data collection for that category.

## 5. Third-Party Service Providers

We share data with the following providers:

- Hetzner Cloud (Germany, EU) — backend infrastructure, all server-side data
- Anthropic Claude API (US) — AI conversation processing, with Standard Contractual Clauses and explicit consent
- Stripe (US/EU) — payment processing
- Google Firebase (US) — website database and analytics
- Apple HealthKit / Google Health Connect — health data stays on device + our servers
- Expo EAS (US) — app build and updates

## 6. Artificial Intelligence Processing

Your conversations with Luni are processed by artificial intelligence provided by Anthropic PBC (US), under EU Standard Contractual Clauses. Anthropic does not use your conversations to train its models and deletes them within a maximum of 30 days.

Your messages are sent to Anthropic to generate responses. Structured health profile data (conditions, medications, symptoms), email, phone number, and account identifiers are not sent.

For more information: https://www.anthropic.com/privacy

## 7. Where Your Data Is Stored

Mobile device: Profile, symptoms, chat history, and behavioral data are stored locally on your device using encrypted storage (iOS Keychain / Android Keystore for credentials; AsyncStorage for non-sensitive preferences). European servers: Backend data is stored on Hetzner Cloud servers in Germany (EU). Your health data never leaves the European Union unless you consent to external AI processing.

## 8. Security

We implement the following security measures: AES-256-GCM encryption at rest for sensitive fields; JWT authentication with short-lived access tokens stored in the device's secure keychain; rate limiting on all API endpoints; no health data in application logs; AI conversation turns encrypted before database persistence; non-root containers for all backend services; input sanitisation and output filtering on AI responses.

## 9. Data Retention

Account data: until account deletion. Onboarding conversations: 30 days after completion. Symptom diary entries: until account deletion or user request. Chat history: until account deletion. Wearable health data: cached locally; server sync until deletion. Tempo behavioral data: until consent withdrawal or account deletion. Clinical reports: until account deletion; PDF links expire after 48h. Forum posts: until user deletion or moderation removal. Consent audit logs: retained indefinitely (GDPR regulatory requirement). Device identifier hashes (abuse prevention): 12 months after the device was last seen, then deleted automatically.

## 10. Your Rights

Under the GDPR, you have the right to:

- Right of Access (Art. 15) — request a human-readable copy (PDF) of your personal data via Account → View my data. We will respond within one month.
- Right to Rectification (Art. 16) — correct inaccurate or incomplete data. You can edit profile data directly in the app; for AI-extracted data, contact hello@lunia.health.
- Right to Erasure (Art. 17) — delete your account and all associated data via Profile → Delete Account. Deletion cascades within 72 hours.
- Right to Restrict Processing (Art. 18) — disable individual consent categories at any time in Profile → Privacy Settings.
- Right to Data Portability (Art. 20) — export your data in structured JSON format, portable to another service, via Account → Export my data.
- Right to Object (Art. 21) — object to processing of your personal data based on legitimate interest, including automated content moderation and pattern analysis. Contact hello@lunia.health to exercise this right.
- Right Not to Be Subject to Automated Individual Decision-Making (Art. 22) — LUNIA uses AI to extract symptom patterns and generate suggestions, but these are informational aids only, not medical or legal decisions. You may request human review of any AI-extracted data.
- Right to Lodge a Complaint (Art. 77) — you have the right to lodge a complaint with a supervisory authority. In Portugal, this is the Comissão Nacional de Proteção de Dados (CNPD): geral@cnpd.pt, www.cnpd.pt, Av. D. Carlos I, 134 — 1.º, 1200-651 Lisboa.
- Right to Compensation (Art. 82) — if you suffer material or non-material damage as a result of an infringement of the GDPR, you have the right to receive compensation from the data controller or processor. Contact hello@lunia.health or seek redress through the Portuguese courts.
- Right to Withdraw Consent (Art. 7(3)) — you may withdraw your consent at any time without affecting the lawfulness of processing based on consent before its withdrawal.

To exercise any of these rights, contact hello@lunia.health. We will respond within one month (extendable to three months for complex requests, with notice).

## 11. Children's Privacy

The LUNIA app is designed for adult women. We do not knowingly collect data from anyone under 16 years of age. If we discover that we have collected data from a child under 16, we will delete it immediately.

## 12. Medical Disclaimer

LUNIA is an informational wellness companion. It does NOT provide medical diagnoses, prescriptions, or treatment recommendations. Information provided by the AI companion (Luni) is intended for educational purposes only. LUNIA is not a substitute for professional medical advice. In case of emergency, call 112 (European emergency number) or SNS 24 (808 24 24 24 in Portugal).

## 13. Data Breach Notification

In the event of a personal data breach that poses a risk to your rights and freedoms, we will: notify the Portuguese Data Protection Authority (CNPD) within 72 hours; notify affected users without undue delay if the breach poses a high risk; document the breach, its effects, and remedial actions taken.

## 14. International Transfers

Your data is primarily stored and processed within the European Union (Hetzner Cloud, Germany). Transfers outside the EU (Stripe, Firebase, Anthropic, Expo — all US-based) are protected by Standard Contractual Clauses or the EU-US Data Privacy Framework. Health data (GDPR Art. 9 special category) is only transferred outside the EU with your explicit consent and appropriate safeguards.

## 15. Cookies

The LUNIA mobile app does not use cookies. Local data storage uses AsyncStorage (non-sensitive data) and the device's secure keychain (credentials and tokens). The lunia.health website uses cookies as described in Cookie Settings.

## 16. Contact

For questions about this Privacy Policy, contact us at hello@lunia.health.
