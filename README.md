# Blynk

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

Blynk is a low-code / no-code IoT software platform that helps companies prototype, deploy, and remotely manage connected devices and applications across consumer and commercial markets. The platform combines four components — Blynk.Console (web dashboard), Blynk.Apps (white-labeled iOS and Android apps), Blynk.Edgent (device-side connection library), and Blynk.Cloud (managed backend) — into a full-stack offering that removes the need to build custom IoT infrastructure. Developers can build interactive mobile and web dashboards with a drag-and-drop builder, connect hardware over Wi-Fi, Cellular, LoRaWAN, Ethernet, or satellite, and operate fleets with provisioning, OTA firmware updates, multi-tenancy, automations, webhooks, and SOC 2 cloud infrastructure. Commercial customers use Blynk for branded consumer products, industrial monitoring, agriculture, energy and HVAC, smart cities, and smart buildings, with more than 5,000 companies and 1M+ developers on the platform. Blynk exposes two HTTPS REST APIs — the Device HTTPS API for telemetry and command exchange from individual hardware units, and the Platform HTTPS API (Enterprise plan) for full programmatic CRUD over devices, users, organizations, templates, automations, webhooks, and tags using OAuth2 client-credential authentication.

**Areas:** IoT · No-Code · Low-Code · Connected Devices · Device Management · Fleet Management · Mobile App · Dashboards · Telemetry · Firmware · Over-the-Air Updates · White Label

## Blynk on APIs.io

Everything profiled for Blynk is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/blynk/](https://apis.io/providers/blynk/)** — or go straight to one of the APIs or properties below.

### APIs (3)

- [Blynk Device HTTPS API](https://apis.io/apis/blynk/blynk-device-https-api/) — Token-authenticated HTTPS REST API used by individual devices to read and write datastream values, batch update multiple datastreams, retrieve historical…
- [Blynk Platform HTTPS API](https://apis.io/apis/blynk/blynk-platform-https-api/) — Enterprise-tier OAuth2 REST API for full programmatic CRUD across Blynk Cloud tenancy. Resources include devices (create from template, list, search, online…
- [Blynk Device Streaming Protocol](https://apis.io/apis/blynk/blynk-device-streaming-protocol/) — Bi-directional low-latency streaming connection protocol used by the Blynk Library and Blynk.Edgent to maintain a persistent link between devices and…

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Security (1)

Authentication, trust centre, and vulnerability disclosure.

- [Blynk Domain Security](https://apis.io/security/blynk/blynk-domain-security/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://blynk.io)
- [Documentation](https://docs.blynk.io/en/getting-started/intro)
- [Getting started](https://docs.blynk.io/en/getting-started)
- [Pricing](https://blynk.io/pricing)
- [Support](https://blynk.io/contact-us)
- [Blog](https://blynk.io/resources/blog)
- [Security](https://blynk.io/security)
- [Terms of service](https://blynk.io/terms-and-conditions)
- [Privacy policy](https://blynk.io/privacy-policy)
- [GitHub](https://github.com/blynkkk)

## API Evangelist rating

**Kin Score 27.5** — thin · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 62.5 |
| Contract quality | 6.4 |
| Contract governance | 0.0 |
| Operational transparency | 26.3 |
| Developer ergonomics | 54.8 |
| Access clarity | 27.6 |

**Agent readiness 10.2** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | — |
| Agentic Access | — |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | documented (partial credit) |
| Rate Limit Signal | documented (partial credit) |
| Event Surface Described | unknown |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |

**Regulatory alignment 13.1** — Energy & Utilities

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/blynk/](https://apis.io/providers/blynk/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Blynk: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/blynk/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
