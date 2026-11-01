# University of Michigan-Ann Arbor

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

The University of Michigan-Ann Arbor is a public research university (QS World University Rankings 2025 #20-21, United States), a member of the Association of American Universities and the Big Ten Academic Alliance. Its programmable footprint is large in aggregate and almost entirely closed to the public. The enterprise estate — MCommunity directory, Schedule of Classes, class rosters, room scheduling and other institutional data — sits behind the U-M ITS API Directory on Google Apigee X, which cannot be browsed, let alone called, without a U-M uniqname, Duo two-factor authentication and presence on the U-M network or VPN. What is genuinely open and genuinely U-M's own is library and identity infrastructure: the Deep Blue Documents DSpace repository publishes a fully working OAI-PMH 2.0 harvesting endpoint on a umich.edu host (all six verbs verified live, twelve metadata formats, 726 sets, records back to 2005), and U-M ITS Identity and Access Management operates its own Shibboleth SAML 2.0 identity provider registered in InCommon, with public SAML and OIDC integration examples on GitHub. U-M Library is a DataCite direct member (symbol UMICH, five repositories) and a Crossref member (prefix 10.3998). Around those sit smaller institution-run surfaces — the Magic Bus transit API and Deep Blue Data — and one large vendor tenancy, Canvas at umich.instructure.com, whose contract belongs to Instructure and is not stored here. U-M publishes no public developer portal, no OpenAPI, no changelog and no API terms of service. Most of the umich.edu estate returns a Cloudflare bot challenge to automated clients, so several pointers below are documented-and-live rather than machine-readable.

**Areas:** University · Higher Education · Education · Public Research University · United States · Michigan · Big Ten · Association of American Universities · Research Data · Institutional Repository · Identity Federation · OAI-PMH

## University of Michigan-Ann Arbor on APIs.io

Everything profiled for University of Michigan-Ann Arbor is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/university-of-michigan-ann-arbor/](https://apis.io/providers/university-of-michigan-ann-arbor/)** — or go straight to one of the APIs or properties below.

### APIs (7)

- [U-M Shibboleth Identity Provider (InCommon)](https://apis.io/apis/university-of-michigan-ann-arbor/shibboleth-idp/) — The University of Michigan's own Shibboleth SAML 2.0 identity provider, and the most unambiguously institution-operated machine-readable surface U-M…
- [U-M ITS API Directory](https://apis.io/apis/university-of-michigan-ann-arbor/api-directory/) — Enterprise API directory and gateway operated by U-M Information and Technology Services on Google Apigee X (migrated from IBM API Connect v5 in 2024),…
- [Deep Blue Data REST API](https://apis.io/apis/university-of-michigan-ann-arbor/deep-blue-data/) — Public REST API for Deep Blue Data, the University of Michigan Library's open repository for research datasets produced by U-M researchers, with DataCite…
- [Magic Bus (U-M Transit) BusTime API](https://apis.io/apis/university-of-michigan-ann-arbor/magic-bus/) — Real-time campus transit API for U-M's Magic Bus service, served from a U-M host on Clever Devices BusTime. Live and gated by an API access key — GET…
- [Materials Commons](https://apis.io/apis/university-of-michigan-ann-arbor/materials-commons/) — Materials-science data repository for storing, sharing and publishing research datasets and workflows, operated by the PRISMS Center at the University of…
- [Canvas LMS (U-M tenancy on Instructure)](https://apis.io/apis/university-of-michigan-ann-arbor/canvas-lms/) — The University of Michigan's Canvas learning management system tenancy. The courses, the enrollments and the data are U-M's; the API contract is…
- [University of Michigan-Ann Arbor Repository API](https://apis.io/apis/university-of-michigan-ann-arbor/university-of-michigan-ann-arbor-repository-api/) — Repository-level description and capability discovery.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### JSON Schema (1)

The data models the API reads and writes.

- [Deep Blue Documents OAI-PMH Response](https://apis.io/schemas/university-of-michigan-ann-arbor/university-of-michigan-ann-arbor-oai-pmh/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [University Of Michigan Ann Arbor Context](https://apis.io/jsonld/university-of-michigan-ann-arbor/university-of-michigan-ann-arbor-context/)

#### Governance rules (1)

Spectral rulesets for the provider's contracts.

- [University of Michigan-Ann Arbor API Rules](https://apis.io/rules/university-of-michigan-ann-arbor/university-of-michigan-ann-arbor-rules/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [University Of Michigan Ann Arbor Authentication](https://apis.io/security/university-of-michigan-ann-arbor/university-of-michigan-ann-arbor-authentication/)
- [University Of Michigan Ann Arbor Domain Security](https://apis.io/security/university-of-michigan-ann-arbor/university-of-michigan-ann-arbor-domain-security/)

#### OAuth scopes (1)

The permissions the API asks for.

- [University Of Michigan Ann Arbor Scopes](https://apis.io/scopes/university-of-michigan-ann-arbor/university-of-michigan-ann-arbor-scopes/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [University Of Michigan Ann Arbor Plans Pricing](https://apis.io/plans/university-of-michigan-ann-arbor/university-of-michigan-ann-arbor-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [University Of Michigan Ann Arbor Rate Limits](https://apis.io/rate-limits/university-of-michigan-ann-arbor/university-of-michigan-ann-arbor-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [University Of Michigan Ann Arbor Finops](https://apis.io/finops/university-of-michigan-ann-arbor/university-of-michigan-ann-arbor-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://umich.edu)
- [Documentation](https://documentation.its.umich.edu/api-directory)
- [Support](https://its.umich.edu/data/data-database/api-directory/support)
- [Privacy policy](https://www.lib.umich.edu/about-us/policies/library-privacy-statement)
- [GitHub](https://github.com/umich)

## API Evangelist rating

**Kin Score 42.3** — developing · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 57.1 |
| Contract quality | 58.2 |
| Contract governance | 44.7 |
| Operational transparency | 7.9 |
| Developer ergonomics | 47.6 |
| Access clarity | 15.8 |

**Agent readiness 27.8** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | — |
| Reversibility Documented | na |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | na |
| Error Semantics | documented (partial credit) |
| OpenAPI Examples | verified |
| Rate Limit Signal | derived (partial credit) |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | na |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | na |
| Operation Distinctiveness | na |

**Regulatory alignment 38.2** — Education & Research

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/university-of-michigan-ann-arbor/](https://apis.io/providers/university-of-michigan-ann-arbor/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for University of Michigan-Ann Arbor: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/university-of-michigan-ann-arbor/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
