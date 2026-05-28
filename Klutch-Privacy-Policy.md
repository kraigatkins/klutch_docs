# Klutch Digital Marketing — Privacy Policy

**Effective date:** May 27, 2026
**Last updated:** May 27, 2026

This Privacy Policy describes how Klutch Digital Marketing, LLC ("Klutch," "we," "us," or "our") collects, uses, and shares information when our clients (automotive dealerships and other business clients, collectively "Clients") use our review management, reporting, and reputation services (collectively, the "Services").

This policy is written to comply with Meta's Platform Terms, Google's API Services User Data Policy, and applicable privacy laws including the California Consumer Privacy Act (CCPA).

---

## 1. Who We Are

Klutch Digital Marketing, LLC is a marketing technology provider based in Springdale, Arkansas, USA. We provide reputation management, review monitoring and response, social media auditing, and visitor analytics tools for our Clients.

**Contact:**
- Email: kraig@klutchdigitalmarketing.com
- Support: support@klutchdigitalmarketing.com (where available)
- Mailing address available on request

---

## 2. Scope of This Policy

This policy covers data we handle in connection with the Services, including:
- Data from **Google Business Profile** (review content, ratings, reply text)
- Data from **Facebook Pages** (recommendations, ratings, comments, posts)
- Data from website visitor tracking pixels (SmartPixl / Klutch Radar)
- Data from social media profile audits (publicly available metrics)
- Operational data from Clients using our reporting dashboards (KDMI)

This policy applies to:
- **Our Clients** (the businesses that contract with Klutch)
- **End users** of those Clients' platforms whose data we may process (e.g., a customer who leaves a Google review for a dealer)

### Our Role: Data Processor for Our Clients

**Klutch acts as a "data processor" or "service provider" on behalf of our Clients, who are the "data controllers" for end-user information.** This is a fundamental aspect of how the Services work:

- **The Client decides** what data is collected through the Services, why it is collected, how long it is retained, and what actions (such as posting a reply or sending a message) are taken using that data.
- **Klutch acts only on the Client's instructions.** We do not independently determine the purposes or means of processing end-user data.
- **End-user data is collected and processed at the Client's direction.** This includes any consent, opt-in language, terms of service, and privacy notices that the Client provides to its own customers under the Client's own privacy program.
- **End-user privacy requests** (access, deletion, opt-out) should be directed to the **Client** in the first instance, as the Client controls the relationship with the end user. Klutch will assist the Client in fulfilling such requests when contacted.

By using the Services, each Client represents and warrants that it has obtained all necessary consents, provided all required notices, and has the legal right to direct Klutch to collect and process the data described in this policy. **Responsibility and liability for the lawful basis of data processing rests with the Client as the data controller.**

---

## 3. Information We Collect

### 3.1 From Clients
When you become a Klutch Client and access our dashboards (KDMI), we collect:
- Business profile information (business name, address, contact details, hours, social profile links)
- Authorized user accounts (name, email, password hash, role)
- Authentication tokens you grant us to access third-party platforms on your behalf (Google Business Profile OAuth tokens, Facebook Page access tokens)
- Communications you initiate with us (support emails, in-app messages)
- Usage data within our dashboards (which pages you visit, what reports you run)

### 3.2 From Public Review Platforms (on Client's Behalf)
With Client authorization, we connect to platforms like Google Business Profile and Facebook Pages and retrieve:
- Reviews and recommendations posted about the Client (review text, star rating or recommendation, reviewer name as shown on the platform, date posted, replies)
- Page metadata (Page ID, Page name, category)
- Post engagement metrics (where relevant for reporting)

We do **not** collect reviewer contact information beyond what is publicly displayed on the source platform.

### 3.3 From Website Visitors (SmartPixl / Klutch Radar)
When a Client deploys our visitor tracking pixel on their website, we may receive — through our vendor partners — identity-resolution data about visitors who have separately opted into data sharing with the underlying identity provider. This may include:
- Hashed identifiers
- Approximate location (city, state, ZIP)
- Demographic estimates (age range, gender)
- Page visits (URL, timestamp, source)
- Marketing attribution (utm_source, utm_medium, utm_campaign, referrer)

This data is provided by third-party identity-resolution vendors who maintain their own consent and disclosure frameworks. Klutch does not directly collect this data from website visitors.

### 3.4 Information We Do **Not** Collect
- Payment card numbers or banking information (Clients pay through external billing systems)
- Social Security numbers, driver's license numbers, or government IDs
- Health information
- Children's data (our Services are not directed to anyone under 18)
- Login credentials for third-party platforms (we use OAuth tokens, never passwords)

---

## 4. How We Use Information

We use the information described above to:
- Operate, maintain, and improve the Services
- Display reviews, recommendations, and analytics to authorized Client users
- Generate AI-assisted draft replies to reviews (using Anthropic's Claude API; see Section 5)
- Post review replies on the Client's behalf when authorized
- Send Clients notifications about new reviews, low-rated reviews, or SLA digests
- Provide reporting and dashboards to Clients
- Maintain audit logs of actions taken through the Services
- Communicate with Clients about service updates, billing, and support
- Comply with legal obligations

We do **not** use the information for advertising, data brokering, or sale to third parties.

---

## 5. How We Share Information

We share information only as follows:

### 5.1 Service Providers
We use the following service providers to operate the Services. Each is contractually obligated to protect data:
- **Google Cloud Platform** — hosting, BigQuery storage, Cloud Run compute, Cloud Storage, Secret Manager
- **Anthropic, PBC** — AI-assisted reply generation (review text is sent to Claude API to produce draft replies; Anthropic's policy is to not train on API content)
- **GoHighLevel (HighLevel, Inc.)** — CRM, marketing automation, and outbound communication delivery (SMS and email) on the Client's behalf
- **Mailgun (Sinch)** — transactional email delivery for review notifications and digests
- **Meta Platforms** — when posting replies or content back to Facebook Pages on a Client's behalf
- **Google LLC** — when posting replies back to Google Business Profile on a Client's behalf

### 5.2 With Client Authorization
We share data with the platform from which it originated (e.g., posting a reply back to Google or Facebook) only when the Client authorizes that action through the dashboard or pre-approved automation rules.

### 5.3 Legal Requirements
We may disclose information if required to do so by law, court order, or government request, or to protect the rights, property, or safety of Klutch, our Clients, or others.

### 5.4 Business Transfers
If Klutch is acquired or merged, information may be transferred as part of that transaction. We will notify Clients before any such transfer becomes effective.

We do **not** sell personal information, and we do **not** share information for cross-context behavioral advertising.

---

## 6. Data Retention

- **Client account data** — retained for the duration of the Service relationship plus 90 days after termination, then deleted unless legal retention is required.
- **Review and recommendation data** — retained as long as the Client maintains the connected platform integration. On disconnection, retention is governed by the Client's deletion request (see Section 7).
- **Audit logs (reply history, automation actions)** — retained for 24 months for compliance and dispute resolution purposes.
- **OAuth tokens and Page access tokens** — retained only as long as needed to maintain the integration. Revoked tokens are removed within 7 days.
- **BigQuery time-travel** — provides an additional 7-day data recovery window for accidental deletion, as a built-in feature of our storage layer.

---

## 7. Your Rights and Choices

### 7.1 Client Rights
Clients may, at any time:
- Access their data stored in Klutch through the KDMI dashboard
- Request a data export by emailing kraig@klutchdigitalmarketing.com
- Request data deletion by emailing kraig@klutchdigitalmarketing.com
- Disconnect a third-party integration (Google Business Profile, Facebook Page) through the dashboard or by request
- Revoke our authorization tokens through the source platform's settings (e.g., Google Account → Security, or Facebook → Business Integrations)

### 7.2 Data Deletion Instructions
To request deletion of all data associated with your account, email **kraig@klutchdigitalmarketing.com** with the subject line "Data Deletion Request" and include:
- Your business name
- The email address associated with your Klutch account
- The platforms you'd like data removed from (Klutch dashboards, Google connections, Facebook connections, or all)

We will confirm receipt within 5 business days and complete deletion within 30 days, except where retention is required by law (e.g., billing records, audit logs subject to ongoing compliance requirements).

### 7.3 End-User Rights
If you are an end user (e.g., a customer whose Google review or Facebook recommendation we have processed on behalf of a Client) and you wish to inquire about or request deletion of your data, contact us at kraig@klutchdigitalmarketing.com. We may need to coordinate with the relevant Client to fulfill your request.

### 7.4 California Residents (CCPA)
California residents have additional rights under the California Consumer Privacy Act, including the right to know what personal information we collect, the right to delete personal information, and the right to opt out of the sale of personal information. As stated above, we do not sell personal information. To exercise other rights, contact us at the email above.

---

## 8. Security

We implement industry-standard security measures including:
- Encryption in transit (TLS) for all data exchanged with our Services
- Encryption at rest for stored data in Google Cloud Platform
- Access controls limiting Client data access to authorized personnel only
- OAuth tokens and API secrets stored in Google Secret Manager (never in source code)
- Audit logging of administrative actions

No system is perfectly secure. If we become aware of a security incident affecting your data, we will notify you and the relevant authorities as required by applicable law.

---

## 9. Children's Privacy

The Services are not directed to individuals under the age of 18, and we do not knowingly collect personal information from minors. If we learn that we have collected information from a minor, we will delete it promptly.

---

## 10. International Users

Klutch operates from Springdale, Arkansas, USA, and all data is processed in the United States (specifically, Google Cloud Platform's `us-south1` region). If you access the Services from outside the United States, you consent to the transfer and processing of your data in the United States.

---

## 11. Changes to This Policy

We may update this Privacy Policy from time to time. The "Last updated" date at the top will reflect the most recent revision. Material changes will be communicated to Clients via email at least 30 days before they take effect. Continued use of the Services after the effective date of changes constitutes acceptance.

---

## 12. Contact Us

For any questions about this Privacy Policy or our data practices:

**Klutch Digital Marketing, LLC**
Email: kraig@klutchdigitalmarketing.com
Springdale, Arkansas, USA

---

*This Privacy Policy is provided for transparency and to satisfy the requirements of Meta's Platform Terms, Google's API Services User Data Policy, and applicable privacy regulations. It is not legal advice. We recommend Clients consult their own counsel for specific compliance questions.*
