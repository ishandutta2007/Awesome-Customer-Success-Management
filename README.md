# Awesome-Customer-Success-Management

# Awesome-Customer-Success-Management

**Top Customer Success Management (Opensource) 🌟 Star if you like it! 🌟**



**Curated List of SaaS Products & Open-Source GitHub Projects**

*Focused on Health Scoring, Churn Prediction, Playbook Automation & Self-Hosted CS Platforms*

**Last updated: November 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Customer Success Management**. These tools enable CS teams to monitor account health, predict churn, automate playbooks, and drive expansion revenue—from fully managed enterprise platforms with AI copilots to self-hosted projects that give teams control over their customer data.



**Examples** include Gainsight, ChurnZero, Totango, Catalyst, Planhat, Vitally, ClientSuccess, Custify, SmartKarrot, and HubSpot Customer Success Tools (the category leaders in commercial space).



**Open-source emphasis**: This section is expanded with every relevant project for self-hosted customer success, health scoring, and open CS infrastructure. **Critical note**: True open-source customer success management is extremely sparse—**CXM-Tool** is the only open-source CX/CS platform found in this research, but it is a React/Express/SQLite project with limited production validation . The category is dominated by proprietary vendors with deep CRM integrations, AI scoring, and playbook engines that open-source projects do not replicate.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [Sector Overview & Market Dynamics](#sector-overview--market-dynamics)
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## Sector Overview & Market Dynamics

The Customer Success Management (CSM) software market is estimated at approximately $2.2B to $2.7B in 2025–2026, expanding at an annual growth rate (CAGR) of over 20% toward $3.4B+ as recurring revenue businesses prioritize net retention and churn reduction over pure acquisition. The sector is moderately concentrated at the top—anchored by established pure-play pioneers (Gainsight, ChurnZero, Totango) and massive CRM ecosystems (HubSpot, Salesforce)—surrounded by a fragmented long tail of specialized point solutions for customer telemetry, onboarding, and self-hosted tooling.

## SaaS/Hosted Platforms

| Platform | Company Size (Valuation / Revenue) | Pricing | Free Tier / Trial Limits | Description & Key Strengths |
| :--- | :--- | :--- | :--- | :--- |
| **[HubSpot Customer Success Tools](https://www.hubspot.com/)** | ~$12B+ Market Cap (NYSE: HUBS) / ~$3.1B+ ARR | Paid Service Hub starts at $15–$20/seat/mo (Starter); CS features require Professional tier at $90–$100/seat/mo + onboarding | Free forever tier available: Capped at 2 users, 1,000 contacts, 1 shared inbox, 3 canned snippets, 1 meeting link, and community-only support | CS tools integrated directly within Service Hub; best for teams already running on HubSpot CRM. Health scoring is basic compared to pure-play platforms. |
| **[Gainsight](https://www.gainsight.com/)** | $1.1B Valuation (Vista Equity acquisition) / ~$200M+ ARR | Starts at ~$150/user/month (annual contract ~$30,000/year minimum) | No free tier; free trial on website is restricted to Product Experience (PX) only (CS platform requires guided demo / pilot) | Enterprise category leader with deep health scoring, AI copilots (Atlas), and automated playbooks; requires ~5 month implementation. |
| **[Planhat](https://www.planhat.com/)** | ~$550M Valuation ($50M Series A) / ~$25M–$33M ARR | Starts at $1,150/month (billed annually, ~$13,800/year minimum) for Start-Up plan with unlimited seats | No free tier and no self-serve free trial; access requires a vendor demo and guided proof-of-concept (POC) | Highly configurable customer platform offering unlimited user seats and modern data-layer modeling across customer journeys. |
| **[Totango](https://www.totango.com/)** | ~$150M+ Total Funding / ~$40M ARR (Merged with Catalyst) | Starts at ~$1,000–$1,500/month (typically ~$12,000–$18,000/year annual contract) | No free tier and no self-serve free trial; evaluation requires demo request and sales-assisted trial/pilot | Enterprise customer retention and product-led growth platform; features modular composable CS architecture. |
| **[Catalyst](https://catalyst.io/)** | ~$65M+ Total Funding / ~$10M–$20M ARR (Merged with Totango) | Starts at ~$500/month (annual agreements starting ~$6,000–$12,000/year) | No free tier and no self-serve free trial; sandbox access granted via sales consultation | Customer growth and collaboration platform with intuitive UI and bidirectional CRM sync; merged with Totango under Great Hill Partners. |
| **[ChurnZero](https://churnzero.com/)** | ~$35M Total Funding / ~$25M–$50M ARR | Starts at $12,000/year ($1,000/month billed annually) for entry tier | No free tier and no self-serve free trial; evaluation requires a scheduled consultation and live product demo | Real-time health scoring, customer journeys, and automated playbooks optimized for mid-market and SMB SaaS teams. |
| **[Vitally](https://www.vitally.io/)** | ~$40M+ Funding ($30M Series B) / ~$15M–$25M ARR | Starts at $299/month for starter tier; higher tiers scale via custom annual contracts | 14-day free trial available (sandbox environment accessed through sales-assisted signup); no permanent free tier | Modern, collaborative CS platform with built-in AI copilots, customer-facing docs/portals, and flexible real-time integrations. |
| **[ClientSuccess](https://www.clientsuccess.com/)** | Bootstrapped / Seed-funded / ~$10M–$15M ARR | Starts at $15,000/year ($1,250/month billed annually) | No free tier and no self-serve free trial; platform evaluation is provided via scheduled sales demo and guided POC | Structured customer onboarding, success scores, and renewal tracking designed for growing mid-market B2B teams. |
| **[Custify](https://www.custify.com/)** | Bootstrapped / Private / ~$2.7M ARR | Starts at $899/month (entry plan typically covering up to 3 CSM users) | No permanent free tier; 14-day guided trial/sandbox provided upon request via sales demo | Agile CS platform tailored for B2B SaaS businesses wanting automated health scoring, KPI tracking, and rapid setup. |
| **[SmartKarrot](https://www.smartkarrot.com/)** | Early Stage / ~$1.1M Funding / ~$1M–$5M ARR | Starts at $15,000/year (or entry plans starting at $499/user/month) | No free tier and no self-serve free trial; access requires a scheduled personalized product demo | Blends customer success management with product engagement analytics, account surveys, and automated playbooks. |

## Open-Source GitHub Projects



- **[CXM-Tool](https://github.com/antigravitysoham-eng/CXM-Tool)**

  **Full-stack Customer Experience management portal** (license per repo) — **the only open-source CX/CS platform** found in this research . **Features**: **Portfolio management**—interactive dashboard with Gross/Net Retention, Churn Risk, upcoming Renewals; customer directory segmented by Customers/Prospects/Partners; **health checks** with proactive account scoring and risk categorization . **Lifecycle & engagement**—CLM (contract stages, pipeline value, renewal dates); onboarding tracker with milestone steps; customer training/certification tracking; events and webinars coordination . **Connectivity**—centralized integration hub for Zoho CRM, Salesforce, HubSpot; smart module mapping; global sync audit trail; encrypted credential storage . **AI copilot**—context-aware assistant analyzing SQLite database for NPS, account health, revenue forecasting; flags "Critical" or "Poor" health accounts . **Tech stack**: React 19 + Vite (frontend), Express/Node.js (backend), SQLite, JWT auth with bcrypt . **Deploy**: Local (`cd server && npm install && npm start` for backend; `npm install && npm run dev` for frontend) . **Trade-off**: **Early-stage project**—no production validation, no multi-tenancy, no enterprise SSO; SQLite limits scale. Integration hub exists but live sync maturity unverified. **Best for**: developers wanting a functional reference implementation for a CX/CS platform—or small teams willing to self-host and extend.



### Additional Strong Open-Source Options



- **No mature open-source customer success platform exists.** Gainsight, ChurnZero, Totango, Catalyst, Planhat, Vitally, ClientSuccess, Custify, and SmartKarrot are all proprietary. Teams needing CS software must use commercial platforms or build custom solutions. **CXM-Tool** provides a conceptual starting point but lacks the playbook engines, AI scoring, and CRM sync depth of commercial platforms.



**Frameworks for building custom systems**: **None available**. The open-source ecosystem for customer success is essentially empty. **CXM-Tool** is the only functional starting point, but it is a student/portfolio project, not production software.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, license (for open-source), and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Customer success platforms handling account health and revenue data must comply with data protection regulations (GDPR, CCPA, etc.) and implement appropriate access controls.

- **The "enterprise CS platform" vs. "mid-market CS platform" vs. "CS module" vs. "open-source project" distinction is critical.** **Gainsight, Totango, and Catalyst** are **enterprise CS platforms**—deep health scoring, playbooks, and AI, but quote-only with long implementations . **ChurnZero, Vitally, ClientSuccess, Custify, and SmartKarrot** are **mid-market CS platforms**—published entry pricing or quote-only, faster deployment . **HubSpot Customer Success Tools** are a **CS module** within Service Hub—not a dedicated CS platform. **CXM-Tool** is an **open-source student project**—it demonstrates CX concepts but lacks production infrastructure . **No production-ready open-source customer success platform exists.**

- **Gainsight cannot be evaluated without sales engagement.** No published pricing, no self-serve trial, and ~5 month implementation . **Budget for a lengthy procurement cycle.**

- **Vitally publishes $299/month entry but requires sales for all tiers.** Trial is accessed through sales motion, not self-serve . **ClientSuccess and SmartKarrot both start at $15,000/year** . **ChurnZero starts at $12,000/year** .

- **Custify, Catalyst, and Totango publish no pricing at all**—demo-required sales motion with no self-serve trial . **Do not plan evaluation without sales engagement.**

- **Planhat and SmartKarrot list free versions** per Software Advice . **Verify scope directly with vendors**—CS platform free tiers are often limited to small account volumes or single-user access.

- **CXM-Tool is the only open-source option**, but it is **early-stage with SQLite and no multi-tenancy** . **For teams wanting to build custom CS tooling, it is a reference implementation; for production CS operations, commercial platforms are required.**

- Self-hosted open-source alternatives **do not exist for production use**. If data sovereignty is a hard requirement, you will need to build custom software with CRM integrations, health scoring, and playbook automation—a significant undertaking.



---



**Made for CS leaders, account managers, and organizations building transparent customer success solutions.**

Let's make Customer Success Management more open, data-driven, and retention-friendly.
