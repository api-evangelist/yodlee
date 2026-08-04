# Yodlee (yodlee)

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

Yodlee (Envestnet | Yodlee) is a financial data aggregation platform providing unified API access to bank accounts, credit card transactions, investments, loans, and insurance data across thousands of financial institutions. The Yodlee Core APIs v1.1 enable secure account aggregation, transaction enrichment, risk analytics, consent management, and account verification for fintech applications.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/yodlee/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/yodlee/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Financial Data
- Data Aggregation
- Banking
- Fintech
- Open Finance

## Timestamps

- **Created:** 2026-03-27
- **Modified:** 2026-05-19

## APIs

### Yodlee Core API

The Yodlee Core APIs v1.1 provide a flexible RESTful API for accessing personal financial data. Key capabilities include account aggregation across banks and brokerages, transaction history and enrichment, holdings and investment data, consent and provider account management, documents, statements, data extracts, risk analytics, and account verification. Supports 90% of top US, UK, Australia, and India financial institutions.

- **Human URL:** [https://developer.yodlee.com/resources/yodlee/yodlee-api-overview/docs/overview](https://developer.yodlee.com/resources/yodlee/yodlee-api-overview/docs/overview)
- **Base URL:** `https://production.api.yodlee.com/ysl`

#### Tags

- Financial Data
- Aggregation
- Transactions
- Accounts
- Banking
- Investments

#### Properties

- [Documentation](https://developer.yodlee.com/resources/yodlee/yodlee-api-overview/docs/overview)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/yodlee/refs/heads/main/openapi/yodlee-core-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Getting Started](https://developer.yodlee.com/docs/getting-started)
- [Postman Collection](collections/yodlee-core.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/yodlee-core.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Yodlee Account Verification API

The Yodlee Account Verification API enables real-time verification of bank account ownership and balance. Supports verification workflows via FastLink 4, holder profile retrieval, verified account status, and account classification summaries.

- **Human URL:** [https://developer.yodlee.com/products/yodlee/account-aggregation/docs/api-reference](https://developer.yodlee.com/products/yodlee/account-aggregation/docs/api-reference)
- **Base URL:** `https://production.api.yodlee.com/ysl`

#### Tags

- Account Verification
- Banking
- Fintech
- KYC

#### Properties

- [Documentation](https://developer.yodlee.com/products/yodlee/account-aggregation/docs/api-reference)
- [Postman Collection](collections/yodlee-core.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/yodlee-core.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Yodlee FastLink

FastLink 4 is Yodlee's white-label account aggregation widget that enables users to securely link their financial accounts. Provides a customizable embedded UI for account login, MFA, account selection, verification, and consent management.

- **Human URL:** [https://developer.yodlee.com/](https://developer.yodlee.com/)

#### Tags

- Account Linking
- Widget
- Embedded Finance

#### Properties

- [Documentation](https://developer.yodlee.com/)
- [Postman Collection](collections/yodlee-core.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/yodlee-core.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/yodlee)
- [Website](https://www.yodlee.com/)
- [Developer  Portal](https://developer.yodlee.com/)
- [Documentation](https://developer.yodlee.com/resources/yodlee/yodlee-api-overview/docs)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/yodlee/refs/heads/main/openapi/yodlee-core-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [GitHub Organization](https://github.com/yodlee)
- [SDK](https://github.com/Yodlee/java-sdk)
- [Getting Started](https://developer.yodlee.com/docs/getting-started)
- [Vocabulary](https://raw.githubusercontent.com/api-evangelist/yodlee/refs/heads/main/vocabulary/yodlee-vocabulary.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
