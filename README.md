# GitHub Enterprise (github-enterprise)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
