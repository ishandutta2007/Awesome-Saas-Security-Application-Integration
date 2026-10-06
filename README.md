# Awesome-Saas-Security-Application-Integration

# Top SaaS Security & Application Integration Ecosystem

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

- **[AWS AppFabric](https://aws.amazon.com/appfabric/)**  
  **AWS's SaaS application integration service** — connects SaaS apps for unified security and productivity insights . **Normalizes audit logs** from SaaS applications into OCSF format . **Best for AWS-centric SaaS security** .

- **[Okta Workflows](https://www.okta.com/)**  
  **Identity automation platform** — no-code workflows for SaaS lifecycle management . **Best for Okta identity users** .

- **[DoControl](https://www.docontrol.io/)**  
  **SaaS security platform** — data access governance, threat detection, and automated remediation . **Best for SaaS data protection** .

- **[AppOmni](https://appomni.com/)**  
  **SaaS security posture management (SSPM)** — continuous monitoring and configuration assessment . **Best for enterprise SaaS security** .

- **[Wing Security](https://www.wing.security/)**  
  **SaaS security platform** — discovery, posture management, and shadow IT detection . **Best for SaaS security automation** .

- **[Obsidian Security](https://www.obsidiansecurity.com/)**  
  **SaaS security posture management** — threat detection and compliance for SaaS . **Best for enterprise SaaS security** .

- **[Adaptive Shield](https://www.adaptiveshield.com/)**  
  **SaaS security posture management** — misconfiguration detection and remediation . **Best for SSPM** .

- **[Grip Security](https://www.grip.security/)**  
  **SaaS identity and access management** — discovery and governance for SaaS apps . **Best for SaaS identity governance** .

- **[Torii](https://www.toriihq.com/)**  
  **SaaS management platform** — discovery, management, and optimization of SaaS applications . **Best for SaaS spend and security** .

- **[BetterCloud](https://www.bettercloud.com/)**  
  **SaaS operations platform** — automation and security for SaaS applications . **Best for SaaS workflow automation** .

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
