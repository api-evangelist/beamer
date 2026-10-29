# Beamer

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

Beamer is a changelog and notification center tool for announcing product updates, new features, and API changes to end users. It provides an embeddable feed widget, push notifications, email digests, and a public changelog page. The Beamer REST API enables programmatic management of posts, users, segments, and notification delivery. Beamer and Userflow now operate as one company, and Beamer's knowledge base has moved to help.userflow.com/beamer. The REST API is versioned at https://api.getbeamer.com/v0, documents 49 operations across posts, comments, reactions, feature requests, users, NPS, team and GDPR erasure, and authenticates with a single account-scoped API key sent in the Beamer-Api-Key header. Four webhook event types are published. No OpenAPI document, Postman collection or MCP server is served on any Beamer host.

**Areas:** Changelog · Deprecation · Notification · Product Updates · User Engagement · Webhook · NPS · Feedback

## Beamer on APIs.io

Everything profiled for Beamer is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/beamer/](https://apis.io/providers/beamer/)** — or go straight to one of the APIs or properties below.

### APIs (1)

- [Beamer API](https://apis.io/apis/beamer/beamer/) — The Beamer REST API provides programmatic access to changelog posts, user management, segmentation, and notification feeds. Key endpoints include unread…

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### AsyncAPI (1)

Event-driven and webhook contracts.

- [Beamer Webhooks](https://apis.io/asyncapis/beamer/beamer-webhooks/)

#### MCP servers (1)

Model Context Protocol servers that expose the API to agents.

- [Candidate MCP tool surface derived from the published API reference (no server exists)](https://apis.io/servers/beamer/candidate-mcp-tool-surface-derived-from-the-published-api-reference-no-server-exists/)

#### Security (4)

Authentication, trust centre, and vulnerability disclosure.

- [Beamer Authentication](https://apis.io/security/beamer/beamer-authentication/)
- [Beamer Domain Security](https://apis.io/security/beamer/beamer-domain-security/)
- [Beamer Trust Center](https://apis.io/security/beamer/beamer-trust-center/)
- [Beamer Vulnerability Disclosure](https://apis.io/security/beamer/beamer-vulnerability-disclosure/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Beamer Plans Pricing](https://apis.io/plans/beamer/beamer-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Beamer Rate Limits](https://apis.io/rate-limits/beamer/beamer-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Beamer Finops](https://apis.io/finops/beamer/beamer-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.getbeamer.com/)
- [Documentation](https://www.getbeamer.com/api)
- [Getting started](https://help.userflow.com/beamer/docs/how-to-install-beamer-using-our-api)
- [Pricing](https://www.getbeamer.com/pricing)
- [Sign up](https://app.getbeamer.com/auth/signup)
- [Support](https://www.getbeamer.com/contact)
- [Blog](https://www.getbeamer.com/blog)
- [Terms of service](https://www.getbeamer.com/terms-of-service)
- [Privacy policy](https://www.getbeamer.com/privacy-policy)
- [Status](https://status.getbeamer.com)

## API Evangelist rating

**Kin Score 59.8** — strong · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 73.2 |
| Contract quality | 39.0 |
| Contract governance | 0.0 |
| Operational transparency | 86.8 |
| Developer ergonomics | 50.0 |
| Access clarity | 92.1 |

**Agent readiness 25.2** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | — |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | documented (partial credit) |
| OpenAPI Examples | — |
| Rate Limit Signal | documented (partial credit) |
| Event Surface Described | yes |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | na |
| Operation Distinctiveness | na |

**Regulatory alignment 35.3** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/beamer/](https://apis.io/providers/beamer/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Beamer: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/beamer/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
