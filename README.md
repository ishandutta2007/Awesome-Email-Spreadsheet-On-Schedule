# Awesome Email Spreadsheet On Schedule 📊 ⏰

<p align="center">
  <img src="./assets/banner.svg" alt="Awesome Email Spreadsheet On Schedule Banner" width="100%" />
</p>

<p align="center">
  <a href="https://github.com/ishandutta2007/Awesome-Awesome-Awesome"><img src="https://img.shields.io/badge/Awesome-%E2%9C%94-blueviolet?style=flat-square&logo=github" alt="Awesome"/></a>
  <a href="https://discord.gg/jc4xtF58Ve"><img src="https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Discord" /></a>
  <a href="https://github.com/ishandutta2007/Awesome-Email-Spreadsheet-On-Schedule/stargazers"><img src="https://img.shields.io/github/stars/ishandutta2007/Awesome-Email-Spreadsheet-On-Schedule?style=social" alt="GitHub_Stars" /></a>
  <a href="https://github.com/ishandutta2007/Awesome-Email-Spreadsheet-On-Schedule/network/members"><img src="https://img.shields.io/github/forks/ishandutta2007/Awesome-Email-Spreadsheet-On-Schedule?style=social" alt="GitHub Forks" /></a>
  <a href="https://github.com/ishandutta2007/Awesome-Email-Spreadsheet-On-Schedule/blob/main/LICENSE"><img src="https://img.shields.io/badge/License-MIT-green.svg" alt="License" /></a>
  <a rref="https://github.com/ishandutta2007"><img alt="GitHub followers" src="https://img.shields.io/github/followers/ishandutta2007?label=Follow" /></a>
</p>

---

> **A curated collection of SaaS platforms, automation engines, and open-source tools for automated spreadsheet generation, scheduled report delivery, and recurring data synchronization via email.** 🚀

Whether you are looking for zero-code SaaS tools like Zapier and Make, purpose-built spreadsheet connectors like Sheetgo and Coefficient, or self-hosted open-source pipelines like n8n and Apache Superset, this directory indexes solutions to automate your reporting workflows.

---

## 📑 Table of Contents
- [🌐 Sector Overview & Market Dynamics](#-sector-overview--market-dynamics)
- [💼 SaaS & Hosted Platforms](#-saas--hosted-platforms)
- [💻 Open-Source GitHub Projects](#-open-source-github-projects)
- [🛠️ Architectural Patterns & Stack Recipes](#️-architectural-patterns--stack-recipes)
- [🤝 How to Contribute](#-how-to-contribute)
- [⭐ Star History](#-star-history)
- [💖 Support](#-support)
- [📜 Disclaimer](#-disclaimer)

---

## 🌐 Sector Overview & Market Dynamics

The global workflow and spreadsheet automation market represents an estimated **$21.5B to $29.9B** sector expanding rapidly at a **11%–16% CAGR** toward **$65B–$87B+ by the early 2030s**. The space remains **moderately fragmented** rather than winner-take-all: while horizontal workflow giants like Zapier and Celonis/Make command substantial market capitalization, specialized spreadsheet sync engines (e.g., Coefficient, Supermetrics) and extensible self-hosted open-source platforms (e.g., n8n, Apache Superset) retain distinct market share due to specialized connector breadth, regulatory compliance, data privacy, and self-hosting requirements.

---

## 💼 SaaS & Hosted Platforms

The table below catalogs leading SaaS platforms for scheduled spreadsheet and email report delivery, ranked in descending order by estimated company size (valuation / revenue).

| Platform 🏷️ | Scale & Valuation 📈 | Starting Price 💳 | Free Tier & Trial Limits ⏳ | Core Capabilities 🔍 |
| :--- | :--- | :--- | :--- | :--- |
| **[Make (Celonis)](https://make.com/)** | **$13B valuation** (~$700M+ ARR) | **$9.00 / month** (billed annually) or $10.59/mo | **Free forever**: 1,000 operations/month, 2 active scenarios, 15-minute sync interval, 100 MB data transfer. | Visual workflow builder with multi-step logic, router branching, and native Google Sheets/email connectors. |
| **[Zapier](https://zapier.com/)** | **$5B valuation** (~$310M ARR) | **$19.99 / month** (billed annually) or $29.99/mo | **Free forever**: 100 tasks/month, 2-step single-trigger/action Zaps only, 15-minute sync interval. | Integrates 6,000+ apps; schedules automated sheet exports, CSV generation, and email dispatches. |
| **[Supermetrics](https://supermetrics.com/)** | **$280M valuation** (~$89.5M ARR) | **$37.00 / month** (billed annually) | **14-day free trial** (Full feature access, 1 destination, up to 3 data sources); No permanent free plan. | Marketing data pipeline pulling metrics from 150+ ad & analytics platforms directly into Sheets/Excel. |
| **[Coefficient](https://coefficient.io/)** | **$72M valuation** ($24.7M funded) | **$49.00 / month** (Starter plan) | **Free forever**: 1 user, up to 3 data sources, 5,000 rows max per import, manual refresh only (no automated schedule). | Real-time bidirectional connectors syncing CRMs, databases, and warehouses into Google Sheets & Excel. |
| **[Rows](https://rows.com/)** | **$43.7M funding** (~$35M+ est. valuation) | **$59.00 / workspace / month** (Plus plan) | **Free forever**: Unlimited spreadsheets, 500 API calls/month, 5 AI tasks/month, 10 integrations, 1 MB import cap. | Next-gen spreadsheet with native API integrations, built-in AI analyst, and scheduled report automation. |
| **[Databox](https://databox.com/)** | **$20.5M revenue** ($4.8M funded) | **$71.00 / month** (Analyst tier) | **Free forever**: 1 user, 3 data sources, 1 dashboard, 50 AI credits, daily scheduled data sync. | Unified business analytics and KPI dashboard suite offering automated daily/weekly email scorecards. |
| **[Klipfolio](https://www.klipfolio.com/)** | **$14M revenue** ($17.3M funded) | **$140.00 / month** (Klips team plan) | **Free forever (PowerMetrics)**: Up to 2 data services, 5 custom metrics, 4-hour sync; **14-day free trial** on Klips. | Metric monitoring and executive dashboard platform with scheduled PDF/image snapshot email delivery. |
| **[Sheetgo](https://www.sheetgo.com/)** | **$8M valuation** (~$2M–$4M ARR) | **$35.00 / month** (billed annually) or $50/mo | **Free forever**: Basic file size limits, up to 99 transfers/month, 1 active automation, manual & basic sync. | Connects Google Sheets, Excel, CSV, and SQL databases to construct automated multi-sheet data workflows. |
| **[Actiondesk](https://www.actiondesk.io/)** | **Acquired by Datadog** ($4.1M funded) | Included in Datadog platform tiers | **14-day free trial** (Datadog full trial including telemetry and live spreadsheet views); No standalone free plan. | Real-time database and data warehouse query interface formatted as an auto-refreshing spreadsheet. |
| **[Coupler.io](https://www.coupler.io/)** | **$3.6M est. valuation** (~$1.5M ARR) | **$32.00 / month** (billed annually) or $40/mo | **7-day free trial** (Full active plan features, 15 sources); **Free forever tier**: 1 account connection, 100 runs/month. | Data integration tool automating exports from 60+ platforms to Google Sheets, Excel, and BI tools. |

---

## 💻 Open-Source GitHub Projects

The following open-source solutions provide self-hosted scheduled report generation, spreadsheet querying, and automated email delivery. Ranked in descending order by GitHub_Stars ⭐.

| Project 📦 | GitHub_Stars ⭐ | Primary Language 🖥️ | License 📄 | Overview & Scheduling Architecture ⚙️ |
| :--- | :--- | :--- | :--- | :--- |
| **[n8n](https://github.com/n8n-io/n8n)** | [![Stars](https://img.shields.io/github/stars/n8n-io/n8n?style=social&color=white)](https://github.com/n8n-io/n8n/stargazers) | TypeScript | Sustainable Use License | Fair-code workflow automation orchestrator. Offers native Google Sheets nodes, email delivery (SMTP/SES), cron triggers, and Python/JS transform steps. |
| **[Apache Superset](https://github.com/apache/superset)** | [![Stars](https://img.shields.io/github/stars/apache/superset?style=social&color=white)](https://github.com/apache/superset/stargazers) | Python / TypeScript | Apache-2.0 | Modern enterprise business intelligence platform. Features scheduled email reports sending CSV, Excel, or dashboard snapshots via Celery workers. |
| **[NocoDB](https://github.com/nocodb/nocodb)** | [![Stars](https://img.shields.io/github/stars/nocodb/nocodb?style=social&color=white)](https://github.com/nocodb/nocodb/stargazers) | TypeScript | AGPL-3.0 | Open-source Airtable alternative transforming any relational database into an interactive smart spreadsheet with API access and automated webhooks. |
| **[Odoo](https://github.com/odoo/odoo)** | [![Stars](https://img.shields.io/github/stars/odoo/odoo?style=social&color=white)](https://github.com/odoo/odoo/stargazers) | Python / JavaScript | LGPL-3.0 | Open-source ERP framework with scheduled filter exports and cron mailers that automatically build CSV/Excel files and email them with permission checks. |
| **[Huginn](https://github.com/huginn/huginn)** | [![Stars](https://img.shields.io/github/stars/huginn/huginn?style=social&color=white)](https://github.com/huginn/huginn/stargazers) | Ruby | MIT | Hackable automation system for building agents that monitor web data, query APIs, format spreadsheet/CSV data, and dispatch scheduled email digests. |
| **[Metabase](https://github.com/metabase/metabase)** | [![Stars](https://img.shields.io/github/stars/metabase/metabase?style=social&color=white)](https://github.com/metabase/metabase/stargazers) | Clojure / TypeScript | AGPL-3.0 | Popular open-source BI tool featuring **Dashboard Subscriptions** that automatically send scheduled queries as attached Excel (.xlsx) or CSV files via email. |
| **[Apache Airflow](https://github.com/apache/airflow)** | [![Stars](https://img.shields.io/github/stars/apache/airflow?style=social&color=white)](https://github.com/apache/airflow/stargazers) | Python | Apache-2.0 | Industry-standard DAG orchestrator. Schedules complex ETL pipelines that dump query results to Excel/CSV and dispatch reports using `EmailOperator`. |
| **[ERPNext](https://github.com/frappe/erpnext)** | [![Stars](https://img.shields.io/github/stars/frappe/erpnext?style=social&color=white)](https://github.com/frappe/erpnext/stargazers) | Python / JavaScript | GPL-3.0 | Mature open-source ERP featuring native **Auto Email Reports**. Converts saved query reports into XLSX/CSV attachments delivered on daily/weekly schedules. |
| **[Activepieces](https://github.com/activepieces/activepieces)** | [![Stars](https://img.shields.io/github/stars/activepieces/activepieces?style=social&color=white)](https://github.com/activepieces/activepieces/stargazers) | TypeScript | MIT | Open-source no-code workflow automation tool. Features pre-built pieces for Google Sheets, Microsoft Excel 365, SMTP, and interval-based cron schedules. |
| **[LibreOffice Core](https://github.com/LibreOffice/core)** | [![Stars](https://img.shields.io/github/stars/LibreOffice/core?style=social&color=white)](https://github.com/LibreOffice/core/stargazers) | C++ | MPL-2.0 | Complete open-source office suite. Calc supports headless CLI macros (`--headless --convert-to`) for scripted spreadsheet report generation in cron jobs. |
| **[ONLYOFFICE Community Server](https://github.com/ONLYOFFICE/CommunityServer)** | [![Stars](https://img.shields.io/github/stars/ONLYOFFICE/CommunityServer?style=social&color=white)](https://github.com/ONLYOFFICE/CommunityServer/stargazers) | C# / JavaScript | AGPL-3.0 | Collaborative office suite offering online spreadsheet editing, document management, and scheduled notification tools for team workspaces. |
| **[mailgrid](https://github.com/bravo1goingdark/mailgrid)** | [![Stars](https://img.shields.io/github/stars/bravo1goingdark/mailgrid?style=social&color=white)](https://github.com/bravo1goingdark/mailgrid/stargazers) | Go | BSD-3-Clause | Ultra-lightweight email automation CLI written in Go. Ingests data from CSV or Google Sheets and delivers personalized emails with rate limiting and concurrency. |
| **[AI_multi_AGENT_N8N](https://github.com/ziadnasar6-lgtm/AI_multi_AGENT_N8N)** | [![Stars](https://img.shields.io/github/stars/ziadnasar6-lgtm/AI_multi_AGENT_N8N?style=social&color=white)](https://github.com/ziadnasar6-lgtm/AI_multi_AGENT_N8N/stargazers) | JavaScript | MIT | Autonomous multi-agent automation architecture using local Ollama LLMs and n8n to parse Google Sheets records, trigger events, and send email digests. |
| **[report](https://github.com/peterydd/report)** | [![Stars](https://img.shields.io/github/stars/peterydd/report?style=social&color=white)](https://github.com/peterydd/report/stargazers) | Go | Apache-2.0 | Production-ready Go utility designed to query databases (MySQL, PostgreSQL, Oracle), write Excel sheets, and email them on a schedule via Kubernetes CronJob. |
| **[Auto-Excel-Reports](https://github.com/Bwhiz/Auto-Excel-Reports)** | [![Stars](https://img.shields.io/github/stars/Bwhiz/Auto-Excel-Reports?style=social&color=white)](https://github.com/Bwhiz/Auto-Excel-Reports/stargazers) | Python | MIT | Serverless report generation using Python `openpyxl` scheduled via GitHub Actions cron workflows (`0 0 * * *`) and delivered over SMTP. |

---

## 🛠️ Architectural Patterns & Stack Recipes

Depending on your engineering constraints and privacy requirements, here are the three primary architectural recipes:

1. **The Serverless Cloud-Native Stack** ☁️:
   - *Workflow*: GitHub Actions / AWS Lambda scheduled by EventBridge.
   - *Processing*: Python (`pandas` + `openpyxl` / `xlsxwriter`).
   - *Delivery*: Amazon SES / SendGrid API.
   - *Pros*: Zero server maintenance, free within GitHub Actions / Lambda monthly tiers.

2. **The Open-Source Low-Code Stack** 🧩:
   - *Workflow*: Self-hosted **n8n** or **Activepieces** on Docker.
   - *Processing*: Built-in Google Sheets & Excel manipulation nodes with custom JavaScript/Python code steps.
   - *Delivery*: Direct SMTP integration with company mail servers.
   - *Pros*: Visual debugging, easy modifications by non-developers, full data sovereignty.

3. **The BI & Analytics Native Stack** 📈:
   - *Workflow*: **Metabase** (Subscriptions) or **Apache Superset** (Alerts & Reports).
   - *Processing*: Direct SQL execution against production replicas or data warehouses (Snowflake, BigQuery, PostgreSQL).
   - *Delivery*: Automated Celery workers compiling charts, CSVs, and Excel files.
   - *Pros*: Best for business intelligence, interactive drill-downs, and automated stakeholder reporting.

---

## 🤝 How to Contribute

Contributions are welcome! Help us keep this directory comprehensive and up-to-date:

1. 🍴 Fork the repository.
2. 🌿 Create a descriptive branch (`git checkout -b add-tool-name`).
3. 📝 Add your tool to the table adhering to the schema (Platform / Project, Pricing / Stars, Limits, Core Capabilities).
4. 🚀 Ensure links are working and pricing / limits are accurate.
5. 📬 Submit a Pull Request with a clear description of the utility.

Check out [Awesome Lists](https://github.com/ishandutta2007/Awesome-Awesome-Awesome) for more curated developer resources!

---

## ⭐ Star History

[![Star History Chart](https://star-history.dera.page/svg?repos=ishandutta2007/Awesome-Email-Spreadsheet-On-Schedule&type=date&legend=top-left)](https://star-history.dera.page/#ishandutta2007/Awesome-Email-Spreadsheet-On-Schedule&type=date&legend=top-left)

---

## 💖 Support

If you find this repository helpful for your projects, operations workflows, or data stack research:
- ⭐ **Star** this repository on GitHub.
- 🍴 **Fork** it to build your own custom automations.
- 📢 **Share** it with fellow developers, analysts, and operators.
- ☕ **Buy me a coffee**: Support ongoing maintenance and open-source curation via the [GitHub Sponsors Dashboard](https://github.com/sponsors/ishandutta2007).

Thank you for supporting open-source software and transparent data automation! 🌟

---

## 📜 Disclaimer

- This is a community-curated list for informational and architectural evaluation purposes.
- Always ensure compliance with data protection laws (GDPR, CCPA) and email delivery policies (CAN-SPAM, SPF, DKIM, DMARC) when scheduling automated emails containing proprietary data.
