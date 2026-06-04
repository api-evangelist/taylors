# Taylor's University (taylors)

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
