# Legal Guidance for Future LUNIA Health Platform

**Document Date: January 10, 2026**

## Purpose of This Document

This document provides guidance on the legal and regulatory requirements you'll need to address when launching the LUNIA health platform application. This is for planning purposes only and is NOT a substitute for professional legal advice.

**CRITICAL**: Before launching the LUNIA health platform, you MUST consult with:
- A healthcare attorney familiar with digital health regulations
- A privacy attorney specializing in health data (HIPAA/GDPR expert)
- Legal counsel in each jurisdiction where you plan to operate

## Key Differences Between Your Landing Page and Health App

### Current Landing Page (Covered by existing Privacy Policy and Terms)
- Informational website
- Basic contact form
- Limited data collection (name, email, interest)
- No health data
- No AI interactions
- No medical features

### Future LUNIA Health Platform (Requires NEW comprehensive legal documents)
- Health tracking and monitoring
- AI companion (LUNI) interactions
- Collection of Protected Health Information (PHI)
- Symptom tracking, cycle tracking
- Potentially predictive health features
- Medical-grade or quasi-medical functionality

**You will need COMPLETELY NEW legal documents for the health platform.**

## Regulatory Frameworks You Must Consider

### 1. United States: HIPAA (Health Insurance Portability and Accountability Act)

#### Does HIPAA Apply to You?

HIPAA applies to:
- **Covered Entities**: Healthcare providers, health plans, healthcare clearinghouses
- **Business Associates**: Companies that handle PHI on behalf of covered entities

**Key Question**: Will LUNIA be a HIPAA-covered entity or business associate?

**Scenarios**:

**Scenario A - Direct-to-Consumer Wellness App (HIPAA May NOT Apply)**
- If LUNIA is a direct-to-consumer app where users track their own health
- Users are NOT referred by healthcare providers
- Data is NOT shared with healthcare providers for treatment
- You do NOT bill insurance or integrate with EHR systems

In this case, HIPAA may not apply, BUT:
- You're still subject to FTC regulations on health data
- You must follow state privacy laws
- You should still follow HIPAA-like best practices for credibility

**Scenario B - Provider-Integrated App (HIPAA APPLIES)**
- If healthcare providers can access patient data from LUNIA
- If LUNIA integrates with EHR systems
- If LUNIA is prescribed or recommended as part of treatment
- If you process PHI on behalf of healthcare organizations

In this case, you MUST comply with HIPAA.

#### HIPAA Requirements (If Applicable)

1. **Privacy Rule**
   - Obtain patient authorization for PHI use
   - Provide Notice of Privacy Practices
   - Implement minimum necessary access controls
   - Allow patients to access their data
   - Track disclosures of PHI

2. **Security Rule**
   - Administrative safeguards (policies, training, access controls)
   - Physical safeguards (facility access, device security)
   - Technical safeguards (encryption, audit controls, authentication)
   - Risk analysis and management

3. **Breach Notification Rule**
   - Notify affected individuals within 60 days of breach
   - Notify HHS (Department of Health and Human Services)
   - Notify media if breach affects 500+ individuals

4. **Business Associate Agreements (BAAs)**
   - Execute BAAs with all vendors who handle PHI
   - Ensure Firebase/Google Cloud has a BAA (they offer this)
   - Verify all service providers are HIPAA-compliant

#### FTC Health Breach Notification Rule

Even if HIPAA doesn't apply, the FTC Health Breach Notification Rule may require you to:
- Notify users of data breaches
- Notify the FTC if a breach affects 500+ users
- Implement reasonable security measures

### 2. European Union: GDPR (General Data Protection Regulation)

If you have users in the EU (which you likely will, based on your global approach):

#### GDPR Applies When
- You offer services to people in the EU
- You monitor behavior of people in the EU
- You process data of EU residents

#### GDPR Requirements for Health Data

Health data is a **Special Category of Personal Data** under GDPR (Article 9), requiring:

1. **Legal Basis for Processing**
   - Explicit consent (most common for health apps)
   - Necessary for medical diagnosis/treatment
   - Public health interests
   - Other limited exceptions

2. **Enhanced Rights for Users**
   - Right to access
   - Right to rectification
   - Right to erasure ("right to be forgotten")
   - Right to data portability
   - Right to restrict processing
   - Right to object

3. **Data Protection Impact Assessment (DPIA)**
   - Required when processing sensitive health data
   - Must assess risks to user rights
   - Must document mitigation measures

4. **Data Protection Officer (DPO)**
   - May be required depending on scale and scope
   - Must be independent and expert in data protection

5. **Data Processing Agreement (DPA)**
   - Required with all processors (vendors)
   - Must specify security measures and obligations

6. **International Data Transfers**
   - If storing EU data outside EU, must use Standard Contractual Clauses (SCCs) or other approved mechanisms
   - Firebase/Google Cloud offers GDPR-compliant configurations

7. **Breach Notification**
   - Notify supervisory authority within 72 hours
   - Notify affected individuals if high risk

#### GDPR Penalties
- Up to €20 million or 4% of annual global turnover (whichever is higher)
- This is serious - GDPR compliance is critical

### 3. Other Jurisdictions

#### United Kingdom: UK GDPR
- Similar to EU GDPR after Brexit
- Requires separate compliance if serving UK users

#### Canada: PIPEDA (Personal Information Protection and Electronic Documents Act)
- Requires consent for health data collection
- Users have right to access and correct data
- Breach notification requirements

#### Brazil: LGPD (Lei Geral de Proteção de Dados)
- Similar to GDPR
- Health data is sensitive data requiring special protections

#### California: CCPA/CPRA
- Applies to businesses collecting data of California residents
- Enhanced rights for users
- Health data has additional protections under CMIA (Confidentiality of Medical Information Act)

#### Australia: Privacy Act and My Health Records Act
- Strict requirements for health data
- Australian Privacy Principles (APPs)

### 4. FDA Regulations (United States)

#### Does Your App Need FDA Approval?

The FDA regulates "medical devices," which can include software.

**FDA Considers Your App a Medical Device If It**:
- Diagnoses, treats, prevents, or mitigates disease
- Affects the structure or function of the body
- Makes specific medical claims

**Examples of FDA-Regulated Health Apps**:
- Apps that analyze medical images
- Apps that control medical devices
- Apps that provide diagnostic algorithms
- Apps that calculate medication dosages

**Examples of Non-Regulated Wellness Apps**:
- General fitness tracking
- Menstrual cycle tracking (without medical claims)
- Meditation and stress management
- General health education

**Gray Area for LUNIA**:
- Basic cycle tracking: Likely NOT regulated
- Symptom tracking with pattern recognition: Possibly regulated
- Predictive health alerts (e.g., "You may have PCOS"): Likely regulated
- AI providing medical recommendations: Likely regulated

**Important**: FDA enforcement policy can change. Consult with a regulatory expert.

#### FDA Requirements (If Applicable)
- Premarket notification (510(k)) or approval
- Quality System Regulation (QSR) compliance
- Post-market surveillance
- Adverse event reporting

### 5. Medical Device Regulations (EU)

#### EU MDR (Medical Device Regulation)

If your app qualifies as a medical device in the EU:
- Must obtain CE marking
- Must comply with EU MDR requirements
- Clinical evaluation required
- Post-market surveillance

### 6. Accessibility Requirements

#### ADA (Americans with Disabilities Act) - US
- Websites and apps must be accessible to people with disabilities
- Follow WCAG 2.1 AA standards

#### European Accessibility Act
- Digital services must be accessible
- Compliance required by June 2025

## Legal Documents You'll Need for Health Platform

### 1. Updated Privacy Policy

Must address:

**Health Data Collection**
- What health data you collect (symptoms, cycles, mood, etc.)
- How AI processes this data
- Data retention for health information
- Anonymization and de-identification practices

**Special Protections**
- Enhanced security measures for health data
- Encryption at rest and in transit
- Access controls and auditing
- Backup and disaster recovery

**User Rights**
- How to export health data
- How to delete all health data
- How to correct inaccurate data
- How to withdraw consent

**AI and Machine Learning**
- How AI is trained
- Whether user data is used for training
- Opt-out options for AI features
- Transparency about AI decision-making

**Third-Party Sharing**
- If/when health data is shared with providers
- User consent mechanisms
- Healthcare provider integrations
- Research or anonymized data sharing

**Regional Compliance**
- HIPAA provisions (if applicable)
- GDPR compliance statements
- Other jurisdictional requirements

### 2. Updated Terms of Service

Must address:

**Medical Disclaimers**
- NOT a substitute for professional medical advice
- NOT intended to diagnose, treat, or cure
- Users should consult healthcare providers
- Emergency situations - direct to 911/emergency services

**AI Companion Limitations**
- LUNI is an assistant, not a medical professional
- AI responses are informational only
- Accuracy limitations
- User responsibility for health decisions

**User Responsibilities**
- Accurate data entry
- Not relying solely on app for health decisions
- Consulting healthcare providers
- Emergency protocols

**Liability Limitations**
- Limitations for health outcomes
- No guarantee of accuracy
- Disclaimer for AI predictions

**Account Termination**
- User's right to delete account and data
- Your right to suspend accounts for violations
- Data preservation after termination

### 3. Informed Consent Forms

For health apps, you may need separate consent forms:

**General Health Data Consent**
- Explaining what health data you collect
- How it will be used
- Risks and benefits
- User's right to withdraw

**AI Processing Consent**
- How AI will analyze user data
- What predictions/insights will be generated
- Opt-in for AI features

**Research Consent** (if applicable)
- If using anonymized data for research
- How data will be de-identified
- Publications and findings

**Data Sharing Consent** (if applicable)
- Sharing data with healthcare providers
- Sharing with researchers
- Third-party integrations

### 4. Notice of Privacy Practices (HIPAA)

If HIPAA applies:
- Required under HIPAA Privacy Rule
- Must describe PHI uses and disclosures
- User rights under HIPAA
- Complaint procedures

### 5. Data Processing Agreement (GDPR)

If EU users:
- Agreement between you (controller) and vendors (processors)
- Firebase, analytics providers, AI vendors
- Must specify data protection obligations

### 6. Cookie Policy

Updated for health platform:
- Essential cookies for app functionality
- Analytics cookies for usage tracking
- Preference cookies
- User consent mechanisms (especially for EU)

### 7. Accessibility Statement

- Commitment to WCAG compliance
- How to request accommodations
- Contact for accessibility issues

### 8. Community Guidelines

If you have social features:
- Prohibited content (medical misinformation)
- Reporting mechanisms
- Moderation policies

## Technical Security Requirements

### Minimum Security Measures

1. **Encryption**
   - Data in transit: TLS 1.2 or higher
   - Data at rest: AES-256 or equivalent
   - End-to-end encryption for sensitive communications

2. **Authentication**
   - Multi-factor authentication (MFA) option
   - Strong password requirements
   - Session management and timeouts

3. **Access Controls**
   - Role-based access control (RBAC)
   - Principle of least privilege
   - Regular access reviews

4. **Audit Logging**
   - Log all access to health data
   - Log all data modifications
   - Immutable audit trails
   - Retention for at least 7 years (HIPAA) or as required by law

5. **Data Backup and Recovery**
   - Regular automated backups
   - Tested disaster recovery plan
   - Geographic redundancy

6. **Vulnerability Management**
   - Regular security assessments
   - Penetration testing
   - Bug bounty program (recommended)
   - Patch management process

7. **Incident Response**
   - Written incident response plan
   - Breach notification procedures
   - Forensics and remediation protocols

### HIPAA Security Rule Technical Safeguards

If HIPAA applies:
- Access controls (unique user IDs, emergency access, automatic logoff)
- Audit controls
- Integrity controls (data hasn't been altered)
- Person or entity authentication
- Transmission security (encryption, integrity controls)

## AI and Machine Learning Specific Considerations

### Regulatory Uncertainty

AI in healthcare is rapidly evolving. Consider:

1. **FDA Guidance on AI/ML Medical Devices**
   - FDA is developing framework for AI/ML-based software as medical device (SaMD)
   - May require predetermined change control plan
   - Algorithm change protocol

2. **EU AI Act**
   - High-risk AI systems (including health AI) face strict requirements
   - Transparency and explainability
   - Human oversight
   - Accuracy and robustness testing

3. **Transparency Requirements**
   - Disclose when users are interacting with AI
   - Explain how AI makes decisions (explainable AI)
   - Disclose training data sources
   - Disclose limitations and biases

4. **Bias and Fairness**
   - Test for demographic bias
   - Ensure diverse training data
   - Monitor for disparate impact
   - Mitigation strategies

5. **Intellectual Property**
   - If using third-party AI models, verify licensing
   - User-generated data and AI training
   - Ownership of AI-generated insights

## Insurance and Liability

### Insurance Coverage You Should Consider

1. **Cyber Liability Insurance**
   - Data breach response costs
   - Regulatory fines and penalties
   - Business interruption
   - Crisis management

2. **Professional Liability Insurance (E&O)**
   - Errors and omissions coverage
   - AI-related claims
   - Misdiagnosis or inaccurate information claims

3. **General Liability Insurance**
   - Standard business liability

4. **Directors and Officers (D&O) Insurance**
   - Protection for leadership

### Liability Concerns

**Areas of Potential Liability**:
- Inaccurate AI predictions leading to harm
- Data breaches exposing sensitive health information
- Failure to detect serious health conditions
- Misrepresentation of capabilities
- Accessibility failures

**Risk Mitigation**:
- Strong disclaimers and informed consent
- Limitation of liability clauses (where legally enforceable)
- Insurance coverage
- Regular legal review
- Clinical validation of AI models
- Emergency protocols (e.g., directing to 911)

## Implementation Roadmap

### Phase 1: Legal Foundation (6-12 months before launch)

1. **Engage Legal Counsel**
   - Healthcare attorney
   - Privacy attorney (HIPAA/GDPR specialist)
   - Regulatory consultant (if medical device classification uncertain)

2. **Regulatory Determination**
   - Determine if FDA regulation applies
   - Determine if EU MDR applies
   - Identify all applicable regulations by target markets

3. **Compliance Assessment**
   - HIPAA applicability assessment
   - GDPR DPIA (if EU users)
   - State law analysis (especially California, New York)

4. **Document Development**
   - Draft comprehensive Privacy Policy
   - Draft Terms of Service
   - Draft informed consent forms
   - Draft Notice of Privacy Practices (if HIPAA)
   - Cookie Policy
   - Accessibility Statement

5. **Vendor Compliance**
   - Execute BAAs with HIPAA vendors
   - Execute DPAs with GDPR processors
   - Verify all vendors meet security requirements

### Phase 2: Technical Implementation (3-6 months before launch)

1. **Security Infrastructure**
   - Implement encryption (at rest and in transit)
   - Implement authentication and access controls
   - Implement audit logging
   - Set up backup and disaster recovery

2. **Privacy by Design**
   - Data minimization (collect only what's needed)
   - Purpose limitation (use data only for stated purposes)
   - Retention policies and automated deletion
   - User data export functionality
   - User data deletion functionality

3. **User Controls**
   - Privacy settings dashboard
   - Consent management system
   - Data access and download portal
   - Opt-out mechanisms for analytics, AI, etc.

4. **Testing**
   - Security testing (penetration testing, vulnerability assessment)
   - Privacy testing (verify data deletion, export, etc.)
   - Accessibility testing (WCAG 2.1 AA)
   - AI bias testing

### Phase 3: Operational Readiness (1-3 months before launch)

1. **Policies and Procedures**
   - Privacy policies (internal)
   - Security incident response plan
   - Breach notification procedures
   - User complaint handling
   - Content moderation (if applicable)

2. **Training**
   - Train team on HIPAA/GDPR requirements
   - Security awareness training
   - Incident response drills

3. **Documentation**
   - Record of Processing Activities (GDPR)
   - Risk assessments
   - Security documentation
   - Compliance checklist

4. **Insurance**
   - Obtain cyber liability insurance
   - Obtain E&O insurance

### Phase 4: Launch and Ongoing Compliance

1. **User-Facing Documents**
   - Publish Privacy Policy
   - Publish Terms of Service
   - Implement consent flows
   - Cookie banners (if EU)

2. **Monitoring**
   - Security monitoring and alerts
   - Audit log reviews
   - User feedback monitoring
   - Regulatory changes monitoring

3. **Periodic Review**
   - Annual privacy policy review
   - Annual security assessment
   - Compliance audits
   - AI model revalidation

4. **Breach Preparedness**
   - Maintain incident response team
   - Breach notification templates
   - PR/communications plan

## Red Flags and Common Mistakes to Avoid

### Red Flag 1: "We're just a wellness app, regulations don't apply to us"

**Why it's wrong**:
- FTC and state attorneys general are increasingly scrutinizing health apps
- Even non-HIPAA apps face liability for data breaches
- "Wellness" vs "medical" line is blurry and evolving

**What to do**:
- Assume regulations apply until proven otherwise
- Follow best practices even if not legally required

### Red Flag 2: "We'll use the same Privacy Policy and Terms as our landing page"

**Why it's wrong**:
- Health app requires completely different legal framework
- Landing page doesn't address health data, AI, or medical disclaimers
- Insufficient protection for you and users

**What to do**:
- Create new, comprehensive documents for health platform
- Clearly distinguish between landing page and health app

### Red Flag 3: "We'll figure out GDPR compliance later"

**Why it's wrong**:
- GDPR fines can be company-ending
- Retrofitting privacy is much harder than building it in
- User trust is hard to regain after violations

**What to do**:
- GDPR compliance from day one if targeting EU
- Privacy by design and default
- DPIA before launch

### Red Flag 4: "Our AI vendor handles all the compliance"

**Why it's wrong**:
- You are the data controller - ultimate responsibility is yours
- Vendor contracts don't absolve you of liability
- You must verify vendor compliance

**What to do**:
- Due diligence on all vendors
- Execute proper agreements (BAAs, DPAs)
- Regular vendor audits

### Red Flag 5: "We don't need a lawyer, we have templates"

**Why it's wrong**:
- Generic templates don't address your specific use case
- Health tech is high-risk and highly regulated
- Mistakes can be extremely costly

**What to do**:
- Budget for legal counsel (expect $20k-$100k+ for comprehensive review)
- Consider it cost of doing business in health tech
- Cheaper than litigation or regulatory fines

### Red Flag 6: "We'll just copy [Big Health App]'s policies"

**Why it's wrong**:
- Their features and risks may differ from yours
- They may have negotiated special arrangements
- Their policies may not be up-to-date or compliant
- Plagiarism issues

**What to do**:
- Use other policies for reference only
- Create custom policies for your specific situation
- Have attorney review

## Cost Estimates

Budget for legal and compliance (rough estimates):

### Legal Counsel
- **Initial consultation and strategy**: $5,000 - $15,000
- **Privacy Policy, Terms of Service, consents**: $15,000 - $40,000
- **HIPAA compliance review**: $10,000 - $30,000
- **GDPR compliance and DPIA**: $10,000 - $25,000
- **FDA regulatory strategy** (if applicable): $25,000 - $100,000+
- **Ongoing legal support** (annual retainer): $20,000 - $60,000+

### Security and Compliance
- **Security assessment and pen testing**: $10,000 - $50,000
- **HIPAA security implementation**: $20,000 - $100,000+
- **GDPR technical compliance**: $15,000 - $60,000
- **Compliance audits** (annual): $10,000 - $30,000

### Insurance
- **Cyber liability insurance** (annual): $5,000 - $25,000
- **E&O insurance** (annual): $3,000 - $15,000

### Tools and Services
- **HIPAA-compliant hosting** (incremental cost): Variable
- **Compliance management platform**: $5,000 - $20,000/year
- **Security monitoring tools**: $5,000 - $20,000/year

**Total First-Year Estimate**: $100,000 - $400,000+
**Ongoing Annual Estimate**: $50,000 - $150,000+

These are rough estimates. Actual costs depend on:
- Complexity of your features
- Number of jurisdictions
- Whether FDA approval needed
- Size of user base
- Risk tolerance

## Resources

### Legal Resources

**HIPAA**
- HHS HIPAA website: https://www.hhs.gov/hipaa
- HIPAA for Professionals: https://www.hhs.gov/hipaa/for-professionals

**GDPR**
- Official GDPR text: https://gdpr-info.eu/
- ICO (UK) guidance: https://ico.org.uk/for-organisations/guide-to-data-protection/guide-to-the-general-data-protection-regulation-gdpr/

**FDA**
- Digital Health Center of Excellence: https://www.fda.gov/medical-devices/digital-health-center-excellence
- Software as Medical Device: https://www.fda.gov/medical-devices/digital-health-center-excellence/software-medical-device-samd

**FTC**
- Mobile Health Apps Interactive Tool: https://www.ftc.gov/tips-advice/business-center/guidance/mobile-health-apps-interactive-tool

### Professional Organizations

- **American Health Information Management Association (AHIMA)**
- **Healthcare Information and Management Systems Society (HIMSS)**
- **International Association of Privacy Professionals (IAPP)**

### Recommended Next Steps

1. **Immediately** (while still in landing page phase):
   - Research healthcare attorneys in your area or who specialize in digital health
   - Start tracking regulatory developments
   - Join digital health industry groups
   - Begin building relationships with compliance experts

2. **6-12 months before planned health platform launch**:
   - Engage legal counsel
   - Conduct regulatory assessment
   - Begin DPIA (if GDPR applies)
   - Start vendor compliance review

3. **3-6 months before launch**:
   - Finalize all legal documents
   - Implement technical security measures
   - Execute vendor agreements
   - Obtain insurance

4. **1-3 months before launch**:
   - Final legal review
   - Security testing
   - Team training
   - Soft launch to limited users (beta)

## Final Thoughts

Launching a health platform is exciting but comes with significant legal and regulatory responsibilities. The good news:

- **You're thinking about this early** - that's the right approach
- **Many companies have successfully navigated this** - it's doable
- **Users care about privacy and security** - compliance is a competitive advantage
- **Building it right from the start** is much easier than retrofitting

The most important takeaways:

1. **Get expert legal help** - this is not a DIY area
2. **Budget appropriately** - legal and compliance costs are significant
3. **Build privacy and security in from day one** - privacy by design
4. **Stay informed** - regulations are constantly evolving
5. **Don't let fear paralyze you** - with proper guidance, you can navigate this

LUNIA has a meaningful mission. With the right legal foundation, you can build a platform that helps women while protecting their sensitive health information and complying with applicable laws.

---

**This document is for informational purposes only and does not constitute legal advice. Consult with qualified legal counsel before making any legal or regulatory decisions.**