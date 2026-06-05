# Basecamp (basecamp)

Basecamp is a project management and team collaboration platform developed by 37signals. The Basecamp REST API (bc3-api) provides programmatic access to projects, to-do lists, messages, documents, schedules, and team members. OAuth2 authentication via the 37signals Launchpad is required. The API returns JSON and is documented on GitHub at github.com/basecamp/bc3-api.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/basecamp/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/basecamp/refs/heads/main/apis.yml)

## Tags

- Collaboration
- Project Management
- REST
- SaaS
- Team Communication

## Timestamps

- **Created:** 2024-01-01
- **Modified:** 2026-05-19

## APIs

### Basecamp API

The Basecamp API is a REST API providing programmatic access to Basecamp's project management platform. Manage projects, to-do lists, messages, documents, schedules, and team members. Uses OAuth 2.0 for authentication and returns JSON.

- **Human URL:** [https://github.com/basecamp/bc3-api](https://github.com/basecamp/bc3-api)
- **Base URL:** `https://3.basecampapi.com`

#### Tags

- Collaboration
- Project Management
- REST
- Team Communication

#### Properties

- [Documentation](https://github.com/basecamp/bc3-api)
- [OpenAPI](openapi/basecamp-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/basecamp-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/basecamp-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Basecamp Webhooks

Basecamp Webhooks deliver real-time HTTP notifications when events occur within a project. Configure webhooks per project with an HTTPS payload URL and resource types.

- **Human URL:** [https://github.com/basecamp/bc3-api/blob/master/sections/webhooks.md](https://github.com/basecamp/bc3-api/blob/master/sections/webhooks.md)
- **Base URL:** `https://3.basecampapi.com`

#### Tags

- Events
- Notifications
- Project Management
- Webhooks

#### Properties

- [Documentation](https://github.com/basecamp/bc3-api/blob/master/sections/webhooks.md)
- [AsyncAPI](asyncapi/basecamp-webhooks-asyncapi.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)
- [Postman Collection](collections/basecamp-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/basecamp-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/basecamp-oauth.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/basecamp-oauth.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Basecamp OAuth

OAuth 2.0 authentication for Basecamp API access via the 37signals Launchpad. Register at launchpad.37signals.com for a client ID and secret, then implement the authorization code flow to obtain access tokens.

- **Human URL:** [https://github.com/basecamp/bc3-api/blob/master/sections/authentication.md](https://github.com/basecamp/bc3-api/blob/master/sections/authentication.md)
- **Base URL:** `https://launchpad.37signals.com`

#### Tags

- Authentication
- Authorization
- OAuth
- Security

#### Properties

- [Documentation](https://github.com/basecamp/bc3-api/blob/master/sections/authentication.md)
- [OpenAPI](openapi/basecamp-oauth-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/basecamp-oauth.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/basecamp-oauth.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/37signals)
- [Website](https://basecamp.com/)
- [Documentation](https://github.com/basecamp/bc3-api)
- [Sign Up](https://launchpad.37signals.com/)
- [Blog](https://basecamp.com/blog)
- [Terms of Service](https://basecamp.com/about/policies/terms)
- [Privacy Policy](https://basecamp.com/about/policies/privacy)
- [Spectral Rules](rules/basecamp-spectral-rules.yml)
- [Vocabulary](vocabulary/basecamp-vocabulary.yaml)
- [JSON-LD](json-ld/basecamp-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Features](undefined)
- [Use Cases](undefined)
- [Integrations](undefined)
- [Integrations](https://basecamp.com/integrations)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
