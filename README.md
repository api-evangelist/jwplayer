# JW Player (jwplayer)

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

JW Player is a video player and streaming platform offering REST APIs for media management, playlist creation, player configuration, analytics, and live stream orchestration. Now operating as JWP Connatix, the platform serves publishers, broadcasters, and OTT operators with a suite of APIs covering the full video lifecycle — from upload and transcoding through delivery, monetization, and analytics. The Management API v2 enables programmatic control over media libraries, players, playlists, live broadcasts, DRM policies, advertising configurations, and webhooks. The Delivery API provides high-availability CDN-backed content distribution globally.

APIs.json: https://raw.githubusercontent.com/api-evangelist/jwplayer/refs/heads/main/apis.yml

Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=jwplayer-api-evangelist&utm_content=repo

## Tags

Video, Streaming, Media Management, Live Streaming, OTT, Playlists, Analytics, DRM, Advertising, Webhooks, Player

## APIs

| Name | Description |
|---|---|
| JW Player Management API v2 | Read-write REST API for programmatically managing media libraries, players, playlists, live streams, advertising, DRM, transformations, and webhooks. Authenticated via Bearer token with a 60 req/min rate limit. |
| JW Player Delivery API | High-availability CDN-backed API for content embedding, playback metadata, streaming manifests, and SSAI. Calls do not count against the Management API rate limit. |
| JW Player JavaScript Player API | Client-side JavaScript API for controlling the embedded JW Player, exposing playback, playlist, advertising, and analytics event methods. |

## Plans, Rate Limits, and FinOps

| Resource | Description | File |
|---|---|---|
| Plans | Three tiers: Express Edition, Publishing, Broadcasting — all custom-quoted, no public pricing | [plans/jwplayer-plans-pricing.yml](plans/jwplayer-plans-pricing.yml) |
| Rate Limits | Management API: 60 requests/minute per token or IP; Delivery API has no published per-token limit | [rate-limits/jwplayer-rate-limits.yml](rate-limits/jwplayer-rate-limits.yml) |
| FinOps | FOCUS-aligned cost optimization guidance for hours managed, transcoding, CDN delivery, and live ingest | [finops/jwplayer-finops.yml](finops/jwplayer-finops.yml) |

## Timestamps

- Created: 2026-06-12
- Modified: 2026-06-12

## Common

| Type | URL |
|---|---|
| Website | https://jwplayer.com |
| Documentation | https://docs.jwplayer.com |
| GitHub | https://github.com/jwplayer |
| LinkedIn | https://www.linkedin.com/company/jwplayer |
| Blog | https://jwx.com/blog |
| Pricing | https://jwx.com/video-management-delivery-pricing |
| Status Page | https://status.jwplayer.com |
| X | https://twitter.com/jwdevelopers |

## Maintainers

| Name | Email |
|---|---|
| Kin Lane | kin@apievangelist.com |
