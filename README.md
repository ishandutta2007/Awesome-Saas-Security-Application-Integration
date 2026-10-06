# Awesome-Saas-Security-Application-Integration

## Top SaaS Security & Application Integration Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on SSPM, SaaS-to-SaaS Integration & Open-Source Security Automation*  

**Last updated: October 2026**



This repository tracks notable **commercial SaaS security platforms** and **open-source projects** that secure and integrate SaaS applications — discovering shadow IT, managing app-to-app permissions, enforcing security posture, and automating identity lifecycle across cloud applications.



**Examples** include AWS AppFabric, Okta Workflows, DoControl, AppOmni, Wing Security, Obsidian Security, Adaptive Shield, Grip Security, Torii, and BetterCloud (the category leaders).



**Open-source emphasis**: SaaS security is an emerging open-source domain. **Keycloak** and **Authentik** provide identity foundation for SaaS SSO, **DefectDojo** aggregates security findings, **OpenPolicyAgent** enforces policy-as-code, and **N8n** enables SaaS-to-SaaS automation. **Wazuh** and **CloudQuery** provide security posture visibility across cloud and SaaS. **Casbin** handles authorization for multi-tenant applications. This section is heavily expanded.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms

> **Market Overview**: The SaaS Security Posture Management (SSPM) and SaaS Application Integration sector is estimated at **$1.5 Billion to $2.5 Billion** (projected to reach $8+ Billion by 2030 at ~30% CAGR). The sector is currently **highly fragmented**, featuring active competition between cloud hyperscalers (AWS AppFabric), IAM providers (Okta), specialized SSPM startups (Obsidian, AppOmni, Grip), and cybersecurity platform consolidators (CrowdStrike acquiring Adaptive Shield).

| Platform / Vendor | Core Focus & Description | Company Size (Valuation / Revenue) | Starting Tier Pricing | Free Tier / Trial Limit |
| :--- | :--- | :--- | :--- | :--- |
| **[AWS AppFabric](https://aws.amazon.com/appfabric/)** | **AWS SaaS application integration service** — connects SaaS apps for unified security & productivity insights, normalizing audit logs into OCSF format. | **$150B+ AWS Annual Revenue** ($2.0T+ Amazon Market Cap) | **$3.00 / user / month** (base security features across connected SaaS apps, up to 30 apps) | **First 2 connected apps free** for the first 30 days |
| **[Okta Workflows](https://www.okta.com/)** | **Identity automation platform** — no-code workflows for SaaS lifecycle management and security orchestration. | **$3.2B Annual Revenue** ($14B Market Cap) | **$6.00 / user / month** (Okta Starter Suite, includes 5 active workflows) | **30-day free trial** for Workforce Identity suite; free developer plan |
| **[Obsidian Security](https://www.obsidiansecurity.com/)** | **SaaS security posture management** — continuous threat detection, identity security, and compliance enforcement. | **$1.1B Valuation** (Series D, Aug 2026; ~$25M ARR) | **$6.00 / user / month** ($72/user/year base tier) | **Forever-free tier** for up to 1,000 users (app discovery & spear-phishing detection) |
| **[Adaptive Shield](https://www.adaptiveshield.com/)** | **SaaS security posture management** — misconfiguration detection, identity governance, and automated remediation (acquired by CrowdStrike). | **$300M Acquisition Valuation** ($80B+ CrowdStrike Market Cap; ~$14M ARR) | **$15,000 / year** (~$5.00/user/month base subscription tier) | **14-day guided free risk assessment** trial (scans up to 5 SaaS apps) |
| **[BetterCloud](https://www.bettercloud.com/)** | **SaaS operations & security platform** — multi-SaaS management, data loss prevention, and lifecycle automation. | **$150M+ Estimated Valuation** ($67M ARR; acquired by Vista Equity) | **$55.00 / month** (or $3.00/user/month for Google Workspace module) | **21-day free trial** (covers File Governance & SaaS user management modules) |
| **[AppOmni](https://appomni.com/)** | **SaaS security posture management (SSPM)** — continuous configuration assessment and data access control. | **$123M Total Funding** ($35.7M ARR; Series C led by Thoma Bravo) | **$7,500 / year** AWS Marketplace starting tier (~$6.00/user/month) | **14-day free trial** / interactive demo assessment via AWS Marketplace |
| **[DoControl](https://www.docontrol.io/)** | **SaaS data security platform** — data access governance, threat detection, and automated remediation workflows. | **$100M Estimated Valuation** ($10.8M ARR; $43.4M total funding) | **$12,000 / year** base tier (~$4.00/user/month starting plan) | **Free Self-Service SaaS Risk Assessment** (scans M365/Google exposure, unlimited time) |
| **[Torii](https://www.toriihq.com/)** | **SaaS management platform** — automated shadow IT discovery, spend optimization, and app access governance. | **$65M Total Funding** ($15M ARR; Series B led by Tiger Global) | **$3.50 / user / month** ($5,000/year base tier) | **14-day free trial** (full access to SaaS discovery, workflows & spend analytics) |
| **[Grip Security](https://www.grip.security/)** | **SaaS identity & access management** — identity-first SaaS discovery, shadow AI monitoring, and access governance. | **$66M Total Funding** ($10M ARR; Series B led by Third Point Ventures) | **$8.00 / user / month** (SMB starting tier for up to 1,000 employees) | **Free Shadow AI & SaaS Risk Assessment** (custom exposure report & 1-week scan) |
| **[Wing Security](https://www.wing.security/)** | **SaaS security platform** — shadow IT discovery, SSPM, app-to-app permission governance, and threat remediation. | **$26M Total Funding** ($3.7M ARR; Series A led by GGV Capital) | **$4.00 / user / month** (Professional starting tier) | **Forever-free tier** ("Free Discovery" plan with unlimited user & app discovery) |



## Open-Source GitHub Projects



### Identity & Access Management



- **[Keycloak](https://github.com/keycloak/keycloak)**  

  **The leading open-source identity provider**, Apache-2.0 licensed with **36,000+ GitHub stars** . **SSO, MFA, identity brokering, and user federation** . **The identity foundation for SaaS SSO** — supports OAuth 2.0, OIDC, and SAML . **Best for SaaS identity integration** .



- **[Authentik](https://github.com/goauthentik/authentik)**  

  **Flexible open-source identity provider**, MIT/GPL licensed with **10,000+ GitHub stars** . **OAuth2, SAML, LDAP, and proxy support** . **Flow-based authentication customization** . **Best for SaaS SSO with customization** .



- **[Casbin](https://github.com/casbin/casbin)**  

  **Open-source authorization library**, Apache-2.0 licensed with **17,000+ GitHub stars** . **ACL, RBAC, and ABAC** for multi-tenant SaaS . **Best for SaaS authorization** .



- **[Authelia](https://github.com/authelia/authelia)**  

  **Open-source authentication and authorization server**, Apache-2.0 licensed with **20,000+ GitHub stars** . **2FA, SSO, and forward-auth for reverse proxies** . **Best for securing SaaS access** .



### Security Posture & Compliance



- **[DefectDojo](https://github.com/DefectDojo/django-DefectDojo)**  

  **Open-source vulnerability management**, Apache-2.0 licensed . **Aggregates findings from 200+ security tools** . **Best for SaaS security findings aggregation** .



- **[Wazuh](https://github.com/wazuh/wazuh)**  

  **Open-source security platform with SIEM and XDR**, GPLv2 licensed with **16,646+ GitHub stars** . **Compliance modules for PCI-DSS, NIST 800-53, and GDPR** . **Best for security monitoring and compliance** .



- **[CloudQuery](https://github.com/cloudquery/cloudquery)**  

  **Open-source cloud asset inventory**, MPL-2.0 licensed with **6,000+ GitHub stars** . **Extracts, transforms, and loads cloud configuration** . **Best for SaaS and cloud asset visibility** .



- **[Open Policy Agent (OPA)](https://github.com/open-policy-agent/opa)**  

  **General-purpose policy engine**, Apache-2.0 licensed with **10,000+ GitHub stars** . **Unified policy enforcement across SaaS, Kubernetes, and CI/CD** . **Best for policy-as-code** .



- **[Steampipe](https://github.com/turbot/steampipe)**  

  **Zero-ETL cloud API querying with SQL**, AGPL-3.0 licensed with **7,000+ GitHub stars** . **Query SaaS and cloud resources with SQL** . **Best for SaaS security posture queries** .



### Integration & Automation



- **[n8n](https://github.com/n8n-io/n8n)**  

  **Workflow automation platform**, Sustainable Use License with **100,000+ GitHub stars** . **400+ integrations for SaaS automation** . **Best for SaaS-to-SaaS workflow automation** .



- **[Activepieces](https://github.com/activepieces/activepieces)**  

  **MIT-licensed AI-native automation platform**, MIT licensed with **23,000+ GitHub stars** . **200+ integrations with MCP server support** . **Best for open-source SaaS automation** .



- **[Windmill](https://github.com/windmill-labs/windmill)**  

  **Developer-first automation platform**, AGPLv3 licensed with **10,000+ GitHub stars** . **Scripts in Python, TypeScript, Go, Bash, or SQL** . **Best for developer-centric SaaS automation** .



- **[Node-RED](https://github.com/node-red/node-red)**  

  **Flow-based programming for event-driven applications**, Apache-2.0 licensed with **20,000+ GitHub stars** . **Visual wiring of SaaS APIs and services** . **Best for visual SaaS integration** .



- **[Kestra](https://github.com/kestra-io/kestra)**  

  **Declarative orchestration platform**, Apache-2.0 licensed with **10,000+ GitHub stars** . **YAML-based workflows with 500+ plugins** . **Best for declarative SaaS orchestration** .



### Audit & Log Management



- **[OpenSearch](https://github.com/opensearch-project/OpenSearch)**  

  **Open-source search and analytics suite**, Apache-2.0 licensed with **10,000+ GitHub stars** . **Log analytics and security analytics** . **Best for SaaS audit log analysis** .



- **[Grafana Loki](https://github.com/grafana/loki)**  

  **Horizontally scalable log aggregation**, AGPL-3.0 licensed with **24,000+ GitHub stars** . **Cost-effective log storage** . **Best for SaaS audit log aggregation** .



- **[Graylog](https://github.com/Graylog2/graylog2-server)**  

  **Centralized log management**, SSPL licensed . **Search, streams, and alerting** . **Best for SaaS log management** .



### Additional Strong Open-Source Options



- **Zitadel** — Identity infrastructure with multi-tenancy .

- **Ory** — Open-source identity infrastructure .

- **Permify** — Open-source authorization service .

- **Oso** — Open-source authorization framework .

- **Cerbos** — Policy-as-code authorization .

- **OpenFGA** — Fine-grained authorization .

- **SpiceDB** — Authorization database .

- **Apache Airflow** — Workflow orchestration .

- **Dagster** — Data orchestration .

- **Prefect** — Workflow orchestration .



**Frameworks for building custom SaaS security and integration solutions**: Combine **Keycloak** or **Authentik** for SaaS SSO and identity . Use **OPA** or **Casbin** for policy-as-code and authorization . Deploy **DefectDojo** for security findings aggregation . Integrate **CloudQuery** or **Steampipe** for SaaS asset visibility . Use **n8n**, **Activepieces**, or **Windmill** for SaaS-to-SaaS automation . Deploy **OpenSearch** or **Loki** for audit log analysis . Note that true enterprise SSPM with discovery, posture assessment, and automated remediation (AppOmni, Obsidian, Adaptive Shield) remains primarily commercial territory; open-source stacks provide strong identity, authorization, policy, and automation foundations that require integration for complete SaaS security posture management.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- SaaS security platforms access sensitive application data and configurations. Self-hosted solutions require proper security hardening, access controls, and compliance with data privacy regulations.

- **SaaS security requires continuous monitoring** — misconfigurations, shadow IT, and permission sprawl are ongoing risks. Open-source tools provide visibility but require integration and tuning .

- **License considerations**: n8n uses Sustainable Use License (fair-code, not OSI), Activepieces uses MIT, Windmill uses AGPLv3, and Keycloak uses Apache-2.0. Verify licensing against your use case before committing .

- **Open-source SSPM requires operational expertise** — discovery, posture assessment, and remediation workflows require integration across multiple tools. Commercial platforms provide unified SSPM with vendor support.

- The open-source ecosystem provides strong identity, authorization, policy, and automation foundations, but **unified SSPM with discovery, posture assessment, and automated remediation** remain primarily commercial offerings.



---



**Made for security engineers, SaaS administrators, and organizations seeking SaaS security sovereignty.**  

Let's make SaaS security and application integration more open, transparent, and automated.
