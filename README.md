# API Insights (api-insights)

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

API Insights is a free online tool powered by Treblle that provides advanced API analysis and monitoring by evaluating OpenAPI specifications across multiple dimensions including AI readiness, design quality, performance, and security. It scores APIs against industry benchmarks and provides actionable recommendations for improvement.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/api-insights/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - AI Readiness, Analysis, Analytics, API Design, Dashboards, Insights, Monitoring, OpenAPI, Platform, Security, Treblle

## Timestamps

- **Created:** 2025-01-08
- **Modified:** 2026-04-19

## APIs

### API Insights Analysis
API Insights analyzes OpenAPI specifications (OAS v3, JSON or YAML) and produces detailed scorecards across AI Readiness, Design, Performance, and Security dimensions. Each category receives a letter grade and percentage score benchmarked against industry standards, with pass/fail/skipped status for individual checks.

**Human URL:** [https://apiinsights.io/](https://apiinsights.io/)

#### Tags:

 - AI Readiness, Analysis, API Design, OpenAPI, Performance, Security, Scoring

#### Properties

- [Documentation](https://apiinsights.io/)
- [Demo](https://apiinsights.io/reports/demo-report)

## Common Properties

- [Website](https://apiinsights.io/)
- [Support](mailto:support@apiinsights.io)

## Features

| Name | Description |
|------|-------------|
| AI Readiness Scoring | Evaluates schema descriptions, operation IDs, parameter documentation, and response descriptions to ensure APIs are well-structured for AI integration. |
| Design Analysis | Checks contact information, operation documentation, code examples, HTTP method variety, URL versioning, endpoint naming consistency, and rate-limiting headers. |
| Performance Analysis | Assesses compression support, response sizes, HTTP/2 usage, load times, caching policies, and CDN implementation targeting 500ms or less. |
| Security Analysis | Checks authentication enforcement, IDOR vulnerability risks, security scheme definitions, and HTTP security headers including HSTS, X-Frame-Options, and Content-Security-Policy. |
| Industry Benchmarking | Scores APIs against industry peers with percentile rankings such as Top 10% in your industry. |
| OpenAPI Upload and URL Input | Accepts OpenAPI v3 specifications via file upload or URL for instant analysis. |

## Use Cases

| Name | Description |
|------|-------------|
| API Quality Assurance | Validate API design quality before publishing by running specifications through automated scoring checks. |
| Security Compliance Review | Identify authentication gaps, IDOR risks, and missing security headers before deployment. |
| AI Integration Readiness | Ensure APIs are well-documented and structured for consumption by AI agents and LLM-based tools. |
| Performance Optimization | Detect missing compression, caching, or CDN configurations that degrade API performance. |
| API Governance | Establish baseline design quality standards across API portfolios using industry benchmark scores. |

## Maintainers

**FN:** Kin Lane

**Email:** info@apievangelist.com
