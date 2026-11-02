# Privacy Policy

_Last updated: November 1, 2026_

## 1. Scope

This Privacy Policy applies to the LUNIA mobile application ("the App") available on iOS and Android, and all related backend services. It describes how we collect, use, store, and protect your personal data, including special category health data. The LUNIA website (lunia.health) and early access registration are governed by a separate Privacy Policy.

## 2. Data Controller

Virtuous Conviction Lda. (operating as LUNIA Health)
NIF: 517 193 787
Email: hello@lunia.health
Data Protection Officer (DPO): Jorge Daniel Araújo — hello@lunia.health

## 3. Data We Collect

LUNIA collects data in the following categories. All of it is linked to your account. We do not sell your data and do not use it for advertising or to track you across other apps and websites.

| Category | Data and purpose |
|---|---|
| **Account & Authentication** | Email, user ID, session tokens, two-factor secret (encrypted) and authentication method; if you sign in with Google, Apple or Facebook, that account's name, email and photo and, from Google or Facebook, your date of birth, if you allow it — for account creation and sessions, and the date of birth for app functionality and to personalise the service. If you sign in with Apple, we keep a token Apple issues to LUNIA, encrypted, only so we can revoke it when you delete your account. |
| **Profile & Onboarding** | Display name, age range or date of birth, primary symptoms, emotional state, hormonal or life stage (including pregnancy), check-in frequency, language preference, relationship status and whether you have children — for app functionality and to personalise the service. |
| **Health Profile** | Medical conditions (such as PCOS or endometriosis), relevant surgery, allergies and other conditions you tell us — to adapt the information Luni gives you. |
| **Medication and Contraception** | Medicines, doses, schedules, logged doses and their reminders; contraceptive method and hormone therapy — for reminders and health context. |
| **Calendar, Appointments & Reminders** | Calendar events, appointments, appointment requests (including the reason you write) and scheduled reminders — to organise your health and send reminders. |
| **Symptom & Health Diary** | Symptom entries (18 codes with severity), emotional state per entry, free-text notes, entry date and source — for health pattern tracking. |
| **Wearable & Biometric Data** | Sleep (total minutes, stages), heart rate, resting heart rate, daily steps, menstrual flow, mindfulness minutes, hot flash and night sweat counts — via Apple HealthKit / Google Health Connect. Under the same consent, overnight measurements: oxygen saturation, heart rate variability, respiratory rate and wrist temperature (skin temperature overnight; iPhone only). We use this data to give Luni context and, only if you include device data in a share, in the report you show a health professional. Requires your explicit consent to device health data (Apple Health / Health Connect). |
| **Conversation & AI Interaction** | Chat messages (user + AI responses), conversation mode, RAG references, red-flag detection metadata, output filter metadata — for AI companion operation. |
| **AI-Extracted Timeline** | Extracted symptoms from conversations, temporal references, contextual factors, AI confidence score, confirmation status — for automated health pattern analysis. |
| **Derived Data** | Generated on our servers from what you share: health facts, conversation summaries, numerical representations of text (embeddings) for search, the emotion detected in your messages and the patterns Luni notices over time — treated as health data. |
| **Clinical Reports** | Report type, interview answers, AI-generated pattern narrative, suggested questions and the report PDF — to prepare for medical appointments. The link we email to a professional opens a view of what you chose to share, not a PDF. It comes with a code, opens only once and expires after 48 hours. It stops working if you stop it, delete your account or withdraw your consent to share with clinics. |
| **Behavioral Telemetry (Tempo)** | Interaction timing, flow completion rates, screen transitions, typing speed, behavioral embedding — tracks rhythm, NEVER content. Requires opt-in consent. |
| **Companion Circle** | The email and name or label (for example, "Partner") of the person you invite, and the notes you send them, stored encrypted — to connect you with the person supporting you. That person does not see your health data. |
| **Community Forum** | Posts, anonymous mode, AI moderation score, automated PII redaction, reports (the reason only), members you blocked and the name you blocked them under — for peer community support. |
| **App Feedback** | The comments you leave about the app and about Luni's replies, with your user ID — to improve the service. |
| **Subscription & Billing** | Subscription plan, billing dates and subscription status. In the App, you pay Apple (App Store) or Google (Google Play) and subscription status is managed by RevenueCat; on the web, payment is processed by Stripe. LUNIA does NOT store credit card numbers. |
| **Notifications** | Your phone's push notification token, a device identifier for notifications and the delivery log — to send you notifications. |
| **Device & Technical Data** | Operating system, app version, locale, screen dimensions, device model, network type — requires opt-in consent. |
| **Usage Analytics** | Session counts, screens visited and flows completed, linked to your account, to improve the app. Only with your consent; if you withdraw it, we delete these records. |
| **Device Identifier (Abuse Prevention)** | A single per-device identifier provided by the operating system (ANDROID_ID on Android, identifierForVendor on iOS), sent from the start, before any consent, and whenever you create an account or sign in. It is never stored as given to us: it is immediately hashed with a secret server-side key, and only that hash is kept, so the value cannot be reversed or matched against any other service's records. We use it for one purpose — to see when a suspended account returns under a new email — under our legitimate interest in keeping the community safe (GDPR Art. 6(1)(f)). It is not used for advertising, analytics or tracking you across apps, and it is not combined with device model, screen size or any other attribute to profile your device. Kept for 12 months after the device is last seen, then deleted automatically. |
| **IP Address** | Your phone's IP address is recorded in signed-in sessions, security logs, password reset and email verification requests, and consent records — for account security and fraud prevention, under our legitimate interest (GDPR Art. 6(1)(f)), and to prove consent. |
| **Error Reports** | When the app hits an error, it sends us the error code, the screen, the error type, the app version and the platform, never content or health data; before you sign in, with no identification at all. Under our legitimate interest in keeping the app working (GDPR Art. 6(1)(f)). |
| **Location** | Country and time zone: the ones you choose (or, until you choose, the ones your phone reports) go with each message to Luni and are kept on your profile. They are needed to provide the service — showing the right emergency numbers and respecting your local time (GDPR Art. 6(1)(b)) — so they do not depend on consent. City: optional, only with your location consent, we keep the city you pick from a list, as the coordinates of the city centre; if you withdraw the consent, we delete the city. We never use GPS or your phone's exact location. |
| **External Research API Queries** | PubMed searches to find the peer-reviewed studies Luni cites: medical terms taken from your message or, when there are no medical terms, a short excerpt of your message after names and identifiers are removed. Searches carry no account identifiers. Only with your research consent. |
| **Nutrition API Queries** | Recipe searches sent to Spoonacular, with the diet and intolerances you give, and nothing that identifies you. Requires opt-in consent. |

## 4. How We Obtain Your Consent

Before we process any health data, we ask for your explicit consent, on the privacy card shown at the start. Until then, the only things that leave your phone are the device identifier used to prevent abuse and anonymous error reports (section 3). Consent is granular — you choose which categories we may process:

- Health data — symptom tracking, cycle, mood, medication and your other health records (required for the app to work; given when you accept the privacy card).
- AI processing — your messages are processed by Claude at Amazon Web Services, in the EU (section 7); required to chat with Luni.
- Analytics — usage statistics linked to your account (which features you use and when), so we can improve the app. They are not anonymous. Optional.
- Adaptive experience — the pace at which you use the app (time between interactions, screens visited, typing speed), never the content, to adapt the app to your pace. Optional.
- Device information — operating system version, model, screen size and network type. Optional.
- Messages from Luni — only with this consent does Luni write to you on her own initiative: greetings, check-ins, cycle predictions and suggestions. It is off by default. Reminders you set up (medication, appointments and others) are part of the service you asked for and always arrive, as long as your phone allows notifications; you also always receive safety notices, replies to messages you send and notices about access to your data.
- Device health data — Apple HealthKit / Google Health Connect synchronisation, including the overnight measurements described in section 3. Optional.
- Your city — keeping the city you pick from a list (the city centre). Optional; if you withdraw it, we delete the city. Your country and time zone do not depend on this consent (section 3).
- Scientific research APIs — PubMed searches for Luni's citations, with medical terms or a short excerpt of your message without names or identifiers (section 5). Optional.
- Nutrition API — Spoonacular recipe searches (section 5). Optional.
- Contribute to LUNI's improvement — would let health professionals review Luni's replies in your conversations. This review is currently switched off and no real conversation is reviewed. Optional.
- Sharing with a professional or clinic — recorded each time you share a report with a health professional; the sharing is the consent and covers only that report.
- AI assistant (for supporters) — a person supporting you in the Companion Circle consents, when accepting the invitation, to the questions they ask being processed by Claude, in the EU.

You can change any consent at any time in Profile → Account → Privacy. When you withdraw a consent, we stop collecting data in that category and, for most categories, delete what we already had; the app tells you what will happen before you confirm.

## 5. Third-Party Service Providers

We share data with the following providers and recipients, each only for the purpose stated and never for the recipient's own purposes:

- Hetzner Online (Germany, EU) — servers, database and backups; it also runs the local AI model and the service that removes identifying details before anything is sent to the AI.
- Amazon Web Services (AWS, EU regions only) — runs Claude, by Anthropic, through Amazon Bedrock. It receives the text of your messages, without your name and contact details, and the context summary described in section 7, only with your consent to AI processing.
- Resend — sends account and service emails: email verification, password reset, two-factor codes, legal notices, the notice that your data export is ready, invitations and reminder notices. It receives your email address and generic notices (for example, "You have a reminder in Lunia"), never health content. It also sends the emails addressed to professionals at your request: the reason you write in an appointment request, which goes to the clinic, and the link to what you shared with a professional.
- Slack (US) — internal notices to the LUNIA team: the notice that there is a new crisis alert, with no personal data (the alert stays on our servers in the EU, section 6); the feedback you leave about the app, with your user ID and the comment after identifying details are removed; and notices of your data access or portability requests, with your user ID.
- Expo (US) — checks for app updates every time you open the app, and sees your phone's IP address to do so; delivers push notifications through the Apple Push Notification service (APNs) and Google Firebase Cloud Messaging (FCM). It receives your phone's notification token and opaque identifiers to open the right screen. The phone's system receives only a generic notice and a technical category (for example, reminder), never the symptom, the medication or a prediction.
- Stripe (US/EU) — card payments for subscriptions bought on the web. Card details go straight to Stripe; LUNIA never sees or stores them. Stripe keeps your email, your LUNIA ID, subscriptions, invoices and payments, with no health data, and retains them for 10 years, as Portuguese tax law requires (legal obligation, GDPR Art. 6(1)(c) and Art. 17(3)(b)), even after you delete your account.
- RevenueCat (US) — your user ID and App Store / Google Play purchase history (product, price, dates), to manage your subscription. It receives no name, email or health data. Deleted when you delete your account.
- Apple (App Store) / Google (Google Play) — payment for subscriptions bought in the App, as independent controllers under their own privacy policies.
- Google, Apple and Facebook (US) — only if you sign in with one of these accounts. We receive that account's name, email and photo and, from Google or Facebook, your date of birth, if you allow it.
- Apple HealthKit / Google Health Connect — with your consent, the app reads health data from your phone and sends it to our servers. We send no data to Apple or Google this way.
- Firebase Hosting, by Google (US) — hosts the feedback guide page that opens inside the app and the app download pages; it sees your phone's IP address.
- Spoonacular (US) — recipe searches, with the diet and intolerances you give, and nothing that identifies you. Only with your consent to the Nutrition API.
- PubMed, by the National Library of Medicine (US) — searches for scientific studies for Luni's citations: medical terms taken from your message or, when there are no medical terms, a short excerpt of your message after names and identifiers are removed; with no account identifiers. Only with your research consent.
- Third-party content in the Library and suggestions — images load directly from the services that host them (YouTube, Vimeo, Apple, Spoonacular and the sites hosting covers), which see your phone's IP address. Links (Spotify, Apple Podcasts, PubMed, ClinicalTrials.gov and others) open outside the app, and those services' rules apply.

## 6. Who Can See Your Data

Your data is seen only by those who need it for the purpose stated:

- The LUNIA team — when the safety check detects an emergency, it receives an internal notice with no personal data; the alert (its type, severity and a pseudonymous reference, never your text) is kept on our servers in the EU and read in our admin console. We do this on the basis of your explicit consent to AI processing (GDPR Art. 9(2)(a)) and, only when you cannot consent, to protect your vital interests (Art. 9(2)(c)). Alerts are kept for 2 years after they are resolved, and deleted earlier if you delete your account. The team also receives the feedback you leave about the app and your data requests, to support you and run the service. The admin tools do not show the text of your conversations with Luni. Direct access to the servers is limited to the technical team.
- Forum moderators — the LUNIA team and health professionals with moderation duties see posts held for review before they are published.
- A health professional or clinic — only if you share a report with them or authorise them, and only what you shared or authorised. An appointment request sends the clinic the reason you wrote. If you choose, you can also include your medical history and allergies, your contraception, the doses logged in your medication reminders (under the names you gave them) and your device's vital signs (heart-rate variability, blood oxygen, respiratory rate and, if you share your cycle, wrist temperature). These categories are always off until you turn them on, and never join a share you have already made. We email you the first time a professional opens something you shared, saying when and how it was opened. The email does not say who opened it and contains no health data, and it cannot be switched off.
- The person supporting you in the Companion Circle — only the notes you send them and educational content; they do not see your health data.

## 7. Artificial Intelligence Processing

Your conversations with Luni are processed by Claude, an artificial intelligence model made by Anthropic, which Amazon Web Services (AWS) runs for us through Amazon Bedrock in data centres in the European Union (Ireland, Germany, Sweden, France, Italy and Spain). AWS processes them only on our behalf, under its GDPR Data Processing Addendum. We have configured AWS not to keep your messages or Luni's replies once the reply has been produced, and they are not used to train any model. Anthropic made the model but does not run it: it does not receive your conversations, and LUNIA no longer sends data to Anthropic's own service. Until 17 October 2026, conversations were processed by Anthropic PBC (US) through that service, under EU Standard Contractual Clauses. Anthropic deletes what it received then within 30 days, except messages its automated safety systems flagged, which it may keep for up to 2 years. We only process your messages this way with your consent to AI processing, without which you cannot chat with Luni.

Your messages are sent to AWS to generate Luni's replies, after your name and contact details are automatically removed. Your health records themselves are not sent. So that Luni knows you, a short summary prepared on our servers goes with each message: health facts you have mentioned to Luni (such as conditions, medications, allergies, symptoms and goals), with any free text de-identified first; your mood as a category; the date your last period started, the day and phase of your cycle and the predicted date of your next period; summaries of earlier conversations and weekly summaries, also de-identified; up to two patterns Luni has noticed in your records; your country and time zone; and, when you ask Luni what she knows about you, how many times each symptom was logged. Your day-by-day diary, your notes, the names of your doctors, your email and account identifiers are not sent. This data is pseudonymised, not anonymous: it does not carry your name, but it is about you and your health, so we treat it as health data.

For more information: https://docs.aws.amazon.com/bedrock/latest/userguide/data-protection.html

## 8. Where Your Data Is Stored

On your phone: the app keeps a copy of your health records, conversations, cycle, reports and wearable data, so it works offline. That data is encrypted with a key kept in the device's secure keychain (iOS Keychain / Android Keystore), where your session credentials are also kept. Preferences that contain no health data, such as language or theme, are kept in the app's ordinary storage. When you delete your account, local data is erased. On our servers: data is stored on Hetzner servers in Germany (EU), and backups are also kept at Hetzner, in the EU. Your health records and your conversations do not leave the European Union; what does leave, and why, is described in section 15.

## 9. Security

Before storing them, we encrypt with AES-256-GCM your two-factor authentication secrets, the messages you send to the people who support you, your mood notes and the welcome conversation. Backups are encrypted. Your conversations with Luni and your health records are protected by access control on our servers, but are not yet encrypted field by field. The servers are in Germany (Hetzner) and direct access to them is limited to the technical team. The connection between the app and our servers is encrypted (TLS). Other measures: sessions use short-lived access tokens, kept in your phone's secure keychain; rate limits on every API endpoint; no health data in technical logs; services that run without administrator privileges; filtering of what goes into and comes out of the AI.

## 10. Data Retention

Account data: until account deletion. Onboarding conversations: 30 days after completion. Symptom diary entries: until account deletion or user request. Chat history: until account deletion. Wearable health data: until account deletion or consent withdrawal. Tempo behavioral data: until consent withdrawal or account deletion. Clinical reports: until account deletion; the link emailed to a professional expires after 48 hours. Data exports (files to download in the app): 72 hours, then deleted automatically. Forum posts: until user deletion or moderation removal; when you delete your account, their text and authorship are erased. Consent and terms-acceptance records (including the IP address you gave them from): kept for 3 years after the account ends, to prove consent and to establish or defend legal claims, and then deleted. Crisis alerts: 2 years after they are resolved, and deleted earlier if you delete your account. Device identifier hashes (abuse prevention): 12 months after the device was last seen, then deleted automatically. Operational logs (service activity, errors and a pseudonymous account ID; never health data or message content), kept under our legitimate interest in running and securing the service: 25 days, then deleted automatically. Diagnostic traces of each chat turn (conversation ID, detected intent, model used, token counts, tools used, the safety check outcome and emergency type; never message content): 30 days, removed by the following weekly cleanup, so up to 37 days, and deleted earlier when you clear your chats or delete your account. Payment records at Stripe (customer, invoices and payments, no health data): 10 years, as Portuguese tax law requires (GDPR Art. 6(1)(c) and Art. 17(3)(b)), even after you delete your account. Backups (encrypted copies of our database, kept only for disaster recovery): up to 31 days, then deleted automatically, including data you have already deleted.

## 11. Your Rights

Under the GDPR, you have the right to:

- Right of Access (Art. 15) — request a readable copy of your personal data (PDF) via Profile → Account → Data & privacy → View my data. When it is ready, we email you to say so and you download it in the app within 72 hours. We will respond within one month.
- Right to Rectification (Art. 16) — correct inaccurate or incomplete data. You can edit profile data directly in the app; for AI-extracted data, contact hello@lunia.health.
- Right to Erasure (Art. 17) — delete your account and associated data via Profile → Account → Data & privacy → Delete account. Your account is erased at once and the rest of your data normally within minutes, including the data at RevenueCat; if you signed in with Apple, we ask Apple to revoke LUNIA's access to your Apple ID; the text and authorship of your forum posts are erased; copies in our encrypted backups are deleted automatically within 31 days. Only the consent and terms-acceptance records are kept, for 3 years, and the payment records Stripe holds for 10 years as tax law requires.
- Right to Restrict Processing (Art. 18) — disable individual consent categories at any time in Profile → Account → Privacy.
- Right to Data Portability (Art. 20) — export your data in structured JSON, transferable to another service, via Profile → Account → Data & privacy → Export my data. The file is not sent by email: we email you to say it is ready and you download it in the app within 72 hours.
- Right to Object (Art. 21) — object to processing of your personal data based on legitimate interest, including automated content moderation and pattern analysis. Contact hello@lunia.health to exercise this right.
- Right Not to Be Subject to Automated Individual Decision-Making (Art. 22) — LUNIA uses AI to extract symptom patterns and generate suggestions, but these are informational aids only, not medical or legal decisions. You may request human review of any AI-extracted data.
- Right to Lodge a Complaint (Art. 77) — you have the right to lodge a complaint with a supervisory authority. In Portugal, this is the Comissão Nacional de Proteção de Dados (CNPD): geral@cnpd.pt, www.cnpd.pt.
- Right to Compensation (Art. 82) — if you suffer material or non-material damage as a result of an infringement of the GDPR, you have the right to receive compensation from the data controller or processor. Contact hello@lunia.health or seek redress through the Portuguese courts.
- Right to Withdraw Consent (Art. 7(3)) — you may withdraw your consent at any time without affecting the lawfulness of processing based on consent before its withdrawal.

To exercise any of these rights, contact hello@lunia.health. We will respond within one month (extendable to three months for complex requests, with notice).

## 12. Children's Privacy

The LUNIA app is for adult women aged 18 or over (Terms of Service, section 4). We do not knowingly collect data from anyone under 18. If we discover that we have collected data from someone under 18, we will delete it immediately.

## 13. Medical Disclaimer

LUNIA is an informational wellness companion. It does NOT provide medical diagnoses, prescriptions, or treatment recommendations. Information provided by the AI companion (Luni) is intended for educational purposes only. LUNIA is not a substitute for professional medical advice. In case of emergency, call 112 (European emergency number) or SNS 24 (808 24 24 24 in Portugal).

## 14. Data Breach Notification

In the event of a personal data breach that poses a risk to your rights and freedoms, we will: notify the Portuguese Data Protection Authority (CNPD) within 72 hours; notify affected users without undue delay if the breach poses a high risk; document the breach, its effects, and remedial actions taken.

## 15. International Transfers

Your data is stored and processed in the European Union: on Hetzner servers in Germany and, for the AI, at Amazon Web Services in EU regions. Your health records, your conversations and crisis alerts stay in the EU. Some data leaves the EU for the United States, through the recipients described in section 5 (Slack, Expo, Stripe, RevenueCat, Firebase Hosting, Google, Apple, Facebook, Spoonacular, PubMed). The crisis notice sent to the team through Slack carries no personal data, and push notifications carry only a generic notice and a technical category (Expo). The only ones that can say something about your health are, only with your consent, recipe searches with your diet and intolerances (Spoonacular) and scientific searches with terms or a short excerpt of your message, without names or identifiers (PubMed). These transfers are protected by EU Standard Contractual Clauses or the EU-US Data Privacy Framework.

## 16. Cookies

The LUNIA mobile app does not use cookies. On your phone, the health data the app keeps is encrypted with a key kept in the device's secure keychain, where credentials are also kept; preferences that contain no health data are kept in the app's ordinary storage. The lunia.health website uses cookies as described in Cookie Settings.

## 17. Health Professionals Who Review Content

If you are a health professional and approve a Library item, your name and specialty appear publicly as its clinical reviewer, in the app and on lunia.health, only with your consent (GDPR Art. 6(1)(a)). You can withdraw it at any time in Profile → Consents; your name stops appearing and those items leave the public library.

## 18. Contact

For questions about this Privacy Policy, contact us at hello@lunia.health.
