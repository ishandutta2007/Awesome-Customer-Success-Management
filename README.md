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
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Gainsight](https://www.gainsight.com/)**
  **Enterprise customer success platform** with health scoring, playbooks, and AI (Atlas). **Pricing**: **Quote-only** on both Customer Success tiers; **no self-serve trial**—the free trial on the shared pricing page belongs to Product Experience, not Customer Success . Essentials capped at **10 full users and 100 customers per user** . **Free tier**: None. **Best for**: large enterprises wanting the most mature CS platform—**trade-off**: ~5 month average implementation; cannot evaluate without sales engagement .

- **[ChurnZero](https://churnzero.com/)**
  **Customer success platform** with real-time health scoring and automation. **Pricing**: **Starting at $12,000/year** per Software Advice . **Free tier**: **No free version**; free trial listed . **Best for**: SMBs and mid-market teams wanting real-time churn signals—**trade-off**: limited public pricing detail beyond entry point.

- **[Totango](https://www.totango.com/)**
  **Customer success and retention platform**. **Pricing**: **Not provided by vendor**; **no free version and no free trial** per Software Advice . **Free tier**: None. **Best for**: enterprises wanting a mature CS platform—**trade-off**: no trial; quote-only evaluation.

- **[Catalyst](https://catalyst.io/)** (Totango)
  **Customer growth platform** from Totango. **Pricing**: **Quote-only**; Catalyst, Totango, and Unison AI are **separately subscribed products** . **No free trial or self-serve signup**; ~2 month average implementation . **Free tier**: None. **Best for**: mid-market teams wanting Totango's methodology in a lighter package—**trade-off**: modular costs stack; no self-serve evaluation .

- **[Planhat](https://www.planhat.com/)**
  **Customer success platform** with configurable workflows. **Pricing**: Free version and free trial listed per Software Advice . **Free tier**: Yes, listed. **Best for**: teams wanting flexible workflow configuration—**trade-off**: verify free tier scope directly.

- **[Vitally](https://www.vitally.io/)**
  **Customer success platform** with AI copilot. **Pricing**: **Starting at $299/month**; **no free version**; free trial available . All three tiers require sales engagement; trial sandbox accessed through sales motion . **Free tier**: None. **Best for**: B2B SaaS teams wanting a modern CS platform with AI—**trade-off**: quote-only above entry tier; no self-serve trial .

- **[ClientSuccess](https://www.clientsuccess.com/)**
  **Customer success platform** with onboarding and health scoring. **Pricing**: **Starting at $15,000/year**; **no free version**; free trial available . **Free tier**: None. **Best for**: mid-market to enterprise teams wanting structured CS workflows—**trade-off**: $15K annual minimum.

- **[Custify](https://www.custify.com/)**
  **Mid-market customer success platform**. **Pricing**: **Custom/quote-only**; **no published tiers or starting prices**; **no self-serve trial**—demo-required sales motion . **Free tier**: None. **Best for**: mid-market SaaS teams wanting CS automation—**trade-off**: cannot qualify budget without sales call .

- **[SmartKarrot](https://www.smartkarrot.com/)**
  **Customer success platform** with product analytics. **Pricing**: **Starting at $15,000/year** per Software Advice . **Free tier**: Free trial and free version listed . **Best for**: teams wanting CS plus product engagement—**trade-off**: verify free version scope.

- **[HubSpot Customer Success Tools](https://www.hubspot.com/)**
  **CS tools within HubSpot** Service Hub. **Pricing**: Included with Service Hub Professional ($100/seat/month) and Enterprise. **Free tier**: Limited. **Best for**: HubSpot CRM users wanting CS workflows without a separate platform—**trade-off**: not a dedicated CS platform; health scoring limited.

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
