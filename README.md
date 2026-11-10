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
- [Sector Overview & Market Dynamics](#sector-overview--market-dynamics)
- [SaaS/Hosted Platforms](#saashosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## Sector Overview & Market Dynamics

The Contract Lifecycle Management (CLM) software market is valued at approximately **$2.5B–$3.3B** and projected to exceed **$7B–$11B** by the early 2030s (12%–14% CAGR), while the horizontal Integration Platform as a Service (iPaaS) market is valued at **$11B–$19B** growing at 24%–30% CAGR. The sector is **moderately to highly fragmented** rather than winner-take-all; despite heavyweight incumbents (MuleSoft/Salesforce, Microsoft, Boomi, Workato), continuous proliferation of AI-native CLMs and specialized API orchestration tools prevents monopolization, driving enterprises toward composable, vendor-neutral integration gateways.

## SaaS/Hosted Platforms

| Product | Company Scale (Valuation / Revenue) | Starting Tier Pricing | Free Tier / Trial Limits | Description |
|---|---|---|---|---|
| **[Microsoft Power Automate](https://powerautomate.microsoft.com/)** | ~$3.1T Market Cap (Parent Microsoft) / $245B+ Annual Revenue | **$15/user/month** (Power Automate Premium) or **$0.60/execution** (pay-as-you-go attended) | **90-day free trial** of Power Automate Premium with full connector capabilities; permanent free plan limited to basic desktop/standard cloud connectors (excludes premium CLM connectors) | Workflow automation with pre-built CLM connectors (DocuSign, Adobe Acrobat Sign, SharePoint). |
| **[MuleSoft Anypoint Platform](https://www.mulesoft.com/)** | ~$300B+ Market Cap (Parent Salesforce) / $6.5B acquisition valuation (~$1.5B+ ARR) | **$2,000/month** ($24,000 billed annually for entry tier) | **30-day free trial** with CloudHub worker allocation (limited to 0.1 vCore testing runtime); no perpetual free tier | Enterprise iPaaS and API management with certified CLM connectors for Icertis, DocuSign, and Conga. |
| **[Workato](https://www.workato.com/)** | **$5.7B** Valuation (Series E) / ~$150M ARR | **$75/month** (Pro plan, includes 2,500 credits; additional credits at $0.03/credit) | **Workato Free plan**: 50,000 one-time credits (never expire), full access to 1,000+ connectors; no recurring monthly refill | Low-code enterprise automation platform with pre-built CLM connectors, recipes, and API orchestration. |
| **[Zapier](https://zapier.com/)** | **$5.0B** Valuation / ~$350M+ ARR | **$19.99/month** (Professional plan billed annually for 750 tasks/mo) | **Free forever plan**: 100 tasks/month, 2-step single-trigger Zaps, 15-minute polling interval; **14-day Pro trial** with 1,000 tasks | No-code automation connecting 7,000+ web applications including CLM tools (DocuSign, PandaDoc, Concord). |
| **[Icertis API Integration Gateway](https://www.icertis.com/)** | **$5.0B** Valuation / ~$320M+ ARR | **$100,000/year** (typical enterprise baseline subscription; ~$150–$350/user/month equivalent) | **No self-service free tier or automated trial**; custom guided sandbox demos provided upon qualified sales evaluation | Dedicated REST API gateway for the Icertis Contract Intelligence platform with OAuth 2.0 and SSO support. |
| **[Boomi](https://www.boomi.com/)** | **$4.0B** Acquisition Valuation (TPG & Francisco Partners) / ~$500M+ Revenue | **$99/month** (Pay-As-You-Go tier + ~$0.05/message) or **$20,000/year** (Professional edition) | **30-day free trial** of Boomi Enterprise Platform with access to integration builder and core connectors; no permanent free tier | Cloud-native iPaaS with API Control Plane managing multi-vendor gateways and AI-assisted data routing. |
| **[SnapLogic](https://www.snaplogic.com/)** | **$1.0B** Valuation (Unicorn status) / ~$150M+ Revenue | **$10,000/year** (Developer/Starter package baseline; typical mid-market $86,000+/year) | **30-day free trial** for specific tools (Fast Data Loader); platform evaluation available via guided sales PoC | Generative-integration iPaaS with Snaps for CLM, ERP, CRM, and API management. |
| **[Tray.io (Tray.ai)](https://tray.ai/)** | **$600M** Valuation / ~$71M Revenue | **$50/month** (base platform entry; typical production Pro starts ~$500/month) | **30-day free trial** with up to **1,000,000 tasks** and full connector library access; no permanent free tier | Enterprise low-code iPaaS and Merlin AI Agent builder with 700+ connectors and MCP gateway add-ons. |
| **[Jitterbit](https://www.jitterbit.com/)** | ~$200M Valuation (KKR backed) / ~$85M Revenue | **$1,000/month** ($12,000/year annual contract for Standard tier) | **14-day free trial** for non-production evaluation with manual project export; no permanent free tier | Enterprise iPaaS offering an "Unlimited" connection model across iPaaS, API Manager, EDI, and App Builder. |
| **[Celigo](https://www.celigo.com/)** | ~$150M Valuation / ~$90M ARR | **$600/month** ($7,200/year starting flow tier; median enterprise contract ~$14,787/year) | **Free forever plan**: 2 endpoints, 1 active flow in production; **30-day free trial** with unlimited endpoints and flows | iPaaS optimized for business application and CLM integration with pre-built connectors and sync templates. |

## Open-Source GitHub Projects

Curated open-source API gateways, integration orchestration frameworks, and workflow automation platforms suitable for self-hosted CLM integration pipelines, sorted descending by GitHub stargazers:

| Project | Star Badge | Description |
|---|---|---|
| **[n8n](https://github.com/n8n-io/n8n)** | [![Stars](https://img.shields.io/github/stars/n8n-io/n8n?style=social&color=white)](https://github.com/n8n-io/n8n/stargazers) | Fair-code workflow automation tool with 400+ native integrations, webhook routing, and built-in AI agents. Ideal for self-hosting complete CLM event-driven pipelines. |
| **[Traefik](https://github.com/traefik/traefik)** | [![Stars](https://img.shields.io/github/stars/traefik/traefik?style=social&color=white)](https://github.com/traefik/traefik/stargazers) | Modern HTTP reverse proxy and cloud-native API gateway with automatic discovery, dynamic TLS certificate handling, and middleware for microservice-backed CLM architectures. |
| **[Kong Gateway](https://github.com/Kong/kong)** | [![Stars](https://img.shields.io/github/stars/Kong/kong?style=social&color=white)](https://github.com/Kong/kong/stargazers) | The world's most widely adopted cloud-native API gateway (OpenResty/Nginx engine). Provides sub-millisecond routing, rate-limiting, OAuth2 token validation, and enterprise plugin extensibility for CLM APIs. |
| **[Activepieces](https://github.com/activepieces/activepieces)** | [![Stars](https://img.shields.io/github/stars/activepieces/activepieces?style=social&color=white)](https://github.com/activepieces/activepieces/stargazers) | Open-source (MIT), self-hostable no-code business automation engine. Features modern TypeScript-based pieces/connectors, webhook listeners, and AI actions designed as an open Zapier alternative. |
| **[Airbyte](https://github.com/airbytehq/airbyte)** | [![Stars](https://img.shields.io/github/stars/airbytehq/airbyte?style=social&color=white)](https://github.com/airbytehq/airbyte/stargazers) | Leading open-source ELT data integration platform with 350+ pre-built connectors. Perfect for scheduled data ingestion and bulk synchronization of contract metadata into analytical data warehouses. |
| **[Apache APISIX](https://github.com/apache/apisix)** | [![Stars](https://img.shields.io/github/stars/apache/apisix?style=social&color=white)](https://github.com/apache/apisix/stargazers) | Ultra-high-performance cloud-native API gateway built on Nginx + LuaJIT and etcd. Offers dynamic routing, canary releases, rate limiting, and mTLS security for enterprise contract gateways. |
| **[Tyk Gateway](https://github.com/TykTechnologies/tyk)** | [![Stars](https://img.shields.io/github/stars/TykTechnologies/tyk?style=social&color=white)](https://github.com/TykTechnologies/tyk/stargazers) | Fast, lightweight open-source API gateway written in Go (MPL-2.0 core). Supports REST, GraphQL, and gRPC with built-in quota management, OAuth2 authentication, and developer portal options. |
| **[Apache Camel](https://github.com/apache/camel)** | [![Stars](https://img.shields.io/github/stars/apache/camel?style=social&color=white)](https://github.com/apache/camel/stargazers) | Versatile enterprise integration pattern (EIP) framework with 300+ native connectors. Excellent for defining complex multi-step mediation, data transformation, and event routing between CLM systems. |
| **[KrakenD](https://github.com/krakend/krakend-ce)** | [![Stars](https://img.shields.io/github/stars/krakend/krakend-ce?style=social&color=white)](https://github.com/krakend/krakend-ce/stargazers) | Ultra-fast, stateless open-source API gateway written in Go. Ideal for aggregation, payload transformation, and filtering across disparate contract lifecycle endpoints without external database dependencies. |
| **[WSO2 API Manager](https://github.com/wso2/product-apim)** | [![Stars](https://img.shields.io/github/stars/wso2/product-apim?style=social&color=white)](https://github.com/wso2/product-apim/stargazers) | Complete Apache-2.0 open-source API management platform combining gateway, developer portal, publisher, and key manager. Supports full API lifecycle governance for enterprise contract APIs. |
| **[Gravitee API Management](https://github.com/gravitee-io/gravitee-api-management)** | [![Stars](https://img.shields.io/github/stars/gravitee-io/gravitee-api-management?style=social&color=white)](https://github.com/gravitee-io/gravitee-api-management/stargazers) | Flexible open-core API management platform with native support for both synchronous REST and asynchronous event-driven APIs (Kafka, MQTT, WebSockets) under a unified policy gateway. |

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
