# GitHub Enterprise (github-enterprise)

GitHub Enterprise is GitHub's offering for organizations that need advanced security, compliance, identity, and scale on top of the GitHub platform. It ships in two flavors: GitHub Enterprise Cloud, a hosted multi-tenant service on api.github.com with enterprise-managed users and SAML SSO; and GitHub Enterprise Server (GHES), a self-hosted appliance with the same REST and GraphQL APIs served from a customer's domain at /api/v3 and /api/graphql. Both expose the full GitHub REST API for repositories, issues, pull requests, actions, packages, advanced security, audit log, SCIM, and admin operations, authenticated with personal access tokens or GitHub App tokens.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/github-enterprise/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/github-enterprise/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Source Control
- DevOps
- CI/CD
- Code Hosting
- Enterprise
- Self-Hosted
- SAML SSO
- SCIM
- Advanced Security

## Timestamps

- **Created:** 2026-05-11
- **Modified:** 2026-05-11

## APIs

### GitHub Enterprise Cloud REST API

Hosted GitHub Enterprise Cloud REST API. Provides full access to repositories, issues, pull requests, GitHub Actions, packages, code scanning, secret scanning, Dependabot, audit log, SCIM provisioning, and enterprise admin endpoints. Authentication via fine-grained personal access tokens, GitHub App installation tokens, or OAuth.

- **Human URL:** [https://docs.github.com/en/enterprise-cloud@latest/rest](https://docs.github.com/en/enterprise-cloud@latest/rest)
- **Base URL:** `https://api.github.com`

#### Tags

- REST
- Source Control
- Enterprise Cloud
- SCIM
- Audit Log

#### Properties

- [Documentation](https://docs.github.com/en/enterprise-cloud@latest/rest)
- [OpenAPI](https://github.com/github/rest-api-description) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Authentication](https://docs.github.com/en/enterprise-cloud@latest/rest/overview/authenticating-to-the-rest-api)
- [Graph Q L  A P I](https://docs.github.com/en/enterprise-cloud@latest/graphql)
- [Postman Collection](collections/github-enterprise.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/github-enterprise.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### GitHub Enterprise Server REST API

Self-hosted GitHub Enterprise Server REST API served from a customer's own hostname under /api/v3. Per-version OpenAPI descriptions are published for each GHES release (ghes-X.X) alongside the hosted GHEC and api.github.com descriptions in github/rest-api-description.

- **Human URL:** [https://docs.github.com/en/enterprise-server@latest/rest](https://docs.github.com/en/enterprise-server@latest/rest)
- **Base URL:** `https://HOSTNAME/api/v3`

#### Tags

- REST
- Self-Hosted
- Enterprise Server
- On-Premises

#### Properties

- [Documentation](https://docs.github.com/en/enterprise-server@latest/rest)
- [OpenAPI](https://github.com/github/rest-api-description) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Graph Q L  A P I](https://docs.github.com/en/enterprise-server@latest/graphql)
- [Postman Collection](collections/github-enterprise.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/github-enterprise.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/showcase/github-enterprise)
- [Website](https://github.com/enterprise)
- [Documentation](https://docs.github.com/en/enterprise-cloud@latest)
- [Pricing](https://github.com/enterprise/pricing)
- [Sign Up](https://github.com/enterprise/contact)
- [Status Page](https://www.githubstatus.com)
- [Open A P I  Repository](https://github.com/github/rest-api-description)
- [L L Ms Txt](https://docs.github.com/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
