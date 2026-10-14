# Awesome-Email-Spreadsheet-On-Schedule

# Top Email Spreadsheet on Schedule Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Scheduled Report Delivery, Spreadsheet-to-Email Automation & Data Sync*  
**Last updated: October 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Email Spreadsheet on Schedule**. These tools enable anyone to automatically generate spreadsheets or reports from databases, SaaS platforms, and internal systems—then deliver them via email on a recurring schedule.

**Examples** include Sheetgo, Coefficient, Supermetrics, Klipfolio, Coupler.io, Zapier, Make, Rows, Actiondesk, and Databox (the category leaders).

**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, scheduled report generation, and open automation platforms—ideal for operations teams, analysts, and developers seeking transparent, vendor-independent report delivery.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Sheetgo](https://www.sheetgo.com/)**  
  Workflow automation platform for spreadsheets. Connects Google Sheets, Excel, and databases to automate data transfers with 15+ features. Free tier available; paid plans for larger volumes .

- **[Coefficient](https://coefficient.io/)**  
  Data connector and automation platform for Google Sheets and Excel. Syncs data from CRMs, databases, and SaaS tools on a schedule. Freemium pricing .

- **[Supermetrics](https://supermetrics.com/)**  
  Marketing analytics platform connecting 150+ platforms into Google Sheets, Excel, and BI tools. Trusted by 200K+ organizations .

- **[Klipfolio](https://www.klipfolio.com/)**  
  Business dashboard platform with scheduled email reports. Connects to 100+ data sources.

- **[Coupler.io](https://www.coupler.io/)**  
  All-in-one data analytics and automation platform. Syncs data from 60+ sources to Google Sheets, Excel, and BI tools with scheduled refreshes .

- **[Zapier](https://zapier.com/)**  
  Workflow automation connecting 6,000+ apps. Google Sheets triggers can send emails, create reports, and schedule deliveries. Free tier for basic automations .

- **[Make (Integromat)](https://make.com/)**  
  Visual workflow automation with Google Sheets and email integrations. Supports scheduled scenarios and AI-powered content generation .

- **[Rows](https://rows.com/)**  
  Spreadsheet with built-in data integrations and scheduling. Connects to APIs, databases, and SaaS tools with automated refresh .

- **[Actiondesk](https://www.actiondesk.io/)**  
  Spreadsheet automation platform pulling live data from databases and SaaS tools with scheduled refreshes.

- **[Databox](https://databox.com/)**  
  Business analytics platform with scheduled email reports. Connects 130+ data sources and delivers dashboards via email.

## Open-Source GitHub Projects

- **[report (peterydd)](https://github.com/peterydd/report)**  
  Open-source Go program that queries databases (Oracle, MySQL, PostgreSQL), writes results to Excel, and emails reports on a schedule . **The most directly applicable open-source scheduled report tool available.** Configuration via YAML with support for multiple sheet pages, column mapping, sum calculations, and email recipients (to/cc/bcc). Deployable as **Kubernetes CronJob** with `schedule: "*/30 * * * *"` and `concurrencyPolicy: Forbid` . Docker image available (`peterydd/report`). **The most production-ready open-source solution for database-to-Excel-to-email reporting.**

- **[Scheduled Export by Email (Odoo)](https://apps.odoo.com/apps/modules/19.0/scheduled_filter_export)**  
  Open-source Odoo module (LGPL-3) for scheduled report delivery . Pick any model, apply filters, choose columns, set schedule and recipients. **Hourly cron builds the file and mails it as attachment.** Features **Run As user permissions**—recipients see exactly what that user is allowed to see, nothing more. CSV always, Excel when `xlsxwriter` installed. Truncation warnings at 5000 rows. Empty results send no email. **The most permission-aware open-source scheduled report module.**

- **[Auto-Excel-Reports (Bwhiz)](https://github.com/Bwhiz/Auto-Excel-Reports)**  
  Open-source scripts and workflows using Python's `openpyxl` for Excel report generation with **GitHub Actions scheduling** . Features scheduled execution via cron (`'0 0 * * *'`), email distribution via SMTP, and environment variables via GitHub Secrets. **The most GitHub-native open-source approach**—no servers to manage, just push and let Actions run.

- **[mailgrid (bravo1goingdark)](https://github.com/bravo1goingdark/mailgrid)**  
  Ultra-lightweight, high-throughput email automation CLI in Go (BSD-3-Clause) . Reads recipients from **CSV or Google Sheet** and delivers emails via SMTP with **concurrency, rate-limiting, and optional scheduling**. **13 GitHub stars**. Designed without bloat—single binary deployment. **The most focused open-source tool for spreadsheet-to-email delivery.**

- **[ERPNext Auto Email Reports](https://docs.frappe.io/erpnext/auto-email-reports)**  
  Open-source ERP (GPL-3.0) with **built-in Auto Email Report** functionality . Configure any saved report (Report Builder, Script, or Query Report) to send at regular intervals (daily/weekly/monthly/yearly). Features **per-user permissions**, filter application, row limits (max 500), and format options (HTML, XLSX, CSV). Emails sent at midnight. **The most mature open-source ERP-native scheduled reporting.**

- **[n8n](https://github.com/n8n-io/n8n)**  
  Open-source workflow automation platform (Sustainable Use License) with Google Sheets and email nodes . **Runs every minute watching linked Google Sheet** for automated responses and notifications. Self-hostable with Docker (`docker run -it --rm --name n8n -p 5678:5678 n8nio/n8n`) . Custom code nodes for JavaScript/Python transformation. Error handling with retries and fallback paths. **The most flexible open-source automation platform for spreadsheet-to-email workflows.**

- **[AI_multi_AGENT_N8N (NexusAgent)](https://github.com/ziadnasar6-lgtm/AI_multi_AGENT_N8N)**  
  Open-source multi-agent automation system built on n8n (MIT) . **Central Orchestrator Agent** with specialized sub-agents: **Meeting Management** (queries Google Sheets, sends Gmail reminders, provisions Calendar events), **Database & Sheet Agent** (reads/appends/updates Google Sheets records), **Email Agent** (retrieves messages, sends status updates), **Web Exploration Agent** (live search + Calendar actions). Powered by **Ollama** local LLMs. Telegram interface for hands-free control. **The most advanced open-source agent-based spreadsheet/email automation.**

- **[outreach-os](https://www.npmjs.com/package/outreach-os)**  
  Open-source N8N workflow collection for B2B outreach (MIT) . **Lead Search & Scoring Engine** (Google Places → 100-point scoring → Google Sheets), **AI Email Automation** (GLM-4 generated emails → Gmail), **Email Reply Tracker & Auto Follow-Up** (daily Gmail checks, 3-day follow-up). Full status tracking in Google Sheets: Pending → Emailed → Replied/FollowedUp. **The most complete open-source outreach automation with spreadsheet tracking.**

### Additional Strong Open-Source Options

- **[Ethersheet](https://github.com/ether/ethersheet)** — Open-source collaborative spreadsheet (Apache-2.0) for team data editing before scheduled export .
- **[ONLYOFFICE](https://github.com/ONLYOFFICE/CommunityServer)** — Open-source office suite (AGPL-3.0) with spreadsheet editing and integration capabilities .
- **[LibreOffice Calc](https://github.com/LibreOffice/core)** — Open-source spreadsheet (MPL-2.0) with macro support for scripted report generation .
- **[NocoDB](https://github.com/nocodb/nocodb)** — Open-source Airtable alternative (AGPL-3.0) with API access for scheduled data export .
- Community **n8n** workflows for spreadsheet-to-email scheduling and multi-step approval routing.

**Frameworks for building custom systems**: Combine **report (peterydd)** for database-to-Excel-to-email with **Scheduled Export by Email** for permission-aware report delivery, **mailgrid** for lightweight CSV-to-email, **n8n** for workflow orchestration, and **PostgreSQL** for persistence—creating a fully self-hosted, enterprise-grade scheduled report platform.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Scheduled report systems handling business data must comply with data protection regulations (GDPR, CCPA, etc.) and email sending regulations (CAN-SPAM, SPF/DKIM/DMARC).
- **Open-source scheduled reporting is mature for database-to-Excel workflows.** `report (peterydd)` provides production-ready Kubernetes CronJob deployment . Odoo's Scheduled Export by Email adds permission-aware delivery . ERPNext includes Auto Email Reports natively . **These are genuine alternatives to Sheetgo and Coupler.io for internal reporting.**
- **n8n is the most flexible open-source automation platform.** With 400+ integrations, custom code nodes, and self-hosting via Docker, it can replicate most SaaS automation workflows . The trade-off is setup and maintenance effort compared to managed platforms.
- **GitHub Actions provides serverless scheduling.** Auto-Excel-Reports demonstrates cron-based report generation and email delivery without managing servers . Ideal for teams already using GitHub.
- Self-hosted open-source solutions require proper security hardening, email deliverability configuration, and ongoing maintenance. Scheduled reports may contain sensitive data—ensure access controls and audit trails are in place.

---

**Made for operations teams, analysts, and developers building transparent scheduled reporting solutions.**  
Let's make Email Spreadsheet on Schedule more open, data-driven, and reliable.
