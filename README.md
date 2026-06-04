# Qatar University (qatar)

Qatar University is the national public research university of the State of Qatar, located in Doha, and ranked #122 in the QS World University Rankings 2025. This repository catalogs the university's public developer/API footprint as an [APIs.json](https://apisjson.org) profile. The strongest confirmed surface is QSpace, the institutional repository running on DSpace 7.6, which exposes a public OAI-PMH metadata endpoint and a public DSpace REST/HAL API.

- APIs.json: https://raw.githubusercontent.com/api-evangelist/qatar/refs/heads/main/apis.yml
- Run with Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=qatar-api-evangelist&utm_content=repo

## Type

- Index / Consumer / 3rd-Party

## Tags

Education, Higher Education, University, Qatar, Middle East, Research, Open Access, Institutional Repository, DSpace, OAI-PMH

## APIs

- **QSpace OAI-PMH Metadata Endpoint** — OAI-PMH 2.0 harvesting endpoint for the QSpace institutional repository (DSpace 7.6). Base: `https://qspace.qu.edu.qa/server/oai/request`. Docs: https://libguides.qu.edu.qa/quir
- **QSpace DSpace REST API** — Public DSpace 7.6 REST/HAL API backing QSpace. Base: `https://qspace.qu.edu.qa/server/api`. Docs: https://libguides.qu.edu.qa/quir

## Plans, Rate Limits, and FinOps

- Plans & Pricing: [plans/qatar-plans-pricing.yml](plans/qatar-plans-pricing.yml)
- Rate Limits: [rate-limits/qatar-rate-limits.yml](rate-limits/qatar-rate-limits.yml)
- FinOps: [finops/qatar-finops.yml](finops/qatar-finops.yml)

## Timestamps

- Created: 2026-06-03
- Modified: 2026-06-03

## Common Properties

- Website: https://www.qu.edu.qa/
- GitHub: https://github.com/qataruniversity (org exists, 0 public repos)
- LinkedIn: https://www.linkedin.com/school/qatar-university/
- Review: [review.yml](review.yml)

## Notes

All endpoints were probed live during cataloging. QSpace OAI-PMH and the DSpace REST API root both returned HTTP 200 and self-identify as DSpace 7.6 ("Qspace"). No dedicated developer portal, open-data API, or published mobile/SIS API was found; Self-Service Banner (MyBanner) and SSO/MFA are authentication-gated with no open developer documentation. The official GitHub org `qataruniversity` exists but currently has no public repositories. No endpoints were fabricated — only verified URLs are cataloged.

## Maintainers

- Kin Lane — kin@apievangelist.com
