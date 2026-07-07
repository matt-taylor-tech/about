# Matt Taylor

**IT Director · Infrastructure, Automation, and AI Engineering**

Huntersville, NC · matt@matt-taylor.tech · [matt-taylor.tech](https://matt-taylor.tech) · [LinkedIn](https://www.linkedin.com/in/matt-taylor-tech) · [GitHub](https://github.com/matt-taylor-tech)

IT Director and hands-on engineer running IT end to end for a national food sales and brokerage organization (1,000+ employees across 80+ locations, three-person team). I build the systems, not just manage them: hybrid Microsoft 365 and Azure at scale, multi-vendor network and telephony across the fleet, a defense-in-depth security and identity stack, and a growing layer of AI and agent engineering. Self-taught product builder and operator (a profitable mobile-app LLC and a small business run on custom software). Most of what I build is running in production or documented at [matt-taylor.tech](https://matt-taylor.tech), so you can verify the work rather than take my word for it.

> Full project write-ups, with architecture and detail, live at **[matt-taylor.tech](https://matt-taylor.tech)**.

---

## Experience

### IT Director · Affinity Group · Charlotte, NC · Oct 2022 to Present

Own IT end to end for a national food sales and brokerage organization: 1,000+ employees, 80+ locations, on a three-person team.

- Run the Microsoft 365 estate (Exchange Online, SharePoint, Teams, OneDrive) and hybrid Active Directory / Entra ID: Conditional Access, MFA, Privileged Identity Management, SSO, and dynamic group-based licensing and access.
- Led an infrastructure and licensing modernization that consolidated onto Microsoft Fabric F64 and EMS E5, cutting BI licensing cost by roughly 60% and hardening identity without adding a security headcount.
- Led IT integration for five completed acquisitions on a reusable cross-tenant Microsoft 365 migration toolkit, backed by a 26-page operating playbook.
- Administer Microsoft Intune across the endpoint fleet, plus a proactive-remediation and endpoint-automation suite (device provisioning, Windows 11 upgrades, bloatware removal, printer and diagnostics tooling).
- Architected a multi-site Remote Desktop Services platform for roughly 850 users, with a DMZ-isolated gateway, dual-client access, and automated TLS certificate renewal.
- Operate a defense-in-depth security stack: Microsoft Defender XDR, Conditional Access and PIM, CISA ScubaGear baseline assessments, Unified Audit Log forensics, and authorized web-application penetration testing with formal reporting.
- Built the internal automation layer: a 70+ script Microsoft 365 PowerShell admin library for monthly compliance reviews, an employee SMS broadcast platform (Power Automate, Graph, Twilio), an Office 365 to Snowflake user sync as a Snowflake-native stored procedure, and a serverless Azure Automation reporting runbook on managed identity.
- Authored a ten-domain, Python-generated IT documentation framework and an interlocking naming-standards taxonomy across three identity systems (300+ dynamic groups).

**AI and agent engineering**

- Own the company-wide AI program: a three-tier governance framework (a corporate AI policy co-owned with HR and Business Intelligence, an AI-assisted development policy, and a developer handbook with a production-ready repo template) plus the rollout of Claude Enterprise, GitHub Copilot, and Microsoft Copilot Studio agents, backed by a managed developer platform.
- Architected and deployed an autonomous IT operations agent: a Python and Supabase platform unifying the team's source systems (ITSM, identity, remote support, network, endpoint security) that posts diagnostic notes on new tickets with machine and network context and screenshot reading via vision, running on Azure Functions with a read-and-suggest default and confirm-gated actions.
- Built and deployed a live Model Context Protocol (MCP) server (Python, FastMCP on Azure Container Apps) exposing the team's operational systems to Claude and Cowork as one namespaced connector of 35 tools, with a set of governed write tools whose trust boundary sits at the identity layer (Entra OAuth connector plus delegated Graph on-behalf-of scoping).

### IT Manager · Ross & Witmer · Charlotte, NC · Apr 2011 to Oct 2022

Built and ran the entire IT function from the ground up for a 125-user, three-office HVAC business over an 11.5-year tenure. Systems shipped here remain in production.

- Architected the network, hybrid Active Directory / Entra ID environment, Hyper-V virtualization, and a three-layer monitoring stack (PRTG, InfluxDB, Grafana) from scratch.
- Launched the company's first Microsoft 365 / Exchange Online environment in 2014, the origin of 11+ years of M365 administration.
- Led selection and rollout of a third-party HVAC service-management platform, migrating off a legacy Unix system and moving field technicians from paper work orders to iPads with in-field card processing.
- Ran two full telephony migrations and a published cost-reduction case study; built brand-distinct company websites end to end.

### HVAC Contractor · May 2002 to Apr 2011

Design, installation, repair, and service of residential and commercial HVAC systems, with end-to-end project management under deadline. Operational rigor and disciplined troubleshooting that transferred directly to IT.

---

## Selected Projects

- **Autonomous IT Operations Agent**: Python + Supabase + Azure Functions platform with a live Claude triage agent (vision, machine/network context, confirm-gated actions).
- **IT Ops MCP Server**: deployed FastMCP connector (Azure Container Apps) exposing five operational systems as 35 governed tools with identity-layer authorization.
- **AI Governance & Development Program**: company-wide AI policy, developer handbook, and managed dev platform across 1,000+ employees.
- **Microsoft Fabric F64 Migration**: moved enterprise BI off 100+ Power BI Pro licenses with zero-downtime cutover, RLS, and external partner sharing.
- **Multi-site RDS Platform**: ~850 users, split-role and single-server deployments, automated TLS renewal, dual-client access.
- **[VolleyballEngine](https://mattsvolleyball.com)**: full-stack tournament platform (Next.js, Supabase, Cloudflare Workers): six formats including a Swiss pairing algorithm, RBAC, real-time live scoring, and 1099 payout calculation.
- **[EPA 608 Practice](https://epa608app.com)**: published iOS and Android study app (Flutter), 4.0 stars and 110+ ratings, with full Spanish localization.
- **Home lab**: enterprise-style home network and Home Assistant automation at scale (370+ devices, 3,578 entities), plus a woodworking and digital-fabrication shop. See [matt-taylor.tech/maker](https://matt-taylor.tech/maker).

---

## Skills

**Microsoft hybrid infrastructure**: Azure, Microsoft 365 administration, hybrid AD + Entra ID, Intune / MDM, Windows Server + Hyper-V, RDS / RemoteApp

**Automation, scripting & AI**: PowerShell (advanced), Python (FastAPI, Flask), Microsoft Graph API, Power Automate, Azure Functions & Automation, Claude API in production (vision, model routing), MCP server authorship (FastMCP), Microsoft Copilot Studio, AI policy & governance

**Networking & telephony**: Cisco Meraki (MX/MR/SM) across 80+ sites, HPE Aruba Instant On, site-to-site VPN, Microsoft Teams Phone

**Data & analytics**: Microsoft Fabric F64, Power BI, Snowflake (Python runtime), SQL Server, SQLite

**Security & identity**: Microsoft Defender XDR, Conditional Access + MFA + PIM, CISA ScubaGear, Microsoft Purview, Unified Audit Log forensics, authorized web-app penetration testing, PKI / SSL-TLS lifecycle

**Web & app development**: Astro, Next.js + TypeScript, React, Tailwind CSS, Cloudflare Pages / Workers / R2, Supabase (Postgres + RLS), Flutter / Dart

**Cross-cutting operations**: ITIL on Freshservice, cross-tenant M&A migration, documentation-as-code pipelines, naming-standards design, IT policy and runbook authorship

---

## Founder Ventures

- **After Hours Data Systems LLC** (2014 to present): self-published EPA 608 Practice on iOS and Android; self-taught cross-platform mobile development (App Inventor to Thunkable to Flutter).
- **Matt's Volleyball League** (2023 to present): founded and run a recreational sand volleyball league (150 to 200 players per season) on custom software (VolleyballEngine) built and operated end to end.

---

## Education & Certifications

**B.S., Computer Information Systems**, Western Carolina University

*Earlier certifications:* Microsoft Certified Solutions Expert (MCSE), VMware Certified Associate, CompTIA Server+. Current work is best evidenced by the shipped projects above and at [matt-taylor.tech](https://matt-taylor.tech).
