# Momence (momence)

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
