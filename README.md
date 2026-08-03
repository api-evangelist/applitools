# Applitools (applitools)

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

Applitools is a Visual AI testing platform for end-to-end functional, visual, and API testing. The product line covers Eyes (Visual AI inside existing test frameworks), Autonomous (no-code AI-powered E2E platform), Execution Cloud (self-healing cloud test runner), and Ultrafast Grid (cross-browser/device visual rendering). Applitools exposes a REST server API at eyesapi.applitools.com and ships SDKs for Selenium, Cypress, Playwright, WebdriverIO, Puppeteer, Appium, Espresso, XCUI, Robot Framework, and more across JavaScript, TypeScript, Java, Python, C#, and Ruby.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/applitools/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/applitools/refs/heads/main/apis.yml)

## Tags

- Testing
- Visual AI
- Visual Testing
- Autonomous Testing
- REST
- SDK
- Cross-Browser
- Execution Cloud

## Timestamps

- **Created:** 2026-05-23
- **Modified:** 2026-05-23

## APIs

### Applitools Eyes Server REST API

REST API for the Applitools Eyes cloud server. Endpoint groups include Batch Management (results, statistics, properties, deletion), Discussions (list and manage comments), and SCM Integrations (status setting for source control systems). Authentication uses the user's Applitools API key.

- **Human URL:** [https://applitools.com/docs/eyes/reference/server-api](https://applitools.com/docs/eyes/reference/server-api)
- **Base URL:** `https://eyesapi.applitools.com`

#### Tags

- REST
- Eyes
- Batches
- Discussions
- SCM

#### Properties

- [Documentation](https://applitools.com/docs/eyes/reference/server-api)
- [Product Docs](https://applitools.com/docs/)
- [Postman Collection](collections/applitools.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/applitools.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Applitools Eyes SDKs

Visual testing SDKs that integrate with existing test frameworks (Selenium, Cypress, Playwright, WebdriverIO, Puppeteer, Appium, Espresso, XCUI, Robot Framework, Images) across JavaScript/TypeScript, Java, Python, C#, and Ruby. SDKs send screenshots and DOM snapshots to the Eyes cloud server for Visual AI comparison.

- **Human URL:** [https://applitools.com/docs/eyes](https://applitools.com/docs/eyes)
- **Base URL:** `https://eyesapi.applitools.com`

#### Tags

- SDK
- Selenium
- Cypress
- Playwright
- Appium
- Visual AI

#### Properties

- [Documentation](https://applitools.com/docs/eyes)
- [Cypress](https://applitools.com/docs/eyes/sdks/cypress)
- [Playwright Python](https://applitools.com/docs/eyes/sdks/playwright-python)
- [Robot](https://applitools.com/docs/eyes/sdks/robot)
- [Espresso](https://applitools.com/docs/eyes/sdks/espresso)
- [Postman Collection](collections/applitools.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/applitools.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Applitools Autonomous

AI-powered no-code platform for end-to-end functional, visual, and API testing. Handles test authoring, result analysis, and provides REST API access for programmatic integration into CI/CD.

- **Human URL:** [https://applitools.com/platform/autonomous/](https://applitools.com/platform/autonomous/)
- **Base URL:** `https://eyes.applitools.com`

#### Tags

- Autonomous
- AI
- No-Code
- E2E Testing

#### Properties

- [Product Page](https://applitools.com/platform/autonomous/)
- [Documentation](https://applitools.com/docs/)
- [Postman Collection](collections/applitools.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/applitools.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Applitools Execution Cloud

Cloud test execution infrastructure with self-healing capabilities - tests remain functional even when UI elements change. Drop-in remote WebDriver replacement for Selenium, Playwright, and WebdriverIO tests.

- **Human URL:** [https://applitools.com/platform/execution-cloud/](https://applitools.com/platform/execution-cloud/)
- **Base URL:** `https://exec-wus.applitools.com`

#### Tags

- Execution Cloud
- Self-Healing
- WebDriver

#### Properties

- [Product Page](https://applitools.com/platform/execution-cloud/)
- [Documentation](https://applitools.com/docs/)
- [Postman Collection](collections/applitools.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/applitools.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Applitools Ultrafast Grid

Cross-browser and device visual rendering grid. Renders DOM snapshots captured by Eyes SDKs across many browser/viewport combinations in parallel and applies Visual AI comparison.

- **Human URL:** [https://applitools.com/platform/ultrafast-grid/](https://applitools.com/platform/ultrafast-grid/)
- **Base URL:** `https://eyesapi.applitools.com`

#### Tags

- Ultrafast Grid
- Cross-Browser
- Visual AI

#### Properties

- [Product Page](https://applitools.com/platform/ultrafast-grid/)
- [Postman Collection](collections/applitools.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/applitools.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Website](https://applitools.com/)
- [Documentation](https://applitools.com/docs/)
- [Git Hub](https://github.com/applitools)
- [LinkedIn](https://www.linkedin.com/company/applitools)
- [Plans](plans/applitools-plans-pricing.yml)
- [Rate Limits](rate-limits/applitools-rate-limits.yml)
- [Fin Ops](finops/applitools-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
