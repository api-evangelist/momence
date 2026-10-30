# Momence

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

Momence is an all-in-one management platform for fitness, wellness, and experience-based businesses - studios, gyms, spas, and instructors - covering class and appointment scheduling, memberships and packages, point-of-sale and payments, marketing, and a branded member app. Momence exposes a documented public REST API (api.momence.com, /api/v2) split into a Host API for staff and back-office automation and a Member API scoped to the logged-in customer. The API is authenticated with OAuth2 (authorization code for customers, password grant for staff automation) using public API clients created in the Momence dashboard, and covers members, sessions and bookings, memberships, checkout and sales, reports, appointments, addresses, and saved payment methods.

**Areas:** Fitness · Wellness · Studio Management · Booking · Scheduling · Membership · Payments · Class Management

## Momence on APIs.io

Everything profiled for Momence is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/momence/](https://apis.io/providers/momence/)** — or go straight to one of the APIs or properties below.

### APIs (8)

- [Momence Auth API](https://apis.io/apis/momence/momence-auth-api/) — The auth API from Momence — 4 operation(s) for auth.
- [Momence Host API](https://apis.io/apis/momence/momence-host-api/) — The host API from Momence — 29 operation(s) for host.
- [Momence Host Checkout API](https://apis.io/apis/momence/momence-host-checkout-api/) — The host-checkout API from Momence — 3 operation(s) for host-checkout.
- [Momence Member Addresses API](https://apis.io/apis/momence/momence-member-addresses-api/) — The member-addresses API from Momence — 2 operation(s) for member-addresses.
- [Momence Member API](https://apis.io/apis/momence/momence-member-api/) — The member API from Momence — 11 operation(s) for member.
- [Momence Member Checkout API](https://apis.io/apis/momence/momence-member-checkout-api/) — The member-checkout API from Momence — 3 operation(s) for member-checkout.
- [Momence Member Host API](https://apis.io/apis/momence/momence-member-host-api/) — The member-host API from Momence — 5 operation(s) for member-host.
- [Momence Member Sessions API](https://apis.io/apis/momence/momence-member-sessions-api/) — The member-sessions API from Momence — 2 operation(s) for member-sessions.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Momence Agentic Access](https://apis.io/agentic-access/momence/momence-agentic-access/)

#### Collections (9)

Postman and Open Collection request collections.

- [Momence Public API](https://apis.io/collections/momence/open-momence/)
- [Momence Public auth API](https://apis.io/collections/momence/open-momence-auth-api/)
- [Momence Public auth host API](https://apis.io/collections/momence/open-momence-host-api/)
- [Momence Public auth host-checkout API](https://apis.io/collections/momence/open-momence-host-checkout-api/)
- [Momence Public auth member-addresses API](https://apis.io/collections/momence/open-momence-member-addresses-api/)
- [Momence Public auth member API](https://apis.io/collections/momence/open-momence-member-api/)
- [Momence Public auth member-checkout API](https://apis.io/collections/momence/open-momence-member-checkout-api/)
- [Momence Public auth member-host API](https://apis.io/collections/momence/open-momence-member-host-api/)
- [Momence Public auth member-sessions API](https://apis.io/collections/momence/open-momence-member-sessions-api/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Momence Authentication](https://apis.io/security/momence/momence-authentication/)
- [Momence Domain Security](https://apis.io/security/momence/momence-domain-security/)

#### OAuth scopes (1)

The permissions the API asks for.

- [Momence Scopes](https://apis.io/scopes/momence/momence-scopes/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Momence Plans Pricing](https://apis.io/plans/momence/momence-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Momence Rate Limits](https://apis.io/rate-limits/momence/momence-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Momence Finops](https://apis.io/finops/momence/momence-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://momence.com/)
- [Documentation](https://api.docs.momence.com/)

## API Evangelist rating

**Kin Score 23.7** — emerging · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 66.1 |
| Contract quality | 40.9 |
| Contract governance | 0.0 |
| Operational transparency | 5.3 |
| Developer ergonomics | 26.2 |
| Access clarity | 7.9 |

**Agent readiness 27.2** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | documented (partial credit) |
| MCP Server | — |
| Auth Clarity | negotiable (partial credit) |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | partial |
| Rate Limit Signal | derived (partial credit) |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | documented (partial credit) |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |

**Regulatory alignment 19.6** — Payments

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/momence/](https://apis.io/providers/momence/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Momence: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/momence/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
