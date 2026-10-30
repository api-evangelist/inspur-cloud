# Inspur Cloud

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

Inspur Cloud (浪潮云) is the public-cloud arm of the Chinese IT conglomerate Inspur Group, operating from cloud.inspur.com across the cn-north-3 (华北三), cn-south-1 (华南一) and cn-east-1 (华东一) regions. It publishes a broad IaaS/PaaS catalog — 94 products documented in its GitBook help centre — of which at least 16 ship a public HTTP API reference covering elastic compute (ECS), bare metal (CPS), block storage (EBS), backup (CBS), VPC networking, elastic IP, load balancing, IAM, RDS for MySQL, time-series database, container engine, blockchain and an S3-compatible object storage service (OSS). APIs are authenticated with an AK/SK request signature (x-secret-id / x-sign / x-time / x-random headers) or an IAM-issued bearer token. No OpenAPI, AsyncAPI or other machine-readable contract is published: the entire surface is hand-written HTML reference documentation in Simplified Chinese.

**Areas:** Cloud · Infrastructure · Compute · Storage · Networking · Object Storage · Identity · Database · Containers · IoT · Blockchain · China

## Inspur Cloud on APIs.io

Everything profiled for Inspur Cloud is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/inspur-cloud/](https://apis.io/providers/inspur-cloud/)** — or go straight to one of the APIs or properties below.

### APIs (18)

- [Inspur Cloud Elastic Cloud Server (ECS) API](https://apis.io/apis/inspur-cloud/inspur-cloud-elastic-cloud-server-ecs-api/) — REST API for Inspur Cloud's elastic compute service: create, start, stop, reboot, resize, rebuild and delete cloud servers, manage private images,…
- [Inspur Cloud Physical Server (CPS) API](https://apis.io/apis/inspur-cloud/inspur-cloud-physical-server-cps-api/) — REST API for Inspur Cloud's bare-metal cloud physical host service — list, start, stop, reboot and inspect dedicated physical servers. 14 documented operations.
- [Inspur Cloud Elastic Block Storage (EBS) API](https://apis.io/apis/inspur-cloud/inspur-cloud-elastic-block-storage-ebs-api/) — REST API for Inspur Cloud block storage — create, extend, renew, attach, detach and delete cloud disks, plus backup creation, restore, statistics and backup…
- [Inspur Cloud Backup Service (CBS) API](https://apis.io/apis/inspur-cloud/inspur-cloud-backup-service-cbs-api/) — REST API for Inspur Cloud's cloud backup service, covering backup jobs, restore and backup policy operations. 10 documented operations.
- [Inspur Cloud Virtual Private Cloud (VPC) API](https://apis.io/apis/inspur-cloud/inspur-cloud-virtual-private-cloud-vpc-api/) — REST API for Inspur Cloud software-defined networking — create and manage VPCs, subnets, route tables, routes, security groups and security-group rules. 26…
- [Inspur Cloud Elastic IP (EIP) API](https://apis.io/apis/inspur-cloud/inspur-cloud-elastic-ip-eip-api/) — REST API for elastic public IP addresses, shared bandwidth packages and the IPv6 translation service — create, bind, unbind, resize bandwidth, renew and…
- [Inspur Cloud IPv6 Translation Service (IPTS) API](https://apis.io/apis/inspur-cloud/inspur-cloud-ipv6-translation-service-ipts-api/) — REST API for the IPv6 translation service that fronts IPv4 resources with IPv6 addresses. 6 documented operations, served from the EIP host.
- [Inspur Cloud Server Load Balancer (SLB) API](https://apis.io/apis/inspur-cloud/inspur-cloud-server-load-balancer-slb-api/) — REST API for Inspur Cloud load balancing: load balancer, listener, backend server group, certificate and forwarding-strategy management, plus EIP binding.…
- [Inspur Cloud Identity and Access Management (IAM) API](https://apis.io/apis/inspur-cloud/inspur-cloud-identity-and-access-management-iam-api/) — REST API for Inspur Cloud identity — services and resource-type discovery, policy CRUD and attach/detach, user and user-group management, MFA/TOTP binding,…
- [Inspur Cloud RDS for MySQL API](https://apis.io/apis/inspur-cloud/inspur-cloud-rds-for-mysql-api/) — REST API for Inspur Cloud's managed MySQL relational database service — instance lifecycle, instance classes, database and account management, backup,…
- [Inspur Cloud Object Storage Service (OSS) API](https://apis.io/apis/inspur-cloud/inspur-cloud-object-storage-service-oss-api/) — S3-compatible REST API for Inspur Cloud object storage: ListBuckets, PutBucket, HeadBucket, DeleteBucket, bucket ACL/lifecycle/CORS/versioning/encryption/…
- [Inspur Cloud Time Series Database (TSDB) API](https://apis.io/apis/inspur-cloud/inspur-cloud-time-series-database-tsdb-api/) — REST API for Inspur Cloud's managed time-series database — instance lifecycle, parameter configuration, data write and query, OpenTSDB-compatible endpoints,…
- [Inspur Cloud Container Engine (ICE/CKS) API](https://apis.io/apis/inspur-cloud/inspur-cloud-container-engine-icecks-api/) — REST API for Inspur Cloud's Kubernetes container engine — application and instance management, service mesh (VirtualService) discovery, service gateway…
- [Inspur Cloud Blockchain Service (IBaaS) API](https://apis.io/apis/inspur-cloud/inspur-cloud-blockchain-service-ibaas-api/) — REST API for Inspur Cloud blockchain-as-a-service instance management — name checking, instance listing, instance detail and deletion. 5 documented operations.
- [Inspur Cloud Consortium Chain Service (ACS) API](https://apis.io/apis/inspur-cloud/inspur-cloud-consortium-chain-service-acs-api/) — REST API for Inspur Cloud's consortium blockchain service — instance management and renewal orders. 6 documented operations.
- [Inspur Cloud IBot Conversational AI API](https://apis.io/apis/inspur-cloud/inspur-cloud-ibot-conversational-ai-api/) — REST API for Inspur Cloud's IBot intelligent assistant — POST /qa/bot/sdk/talk for a conversation turn, /qa/bot/sdk/similarities for a similar-question list…
- [Inspur Cloud IoT Platform API](https://apis.io/apis/inspur-cloud/inspur-cloud-iot-platform-api/) — Cloud-side and device-side API for the Inspur Cloud IoT platform, with an MQTT device protocol, device dynamic registration and a C device SDK built on mbedTLS.
- [Inspur Cloud API Gateway (APIG)](https://apis.io/apis/inspur-cloud/inspur-cloud-api-gateway-apig/) — Inspur Cloud's API Gateway product, which lets customers publish their own APIs with Swagger import/export, traffic control, circuit breaking, anti-replay,…

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### MCP servers (1)

Model Context Protocol servers that expose the API to agents.

- [inspur-cloud-mcp.yml](https://apis.io/servers/inspur-cloud/inspur-cloud-mcp-yml/)

#### Security (3)

Authentication, trust centre, and vulnerability disclosure.

- [Inspur Cloud Authentication](https://apis.io/security/inspur-cloud/inspur-cloud-authentication/)
- [Inspur Cloud Domain Security](https://apis.io/security/inspur-cloud/inspur-cloud-domain-security/)
- [Inspur Cloud Vulnerability Disclosure](https://apis.io/security/inspur-cloud/inspur-cloud-vulnerability-disclosure/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Inspur Cloud Plans Pricing](https://apis.io/plans/inspur-cloud/inspur-cloud-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Inspur Cloud Rate Limits](https://apis.io/rate-limits/inspur-cloud/inspur-cloud-rate-limits/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://cloud.inspur.com/)
- [Documentation](https://console1.cloud.inspur.com/document/)
- [Getting started](https://console1.cloud.inspur.com/document/ecs/3-quickstart.html)
- [API reference](https://console1.cloud.inspur.com/document/ecs/5-API/5.1-1-api-overview.html)
- [Pricing](https://console1.cloud.inspur.com/document/ecs/2-product-pricing.html)
- [Sign up](https://console1.cloud.inspur.com/)
- [Support](https://cloud.inspur.com/support/index.html)
- [Blog](https://cloud.inspur.com/about-inspurcloud/about-us/news/index.html)
- [Security](https://www.inspur.com/lcjtww/2312126/2432763/index.html)
- [Terms of service](https://console1.cloud.inspur.com/document/declaration/protocol/client/client.html)
- [Privacy policy](https://cloud.inspur.com/privacy-policy/index.html)
- [GitHub](https://github.com/OpenInspur)

## API Evangelist rating

**Kin Score 34.1** — thin · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 62.5 |
| Contract quality | 0.0 |
| Contract governance | 0.0 |
| Operational transparency | 28.9 |
| Developer ergonomics | 64.3 |
| Access clarity | 44.7 |

**Agent readiness 7.9** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | — |
| Agentic Access | — |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | documented (partial credit) |
| OpenAPI Examples | — |
| Rate Limit Signal | documented (partial credit) |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |

**Regulatory alignment 30.4** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/inspur-cloud/](https://apis.io/providers/inspur-cloud/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Inspur Cloud: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/inspur-cloud/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
