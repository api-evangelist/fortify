# Fortify (fortify)

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

Fortify is a comprehensive application security platform from OpenText that provides static application security testing (SAST), dynamic application security testing (DAST), and software composition analysis (SCA) capabilities. It helps organizations identify and remediate vulnerabilities across the software development lifecycle.

**APIs.json:** [https://www.opentext.com/products/fortify-on-demand](https://www.opentext.com/products/fortify-on-demand)

## Tags

- Application Security
- DAST
- DevSecOps
- SAST
- SCA
- Security Testing
- Vulnerability Scanning

## Timestamps

- **Created:** 2024-01-15
- **Modified:** 2026-05-19

## APIs

### Fortify on Demand API

REST API for Fortify on Demand (FoD), the cloud-based application security testing service from OpenText. Provides programmatic access to manage applications, initiate scans, and retrieve vulnerability results.

- **Human URL:** [https://www.opentext.com/products/fortify-on-demand](https://www.opentext.com/products/fortify-on-demand)
- **Base URL:** `https://api.ams.fortify.com`

#### Tags

- Application Security
- DAST
- SAST
- Security Testing
- Vulnerability Management

#### Properties

- [Documentation](https://www.microfocus.com/documentation/fortify-on-demand/)
- [OpenAPI](https://api.ams.fortify.com/swagger/docs/v3) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [OpenAPI](openapi/fortify-on-demand-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/fortify-on-demand.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/fortify-on-demand.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [API Reference](https://api.ams.fortify.com/swagger/ui/index)
- [Authentication](https://api.ams.fortify.com/oauth/token)
- [Getting Started](https://www.microfocus.com/documentation/fortify-on-demand/251/Fortify_on_Demand_Guide_25.1_EN.pdf)

### Fortify Software Security Center API

REST API for the on-premise Fortify Software Security Center (SSC), which provides centralized management and reporting of security assessment data across an organization's application portfolio.

- **Human URL:** [https://www.microfocus.com/documentation/fortify-software-security-center/](https://www.microfocus.com/documentation/fortify-software-security-center/)
- **Base URL:** `https://your-ssc-server/ssc/api/v1`

#### Tags

- Application Security
- Compliance
- On-Premise
- Security Analytics
- Vulnerability Management

#### Properties

- [Documentation](https://www.microfocus.com/documentation/fortify-software-security-center/2520/)
- [OpenAPI](openapi/fortify-software-security-center-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/fortify-software-security-center.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/fortify-software-security-center.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [API Reference](https://your-ssc-server/ssc/html/docs/api-reference/)
- [Authentication](https://your-ssc-server/ssc/api/v1/auth)
- [Getting Started](https://www.microfocus.com/documentation/fortify-software-security-center/)
- [S D Ks](https://github.com/fortify/ssc-restapi-client)

### Fortify ScanCentral DAST API

REST API for Fortify ScanCentral DAST, which provides centralized dynamic application security testing management. Enables orchestration of DAST scans across distributed sensors and integration with CI/CD pipelines.

- **Human URL:** [https://www.microfocus.com/documentation/fortify-ScanCentral-DAST/](https://www.microfocus.com/documentation/fortify-ScanCentral-DAST/)
- **Base URL:** `https://your-scancentral-dast-server/api/`

#### Tags

- CI/CD
- DAST
- Dynamic Analysis
- Security Testing
- Web Application Security

#### Properties

- [Documentation](https://www.microfocus.com/documentation/fortify-ScanCentral-DAST/2520/)
- [OpenAPI](openapi/fortify-scancentral-dast-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/fortify-scancentral-dast.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/fortify-scancentral-dast.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Getting Started](https://www.microfocus.com/documentation/fortify-ScanCentral-DAST/2520/sc-dast-ugd-25.2.0.pdf)

## Common Properties

- [Portal](https://ams.fortify.com/)
- [Documentation](https://www.microfocus.com/documentation/fortify-on-demand/)
- [Getting Started](https://www.microfocus.com/documentation/fortify-on-demand/)
- [Authentication](https://api.ams.fortify.com/swagger/ui/index)
- [Blog](https://community.opentext.com/cyberres/b/cybersecurity-blog)
- [Status Page](https://status.fortify.com/)
- [Support](https://www.opentext.com/support)
- [Terms of Service](https://www.opentext.com/about/legal/website-terms-of-use)
- [Privacy Policy](https://www.opentext.com/about/privacy)
- [GitHub Organization](https://github.com/fortify)
- [Community](https://community.opentext.com/cybersec/fortify)
- [Website](https://www.opentext.com/products/fortify-on-demand)
- [Login](https://ams.fortify.com/)
- [Sign Up](https://www.opentext.com/products/fortify-on-demand/trial)
- [Changelog](https://community.opentext.com/cybersec/fortify/w/tips)
- [S D Ks](https://github.com/fortify/fortify-client-api)
- [J S O N- L D  Context](json-ld/fortify-context.jsonld)
- [J S O N  Schema](json-schema/fortify-application-schema.json)
- [J S O N  Schema](json-schema/fortify-vulnerability-schema.json)
- [J S O N  Schema](json-schema/fortify-scan-schema.json)
- [J S O N  Schema](json-schema/fortify-release-schema.json)
- [J S O N  Schema](json-schema/fortify-project-version-schema.json)
- [Agent Skill](https://github.com/fortify/skills)

## Maintainers

**Email:** kin@apievangelist.com
**URL:** https://apievangelist.com
