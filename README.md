# Qatar University

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

Qatar University is the national public research university of the State of Qatar, in Doha, founded 1973 and registered as https://ror.org/00yhnba62. Its institution-operated programmable footprint is small, real, and not where the June 2026 profile said it was. That pass recorded QSpace — the institutional repository at qspace.qu.edu.qa — as Qatar University's own API. It is not: qspace.qu.edu.qa CNAMEs to qataru.cname.openrepository.com and terminates on Amazon eu-west-1, making it a tenant of Open Repository, a commercial hosted-DSpace service. The 66,950 records, the Handle prefix 10576 and the administrative contact are Qatar University's; the DSpace REST and OAI-PMH contracts are the hosting platform's engineering, and they are recorded here as a tenancy rather than saved as Qatar University's contracts. What the earlier pass missed is the part Qatar University actually runs. It operates its own identity provider at sso.qu.edu.qa — a WSO2 Identity Server on QUNET, its own RIPE allocation — publishing both a SAML 2.0 IdP metadata document and a complete OpenID Connect discovery document, which together are the strongest machine-readable contract in this profile. Qatar University Press self-hosts Open Journal Systems 3.3.0.7 at journals.qu.edu.qa, also on QUNET, serving an anonymous OAI-PMH 2.0 endpoint over eight journals and 3,186 records in Arabic and English, and registers DOIs as Crossref member 11655 under prefix 10.29117. Learning is a Blackboard Learn tenant and library guides are a Springshare tenant. There is no developer portal, no changelog, no status page, no API terms of service, and no published OpenAPI for anything — and there is an institutional API gateway at api.qu.edu.qa that fronts a live production API pool while publishing no route, documentation or access path whatsoever. Three verified defects sit on the surfaces Qatar University does run: sso.qu.edu.qa and journals.qu.edu.qa both serve an incomplete TLS chain that a default client cannot verify, the SAML entityID is a bare hostname rather than a URI so the IdP cannot be federated as published, and the OAI-PMH endpoint emits record identifiers that its own GetRecord verb rejects.

**Areas:** Education · Higher Education · University · Qatar · Middle East · Research · Identity Federation · Scholarly Publishing · Research Repository · Open Access · OAI-PMH · SAML

## Qatar University on APIs.io

Everything profiled for Qatar University is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/qatar/](https://apis.io/providers/qatar/)** — or go straight to one of the APIs or properties below.

### APIs (13)

- [Qatar University SAML 2.0 Identity Provider](https://apis.io/apis/qatar/qu-sso-saml/) — The same host publishes a SAML 2.0 IDPSSODescriptor at /identity/metadata/saml2, entityID `sso.qu.edu.qa`, with separate signing and encryption key…
- [QSpace Institutional Repository (Open Repository tenant)](https://apis.io/apis/qatar/qspace/) — QSpace is Qatar University's institutional repository — 66,950 records, DSpace 7.6, administered by Qatar University Library at quspace@qu.edu.qa, with…
- [Qatar University Blackboard Learn (Anthology tenant)](https://apis.io/apis/qatar/blackboard-learn/) — Qatar University's learning management system is a Blackboard Learn SaaS tenant at elearning.qu.edu.qa. The Anthology Blackboard Learn REST API is reachable…
- [Qatar University Library Research Guides (Springshare tenant)](https://apis.io/apis/qatar/libguides/) — Qatar University Library's research guides, including the QSpace institutional-repository guide that is the only public documentation for the repository,…
- [Qatar University Student Information System (Ellucian Banner)](https://apis.io/apis/qatar/banner-sis/) — Qatar University runs Ellucian Banner Self-Service at mybanner.qu.edu.qa, on its own network (netname QUNET). The host answers 200 with a real Banner menu,…
- [Research Organization Registry membership](https://apis.io/apis/qatar/ror/) — Qatar University is registered in ROR as https://ror.org/00yhnba62 — status active, established 1973, domain qu.edu.qa, located in Doha, Qatar —…
- [Crossref membership (Qatar University Press)](https://apis.io/apis/qatar/crossref/) — Qatar University Press is a Crossref member in its own right — member 11655, DOI prefix 10.29117, 2,533 DOIs registered (510 current, 2,023 backfile) —…
- [Handle.Net naming authority 10576](https://apis.io/apis/qatar/handle/) — Qatar University holds Handle.Net prefix 10576 and every QSpace item carries a persistent identifier under it, resolving through hdl.handle.net to the…
- [Qatar University Client Registration API](https://apis.io/apis/qatar/qatar-client-registration-api/) — OpenID Connect Dynamic Client Registration.
- [Qatar University Discovery API](https://apis.io/apis/qatar/qatar-discovery-api/) — Provider metadata and signing keys.
- [Qatar University OAI PMH API](https://apis.io/apis/qatar/qatar-oai-pmh-api/) — The six OAI-PMH 2.0 protocol verbs, site-wide and per journal.
- [Qatar University OpenID Connect API](https://apis.io/apis/qatar/qatar-openid-connect-api/) — Authorization, user info and session management.
- [Qatar University O Auth API](https://apis.io/apis/qatar/qatar-oauth-api/) — Token issuance, introspection and revocation.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### JSON Schema (2)

The data models the API reads and writes.

- [QU Press OAI-PMH Record (JSON projection)](https://apis.io/schemas/qatar/qatar-oai-pmh-record.schema/)
- [Qatar University SSO — OpenID Provider Metadata](https://apis.io/schemas/qatar/qatar-qu-sso-openid-configuration.schema/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Qatar Context](https://apis.io/jsonld/qatar/qatar-context/)

#### Examples (4)

Example requests and responses.

- [Qatar Crossref Member](https://apis.io/examples/qatar/qatar-crossref-member/)
- [Qatar Handle Resolution](https://apis.io/examples/qatar/qatar-handle-resolution/)
- [Qatar Qu Sso Openid Configuration](https://apis.io/examples/qatar/qatar-qu-sso-openid-configuration/)
- [Qatar Ror Record](https://apis.io/examples/qatar/qatar-ror-record/)

#### Governance rules (1)

Spectral rulesets for the provider's contracts.

- [Qatar University API Rules](https://apis.io/rules/qatar/qatar-rules/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Qatar Authentication](https://apis.io/security/qatar/qatar-authentication/)
- [Qatar Domain Security](https://apis.io/security/qatar/qatar-domain-security/)

#### OAuth scopes (1)

The permissions the API asks for.

- [Qatar Scopes](https://apis.io/scopes/qatar/qatar-scopes/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Qatar Plans Pricing](https://apis.io/plans/qatar/qatar-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Qatar Rate Limits](https://apis.io/rate-limits/qatar/qatar-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Qatar Finops](https://apis.io/finops/qatar/qatar-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.qu.edu.qa/)
- [Documentation](https://libguides.qu.edu.qa/quir)

## API Evangelist rating

**Kin Score 20.2** — emerging · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 71.4 |
| Contract quality | 24.3 |
| Contract governance | 3.8 |
| Operational transparency | 5.3 |
| Developer ergonomics | 21.4 |
| Access clarity | 5.3 |

**Agent readiness 18.6** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | — |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | partial |
| Rate Limit Signal | derived (partial credit) |
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

**Regulatory alignment 26.5** — Education & Research

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/qatar/](https://apis.io/providers/qatar/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Qatar University: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/qatar/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
