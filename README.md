# Basecamp (basecamp)

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
