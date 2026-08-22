# Blynk (blynk)

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

Blynk is a low-code / no-code IoT software platform that helps companies prototype, deploy, and remotely manage connected devices and applications across consumer and commercial markets. The platform combines Blynk.Console (web dashboard), Blynk.Apps (white-labeled iOS / Android apps), Blynk.Edgent (device-side connectivity library), and Blynk.Cloud (managed backend) into a full-stack offering that removes the need to build custom IoT infrastructure. More than 5,000 companies and 1M+ developers use Blynk across agriculture, industrial monitoring, energy and HVAC, smart cities, smart buildings, and consumer products.

**URL:** [Visit APIs.json](https://raw.githubusercontent.com/api-evangelist/blynk/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags

 - IoT, Internet of Things, No-Code, Low-Code, Connected Devices, Device Management, Fleet Management, Mobile Apps, Dashboards, Telemetry, Firmware, Over The Air Updates, White Label, Embedded, Smart Home, Smart Buildings, Smart Cities, Industrial, Agriculture, Energy

## Timestamps

- **Created:** 2026-05-25
- **Modified:** 2026-05-25

## APIs

### Blynk Device HTTPS API
Token-authenticated REST API for individual devices to read and write datastream values, batch-update multiple datastreams, retrieve history, set widget and datastream properties, trigger log events, upload files, and read or update device metadata. Base URL is `https://{server}.blynk.cloud/external/api`.

**Human URL:** [https://docs.blynk.io/en/blynk.cloud/device-https-api](https://docs.blynk.io/en/blynk.cloud/device-https-api)

- [Documentation](https://docs.blynk.io/en/blynk.cloud/device-https-api)
- [Update Datastream Value](https://docs.blynk.io/en/blynk.cloud/device-https-api/update-datastream-value)
- [Get Datastream Value](https://docs.blynk.io/en/blynk.cloud/device-https-api/get-datastream-value)
- [Batch Update Datastreams](https://docs.blynk.io/en/blynk.cloud/device-https-api/batch-update-datastreams)
- [Trigger Log Event](https://docs.blynk.io/en/blynk.cloud/device-https-api/trigger-event)
- [Upload File](https://docs.blynk.io/en/blynk.cloud/device-https-api/upload-file)

### Blynk Platform HTTPS API
Enterprise-tier OAuth2 REST API for full CRUD across Blynk Cloud — devices, users, organizations, templates, automations, webhooks, and tags. Bearer tokens are obtained from `POST /oauth2/token`; rate-limited to 10,000 requests per minute per organization.

**Human URL:** [https://docs.blynk.io/en/blynk.cloud/platform-https-api](https://docs.blynk.io/en/blynk.cloud/platform-https-api)

- [Documentation](https://docs.blynk.io/en/blynk.cloud/platform-https-api)
- [Devices](https://docs.blynk.io/en/blynk.cloud/platform-https-api/devices.md)
- [Users](https://docs.blynk.io/en/blynk.cloud/platform-https-api/users.md)
- [Organizations](https://docs.blynk.io/en/blynk.cloud/platform-https-api/organizations.md)
- [Templates](https://docs.blynk.io/en/blynk.cloud/platform-https-api/templates.md)
- [Automations](https://docs.blynk.io/en/blynk.cloud/platform-https-api/automations.md)
- [Webhooks](https://docs.blynk.io/en/blynk.cloud/platform-https-api/webhooks.md)
- [Tags](https://docs.blynk.io/en/blynk.cloud/platform-https-api/tags.md)

### Blynk Device Streaming Protocol
Bi-directional, low-latency streaming protocol used by the Blynk Library and Blynk.Edgent to maintain a persistent link between MCUs (Arduino, ESP32, ESP8266, Particle, Raspberry Pi) and Blynk.Cloud. Surfaced to firmware developers as the Blynk Library C++ API.

**Human URL:** [https://docs.blynk.io/en/getting-started/intro](https://docs.blynk.io/en/getting-started/intro)

- [Blynk Library Firmware API](https://docs.blynk.io/en/blynk-library-firmware-api)
- [blynk-library (C++) — GitHub](https://github.com/blynkkk/blynk-library)

## Plans

| Plan | Price | Devices | Users | Data Retention | Messages | Notes |
|---|---|---|---|---|---|---|
| Free | $0 / month | 5 | 1 | 1 week | 100k / month | Entry-level exploration |
| Starter | $29 / month | 10 | 1 | 1 month | 10M / month | Hobby projects, PoCs |
| Prototype | $99 / month | 50 | 50 | 6 months | Unlimited | Prototyping tier |
| Production | $199–$1,099 / month | 100–1,000 | 100–1,000 | 12 months | Unlimited | 99.95% uptime SLA, SMS, priority support |
| Enterprise | Custom | Custom | Custom | Custom | Custom | White-label, on-prem option, 99.99% uptime SLA, dedicated DevOps |

## Common Resources

- [Website](https://blynk.io)
- [Documentation Portal](https://docs.blynk.io)
- [Getting Started](https://docs.blynk.io/en/getting-started)
- [Blynk.Console](https://blynk.cloud)
- [Blynk Mobile App (iOS)](https://apps.apple.com/us/app/blynk-iot/id1559317868)
- [Blynk Mobile App (Android)](https://play.google.com/store/apps/details?id=cloud.blynk)
- [Pricing](https://blynk.io/pricing)
- [Solutions](https://blynk.io/solutions)
- [Use Cases](https://blynk.io/use-cases)
- [Case Studies](https://blynk.io/case-studies)
- [Blog](https://blynk.io/resources/blog)
- [Community Forum](https://community.blynk.cc)
- [GitHub Organization (blynkkk)](https://github.com/blynkkk)
- [blynk-library (C++)](https://github.com/blynkkk/blynk-library)
- [Edgent-PlatformIO templates](https://github.com/Blynk-Technologies/Edgent-PlatformIO)
- [Blynk.NCP Arduino example](https://github.com/Blynk-Technologies/Blynk-NCP-Example-Arduino)
- [Blueprints](https://github.com/blynkkk/blueprints)
- [Security](https://blynk.io/security)
- [Terms of Service](https://blynk.io/terms-and-conditions)
- [Privacy Policy](https://blynk.io/privacy-policy)

## Features

- Drag-and-drop mobile app builder for iOS and Android (Blynk.Apps)
- Web console for device management, dashboards, and fleet operations (Blynk.Console)
- White-label branded apps for commercial deployments
- Over-the-air (OTA) firmware updates with rollout management
- Device provisioning, claiming, and lifecycle management
- Multi-tenancy with organizations and sub-organizations
- Real-time bi-directional streaming protocol via Blynk Library
- Device HTTPS API for token-authenticated telemetry and commands
- Platform HTTPS API with OAuth2 for full CRUD across devices, users, templates, automations, webhooks, tags
- MQTT support for device connectivity
- Webhooks for outbound integrations
- Automations engine (event-driven rules) and scheduling
- Multi-protocol device connectivity — Wi-Fi, Ethernet, Cellular, LoRaWAN, Satellite
- Pre-integrated with hundreds of MCU boards (Arduino, ESP32, ESP8266, Raspberry Pi, Particle, Nordic)
- Blynk.Edgent — packaged device-side connectivity stack
- Blynk.NCP — network co-processor reference design
- SOC 2 compliant managed cloud infrastructure (Blynk.Cloud)
- On-premise / private-server option for Enterprise customers
- SMS and push notifications, email alerts
- Custom branding, app store publishing for white-label apps
- Rate limit of 10,000 Platform API requests per minute per organization
- 99.95% uptime SLA on Production plan, 99.99% on Enterprise

## Maintainers

- **Kin Lane** — kin@apievangelist.com
