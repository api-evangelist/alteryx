# Alteryx (alteryx)

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
