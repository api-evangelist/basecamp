# Basecamp (basecamp)
Basecamp is a project management and team communication platform developed by 37signals that helps teams organize work, track to-dos, share files, and communicate in one place. Their developer platform provides REST APIs and webhook support, enabling programmatic access to projects, messages, schedules, documents, and team members across Basecamp accounts.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/basecamp/refs/heads/main/apis.yml)

## Scope

- **Type:** Contract
- **Position:** Consuming
- **Access:** 3rd-Party

## Tags:

 - Project Management, Team Communication, Collaboration, REST

## Timestamps

- **Created:** 2026-03-21
- **Modified:** 2026-03-21

## APIs

### Basecamp API
The Basecamp API is a REST API that provides programmatic access to Basecamp's project management and team communication platform. It enables developers to manage projects, to-do lists, messages, documents, schedules, and team members across Basecamp accounts. The API uses OAuth 2.0 for authentication and returns JSON responses, with all requests scoped to an account ID in the base URL. Resources include projects, people, to-dos, message boards, documents, card tables, campfires, questionnaires, and webhooks, covering the full breadth of Basecamp's collaboration toolset.

**Human URL:** [https://github.com/basecamp/bc3-api](https://github.com/basecamp/bc3-api)


#### Tags:

 - Project Management, Team Communication, Collaboration, REST

#### Properties

- [Documentation](https://github.com/basecamp/bc3-api)
- [OpenAPI](openapi/basecamp-api-openapi.yml)

### Basecamp Webhooks
Basecamp Webhooks allow developers to receive real-time HTTP notifications when events occur within a Basecamp project. Webhooks are configured per project with an HTTPS payload URL and a list of resource types that should trigger notifications. Basecamp will attempt delivery up to 10 times with exponential backoff before deactivating a webhook if the endpoint does not return a 2xx status code. Developers can manage webhook subscriptions via the REST API, including creating, listing, updating, and deleting webhooks for a given project.

**Human URL:** [https://github.com/basecamp/bc3-api/blob/master/sections/webhooks.md](https://github.com/basecamp/bc3-api/blob/master/sections/webhooks.md)


#### Tags:

 - Webhooks, Events, Notifications, Project Management

#### Properties

- [Documentation](https://github.com/basecamp/bc3-api/blob/master/sections/webhooks.md)
- [AsyncAPI](asyncapi/basecamp-webhooks-asyncapi.yml)

### Basecamp OAuth
Basecamp OAuth 2.0 is the required authentication mechanism for accessing all Basecamp APIs. Developers register their applications at launchpad.37signals.com to receive a client ID and client secret, then implement the OAuth authorization code flow to obtain access tokens on behalf of users. Access tokens expire after two weeks and can be refreshed using refresh tokens without requiring the user to re-authorize. All API requests must include an Authorization Bearer token header along with a descriptive User-Agent header identifying the application and a contact email address.

**Human URL:** [https://github.com/basecamp/bc3-api/blob/master/sections/authentication.md](https://github.com/basecamp/bc3-api/blob/master/sections/authentication.md)


#### Tags:

 - OAuth, Authentication, Authorization, Security

#### Properties

- [Documentation](https://github.com/basecamp/bc3-api/blob/master/sections/authentication.md)
- [OpenAPI](openapi/basecamp-oauth-openapi.yml)

## Common Properties

- [Portal](https://dev.37signals.com/)
- [Documentation](https://github.com/basecamp/bc3-api)
- [Website](https://basecamp.com/)
- [PrivacyPolicy](https://basecamp.com/about/policies/privacy)
- [TermsOfService](https://basecamp.com/about/policies/terms)
- [Support](https://basecamp.com/support)
- [Blog](https://basecamp.com/blog)
- [Login](https://launchpad.37signals.com/signin)

## Maintainers

**FN:** API Evangelist

**Email:** info@apievangelist.com
