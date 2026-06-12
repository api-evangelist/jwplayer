# JW Player (jwplayer)

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
