# Beamer (beamer)

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

Beamer is a changelog and notification center tool for announcing product updates, new features, and API changes to end users. It provides an embeddable feed widget, push notifications, email digests, and a public changelog page. The Beamer REST API enables programmatic management of posts, users, segments, and notification delivery. Beamer is now part of the Userflow product suite. The API uses API key authentication and supports OpenAPI specifications and Postman collections.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/beamer/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Changelog, Deprecation, Notifications, Product Updates, User Engagement

## Timestamps

- **Created:** 2026-03-29
- **Modified:** 2026-04-19

## APIs

### Beamer API
The Beamer REST API provides programmatic access to changelog posts, user management, segmentation, and notification feeds. Key endpoints include unread count retrieval, post creation and management, user profile updates, and segment management. Authentication uses an API key from Beamer settings.

**Human URL:** [https://www.getbeamer.com/api](https://www.getbeamer.com/api)

#### Tags:

 - Changelog, Notifications, Product Updates

#### Properties

- [Documentation](https://www.getbeamer.com/api)
- [APIReference](https://www.getbeamer.com/api)
- [Authentication](https://www.getbeamer.com/api)

## Common Properties

- [Website](https://www.getbeamer.com/)
- [Documentation](https://www.getbeamer.com/api)
- [GettingStarted](https://www.getbeamer.com/help/how-to-install-beamer-using-our-api)
- [StatusPage](https://status.getbeamer.com)

## Features

| Name | Description |
|------|-------------|
| Changelog Feed Widget | Embeddable changelog widget that displays product updates to users within your application. |
| Push Notifications | In-app push notifications to alert users about new features and product updates. |
| Email Digests | Automated email digest delivery of changelog posts to user segments. |
| User Segmentation | Target changelog announcements and notifications to specific user segments based on attributes. |
| Unread Count API | REST API endpoint to retrieve unread notification count for individual users. |
| Public Changelog | Hosted public changelog page for external users, prospects, and documentation. |

## Use Cases

| Name | Description |
|------|-------------|
| Product Update Announcements | Announce new product features, improvements, and bug fixes to end users via in-app notifications. |
| API Changelog | Maintain a dedicated API changelog for developers tracking breaking changes, deprecations, and new endpoints. |
| User Onboarding | Surface new features to relevant users through targeted notifications and changelog posts. |
| Release Notes Automation | Automate release note publishing from CI/CD pipelines using the Beamer API. |

## Integrations

| Name | Description |
|------|-------------|
| Zapier | Automation integration connecting Beamer with thousands of apps via Zapier workflows. |
| Segment | Customer data platform integration for sending Beamer user events and changelog views to Segment. |
| Intercom | Customer messaging platform integration enabling Beamer notifications alongside Intercom conversations. |
| ActiveCampaign | Email marketing integration for delivering Beamer changelog digests through ActiveCampaign. |
| WordPress | WordPress plugin for embedding Beamer changelog feed in WordPress websites. |

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
