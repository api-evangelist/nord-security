# Nord Security

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

Nord Security is a Lithuania-founded digital security and privacy company whose consumer and business portfolio spans NordVPN, NordPass, NordLocker, NordLayer (network access security for business), NordProtect/Coveron, Saily (eSIM) and NordStellar (external threat exposure management). Its developer-facing surface is concentrated in NordStellar, which publishes five OpenAPI-described enterprise APIs — the Enterprise Data (Dark Web) API, Company Risk Scoring API, Cybersec API, Partners API and Platform Integrations API — plus a remote MCP server, sixteen provider-published agent skills, an n8n community node and SIEM integrations (Microsoft Sentinel, CrowdStrike). NordLayer adds SCIM 2.0 user provisioning and a partner/MSP API key surface, while the NordSecurity GitHub organization publishes the NordVPN Linux client together with 43 gRPC/protobuf service definitions covering the daemon, meshnet, fileshare, norduser and telemetry surfaces.

**Areas:** Cybersecurity · Threat Intelligence · Dark Web Monitoring · Attack Surface Management · Breach Intelligence · VPN · Password Management · Network Security · Zero Trust · Privacy · MCP · Agent Skills

## Nord Security on APIs.io

Everything profiled for Nord Security is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/nord-security/](https://apis.io/providers/nord-security/)** — or go straight to one of the APIs or properties below.

### APIs (35)

- [NordStellar MCP Server](https://apis.io/apis/nord-security/nordstellar-mcp-server/) — Remote MCP server that lets any MCP-compatible assistant query the NordStellar platform in natural language. Clients connect through the open-source…
- [NordLayer Partner / MSP API](https://apis.io/apis/nord-security/nordlayer-partner-msp-api/) — Partner-facing API behind the NordLayer Service Management Portal. API keys are self-issued in the SMP Integrations tab with expiry and one-time visibility,…
- [NordLayer SCIM 2.0 Provisioning](https://apis.io/apis/nord-security/nordlayer-scim-20-provisioning/) — SCIM-based user provisioning surface used to create users, update user attributes, deactivate users and push groups from Okta and Microsoft Entra ID into…
- [NordPass Provider API](https://apis.io/apis/nord-security/nordpass-provider-api/) — Usage-reporting API for NordPass provider/MSP partners, documented in the NordPass help centre. NordPass separately supports SCIM provisioning from Okta and…
- [NordVPN Public Server API](https://apis.io/apis/nord-security/nordvpn-public-server-api/) — Unauthenticated JSON API that NordVPN's own clients and the open-source Linux client use to enumerate the server estate — servers, countries, cities, groups…
- [Nord Security API User Management API](https://apis.io/apis/nord-security/nord-security-api-user-management-api/) — Endpoints for administering API keys, and web hook settings. These operations enable administrators to list and manage API keys, update webhook configuration.
- [Nord Security Applications API](https://apis.io/apis/nord-security/nord-security-applications-api/) — The Applications API from Nord Security — 1 operation(s) for applications.
- [Nord Security AUC API](https://apis.io/apis/nord-security/nord-security-auc-api/) — The AUC API from Nord Security — 2 operation(s) for auc.
- [Nord Security Breached Databases API](https://apis.io/apis/nord-security/nord-security-breached-databases-api/) — Endpoints for retrieving detailed metadata about breach origins, including databases. These operations provide comprehensive context about database breach…
- [Nord Security Company Details API](https://apis.io/apis/nord-security/nord-security-company-details-api/) — The Company Details API from Nord Security — 4 operation(s) for company details.
- [Nord Security Cookie Intelligence API](https://apis.io/apis/nord-security/nord-security-cookie-intelligence-api/) — Endpoints for comprehensive cookie data monitoring in data breaches, including zero-knowledge search capabilities. These operations enable robust cookie…
- [Nord Security Cookies API](https://apis.io/apis/nord-security/nord-security-cookies-api/) — The Cookies API from Nord Security — 1 operation(s) for cookies.
- [Nord Security Credential Lists API](https://apis.io/apis/nord-security/nord-security-credential-lists-api/) — Endpoints for retrieving detailed metadata about breach origins, including credential lists. These operations provide comprehensive context about credential…
- [Nord Security Credit Card Intelligence API](https://apis.io/apis/nord-security/nord-security-credit-card-intelligence-api/) — Endpoints for comprehensive credit card data monitoring in data breaches, including zero-knowledge search capabilities. These operations enable robust…
- [Nord Security Crypto Addresses API](https://apis.io/apis/nord-security/nord-security-crypto-addresses-api/) — The Crypto Addresses API from Nord Security — 1 operation(s) for crypto addresses.
- [Nord Security Dark Web Intelligence API](https://apis.io/apis/nord-security/nord-security-dark-web-intelligence-api/) — Endpoints for searching scraped content from the dark web
- [Nord Security Domain Intelligence API](https://apis.io/apis/nord-security/nord-security-domain-intelligence-api/) — Endpoints for investigating domain exposure in data breaches, including detailed breach information and compromise analysis. These operations support…
- [Nord Security Email Intelligence API](https://apis.io/apis/nord-security/nord-security-email-intelligence-api/) — Endpoints for comprehensive email address monitoring in data breaches, including detailed breach information, password exposure, and statistical analysis.…
- [Nord Security Events API](https://apis.io/apis/nord-security/nord-security-events-api/) — The Events API from Nord Security — 36 operation(s) for events.
- [Nord Security Files API](https://apis.io/apis/nord-security/nord-security-files-api/) — The Files API from Nord Security — 8 operation(s) for files.
- [Nord Security Lists API](https://apis.io/apis/nord-security/nord-security-lists-api/) — The Lists API from Nord Security — 3 operation(s) for lists.
- [Nord Security Malware Logs Intelligence API](https://apis.io/apis/nord-security/nord-security-malware-logs-intelligence-api/) — Endpoints for retrieving detailed metadata about breach origins, including malware logs. These operations provide comprehensive context about malware logs…
- [Nord Security ML Models API](https://apis.io/apis/nord-security/nord-security-ml-models-api/) — The ML Models API from Nord Security — 2 operation(s) for ml models.
- [Nord Security National Identification Number Intelligence API](https://apis.io/apis/nord-security/nord-security-national-identification-number-intelligence-api/) — Endpoints for comprehensive national identification number data monitoring in data breaches, including zero-knowledge search capabilities. These operations…
- [Nord Security Partners API](https://apis.io/apis/nord-security/nord-security-partners-api/) — The Partners API from Nord Security — 4 operation(s) for partners.
- [Nord Security Password Intelligence API](https://apis.io/apis/nord-security/nord-security-password-intelligence-api/) — Endpoints for comprehensive password data monitoring in data breaches, including zero-knowledge search capabilities. These operations enable robust password…
- [Nord Security Phone Intelligence API](https://apis.io/apis/nord-security/nord-security-phone-intelligence-api/) — Endpoints for investigating phone number exposure in data breaches, including detailed breach information and compromise analysis. These operations support…
- [Nord Security Profiling API](https://apis.io/apis/nord-security/nord-security-profiling-api/) — Endpoints for generating OSINT-based profiling reports on email addresses and phone numbers. Reports aggregate data from external intelligence sources,…
- [Nord Security Projects API](https://apis.io/apis/nord-security/nord-security-projects-api/) — The Projects API from Nord Security — 6 operation(s) for projects.
- [Nord Security Results API](https://apis.io/apis/nord-security/nord-security-results-api/) — The Results API from Nord Security — 8 operation(s) for results.
- [Nord Security Scanning API](https://apis.io/apis/nord-security/nord-security-scanning-api/) — The Scanning API from Nord Security — 2 operation(s) for scanning.
- [Nord Security Subscription Management API](https://apis.io/apis/nord-security/nord-security-subscription-management-api/) — Endpoints for managing user subscriptions to data breach monitoring services. These operations enable administrators to create, update, and delete…
- [Nord Security URL scanner API](https://apis.io/apis/nord-security/nord-security-url-scanner-api/) — The URL scanner API from Nord Security — 1 operation(s) for url scanner.
- [Nord Security URLS API](https://apis.io/apis/nord-security/nord-security-urls-api/) — The Urls API from Nord Security — 4 operation(s) for urls.
- [Nord Security Utility Endpoints API](https://apis.io/apis/nord-security/nord-security-utility-endpoints-api/) — Utility endpoints for supporting zero-knowledge functionalities, such as retrieving salts. These operations are essential for the proper functioning of…

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### MCP servers (1)

Model Context Protocol servers that expose the API to agents.

- [nordstellar](https://apis.io/servers/nord-security/nordstellar/)

#### Collections (7)

Postman and Open Collection request collections.

- [Company Risk Scoring API](https://apis.io/collections/nord-security/open-nord-security-nordstellar-company-risk-scoring-api/)
- [Cybersec API](https://apis.io/collections/nord-security/open-nord-security-nordstellar-cybersec-api/)
- [NordStellar Enterprise Data API](https://apis.io/collections/nord-security/open-nord-security-nordstellar-enterprise-data-api/)
- [Nordstellar Partners API](https://apis.io/collections/nord-security/open-nord-security-nordstellar-partners-api/)
- [Platform Integration API](https://apis.io/collections/nord-security/open-nord-security-nordstellar-platform-integration-api-v1/)
- [Platform Integration API](https://apis.io/collections/nord-security/open-nord-security-nordstellar-platform-integration-api-v2/)
- [Platform Integration API](https://apis.io/collections/nord-security/open-nord-security-nordstellar-platform-integration-api-v3/)

#### Overlays (2)

OpenAPI overlays, including conversational phrasing for each operation.

- [Nord Security Nordstellar Enterprise Data Api Overlay](https://apis.io/overlays/nord-security/nord-security-nordstellar-enterprise-data-api-overlay/)
- [Nord Security Nordstellar Platform Integration Api V3 Overlay](https://apis.io/overlays/nord-security/nord-security-nordstellar-platform-integration-api-v3-overlay/)

#### Security (4)

Authentication, trust centre, and vulnerability disclosure.

- [Nord Security Authentication](https://apis.io/security/nord-security/nord-security-authentication/)
- [Nord Security Domain Security](https://apis.io/security/nord-security/nord-security-domain-security/)
- [Nord Security Trust Center](https://apis.io/security/nord-security/nord-security-trust-center/)
- [Nord Security Vulnerability Disclosure](https://apis.io/security/nord-security/nord-security-vulnerability-disclosure/)

#### Rate limits (1)

Published request limits.

- [Nord Security Rate Limits](https://apis.io/rate-limits/nord-security/nord-security-rate-limits/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://nordsecurity.com/)
- [Documentation](https://docs.nordstellar.com/)
- [Getting started](https://docs.nordstellar.com/quick-start)
- [API reference](https://docs.nordstellar.com/enterprise-apis/product-integrations/swagger)
- [Pricing](https://nordstellar.com/pricing/)
- [Sign up](https://platform.nordstellar.com/login)
- [Support](https://nordsecurity.com/contact-us)
- [Blog](https://nordsecurity.com/blog/)
- [Security](https://nordlayer.com/.well-known/security.txt)
- [Compliance](https://nordlayer.com/compliance/)
- [Terms of service](https://business.nordsec.com/legal/terms-of-service)
- [Privacy policy](https://nordsecurity.com/privacy-policy)
- [GitHub](https://github.com/NordSecurity)
- [Status](https://status.nordvpn.com/)

## API Evangelist rating

**Kin Score 56.9** — strong · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 80.0 |
| Contract quality | 52.6 |
| Contract governance | 4.5 |
| Operational transparency | 31.6 |
| Developer ergonomics | 71.4 |
| Access clarity | 47.4 |

**Agent readiness 42.9** — agent-ready (gated down from agent-native)

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | — |
| Reversibility Documented | — |
| MCP Server | verified |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | verified |
| OpenAPI Examples | verified |
| Rate Limit Signal | verified |
| Event Surface Described | — |
| Agent Skills | yes |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | partial |
| Operation Distinctiveness | — |

**Regulatory alignment 35.3** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/nord-security/](https://apis.io/providers/nord-security/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Nord Security: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/nord-security/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
