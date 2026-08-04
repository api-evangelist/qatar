# Qatar University (qatar)

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
