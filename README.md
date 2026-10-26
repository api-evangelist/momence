# Momence (momence)

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

Momence is an all-in-one management platform for fitness, wellness, and experience-based businesses - studios, gyms, spas, and instructors - covering class and appointment scheduling, memberships and packages, point-of-sale and payments, marketing, and a branded member app. Momence exposes a documented public REST API (api.momence.com, `/api/v2`) split into a **Host API** for staff and back-office automation and a **Member API** scoped to the logged-in customer. The API is authenticated with OAuth2 (authorization code for customers, password grant for staff automation) using public API clients created in the Momence dashboard, and covers members, sessions and bookings, memberships, checkout and sales, reports, appointments, addresses, and saved payment methods.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/momence/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/momence/refs/heads/main/apis.yml)

## Tags

- Fitness
- Wellness
- Studio Management
- Booking
- Scheduling
- Memberships
- Payments
- Class Management

## Timestamps

- **Created:** 2026-07-04
- **Modified:** 2026-07-04

## APIs

### Momence Authentication API

OAuth2 authorization and token endpoints for the Momence Public API. Supports the authorization code grant (redirecting customers to a Momence login screen), the password grant for staff automation, and refresh tokens, plus endpoints to fetch the logged-in user profile and log out. Public API clients (client_id / client_secret) are created in the Momence dashboard.

- **Human URL:** [https://api.docs.momence.com/docs/authorization](https://api.docs.momence.com/docs/authorization)
- **Base URL:** `https://api.momence.com/api/v2`

#### Tags

- Authentication
- OAuth2
- Identity

#### Properties

- [Documentation](https://api.docs.momence.com/docs/authorization)
- [API Reference](https://api.docs.momence.com/docs/getting-started)
- [OpenAPI](openapi/momence-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/momence.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/momence.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Momence Host Members API

Staff-side management of the members (customers) in a Momence host - list and filter members, create members, retrieve a member, update name, email, and phone number, read and manage member notes, and assign or unassign tags for segmentation and access control.

- **Human URL:** [https://api.docs.momence.com/reference/apiv2hostmemberscontroller_list](https://api.docs.momence.com/reference/apiv2hostmemberscontroller_list)
- **Base URL:** `https://api.momence.com/api/v2`

#### Tags

- Members
- Customers
- CRM

#### Properties

- [Documentation](https://api.docs.momence.com/docs/terminology)
- [API Reference](https://api.docs.momence.com/reference/apiv2hostmemberscontroller_list)
- [OpenAPI](openapi/momence-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/momence.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/momence.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Momence Host Sessions & Bookings API

Staff-side scheduling surface - list sessions (classes) and retrieve session detail, list a session's bookings, add a member to a session for free or to its waitlist, mark a booking checked-in or not, and cancel individual or recurring session bookings.

- **Human URL:** [https://api.docs.momence.com/reference/apiv2hostsessionscontroller_getsessions](https://api.docs.momence.com/reference/apiv2hostsessionscontroller_getsessions)
- **Base URL:** `https://api.momence.com/api/v2`

#### Tags

- Sessions
- Classes
- Bookings
- Waitlist

#### Properties

- [API Reference](https://api.docs.momence.com/reference/apiv2hostsessionscontroller_getsessions)
- [OpenAPI](openapi/momence-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/momence.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/momence.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Momence Host Memberships API

Manage the membership products a host sells and the memberships a member has bought - list available host memberships, list a member's active subscriptions and packs, adjust class credits, and freeze, schedule freeze/unfreeze, or unfreeze a member's bought membership.

- **Human URL:** [https://api.docs.momence.com/reference/apiv2hostmembershipscontroller_list](https://api.docs.momence.com/reference/apiv2hostmembershipscontroller_list)
- **Base URL:** `https://api.momence.com/api/v2`

#### Tags

- Memberships
- Subscriptions
- Packages

#### Properties

- [API Reference](https://api.docs.momence.com/reference/apiv2hostmembershipscontroller_list)
- [OpenAPI](openapi/momence-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/momence.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/momence.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Momence Host Checkout & Sales API

Staff-side commerce and reporting - resolve compatible memberships and prices for a cart, perform checkout on behalf of a member (buy a session with a subscription or a saved payment method, or buy a membership), list sales, manage appointment reservations, and run and retrieve host reports.

- **Human URL:** [https://api.docs.momence.com/reference/apiv2hostcheckoutcontroller_post](https://api.docs.momence.com/reference/apiv2hostcheckoutcontroller_post)
- **Base URL:** `https://api.momence.com/api/v2`

#### Tags

- Checkout
- Payments
- Sales
- Reports

#### Properties

- [API Reference](https://api.docs.momence.com/reference/apiv2hostcheckoutcontroller_post)
- [OpenAPI](openapi/momence-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/momence.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/momence.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Momence Member Account API

Customer-scoped account management for the logged-in member - read and update member info, email, and phone number, request a password-reset email, list visits, CRUD member addresses, list a member's active memberships and manage their freeze schedule, and save, list, and remove payment methods.

- **Human URL:** [https://api.docs.momence.com/reference/apiv2membercontroller_get](https://api.docs.momence.com/reference/apiv2membercontroller_get)
- **Base URL:** `https://api.momence.com/api/v2`

#### Tags

- Member
- Profile
- Addresses
- Payment Methods

#### Properties

- [API Reference](https://api.docs.momence.com/reference/apiv2membercontroller_get)
- [OpenAPI](openapi/momence-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/momence.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/momence.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Momence Member Booking API

Customer-facing booking flow - browse a host's available locations, memberships, and sessions, resolve compatible memberships and prices, perform checkout to buy or book a session, list and cancel the member's own session bookings, and read and sign required signable documents (waivers and contracts).

- **Human URL:** [https://api.docs.momence.com/reference/apiv2memberhostsessionscontroller_list](https://api.docs.momence.com/reference/apiv2memberhostsessionscontroller_list)
- **Base URL:** `https://api.momence.com/api/v2`

#### Tags

- Booking
- Sessions
- Checkout
- Documents

#### Properties

- [API Reference](https://api.docs.momence.com/reference/apiv2memberhostsessionscontroller_list)
- [OpenAPI](openapi/momence-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/momence.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/momence.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/momence)
- [Website](https://momence.com/)
- [Documentation](https://api.docs.momence.com/)
- [Plans](plans/momence-plans-pricing.yml)
- [Rate Limits](rate-limits/momence-rate-limits.yml)
- [Fin Ops](finops/momence-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
