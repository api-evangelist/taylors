# Taylor's University (taylors)

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
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Taylor's University is a private research university in Subang Jaya, Selangor, Malaysia, ranked #251 in the QS World University Rankings 2025. While it publishes no formal branded developer portal, several real, publicly reachable machine interfaces exist across its library and research infrastructure — a Koha-powered library catalog (REST API + OAI-PMH) and a DSpace CRIS e-Repository (REST API + OAI-PMH).

This repository catalogs that footprint as an APIs.json provider profile.

- APIs.json: https://raw.githubusercontent.com/api-evangelist/taylors/refs/heads/main/apis.yml
- Run with Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=taylors-api-evangelist&utm_content=repo

## Type

- Index / Consumer / 3rd-Party

## Tags

- Education
- Higher Education
- University
- Library
- Institutional Repository
- Open Data
- Malaysia
- Asia

## APIs

- **Taylor's Library Koha REST API** — versioned Koha REST API under `/api/v1`. Docs: https://librarycatalogue.taylors.edu.my/api/v1/
- **Taylor's Library OAI-PMH** — Koha OAI-PMH 2.0 data provider. Docs: https://librarycatalogue.taylors.edu.my/cgi-bin/koha/oai.pl?verb=Identify
- **Taylor's e-Repository DSpace REST API** — DSpace CRIS HAL+JSON REST API. Docs: https://irepo.taylors.edu.my/server/api
- **Taylor's e-Repository OAI-PMH** — DSpace CRIS OAI-PMH 2.0 data provider (OpenAIRE CERIF). Docs: https://irepo.taylors.edu.my/server/oai/request?verb=Identify

## Plans / Rate Limits / FinOps

- Plans: [plans/taylors-plans-pricing.yml](plans/taylors-plans-pricing.yml)
- Rate Limits: [rate-limits/taylors-rate-limits.yml](rate-limits/taylors-rate-limits.yml)
- FinOps: [finops/taylors-finops.yml](finops/taylors-finops.yml)

## Timestamps

- Created: 2026-06-03
- Modified: 2026-06-03

## Common Properties

- Website: https://university.taylors.edu.my/en.html
- GitHub: https://github.com/Taylors-University (org exists, no public repos)
- LinkedIn: https://www.linkedin.com/school/taylor's-university/
- Authentication: Microsoft Entra ID (Taylor's SSO) gating most patron/credentialed endpoints

## Notes

All cataloged APIs were verified live during research on 2026-06-03:
- The Koha OAI-PMH `Identify` verb returns repository name "Taylor's Library".
- The Koha REST OpenAPI spec is publicly retrievable at `/api/v1/`.
- The DSpace REST root at `/server/api` returns HAL+JSON identifying "DSpace cris-2022.01.01".
- The DSpace OAI-PMH `Identify` verb returns "Taylor's University Library".

No formal developer portal, SDKs, public sign-up flow, or status page were found. No course/timetable/SIS or open-data (`data.*`) public APIs were confirmed; student-facing portals (Taylor's Online, TOPAS, Campus Central) are authenticated applications, not documented public APIs. Endpoints are reported only where actually observed — none were fabricated.

## Maintainers

- Kin Lane — kin@apievangelist.com
