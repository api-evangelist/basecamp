# Basecamp (basecamp)
Basecamp is a project management and team collaboration platform developed by 37signals. The Basecamp REST API provides programmatic access to projects, to-do lists, messages, documents, schedules, and team members via OAuth2 authentication.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/basecamp/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Collaboration, Project Management, REST, SaaS, Team Communication

## Timestamps

- **Created:** 2024-01-01
- **Modified:** 2026-04-19

## APIs

### Basecamp API
REST API for programmatic access to Basecamp projects, to-dos, messages, schedules, and team members.

**Human URL:** [https://github.com/basecamp/bc3-api](https://github.com/basecamp/bc3-api)

#### Properties

- [Documentation](https://github.com/basecamp/bc3-api)
- [OpenAPI](openapi/basecamp-api-openapi.yml)

### Basecamp Webhooks
Real-time HTTP notifications for project events.

**Human URL:** [https://github.com/basecamp/bc3-api/blob/master/sections/webhooks.md](https://github.com/basecamp/bc3-api/blob/master/sections/webhooks.md)

### Basecamp OAuth
OAuth 2.0 authentication via 37signals Launchpad.

**Human URL:** [https://github.com/basecamp/bc3-api/blob/master/sections/authentication.md](https://github.com/basecamp/bc3-api/blob/master/sections/authentication.md)

## Common Properties

- [Website](https://basecamp.com/)
- [API Documentation](https://github.com/basecamp/bc3-api)
- [37signals Launchpad](https://launchpad.37signals.com/)
- [Blog](https://basecamp.com/blog)
- [TermsOfService](https://basecamp.com/about/policies/terms)
- [PrivacyPolicy](https://basecamp.com/about/policies/privacy)

## Features

| Name | Description |
|------|-------------|
| Project Management | Create and manage projects with team access controls. |
| To-Do Lists | Hierarchical to-do lists with assignments, due dates, and completion tracking. |
| Message Boards | Threaded message boards for team discussion and announcements. |
| Campfire Chat | Real-time group chat within projects. |
| Schedules | Project calendars with events and milestones. |
| File Storage | Document and file storage with version history. |
| Webhooks | Real-time event notifications for project activity. |
| OAuth2 API | Full REST API with OAuth2 authentication for third-party integrations. |

## Use Cases

| Name | Description |
|------|-------------|
| Software Development | Track sprints, bugs, and feature development with to-do lists. |
| Client Projects | Manage client deliverables, approvals, and communications. |
| Remote Team Collaboration | Asynchronous team communication and project coordination. |
| Project Automation | Automate project workflows and reporting via REST API. |
| Agency Project Management | Multi-client project organization for agencies and consultancies. |

## Artifacts

### OpenAPI

- [Basecamp API](openapi/basecamp-api-openapi.yml)

### JSON-LD

- [Basecamp JSON-LD Context](json-ld/basecamp-context.jsonld)

## Capabilities

### Shared Per-API Definitions

- [Basecamp API](capabilities/shared/basecamp-api.yaml) — 10 key operations

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Project Management](capabilities/project-management.yaml) | Basecamp | 7 | Project Manager, Team Member, Developer |

## Vocabulary

- [Basecamp Vocabulary](vocabulary/basecamp-vocabulary.yaml) — 6 resources, 6 actions, 1 workflow, 3 personas

## Rules

- [Basecamp Spectral Rules](rules/basecamp-spectral-rules.yml) — 15 rules enforcing API conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
