# Cisco Webex (cisco-webex)

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

Cisco Webex is a comprehensive collaboration platform that provides video conferencing, team messaging, file sharing, and calling capabilities for businesses and teams. The Webex developer platform offers REST APIs, SDKs, and integrations for extending and automating collaboration workflows across meetings, messaging, calling, devices, administration, and contact center scenarios. Authentication uses OAuth 2.0 access tokens, personal access tokens, or service apps and all endpoints are served from the webexapis.com base.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/cisco-webex/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/cisco-webex/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- Collaboration
- Communications
- Meetings
- Messaging
- Teams
- Video Conferencing

## Timestamps

- **Created:** 2024-01-01
- **Modified:** 2026-05-19

## APIs

### Webex Meetings API

Enables scheduling, managing, and controlling Webex meetings programmatically. Provides endpoints for creating meetings, managing attendees, preferences, and retrieving meeting details.

- **Human URL:** [https://developer.webex.com/docs/meetings](https://developer.webex.com/docs/meetings)
- **Base URL:** `https://webexapis.com/v1`

#### Tags

- Attendees
- Conferencing
- Meetings
- Scheduling
- Video

#### Properties

- [Documentation](https://developer.webex.com/docs/meetings)
- [OpenAPI](openapi/cisco-webex-meeting-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/cisco-webex-meetings.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cisco-webex-meetings.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Authentication](https://developer.webex.com/docs/getting-started#authentication)

### Webex Messaging API

Send and receive messages, manage spaces and teams, and share files within the Webex messaging platform. Supports rich text, file attachments, and adaptive cards.

- **Human URL:** [https://developer.webex.com/docs/messaging](https://developer.webex.com/docs/messaging)
- **Base URL:** `https://webexapis.com/v1`

#### Tags

- Chat
- Collaboration
- Messaging
- Spaces
- Teams

#### Properties

- [Documentation](https://developer.webex.com/docs/messaging)
- [OpenAPI](openapi/cisco-webex-messaging-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/cisco-webex-messaging.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cisco-webex-messaging.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Webhooks](https://developer.webex.com/docs/webhooks)
- [Getting Started](https://developer.webex.com/messaging/docs/getting-started)

### Webex People API

Access user profile information, manage contacts, and administer user accounts within an organization. Supports listing, creating, updating, and deleting people records.

- **Human URL:** [https://developer.webex.com/docs/api/v1/people](https://developer.webex.com/docs/api/v1/people)
- **Base URL:** `https://webexapis.com/v1`

#### Tags

- Contacts
- Directory
- People
- Profiles
- Users

#### Properties

- [Documentation](https://developer.webex.com/docs/api/v1/people)
- [OpenAPI](openapi/cisco-webex-messaging-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/cisco-webex-people.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cisco-webex-people.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Webex Teams API

Create and manage teams and team memberships within Webex. Teams group people and spaces together for organized collaboration across projects and departments.

- **Human URL:** [https://developer.webex.com/docs/api/v1/teams](https://developer.webex.com/docs/api/v1/teams)
- **Base URL:** `https://webexapis.com/v1`

#### Tags

- Collaboration
- Groups
- Membership
- Organization
- Teams

#### Properties

- [Documentation](https://developer.webex.com/docs/api/v1/teams)
- [OpenAPI](openapi/cisco-webex-messaging-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/cisco-webex-teams.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cisco-webex-teams.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Webex Rooms API

Create and manage Webex spaces (rooms) for collaboration. Rooms are virtual meeting places where people post messages and collaborate, and can be organized within teams.

- **Human URL:** [https://developer.webex.com/docs/api/v1/rooms](https://developer.webex.com/docs/api/v1/rooms)
- **Base URL:** `https://webexapis.com/v1`

#### Tags

- Channels
- Collaboration
- Messaging
- Rooms
- Spaces

#### Properties

- [Documentation](https://developer.webex.com/docs/api/v1/rooms)
- [OpenAPI](openapi/cisco-webex-messaging-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/cisco-webex-rooms.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cisco-webex-rooms.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Webex Webhooks API

Register webhooks to receive real-time HTTP callbacks when specific events occur in Webex. Supports filtering by resource type, event type, and other criteria for efficient event-driven integrations.

- **Human URL:** [https://developer.webex.com/docs/webhooks](https://developer.webex.com/docs/webhooks)
- **Base URL:** `https://webexapis.com/v1`

#### Tags

- Callbacks
- Events
- Notifications
- Real-Time
- Webhooks

#### Properties

- [Documentation](https://developer.webex.com/docs/webhooks)
- [OpenAPI](openapi/cisco-webex-messaging-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/cisco-webex-webhooks.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cisco-webex-webhooks.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Webex Devices API

Manage and control Webex devices and room systems. Provides endpoints for listing, creating, and managing device configurations, activations, and workspace assignments.

- **Human URL:** [https://developer.webex.com/docs/api/v1/devices](https://developer.webex.com/docs/api/v1/devices)
- **Base URL:** `https://webexapis.com/v1`

#### Tags

- Devices
- Hardware
- Management
- Room Systems
- Workspaces

#### Properties

- [Documentation](https://developer.webex.com/docs/api/v1/devices)
- [OpenAPI](openapi/cisco-webex-device-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/cisco-webex-devices.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cisco-webex-devices.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Webex Memberships API

Manage room memberships representing a person's relationship to a room. Use this API to list members of any room, create memberships to invite users, and update or remove memberships.

- **Human URL:** [https://developer.webex.com/docs/api/v1/memberships](https://developer.webex.com/docs/api/v1/memberships)
- **Base URL:** `https://webexapis.com/v1`

#### Tags

- Access Control
- Memberships
- Permissions
- Rooms
- Users

#### Properties

- [Documentation](https://developer.webex.com/docs/api/v1/memberships)
- [OpenAPI](openapi/cisco-webex-messaging-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/cisco-webex-memberships.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cisco-webex-memberships.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Webex Team Memberships API

Manage team memberships representing a person's relationship to a team. Use this API to add and remove people from teams and manage team membership roles.

- **Human URL:** [https://developer.webex.com/docs/api/v1/team-memberships](https://developer.webex.com/docs/api/v1/team-memberships)
- **Base URL:** `https://webexapis.com/v1`

#### Tags

- Access Control
- Collaboration
- Roles
- Team Memberships
- Teams

#### Properties

- [Documentation](https://developer.webex.com/docs/api/v1/team-memberships)
- [OpenAPI](openapi/cisco-webex-messaging-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/cisco-webex-team-memberships.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cisco-webex-team-memberships.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Webex Events API

Access events representing activities within a Webex organization such as message posts, file shares, and membership changes. Provides a historical log of activities for compliance and auditing purposes.

- **Human URL:** [https://developer.webex.com/docs/api/v1/events](https://developer.webex.com/docs/api/v1/events)
- **Base URL:** `https://webexapis.com/v1`

#### Tags

- Activity
- Auditing
- Compliance
- Events
- Monitoring

#### Properties

- [Documentation](https://developer.webex.com/docs/api/v1/events)
- [OpenAPI](openapi/cisco-webex-messaging-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/cisco-webex-events.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cisco-webex-events.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Webex Recordings API

List and manage meeting recordings. Provides access to recording details, download links, and metadata. Includes separate endpoints for admin and compliance officer access with extended filtering capabilities.

- **Human URL:** [https://developer.webex.com/docs/api/v1/recordings](https://developer.webex.com/docs/api/v1/recordings)
- **Base URL:** `https://webexapis.com/v1`

#### Tags

- Compliance
- Media
- Meetings
- Recordings
- Storage

#### Properties

- [Documentation](https://developer.webex.com/docs/api/v1/recordings)
- [OpenAPI](openapi/cisco-webex-meeting-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/cisco-webex-recordings.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cisco-webex-recordings.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Webex Call Controls API

Control active calls in Webex Calling including dial, answer, hold, transfer, and pickup operations. Supports third-party call control for building custom calling experiences and integrations.

- **Human URL:** [https://developer.webex.com/docs/api/v1/call-controls](https://developer.webex.com/docs/api/v1/call-controls)
- **Base URL:** `https://webexapis.com/v1`

#### Tags

- Call Control
- Calling
- Communications
- Telephony
- Voice

#### Properties

- [Documentation](https://developer.webex.com/docs/api/v1/call-controls)
- [OpenAPI](openapi/cisco-webex-cloud-calling-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/cisco-webex-call-controls.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cisco-webex-call-controls.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Webex Attachment Actions API

Create and retrieve attachment actions for adaptive card interactions. Used with Buttons and Cards to capture user input from interactive card elements submitted in Webex messaging spaces.

- **Human URL:** [https://developer.webex.com/docs/api/v1/attachment-actions](https://developer.webex.com/docs/api/v1/attachment-actions)
- **Base URL:** `https://webexapis.com/v1`

#### Tags

- Attachment Actions
- Buttons
- Cards
- Interactive
- Messaging

#### Properties

- [Documentation](https://developer.webex.com/docs/api/v1/attachment-actions)
- [OpenAPI](openapi/cisco-webex-messaging-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/cisco-webex-attachment-actions.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cisco-webex-attachment-actions.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Webex Organizations API

Retrieve organization details for Webex administration. Provides access to organization-level information and settings, available only to organization administrators.

- **Human URL:** [https://developer.webex.com/docs/api/v1/organizations](https://developer.webex.com/docs/api/v1/organizations)
- **Base URL:** `https://webexapis.com/v1`

#### Tags

- Administration
- Enterprise
- Management
- Organizations
- Settings

#### Properties

- [Documentation](https://developer.webex.com/docs/api/v1/organizations)
- [OpenAPI](openapi/cisco-webex-admin-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/cisco-webex-organizations.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cisco-webex-organizations.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Webex Licenses API

Manage and retrieve Webex licenses for an organization. Provides endpoints to list available licenses, view license details, and assign or modify license allocations for users.

- **Human URL:** [https://developer.webex.com/docs/api/v1/licenses](https://developer.webex.com/docs/api/v1/licenses)
- **Base URL:** `https://webexapis.com/v1`

#### Tags

- Administration
- Entitlements
- Licenses
- Management
- Provisioning

#### Properties

- [Documentation](https://developer.webex.com/docs/api/v1/licenses)
- [OpenAPI](openapi/cisco-webex-admin-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/cisco-webex-licenses.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cisco-webex-licenses.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Webex Roles API

Retrieve roles available within a Webex organization. Roles define the level of access and permissions granted to users, such as full administrator or read-only administrator.

- **Human URL:** [https://developer.webex.com/docs/api/v1/roles](https://developer.webex.com/docs/api/v1/roles)
- **Base URL:** `https://webexapis.com/v1`

#### Tags

- Access Control
- Administration
- Permissions
- Roles
- Security

#### Properties

- [Documentation](https://developer.webex.com/docs/api/v1/roles)
- [OpenAPI](openapi/cisco-webex-admin-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/cisco-webex-roles.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cisco-webex-roles.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Webex Workspaces API

Manage workspaces representing physical locations with Webex devices. Provides endpoints to create, list, update, and delete workspaces and manage their associated device configurations.

- **Human URL:** [https://developer.webex.com/docs/api/v1/workspaces](https://developer.webex.com/docs/api/v1/workspaces)
- **Base URL:** `https://webexapis.com/v1`

#### Tags

- Devices
- Facilities
- Locations
- Management
- Workspaces

#### Properties

- [Documentation](https://developer.webex.com/docs/api/v1/workspaces)
- [OpenAPI](openapi/cisco-webex-admin-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/cisco-webex-workspaces.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cisco-webex-workspaces.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Webex Admin Audit Events API

Access admin audit events for tracking administrative actions performed in Webex Control Hub. Available to full administrators for compliance monitoring and security auditing purposes.

- **Human URL:** [https://developer.webex.com/docs/api/v1/admin-audit-events](https://developer.webex.com/docs/api/v1/admin-audit-events)
- **Base URL:** `https://webexapis.com/v1`

#### Tags

- Administration
- Audit
- Compliance
- Events
- Security

#### Properties

- [Documentation](https://developer.webex.com/docs/api/v1/admin-audit-events)
- [OpenAPI](openapi/cisco-webex-admin-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/cisco-webex-admin-audit-events.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cisco-webex-admin-audit-events.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Webex Converged Recordings API

Access converged recording capabilities across Webex Meetings and Webex Calling. Provides unified endpoints for listing, retrieving, and managing recordings from multiple Webex services.

- **Human URL:** [https://developer.webex.com/docs/api/v1/converged-recordings](https://developer.webex.com/docs/api/v1/converged-recordings)
- **Base URL:** `https://webexapis.com/v1`

#### Tags

- Calling
- Compliance
- Media
- Meetings
- Recordings

#### Properties

- [Documentation](https://developer.webex.com/docs/api/v1/converged-recordings)
- [OpenAPI](openapi/cisco-webex-meeting-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/cisco-webex-converged-recordings.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cisco-webex-converged-recordings.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Arazzo Workflows](arazzo/) — [Arazzo Specification](https://spec.openapis.org/arazzo/latest.html)
- [LinkedIn](https://www.linkedin.com/company/webex)
- [Portal](https://developer.webex.com)
- [Documentation](https://developer.webex.com/docs/basics)
- [Getting Started](https://developer.webex.com/docs/getting-started)
- [Authentication](https://developer.webex.com/docs/getting-started#authentication)
- [S D Ks](https://developer.webex.com/docs/sdks)
- [Changelog](https://developer.webex.com/docs/api/changelog)
- [Blog](https://developer.webex.com/blog)
- [Support](https://developer.webex.com/support)
- [Status Page](https://status.webex.com)
- [Rate Limits](https://developer.webex.com/docs/api-rate-limits)
- [Community](https://community.cisco.com/t5/webex-developers/bd-p/4416j-disc-dev-webex)
- [Terms of Service](https://developer.webex.com/terms-of-service)
- [Privacy Policy](https://www.cisco.com/c/en/us/about/legal/privacy-full.html)
- [GitHub Organization](https://github.com/webex)
- [Website](https://www.webex.com)
- [Login](https://developer.webex.com/login)
- [Sign Up](https://developer.webex.com/signup)
- [J S O N- L D  Context](json-ld/cisco-webex-context.jsonld)
- [J S O N  Schema](json-schema/)
- [Spectral Rules](rules/cisco-webex-rules.yml) — [Spectral](https://docs.stoplight.io/docs/spectral)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
**URL:** https://developer.webex.com
