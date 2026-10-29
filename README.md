# Case Western Reserve University

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

Case Western Reserve University (CWRU) is a private research university in Cleveland, Ohio, founded 1826 and a member of the Association of American Universities. It operates no public developer portal and no public API program: api.case.edu, developer.case.edu and developers.case.edu do not resolve, case.edu/llms.txt and /.well-known/security.txt both return 404, and its GitHub organization (github.com/cwru) holds six repositories of which four are archived web-template tooling last touched in 2016-17. What CWRU does operate, and what this profile records, is a small set of genuinely institution-run identity and harvesting surfaces — a Shibboleth SAML 2.0 Identity Provider on login.case.edu registered in InCommon (urn:mace:incommon:case.edu, scoped to case.edu and eight school subdomains), an Apereo CAS single sign-on service on the same host, and an open OAI-PMH 2.0 provider for Scholarly Commons at commons.case.edu — alongside tenancies it holds on other people's platforms (bepress Digital Commons, Ex Libris Primo through the OhioLINK consortium, Tableau Server, Leepfrog CourseLeaf, Microsoft Entra ID) and its registration in the Crossref and ROR registries. Every entry below carries an x-operator saying who actually runs the thing described. No vendor contract is saved under CWRU's name.

**Areas:** Education · Higher Education · University · Private Research University · Association of American Universities · Research · Identity Federation · Shibboleth · SAML · OAI-PMH · Research Repository · Library

## Case Western Reserve University on APIs.io

Everything profiled for Case Western Reserve University is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/case-western-reserve-university/](https://apis.io/providers/case-western-reserve-university/)** — or go straight to one of the APIs or properties below.

### APIs (9)

- [CWRU Shibboleth Identity Provider (SAML 2.0 metadata)](https://apis.io/apis/case-western-reserve-university/shibboleth-idp/) — CWRU's own Shibboleth Identity Provider, entityID urn:mace:incommon:case.edu. Every SingleSignOnService binding in the production descriptor is on CWRU's…
- [CWRU Apereo CAS single sign-on (login.case.edu)](https://apis.io/apis/case-western-reserve-university/apereo-cas/) — CWRU runs an Apereo CAS deployment at login.case.edu as its campus single sign-on service. The CAS 3.0 protocol validation endpoint /cas/p3/serviceValidate…
- [Scholarly Commons @ CWRU — OAI-PMH 2.0 provider](https://apis.io/apis/case-western-reserve-university/scholarly-commons-oai-pmh/) — An open OAI-PMH 2.0 metadata provider on CWRU's own host. Identify reports repositoryName "Scholarly Commons @ Case Western Reserve University",…
- [CWRU Microsoft Entra ID tenant (OIDC + SAML metadata)](https://apis.io/apis/case-western-reserve-university/entra-id-tenant/) — CWRU's Microsoft Entra ID tenant, dc1c97ee-7a12-4624-9a01-9ad4f05d1311, resolved from the case.edu domain hint. OpenID Connect discovery answers…
- [Crossref member registration — Case Western Reserve University (member 7530)](https://apis.io/apis/case-western-reserve-university/crossref-member/) — CWRU is a registered Crossref member, id 7530, primary-name "Case Western Reserve University", holding six DOI prefixes (10.18062, 10.18581, 10.18582,…
- [ROR organization record — Case Western Reserve University (051fd9666)](https://apis.io/apis/case-western-reserve-university/ror-record/) — CWRU's Research Organization Registry record, https://ror.org/051fd9666, established 1826, domain case.edu, located in Cleveland, Ohio, US. External…
- [CWRU Tableau Server deployment (data.case.edu)](https://apis.io/apis/case-western-reserve-university/tableau-server/) — CWRU's institutional analytics platform, hosted on its own domain at data.case.edu. The unauthenticated Tableau REST serverInfo endpoint reports…
- [CWRU library discovery — Ex Libris Primo view 01OHIOLINK_CWRU:CWRUC](https://apis.io/apis/case-western-reserve-university/primo-discovery-view/) — CWRU's library discovery layer is an Ex Libris Primo view operated through the OhioLINK consortium. digital.case.edu — a CWRU-owned hostname — redirects to…
- [CWRU General Bulletin — Leepfrog CourseLeaf catalog (bulletin.case.edu)](https://apis.io/apis/case-western-reserve-university/courseleaf-bulletin/) — The 2026-27 General Bulletin, CWRU's authoritative course catalog, runs on Leepfrog CourseLeaf at bulletin.case.edu — a CWRU host, a vendor product. It…

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Case Western Reserve University Context](https://apis.io/jsonld/case-western-reserve-university/case-western-reserve-university-context/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Case Western Reserve University Authentication](https://apis.io/security/case-western-reserve-university/case-western-reserve-university-authentication/)
- [Case Western Reserve University Domain Security](https://apis.io/security/case-western-reserve-university/case-western-reserve-university-domain-security/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Case Western Reserve University Plans Pricing](https://apis.io/plans/case-western-reserve-university/case-western-reserve-university-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Case Western Reserve University Rate Limits](https://apis.io/rate-limits/case-western-reserve-university/case-western-reserve-university-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Case Western Reserve University Finops](https://apis.io/finops/case-western-reserve-university/case-western-reserve-university-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://case.edu/)
- [Documentation](https://case.edu/utech/)
- [Support](https://cwru.teamdynamix.com/TDClient/126/Portal/Home/)
- [Blog](https://case.edu/news/)
- [Privacy policy](https://case.edu/utech/policies/legal-privacy-notice/)
- [GitHub](https://github.com/cwru)

## API Evangelist rating

**Kin Score 21.0** — emerging · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 71.4 |
| Contract quality | 14.3 |
| Contract governance | 0.0 |
| Operational transparency | 7.9 |
| Developer ergonomics | 28.6 |
| Access clarity | 15.8 |

**Agent readiness 3.1** — human-only

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | — |
| Agentic Access | — |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | — |
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

**Regulatory alignment 20.6** — Education & Research

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/case-western-reserve-university/](https://apis.io/providers/case-western-reserve-university/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Case Western Reserve University: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/case-western-reserve-university/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
