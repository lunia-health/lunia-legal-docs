# Privacy Policy — LUNIA App

**Last Updated: April 16, 2026**

## 1. Scope

This Privacy Policy applies to the LUNIA mobile application ("the App") available on iOS and Android, and all related backend services. It describes how we collect, use, store, and protect your personal data, including special category health data. The LUNIA website (lunia.health) and early access registration are governed by a separate Privacy Policy.

## 2. Data Controller

LUNIA Health  
[LEGAL ENTITY NAME — to be confirmed]  
[REGISTERED ADDRESS — to be confirmed]  
NIF: [NIF — to be confirmed]  
Email: hello@lunia.health  
Data Protection Contact: hello@lunia.health

## 3. Data We Collect

LUNIA collects data in the following categories:

| Category | Data | Purpose |
|---|---|---|
| **Account & Authentication** | Email, phone number (optional), user ID, JWT tokens, authentication method | Account creation and sessions |
| **Profile & Onboarding** | Display name, age bracket, primary symptoms, emotional state, hormonal phase, check-in frequency, language preference | Service personalisation |
| **Symptom & Health Diary** | Symptom entries (18 codes with severity), emotional state per entry, free-text notes, entry date and source | Health pattern tracking |
| **Wearable & Biometric Data** | Sleep (total minutes, stages), heart rate, daily steps, menstrual flow, mindful minutes, hot flash and night sweat counts — via Apple HealthKit / Google Health Connect | Biometric correlation (opt-in, explicit consent) |
| **Conversation & AI Interaction** | Chat messages (user + AI responses), conversation mode, RAG references, red-flag detection metadata, output filter metadata | AI companion operation |
| **AI-Extracted Timeline** | Extracted symptoms from conversations, temporal references, contextual factors, AI confidence score, confirmation status | Automated health pattern analysis |
| **Clinical Reports** | Report type, interview answers, AI-generated pattern narrative, AI-suggested questions, PDF export (48h expiry link) | Medical consultation preparation |
| **Behavioral Telemetry (Tempo)** | Interaction timing, flow completion rates, screen transitions, typing speed, behavioral embedding — tracks rhythm, NEVER content | Adaptive UX pacing (opt-in) |
| **Community Forum** | Posts, anonymous mode, AI moderation score, automated PII redaction, reports | Peer community support |
| **Subscription & Billing** | Subscription plan, billing dates, payment processing via Stripe — LUNIA does NOT store credit card numbers | Subscription management |
| **Device & Technical Data** | Operating system, app version, locale, screen dimensions, device model, network type | Technical support and compatibility (opt-in) |
| **Location** | Coarse location (country, region) derived from network | Region-specific health guidance and regulatory compliance (opt-in) |
| **External Research API Queries** | Anonymised search terms sent to PubMed, arXiv, bioRxiv, CrossRef | Literature-backed AI responses — no personal health data transmitted (opt-in) |
| **Nutrition API Queries** | Anonymised food and nutrition queries sent to Spoonacular | Dietary guidance features (opt-in) |

## 4. How We Obtain Your Consent

When you first use the LUNIA app, we ask for your explicit consent before collecting any data. Our consent system is granular — you choose exactly what data categories we may process:

1. **Core Health Data** — symptom tracking, cycle data, AI conversations *(required for app functionality)*
2. **Analytics** — anonymous usage statistics
3. **Adaptive Experience** — behavioral tempo tracking
4. **Device Information** — OS version, device model, screen size
5. **Notifications** — push notification delivery and smart timing
6. **Wearable Health** — Apple HealthKit / Google Health Connect synchronisation
7. **Location** — coarse location for region-specific guidance and compliance
8. **External Research APIs** — anonymised queries to PubMed, arXiv, bioRxiv, CrossRef for literature-backed AI responses
9. **Nutrition API** — anonymised queries to Spoonacular for dietary guidance features

You can change any consent at any time in **Profile → Privacy Settings**. Withdrawing consent stops future data collection for that category.

## 5. Third-Party Service Providers

We share data with the following providers:

| Provider | Location | Purpose |
|---|---|---|
| Hetzner Cloud | Germany, EU | Backend infrastructure, all server-side data storage |
| Anthropic Claude API | USA | AI conversation processing (Standard Contractual Clauses + explicit consent) |
| Stripe | USA / EU | Payment processing |
| Pinecone | USA | RAG vector search, embeddings only |
| Google Firebase | USA | Website database and analytics |
| Apple HealthKit / Google Health Connect | Device | Health data stays on device + our EU servers |
| Expo EAS | USA | App build and updates |

## 6. AI Processing

Your conversations with Luni are processed using artificial intelligence. In our standard configuration, AI processing occurs on European servers (Hetzner Cloud, Germany) using our self-hosted AI models. For certain features or when our primary AI service is unavailable, your conversation data may be processed by Anthropic (Claude API), based in the United States. When this occurs, your data is protected by Standard Contractual Clauses and Anthropic's data processing agreement. You can withdraw consent for external AI processing at any time in your profile settings.

## 7. Where Your Data Is Stored

- **Mobile device**: Profile, symptoms, chat history, and behavioral data are stored locally on your device using encrypted storage (iOS Keychain / Android Keystore for credentials; AsyncStorage for non-sensitive preferences).
- **European servers**: Backend data is stored on Hetzner Cloud servers in Germany (EU). Your health data never leaves the European Union unless you consent to external AI processing.

## 8. Security

We implement the following security measures:

- AES-256-GCM encryption at rest for sensitive fields
- JWT authentication with short-lived access tokens stored in the device's secure keychain
- Rate limiting on all API endpoints
- No health data in application logs
- AI conversation turns encrypted before database persistence
- Non-root containers for all backend services
- Input sanitisation and output filtering on AI responses

## 9. Data Retention

| Data Category | Retention Period |
|---|---|
| Account data | Until account deletion |
| Onboarding conversations | 30 days after completion |
| Symptom diary entries | Until account deletion or user request |
| Chat history | Until account deletion |
| Wearable health data | Cached locally; server sync until deletion |
| Tempo behavioral data | Until consent withdrawal or account deletion |
| Clinical reports | Until account deletion; PDF links expire after 48h |
| Forum posts | Until user deletion or moderation removal |
| Consent audit logs | Retained indefinitely (GDPR regulatory requirement) |

## 10. Your Rights

Under the GDPR, you have the right to:

- **Right of Access (Art. 15)** — request a copy of your personal data
- **Right to Rectification (Art. 16)** — correct inaccurate data
- **Right to Erasure (Art. 17)** — delete your account and all associated data via Profile → Delete Account. Deletion cascades within 72 hours
- **Right to Restrict Processing (Art. 18)** — disable individual consent categories at any time
- **Right to Data Portability (Art. 20)** — export your data in machine-readable format via Profile → Export My Data
- **Right to Object to Automated Decision-Making (Art. 22)** — LUNIA uses AI to extract symptom patterns, but these are informational aids only, not medical decisions

To exercise any of these rights, contact hello@lunia.health. You may also lodge a complaint with the Portuguese Data Protection Authority (CNPD) at www.cnpd.pt.

## 11. Children's Privacy

The LUNIA app is designed for adult women. We do not knowingly collect data from anyone under 16 years of age. If we discover that we have collected data from a child under 16, we will delete it immediately.

## 12. Medical Disclaimer

LUNIA is an informational wellness companion. It does NOT provide medical diagnoses, prescriptions, or treatment recommendations. Information provided by the AI companion (Luni) is intended for educational purposes only. LUNIA is not a substitute for professional medical advice. In case of emergency, call 112 (European emergency number) or SNS 24 (808 24 24 24 in Portugal).

## 13. Data Breach Notification

In the event of a personal data breach that poses a risk to your rights and freedoms, we will:

- Notify the Portuguese Data Protection Authority (CNPD) within 72 hours of becoming aware of the breach
- Notify affected users without undue delay if the breach poses a high risk to their rights and freedoms
- Document the breach, its effects, and the remedial actions taken

## 14. International Transfers

Your data is primarily stored and processed within the European Union (Hetzner Cloud, Germany). Transfers outside the EU (Stripe, Firebase, Anthropic, Pinecone, Expo — all US-based) are protected by Standard Contractual Clauses or the EU–US Data Privacy Framework. Health data (GDPR Art. 9 special category) is only transferred outside the EU with your explicit consent and appropriate safeguards in place.

## 15. Cookies

The LUNIA mobile app does not use cookies. Local data storage uses AsyncStorage (non-sensitive data) and the device's secure keychain (credentials and tokens). The lunia.health website uses cookies as described in its separate Cookie Policy.

## 16. Contact

For questions about this Privacy Policy, contact us at hello@lunia.health. Response time: within 30 days.
