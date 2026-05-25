# Blynk (blynk)

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
