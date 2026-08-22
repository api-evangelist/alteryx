# Alteryx (alteryx)

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
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Alteryx is an analytics automation platform that enables data analysts and scientists to break data barriers, deliver insights, and experience the thrill of getting to the answer faster.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/alteryx/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/alteryx/refs/heads/main/apis.yml)

## Tags

- Analytics
- Automation
- Data Engineering
- Data Preparation
- Data Science
- ETL
- Machine Learning
- Predictive Analytics

## Timestamps

- **Created:** 2024-01-15
- **Modified:** 2026-05-19

## APIs

### Alteryx Server API

REST API for managing workflows, schedules, and jobs on Alteryx Server. Provides Subscription, User V2, Admin V1, Admin V2, and V3 API endpoints for creating, updating, searching, and deleting users, user groups, schedules, credentials, collections, workflows, and Server connections.

- **Human URL:** [https://help.alteryx.com/current/en/server/api-overview.html](https://help.alteryx.com/current/en/server/api-overview.html)
- **Base URL:** `https://your-server/webapi`

#### Tags

- Automation
- Jobs
- Scheduling
- Server
- Workflows

#### Properties

- [Documentation](https://help.alteryx.com/current/en/server/api-overview.html)
- [API Reference](https://help.alteryx.com/developer-help/server-api-reference)
- [Authentication](https://help.alteryx.com/current/en/server/api-overview/alteryx-server-api-v3/server-api-configuration-and-authorization.html)
- [Getting Started](https://help.alteryx.com/current/en/developer-help/apis/get-started-with-apis.html)
- [Postman Collection](collections/alteryx-server-api-v3.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/alteryx-server-api-v3.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Alteryx Server API V3

The V3 Admin API for Alteryx Server uses OAuth 2 authentication and implements POST, PUT, GET, and DELETE functionality for modifying assets, users, credentials, and connections so admins can automate tasks and integrate Server with their existing API automation tools.

- **Human URL:** [https://help.alteryx.com/current/en/server/api-overview/alteryx-server-api-v3.html](https://help.alteryx.com/current/en/server/api-overview/alteryx-server-api-v3.html)
- **Base URL:** `https://your-server/webapi/v3`

#### Tags

- Admin
- Credentials
- OAuth2
- Server
- Users
- Workflows

#### Properties

- [Documentation](https://help.alteryx.com/current/en/server/api-overview/alteryx-server-api-v3.html)
- [Authentication](https://help.alteryx.com/current/en/server/api-overview/alteryx-server-api-v3/server-api-configuration-and-authorization.html)
- [OpenAPI](openapi/alteryx-server-api-v3.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/alteryx-server-api-v3.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/alteryx-server-api-v3.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Alteryx Server API V1

The V1 API for Alteryx Server provides endpoints for admins including the Migratable Endpoint for migrating workflows across Server environments and the Auditlog Endpoint for tracking changes to system entities.

- **Human URL:** [https://help.alteryx.com/current/en/server/api-overview/alteryx-server-api-v1.html](https://help.alteryx.com/current/en/server/api-overview/alteryx-server-api-v1.html)
- **Base URL:** `https://your-server/webapi/v1`

#### Tags

- Admin
- Audit
- Migration
- Server

#### Properties

- [Documentation](https://help.alteryx.com/current/en/server/api-overview/alteryx-server-api-v1.html)
- [Postman Collection](collections/alteryx-server-api-v3.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/alteryx-server-api-v3.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Alteryx Gallery API

API for interacting with Alteryx Analytics Gallery for workflow sharing and execution.

- **Human URL:** [https://help.alteryx.com/developer-help/gallery-api-overview](https://help.alteryx.com/developer-help/gallery-api-overview)
- **Base URL:** `https://gallery.alteryx.com/api`

#### Tags

- Gallery
- Public API
- Sharing
- Workflows

#### Properties

- [Documentation](https://help.alteryx.com/developer-help/gallery-api-overview)
- [API Reference](https://help.alteryx.com/developer-help/gallery-api-reference)
- [Authentication](https://help.alteryx.com/developer-help/gallery-api-authentication)
- [Postman Collection](collections/alteryx-server-api-v3.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/alteryx-server-api-v3.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Alteryx Connect API

API for Alteryx Connect data catalog and collaboration platform.

- **Human URL:** [https://help.alteryx.com/developer-help/connect-api](https://help.alteryx.com/developer-help/connect-api)
- **Base URL:** `https://your-connect-server/api`

#### Tags

- Collaboration
- Data Catalog
- Governance
- Metadata

#### Properties

- [Documentation](https://help.alteryx.com/developer-help/connect-api)
- [Authentication](https://help.alteryx.com/developer-help/connect-authentication)
- [Postman Collection](collections/alteryx-server-api-v3.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/alteryx-server-api-v3.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Alteryx AlteryxEngine API

The AlteryxEngine API allows you to call into the Alteryx Engine to build applications that can programmatically execute Alteryx Designer workflows. Workflows and applications can be executed as a separate child process or in-process.

- **Human URL:** [https://help.alteryx.com/current/en/developer-help/apis/alteryxengine-api-overview.html](https://help.alteryx.com/current/en/developer-help/apis/alteryxengine-api-overview.html)
- **Base URL:** `https://your-server/api`

#### Tags

- Designer
- Engine
- Execution
- Workflows

#### Properties

- [Documentation](https://help.alteryx.com/current/en/developer-help/apis/alteryxengine-api-overview.html)
- [Getting Started](https://help.alteryx.com/current/en/developer-help/apis/alteryxengine-api-overview/alteryxengine-api-example.html)
- [Postman Collection](collections/alteryx-server-api-v3.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/alteryx-server-api-v3.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Alteryx Designer Cloud API

REST API for Alteryx Designer Cloud (powered by Trifacta) providing data preparation, transformation, and pipeline management capabilities. Enables programmatic access to data preparation workflows and job execution.

- **Human URL:** [https://help.alteryx.com/dataprep/en/developer/api-reference.html](https://help.alteryx.com/dataprep/en/developer/api-reference.html)
- **Base URL:** `https://api.trifacta.com`

#### Tags

- Cloud
- Data Preparation
- Pipelines
- Transformation
- Trifacta

#### Properties

- [Documentation](https://help.alteryx.com/dataprep/en/developer/api-reference.html)
- [API Reference](https://api.trifacta.com/)
- [Authentication](https://help.alteryx.com/Dataprep/en/developer/api-reference/manage-api-access-tokens.html)
- [Postman Collection](collections/alteryx-server-api-v3.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/alteryx-server-api-v3.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Developer Portal](https://help.alteryx.com/current/en/developer-help.html)
- [Getting Started](https://help.alteryx.com/current/en/developer-help/apis/get-started-with-apis.html)
- [SDK](https://help.alteryx.com/current/en/developer-help/platform-sdk.html)
- [Status Page](https://status.alteryx.com)
- [Support](https://community.alteryx.com)
- [Blog](https://community.alteryx.com/t5/Engine-Works/bg-p/engine-works)
- [X (Twitter)](https://twitter.com/alteryx)
- [LinkedIn](https://www.linkedin.com/company/alteryx)
- [GitHub Organization](https://github.com/alteryx)
- [Pricing](https://www.alteryx.com/products/pricing)
- [Trust Center](https://www.alteryx.com/trust)
- [Terms of Service](https://www.alteryx.com/terms-and-conditions)
- [Privacy Policy](https://www.alteryx.com/privacy-policy)
- [Legal](https://www.alteryx.com/legal)
- [Features](undefined)
- [Use Cases](undefined)
- [Integrations](undefined)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
**URL:** https://www.alteryx.com
