# Blackstone (blackstone)

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

Blackstone is the world's largest alternative asset manager with over $1 trillion in assets under management across private equity, real estate, credit, and hedge fund strategies. Blackstone serves institutional investors including pension funds, sovereign wealth funds, endowments, and foundations, as well as accredited individual investors through its private wealth solutions. Technology and data platforms are central to Blackstone's investment operations and portfolio company management.

**URL:** [https://www.blackstone.com](https://www.blackstone.com)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Alternative Assets, Finance, Investment Management, Private Equity, Real Estate

## Timestamps

- **Created:** 2026-03-21
- **Modified:** 2026-04-21

## APIs

### Blackstone Investor Portal
Blackstone provides institutional and individual investors with access to portfolio information, capital account statements, fund documents, and reporting through its Investor Portal. API integrations may be available for institutional investors and data aggregation platforms under direct agreement with Blackstone.

**Human URL:** [https://www.blackstone.com/investor-resources/](https://www.blackstone.com/investor-resources/)

#### Tags:

 - Alternative Assets, Finance, Investment Management, Private Equity

#### Properties

- [Documentation](https://www.blackstone.com/investor-resources/)
- [Login](https://investor.blackstone.com)
- [JSON Schema - Fund](json-schema/blackstone-fund-schema.json)
- [JSON Schema - Investor Account](json-schema/blackstone-investor-account-schema.json)
- [JSON-LD Context](json-ld/blackstone-context.jsonld)
- [Example - Fund](examples/blackstone-fund-example.json)
- [Example - Investor Account](examples/blackstone-investor-account-example.json)

## Common Properties

- [Website](https://www.blackstone.com)
- [Documentation](https://www.blackstone.com/investor-resources/)
- [Login](https://investor.blackstone.com)
- [Terms of Service](https://www.blackstone.com/terms-and-conditions/)
- [Privacy Policy](https://www.blackstone.com/privacy-policy/)
- [Blog](https://www.blackstone.com/insights/)
- [Spectral Rules](rules/blackstone-spectral-rules.yml)
- [Naftiko Capability](capabilities/blackstone-investor-portal.yaml)
- [Vocabulary](vocabulary/blackstone-vocabulary.yaml)

## Features

| Name | Description |
|------|-------------|
| Investor Portal | Web-based portal providing investors with access to fund performance, capital account statements, distributions, and investor documents. |
| Fund Reporting | Quarterly and annual fund-level reporting including audited financials, NAV calculations, and investor-level P&L attribution. |
| Alternative Data Integration | Blackstone's data science and technology teams develop proprietary data products and integrations to support portfolio company operations and investment research. |
| Portfolio Company Technology | Blackstone actively supports portfolio companies in technology transformation, digital infrastructure buildout, and enterprise software adoption. |
| Capital Call and Distribution Notices | Automated delivery of capital call and distribution notices to investors via the portal, email, and data feed integrations. |
| Tax Document Delivery | Annual K-1 and other tax documents delivered electronically to limited partners through the Investor Portal. |

## Use Cases

| Name | Description |
|------|-------------|
| Institutional Investor Reporting | Institutional LPs access fund reporting, capital call and distribution notices, and tax documents through the investor portal or via data integrations. |
| Portfolio Monitoring | Blackstone's investment teams use proprietary data platforms to monitor portfolio company performance metrics, market signals, and risk indicators. |
| Data Aggregation | Third-party data aggregators and institutional investor platforms may access Blackstone investor data via direct data feed agreements. |
| Wealth Management Distribution | Registered investment advisors and wealth managers access Blackstone alternative products through platform integrations for accredited investor clients. |

## Integrations

| Name | Description |
|------|-------------|
| iCapital Network | Blackstone distributes alternative investments to wealth management clients through iCapital Network's feeder fund and technology platform. |
| CAIS | Blackstone alternative investment products are available through the CAIS platform for independent and institutional advisors. |
| Yardi | Blackstone Real Estate uses Yardi for property management, accounting, and data reporting across its real estate portfolio. |
| Allvue Systems | Blackstone's credit and private equity operations use Allvue for portfolio monitoring, investor reporting, and fund accounting. |

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
