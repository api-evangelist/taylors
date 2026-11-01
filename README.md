# Taylor's University

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

Taylor's University is a private research university in Subang Jaya, Selangor, Malaysia, ranked #251 in the QS World University Rankings 2025. It operates no developer portal, no public API programme and no public code: the Taylors-University GitHub organisation has existed since 2020 and still holds zero public repositories. What it does operate, on its own infrastructure under taylors.edu.my, are four live machine-readable surfaces — a self-hosted Koha library system exposing a REST API at /api/v1 and an OAI-PMH 2.0 data provider, and a self-hosted DSpace CRIS e-Repository exposing a HAL+JSON REST API at /server/api and a second OAI-PMH 2.0 provider. Both REST contracts are the upstream products' own documents (Koha Development Team; DSpace CRIS 2022.01.01) running on Taylor's servers: the deployment, the data and the DOIs are the institution's, the contract is not. Identity runs through a Microsoft Entra ID tenant whose SAML 2.0 and OpenID Connect metadata are publicly retrievable, and the institution is registered with ROR and holds a Crossref membership through Taylor's University Press. No open data portal, no course-catalog or timetable API, and no institution-operated developer documentation were found.

**Areas:** Education · Higher Education · University · Private University · Malaysia · Asia · Library · Library Catalog · Institutional Repository · Research Data · OAI-PMH · Identity Federation

## Taylor's University on APIs.io

Everything profiled for Taylor's University is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/taylors/](https://apis.io/providers/taylors/)** — or go straight to one of the APIs or properties below.

### APIs (7)

- [Taylor's Library Koha REST API](https://apis.io/apis/taylors/library-rest/) — REST API of the Taylor's University Library catalog, served under /api/v1 by a Koha integrated library system that Taylor's self-hosts…
- [Taylor's Library OAI-PMH](https://apis.io/apis/taylors/library-oai/) — OAI-PMH 2.0 data provider exposed by the Koha-powered Taylor's Library catalog for harvesting bibliographic metadata. The Identify response returns…
- [Taylor's e-Repository DSpace CRIS REST API](https://apis.io/apis/taylors/irepo-rest/) — The Taylor's e-Repository runs DSpace CRIS 2022.01.01 self-hosted at irepo.taylors.edu.my (resolving through irepo.wip.taylors.edu.my to 103.145.155.17 —…
- [Taylor's e-Repository OAI-PMH](https://apis.io/apis/taylors/irepo-oai/) — OAI-PMH 2.0 data provider for the DSpace CRIS e-Repository, Identifying as repositoryName "Taylor's University Library", repositoryIdentifier…
- [Taylor's University Identity Federation (Microsoft Entra ID)](https://apis.io/apis/taylors/entra-identity-federation/) — Taylor's operates a Microsoft Entra ID tenant, 0a39ee13-5c27-420c-b0af-8e65c6929055, branded "Taylor's Education Group", as the identity provider behind…
- [Taylor's University Crossref Membership](https://apis.io/apis/taylors/crossref-membership/) — Taylor's University Press is Crossref member 37785, registered at Subang Jaya, Selangor, Malaysia, holding DOI prefix 10.58946 with 70 deposited DOIs. This…
- [Taylor's University ROR Registration](https://apis.io/apis/taylors/ror-registration/) — Taylor's University is registered in the Research Organization Registry as ror.org/0498pcx51, located Subang Jaya, Malaysia, cross-walked to Crossref Funder…

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Taylors Agentic Access](https://apis.io/agentic-access/taylors/taylors-agentic-access/)

#### JSON Schema (4)

The data models the API reads and writes.

- [Koha Checkout](https://apis.io/schemas/taylors/taylors-checkout/)
- [Koha Hold](https://apis.io/schemas/taylors/taylors-hold/)
- [Koha Item](https://apis.io/schemas/taylors/taylors-item/)
- [Koha Patron](https://apis.io/schemas/taylors/taylors-patron/)

#### JSON Structure (2)

Data models expressed in JSON Structure.

- [Taylors Item Structure](https://apis.io/json-structure/taylors/taylors-item-structure/)
- [Taylors Patron Structure](https://apis.io/json-structure/taylors/taylors-patron-structure/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Taylors Context](https://apis.io/jsonld/taylors/taylors-context/)

#### Vocabulary (1)

The provider's domain terms, defined.

- [Taylor's Library Koha API Vocabulary](https://apis.io/vocabularies/taylors/taylors-vocabulary/)

#### Examples (3)

Example requests and responses.

- [Taylors Getcheckout Example](https://apis.io/examples/taylors/taylors-getCheckout-example/)
- [Taylors Getitem Example](https://apis.io/examples/taylors/taylors-getItem-example/)
- [Taylors Getpatron Example](https://apis.io/examples/taylors/taylors-getPatron-example/)

#### Collections (6)

Postman and Open Collection request collections.

- [Taylor's Library Koha REST checkouts API](https://apis.io/collections/taylors/open-taylors-checkouts-api/)
- [Taylor's Library Koha REST checkouts holds API](https://apis.io/collections/taylors/open-taylors-holds-api/)
- [Taylor's Library Koha REST checkouts item_types API](https://apis.io/collections/taylors/open-taylors-item-types-api/)
- [Taylor's Library Koha REST checkouts items API](https://apis.io/collections/taylors/open-taylors-items-api/)
- [Taylor's Library Koha REST checkouts libraries API](https://apis.io/collections/taylors/open-taylors-libraries-api/)
- [Taylor's Library Koha REST checkouts patrons API](https://apis.io/collections/taylors/open-taylors-patrons-api/)

#### Governance rules (2)

Spectral rulesets for the provider's contracts.

- [Taylor's University — jsonschema rules](https://apis.io/rules/taylors/taylors-jsonschema-spectral-rules/)
- [Taylor's University API Rules](https://apis.io/rules/taylors/taylors-rules/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Taylors Authentication](https://apis.io/security/taylors/taylors-authentication/)
- [Taylors Domain Security](https://apis.io/security/taylors/taylors-domain-security/)

#### OAuth scopes (1)

The permissions the API asks for.

- [Taylors Scopes](https://apis.io/scopes/taylors/taylors-scopes/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Taylors Plans Pricing](https://apis.io/plans/taylors/taylors-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Taylors Rate Limits](https://apis.io/rate-limits/taylors/taylors-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Taylors Finops](https://apis.io/finops/taylors/taylors-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://university.taylors.edu.my/en.html)
- [API reference](https://librarycatalogue.taylors.edu.my/api/v1/)
- [Support](https://university.taylors.edu.my/en/get-in-touch/contact-information.html)
- [Privacy policy](https://university.taylors.edu.my/en/privacy-policy.html)

## API Evangelist rating

**Kin Score 40.2** — developing · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 66.1 |
| Contract quality | 60.6 |
| Contract governance | 23.5 |
| Operational transparency | 10.5 |
| Developer ergonomics | 33.3 |
| Access clarity | 28.9 |

**Agent readiness 26.3** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | na |
| MCP Server | — |
| Auth Clarity | negotiable (partial credit) |
| Idempotency | na |
| Error Semantics | — |
| OpenAPI Examples | documented (partial credit) |
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
| Pagination Ratio | — |
| Operation Distinctiveness | distinct |

**Regulatory alignment 30.4** — Education & Research

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/taylors/](https://apis.io/providers/taylors/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Taylor's University: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/taylors/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
