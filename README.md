# Awesome-White-Label-Portal-Customization

# Awesome White-Label Portal Customization

> A curated list of top White-Label Portal Customization platforms — both SaaS/Hosted commercial solutions and open-source alternatives for branded client portals, secure file sharing, and client collaboration.  
> 🌟 Star this repo if you find it useful! 🌟

---

## 📋 Table of Contents

- [SaaS / Hosted Platforms](#-saas--hosted-platforms)
  - [Chargebee Portal Customization](#chargebee-portal-customization)
  - [Assembly (formerly Copilot)](#assembly-formerly-copilot)
  - [Clinked](#clinked)
  - [SuiteDash](#suitedash)
  - [ClientPoint](#clientpoint)
  - [MyDocSafe](#mydocsafe)
  - [Softr](#softr)
  - [Onehub](#onehub)
  - [Moxo](#moxo)
- [Open-Source Software](#-open-source-software)
  - [ClientShare](#clientshare)
  - [Atrium](#atrium)
- [Comparison at a Glance](#-comparison-at-a-glance)
- [Contributing](#-contributing)

---

## 🟦 SaaS / Hosted Platforms

Commercial, cloud-hosted White-Label Portal Customization platforms. These are not open-source but are included as reference points for feature comparison.

### Chargebee Portal Customization
**Type:** Subscription billing portal white-labeling  
Chargebee allows white-labeling of its hosted checkout and portal pages by using a custom domain instead of Chargebee's default URL. The feature requires creating a CNAME record pointing to `cd3.chargebee.com`, then contacting support to add the domain to their certificate list (7–10 business days) [citation:3]. **Important:** This feature is available only on the Rise plan and above, and is primarily relevant for the older V2 URL-based checkout flow; V3 checkout is a modal popup that minimizes the need for standalone white-labeled pages [citation:3].  
**Best for:** Existing Chargebee customers on Rise+ plans needing branded billing and portal URLs.

### Assembly (formerly Copilot)
**Type:** White-label client portal for service businesses  
Assembly provides a white-label client portal where clients can communicate, make payments, upload files, submit forms, and sign contracts [citation:4]. The platform includes a built-in CRM with a central dashboard for clients, projects, and billing, plus native invoicing with subscription billing and online payment collection [citation:1]. Pricing starts at $149/month for 3 seats and 500 clients, with a notable limitation: no native mobile app for clients or admins [citation:1]. Healthcare-adjacent firms can use it with a signed BAA on the Advanced plan [citation:1].  
**Best for:** Professional service firms wanting an all-in-one portal with built-in CRM and invoicing, accepting the lack of a native mobile app.

### Clinked
**Type:** Secure white-label collaboration platform  
Clinked is a secure, white-label collaboration platform used by 3,000+ businesses across 40 countries. It brings files, conversations, tasks, and document approvals together in branded spaces for clients, teams, and partners [citation:5]. Branding controls include logo, colors, and a branded mobile app. Custom Portal solutions with interface or feature changes require an Enterprise subscription plus a separate build cost. Native integrations include Google Workspace, Microsoft OneDrive, DocuSign, and Adobe Acrobat Sign [citation:5].  
**Best for:** Organizations in accounting, finance, legal, and M&A needing a polished, branded collaboration space with strong security controls.

### SuiteDash
**Type:** White-label client portal with CRM and business suite  
SuiteDash provides a white-label client portal with configurable Dashboards and Portal Pages. White Labeling is an account-level presentation layer covering Platform Branding (colors, logos), Custom URL and Custom Login, and Email Branding [citation:6]. However, branding settings do not automatically grant content access—assignments and feature settings still govern visibility. The platform has a steep configuration burden; paid "Wizarding Sessions" exist because many users cannot set it up alone [citation:14]. It holds 4.8/5 on G2 (595 reviews) and 4.9/5 on Capterra (608 reviews) [citation:14].  
**Best for:** Agencies wanting a comprehensive white-label portal with CRM, email marketing, and unlimited clients, with tolerance for complex setup.

### ClientPoint
**Type:** Business relationship workspace portal  
ClientPoint provides a private, secure virtual office for business relationships, covering scheduling, meetings, chat, content sharing, e-signatures, and payments. Users can bring their own tools (Zoom, Calendly, AdobeSign, Dropbox) or use ClientPoint's built-in endpoints. Enterprise tier enables fully curated branded corporate experiences [citation:7]. Clients include Securitas, Life Fitness, Principal, Live Nation, and Equifax.  
**Best for:** Enterprises wanting a customizable relationship workspace that integrates with existing sales and communication tools.

### MyDocSafe
**Type:** Document-centric client portal with white-labeling  
MyDocSafe offers white-labeling features including custom favicon upload (visible only with a custom domain or subdomain) and branded mobile apps for Apple and Google platforms (available on request via sales) [citation:9]. The June 2025 release added configurable default portal access profiles, allowing administrators to set appropriate access levels when inviting portal users [citation:9].  
**Best for:** Organizations prioritizing document security and compliance with a need for branded mobile experiences.

### Softr
**Type:** No-code white-label client portal builder  
Softr allows building white-label client portals with AI-assisted generation. Users describe what they need, and Softr builds the interface, database, and workflows. Features include user groups, advanced record-level permissions, native automations, and PWA support for mobile-ready apps [citation:11]. Fully compliant with SOC 2 and GDPR. Positioned as a faster, more flexible alternative to one-size-fits-all portal tools.  
**Best for:** Teams wanting to build a custom portal from existing data sources (Airtable, Google Sheets, etc.) without coding.

### Onehub
**Type:** Branded file sharing portal  
Onehub provides private client portals for secure file sharing, customized with logo and brand colors. Features include drag-and-drop uploads, high-quality previews of 30+ file types, advanced activity tracking, precise permissions, and bank-level encryption in transit and at rest [citation:12]. Trusted by over 1 million users at organizations including Starbucks, Dell, Philips, and Aflac. Offers a free 14-day trial with no long-term contract lockups.  
**Best for:** Teams whose primary need is branded, secure file exchange with clients rather than full project management.

### Moxo
**Type:** Workflow-oriented client portal  
Moxo provides a client portal with strong conditional, multi-step workflow orchestration, document requests, e-signatures, form submissions, video meetings, and approval gates. An AI workflow builder generates templates from natural language [citation:1]. **Limitations:** No native CRM or invoicing, and the Business plan caps at 10 workspaces per year (Enterprise required for more). The learning curve is steep; G2 reviewers report conditional workflows "took longer than expected" [citation:1].  
**Best for:** Firms whose primary need is complex, branching workflow orchestration across multi-party engagements.

---

## 🟩 Open-Source Software

Self-hosted, community-driven White-Label Portal platforms. The open-source ecosystem for full-featured client portals is limited; available projects focus on core file sharing and branding.

### ClientShare
**Stack:** Go / Vue 3 / SQLite (PostgreSQL/MySQL optional) | **License:** Open Source (per repository)  
A secure, branded client portal for teams needing better file exchange and document collection outside email threads. Prioritizes self-hosted deployments with sensible defaults for small firms [citation:2]. Features include expiring secure links, user/role-based access control, client/folder/file organization, email-driven invites and password resets, and branding controls for site title, logo, and primary color. Storage options include local filesystem or S3-compatible object storage; database can be SQLite, PostgreSQL, or MySQL. Deploys via Docker Compose as a single Go service with embedded Vue frontend [citation:2].  
**Best for:** Small firms and teams wanting a self-hosted, branded file-sharing portal with minimal infrastructure overhead.

### Atrium
**Stack:** Docker / PostgreSQL | **License:** Open Source (per Docker Hub)  
A self-hosted client portal for agencies and freelancers that replaces shared drives, spreadsheets, and scattered emails with a single branded portal. Features include project management with customizable status pipelines per organization, file sharing via S3/MinIO/Cloudflare R2 or local storage, white-label branding (custom colors and logo), role-based access (owner/admin for team, member for clients), and email notifications via Resend [citation:15]. Built-in PostgreSQL means no separate database container is required. Deploys with a single Docker command or Docker Compose.  
**Best for:** Agencies and freelancers wanting a lightweight, self-hosted branded portal with project management and file sharing.

---

## 📊 Comparison at a Glance

| Software | License | Type | White-Label Depth | Self-Hosted | Best For |
|----------|---------|------|-------------------|-------------|----------|
| **Chargebee** | Proprietary | Billing portal | Custom domain only | ❌ | Chargebee Rise+ users |
| **Assembly** | Proprietary | Service portal + CRM | Full portal branding | ❌ | Service firms needing CRM |
| **Clinked** | Proprietary | Collaboration portal | Logo, colors, mobile app | ❌ | Secure branded collaboration |
| **SuiteDash** | Proprietary | Business suite portal | Platform/URL/Email branding | ❌ | Agencies needing full suite |
| **ClientPoint** | Proprietary | Relationship workspace | Enterprise curated branding | ❌ | Enterprise relationship mgmt |
| **MyDocSafe** | Proprietary | Document portal | Favicon + branded apps | ❌ | Document security + mobile |
| **Softr** | Proprietary | No-code portal builder | Full visual branding | ❌ | Custom portals from data |
| **Onehub** | Proprietary | File sharing portal | Logo + brand colors | ❌ | Secure file exchange |
| **Moxo** | Proprietary | Workflow portal | (Check) | ❌ | Complex workflow orchestration |
| **ClientShare** | Open Source | File portal | Site title, logo, color | ✅ | Self-hosted file exchange |
| **Atrium** | Open Source | Agency portal | Custom colors + logo | ✅ | Agencies/freelancers |

---

## 🤝 Contributing

Contributions are welcome! If you know of an open-source White-Label Portal Customization platform that should be listed here, please open a pull request with:

- Project name and URL
- Brief description (1–2 sentences)
- Stack and license
- Why it stands out

Please ensure the project is actively maintained (releases within the last 12 months) and genuinely open-source. Note that the open-source ecosystem for white-label client portals is nascent; most available projects focus on file sharing and basic project management rather than full business suites.

---

## 📄 License

This list is released under CC0 1.0 Universal (Public Domain). The software projects listed retain their respective licenses.

---

⭐ **If this list helped you discover a useful tool, please star the repo!** ⭐
