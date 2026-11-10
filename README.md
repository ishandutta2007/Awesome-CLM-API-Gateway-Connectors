# Awesome-CLM-API-Gateway-Connectors

## Top CLM API Gateway & Connectors Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Contract Lifecycle Integration, API Orchestration & Enterprise Connectivity*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **CLM API Gateway & Connectors**. These tools help organizations integrate contract lifecycle management systems with CRM, ERP, procurement, and other enterprise applications—enabling automated contract data flow, status synchronization, and workflow orchestration across systems without custom point-to-point code.

**Examples** include Icertis API Integration Gateway, MuleSoft Anypoint, Workato, Boomi, Zapier, Celigo, Tray.io, Microsoft Power Automate, SnapLogic, and Jitterbit (the category leaders).

**Open-source emphasis**: This section highlights every major active project for self-hosted API gateways, open-source integration platforms, and community-maintained connector frameworks—ideal for integration engineers, platform teams, and developers building transparent, vendor-neutral CLM connectivity without per-task or per-vCore cloud billing surprises.

Contributions welcome! Open an PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

| Product | Description | Pricing (Starting) | Free Tier / Trial Limits |
|---------|-------------|-------------------|--------------------------|
| **[Icertis API Integration Gateway](https://www.icertis.com/)** | Native REST API gateway for the Icertis Contract Intelligence platform. Supports OAuth 2.0 (recommended), ICM AuthToken (testing only), and Client Certificate authentication. Region-specific gateway URLs (e.g., `api-<region>.icertis.com`) with product-key headers for API access. Integrates with customer IdPs (Azure, Okta, Ping) for SSO. Admin console requires APIM Dev Portal User role [citation:1][citation:11]. | Quote-only (enterprise CLM subscription required) | No free tier; demo via sales |
| **[MuleSoft Anypoint Platform](https://www.mulesoft.com/)** | Enterprise iPaaS and API management platform with CLM connector capabilities for Icertis, DocuSign, and other contract systems. vCore-based pricing with typical contract minimums in the mid-five to low-six figures annually. Salesforce integration tightly coupled; implementation services typically 20–40% of first-year software cost [citation:2]. | Enterprise quote-only (typically $68,000+ annual) | 30-day free trial available; no free tier |
| **[Workato](https://www.workato.com/)** | Low-code automation platform with CLM connectors and recipe templates. Credit-based self-service pricing (no sales call required): Pro starts at $75/month for 2,500 credits, scaling to $1,275/month for 50,000 credits. Credits cover tasks, API calls, rows processed, and Genie actions. No rollover—unused Pro credits expire monthly [citation:3][citation:12]. | $75/month (2,500 credits) | **Workato Free**: 50,000 one-time credits (never expire), same platform capabilities; no recurring monthly credits |
| **[Boomi](https://www.boomi.com/)** | Cloud-native iPaaS with CLM connectors and API management (sold separately in Professional to Enterprise Plus editions). Atom-based subscription pricing; typical entry point mid-five figures annually. API Control Plane (launched July 2024) manages gateways from eight vendors. Includes AI Starter Pack (6 agents) in every Integration edition [citation:4][citation:13]. | Quote-only (typical entry: mid-five figures annually) | Free trial via sales; Pay-As-You-Go limited to active trial users |
| **[Zapier](https://zapier.com/)** | No-code automation connecting 7,000+ apps including CLM tools (DocuSign, PandaDoc, Concord). Free tier limited to two-step Zaps; Professional unlocks multi-step workflows, filters, and paths. 14-day Pro trial with 1,000 tasks on new accounts. | Professional: $19.99/month (750 tasks) | **Free forever**: 100 tasks/month, 2-step Zaps only, 15-minute polling; 14-day Pro trial: 1,000 tasks |
| **[Celigo](https://www.celigo.com/)** | iPaaS with strong NetSuite and e-commerce focus, plus CLM connectors. Flow-based pricing; median contract ~$14,787/year. Pre-built apps (e.g., Salesforce connector) priced separately at $300–$1,000/month. 30-day free trial with unlimited endpoints/flows/features; free plan thereafter with 2 endpoints, 1 flow, no SSO or on-prem agent [citation:5][citation:14]. | Flow-based quote (median ~$14,787/year) | **Free plan**: 2 endpoints, 1 flow, production env only, no SSO/API tokens/on-prem agent (no expiration); 30-day trial: unlimited everything |
| **[Tray.io (Tray.ai)](https://tray.ai/)** | Enterprise low-code iPaaS with 700+ connectors and CLM integration capabilities. Rebranded to Tray.ai in 2024 with AI agent layer (Merlin Agent Builder). Pricing not published—Pro/Team/Enterprise tiers require sales contact. Agent Gateway for MCP is a paid add-on [citation:15]. | Quote-only (Pro tier reported from ~$500/month) | Free trial available via sales; no self-serve free tier |
| **[Microsoft Power Automate](https://powerautomate.microsoft.com/)** | Workflow automation with CLM connectors (DocuSign, Adobe Sign, SharePoint-based contracts). Pay-as-you-go: $0.60 per attended flow execution, $3.00 per unattended flow execution. Per-user and per-flow plans also available for predictable volume [citation:7]. | $0.60/execution (pay-as-you-go attended); per-user plans from ~$15/user/month | 90-day free trial of Power Automate Premium; free plan limited to standard connectors (no premium CLM connectors) |
| **[SnapLogic](https://www.snaplogic.com/)** | Enterprise iPaaS with CLM and enterprise app connectors. Task-based pricing; typical contracts: small deployments $30K–$75K/year, mid-market $75K–$175K/year, enterprise $175K–$400K+/year. Implementation costs 20–50% of first-year subscription [citation:8]. | Quote-only (typical: $30,000+/year) | 30-day free trial available |
| **[Jitterbit](https://www.jitterbit.com/)** | Enterprise iPaaS with "Unlimited" pricing model—unlimited endpoints, trading partners, APIs, and AI agents at one locked-in multi-year price. Harmony platform covers iPaaS, EDI, API Manager, and App Builder. Eliminates per-connector or per-task "success tax" [citation:9]. | Quote-only (Unlimited multi-year contract) | Free trial available; no free tier |

## Open-Source GitHub Projects

| Project | Star Badge | Description |
|---------|------------|-------------|
| **[Kong Gateway](https://github.com/Kong/kong)** | [![Stars](https://img.shields.io/github/stars/Kong/kong?style=social&color=white)](https://github.com/Kong/kong/stargazers) | The most widely deployed open-source API gateway. Self-hosted enterprise pricing is custom; no permanent free Konnect tier. Enterprise adds RBAC, SSO, audit logging, and MCP proxy. Ideal for teams wanting open-source gateway with enterprise upgrade path [citation:10]. |
| **[Tyk Gateway](https://github.com/TykTechnologies/tyk)** | [![Stars](https://img.shields.io/github/stars/TykTechnologies/tyk?style=social&color=white)](https://github.com/TykTechnologies/tyk/stargazers) | Open-source API gateway (MPL-2.0 for core). Options: free OSS gateway, Self-Managed, Tyk Cloud (hosted control plane with your or Tyk's data planes). Developer Portal licensed separately. MCP Gateway implements 2025-11-25 MCP revision. AI Studio has AGPL-3.0 Community edition [citation:10]. |
| **[Gravitee API Management](https://github.com/gravitee-io/gravitee-api-management)** | [![Stars](https://img.shields.io/github/stars/gravitee-io/gravitee-api-management?style=social&color=white)](https://github.com/gravitee-io/gravitee-api-management/stargazers) | Apache-2.0 open-core API management with HTTP and event-driven APIs (Kafka, MQTT, webhooks) under one gateway. Planet plan at $2,500/month for one production gateway. AI features (LLM, MCP, A2A proxies) are Enterprise-only add-ons [citation:10]. |
| **[WSO2 API Manager](https://github.com/wso2/product-apim)** | [![Stars](https://img.shields.io/github/stars/wso2/product-apim?style=social&color=white)](https://github.com/wso2/product-apim/stargazers) | Fully open-source (Apache-2.0) API management suite covering gateway, publisher, and developer portal. Self-hosted free to run; support/updates via subscription. SaaS: Growth from $119/month for up to 10 managed interfaces; 30-day trial [citation:10]. |

### Additional Strong Open-Source Options

| Project | Star Badge | Description |
|---------|------------|-------------|
| **[Apache APISIX](https://github.com/apache/apisix)** | [![Stars](https://img.shields.io/github/stars/apache/apisix?style=social&color=white)](https://github.com/apache/apisix/stargazers) | High-performance cloud-native API gateway with rich plugin ecosystem (auth, rate-limiting, observability). Apache 2.0 licensed; suitable for CLM API routing and transformation. |
| **[Krakend](https://github.com/krakend/krakend-ce)** | [![Stars](https://img.shields.io/github/stars/krakend/krakend-ce?style=social&color=white)](https://github.com/krakend/krakend-ce/stargazers) | Ultra-fast API gateway written in Go; stateless, with declarative configuration. Useful for aggregating CLM APIs and backend services. |
| **[Apache Camel](https://github.com/apache/camel)** | [![Stars](https://img.shields.io/github/stars/apache/camel?style=social&color=white)](https://github.com/apache/camel/stargazers) | Integration framework with 300+ connectors (including REST, JMS, file, and cloud services). Can be used to build custom CLM integration flows as an alternative to commercial iPaaS. |

**Frameworks for building custom systems**: Combine **Kong Gateway** or **Apache APISIX** for API routing and policy enforcement, **Apache Camel** for integration flow orchestration, and **WSO2 API Manager** for developer portal and lifecycle management—creating a fully self-hosted CLM API gateway stack with no per-task pricing.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- CLM API gateways handle contract data and authentication credentials; enforce OAuth 2.0, least-privilege scopes, and audit logging for all API access.
- iPaaS pricing models (credits, tasks, vCores, flows) vary dramatically; model total cost based on actual transaction volume and connector requirements before committing to multi-year contracts.

---

**Made for integration engineers, CLM platform teams, DevOps architects, and developers building contract data pipelines.**  
Let's make CLM integration more open, observable, and cost-transparent.
