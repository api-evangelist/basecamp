# Basecamp GraphQL Schema

This is a conceptual GraphQL schema for the Basecamp project management platform, derived from the Basecamp REST API (bc3-api). Basecamp does not currently offer a native GraphQL endpoint; this schema represents the data model as it would be expressed in GraphQL, based on the official REST API documentation at https://github.com/basecamp/bc3-api.

## Coverage

The schema covers the full surface area of the Basecamp 3 API, including:

- **Accounts and Identity** — BasecampAccount, Account, Authorization, Token, OauthToken, LinkedAccount, Person, PersonProfile, KeyPerson
- **Projects and Structure** — Project, ProjectTemplate, Bucket, BucketMembership, Dock, DockItem
- **To-Dos** — Todoset, Todolist, Todo
- **Messaging** — MessageBoard, Message, MessageType, Campfire, CampfireMessage, Ping, PingMessage, Forward
- **Scheduling** — Schedule, ScheduleEntry
- **Documents and Files** — Vault, Document, Upload, Attachment, Clipboard
- **Questions** — Question, QuestionAnswerSet, QuestionAnswer, Answer
- **Comments and Activity** — Comment, Recording, Event, Subscription, GlobalSubscription
- **Clients** — Client, ClientApproval, ClientAccess, Grant
- **Chatbots and Apps** — Chatbot, AppInstall, AppIntegration
- **Webhooks** — Webhook, WebhookTypes

## Base URL

```
https://3.basecampapi.com/{account_id}
```

## Authentication

All requests require OAuth 2.0 Bearer tokens obtained through the 37signals Launchpad at `https://launchpad.37signals.com`. Register an application to receive a client ID and secret, then implement the authorization code flow.

## Schema File

See `basecamp-schema.graphql` for the full type definitions.

## Key Relationships

- A **BasecampAccount** contains many **Projects** (also called Buckets in the API).
- Each **Project** has a **Dock** that lists available tools (DockItems) such as Todoset, MessageBoard, Schedule, Vault, Campfire, and QuestionAnswerSet.
- **Recordings** is the generic base type for all content items (Todos, Messages, Documents, etc.) and supports Comments and Subscriptions.
- **Events** represent the audit trail of all changes within a project.
- **Webhooks** subscribe to event streams per project and post payloads to a configured HTTPS URL.

## Types Count

55 named GraphQL types defined in basecamp-schema.graphql.
