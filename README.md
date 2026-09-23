# University of Bologna (university-of-bologna)

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

The University of Bologna (Alma Mater Studiorum - Università di Bologna) is the oldest university in the Western world, founded in 1088, and Italy's largest public research university. This repository catalogs its public developer and API footprint as an APIs.json provider profile for the api-evangelist network, profiled under the university pipeline — which settles **who operates** each surface before saving anything.

The university publishes no OpenAPI, runs no developer portal and issues no API keys. What it does operate, on its own unibo.it hosts, is an unusually deep set of standards-based machine surfaces: a CKAN open data portal, four separate live OAI-PMH 2.0 providers run by the AlmaDL digital library, a Shibboleth SAML 2.0 identity provider published in the IDEM GARR AAI federation, and an LTI 1.3 platform surface on its self-hosted Moodle.

- APIs.json: https://raw.githubusercontent.com/api-evangelist/university-of-bologna/refs/heads/main/apis.yml
- Run with Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=university-of-bologna-api-evangelist&utm_content=repo

## Type

- University / Public Research University / Index / Consumer / 3rd-Party

## Tags

Education, Higher Education, University, Italy, Europe, Research, Research Repository, Open Data, Open Access, Library, OAI-PMH, Identity Federation, Scholarly Publishing, Learning Management

## Surfaces — by operator

Every entry carries an `x-operator`. `institution` means the university runs the thing the entry describes; `tenant` means the data is theirs and the platform is a vendor's; `federation` and `registry` are relationships, recorded as facts about the institution.

### institution

- **University of Bologna Open Data (CKAN Action API)** — CKAN 2.6.9 Action API over institutional datasets. `https://dati.unibo.it/api/3/action/`
- **AMS Acta Institutional Repository OAI-PMH** — EPrints, ten metadata formats including `oai_datacite` and `openaire_oai_dc`. `https://amsacta.unibo.it/cgi/oai2`
- **AMS Tesi di Dottorato (Doctoral Theses) OAI-PMH** — `https://amsdottorato.unibo.it/cgi/oai2`
- **AMS Tesi di Laurea (Graduate Theses) OAI-PMH** — `https://amslaurea.unibo.it/cgi/oai2`
- **AlmaDL Journals OAI-PMH** — Open Journal Systems, 100 open-access journal sets. `https://journals.unibo.it/index.php/index/oai`
- **Virtuale (Moodle) LTI 1.3 Platform and Web Services** — public JWKS plus an OAuth2 token endpoint; Moodle Web Services is token-gated. `https://virtuale.unibo.it/mod/lti/certs.php`

### federation

- **UNIBO Shibboleth Identity Provider (IDEM GARR AAI)** — entityID `https://shib.unibo.it/idp/shibboleth`, `shibmd:Scope` unibo.it, published in the IDEM GARR aggregate alongside two UNIBO service providers.

### tenant

- **IRIS Research Information System (CINECA tenancy)** — `cris.unibo.it` CNAMEs to `unibo.prod.iris.cineca.it`. The metadata and DOIs are the university's; the software and its contract are CINECA's.
- **AlmaStart Library Discovery (Ex Libris Primo VE tenancy)** — `almastart.unibo.it` CNAMEs to `unibo.primo.exlibrisgroup.com`, tenant code `39UBO_INST`.

### registry

- **DataCite** — provider UYEY, five repositories, five prefixes (10.6092, 10.13123, 10.48676, 10.48678, 10.60760), 32,291 DOIs.
- **Crossref** — member 32492, prefix 10.60923, 1,170 DOIs.
- **ROR** — https://ror.org/01111rn36

## Domain standards (Kin Score `education` regime)

Evidenced from live endpoints, not from prose claims — see [conformance/university-of-bologna-domain-standards.yml](conformance/university-of-bologna-domain-standards.yml).

| Standard | Conformant | Operator |
|---|---|---|
| oai-pmh 2.0 | yes | institution |
| shibboleth | yes | institution |
| saml 2.0 | yes | institution |
| lti 1.3 | yes | institution |
| datacite | yes | registry |
| crossref | yes | registry |
| orcid | no | — |
| scim, oneroster, ed-fi, caliper, qti | no | — |

## Authentication

Three REST APIs sit on institution or institution-branded hosts and all three refuse anonymous callers — OJS returns 403, Moodle Web Services returns `invalidtoken`, IRIS returns 401 basic-auth. Recorded in [authentication/university-of-bologna-authentication.yml](authentication/university-of-bologna-authentication.yml) rather than counted as callable.

## Plans / Rate Limits / FinOps

- Plans: [plans/university-of-bologna-plans-pricing.yml](plans/university-of-bologna-plans-pricing.yml)
- Rate Limits: [rate-limits/university-of-bologna-rate-limits.yml](rate-limits/university-of-bologna-rate-limits.yml)
- FinOps: [finops/university-of-bologna-finops.yml](finops/university-of-bologna-finops.yml)

## Timestamps

- Created: 2026-06-03
- Modified: 2026-09-01

## Common Properties

- Website: https://www.unibo.it/en
- Open Data: https://dati.unibo.it/
- Research Repository: https://amsacta.unibo.it/
- Identity Federation: https://shib.unibo.it/idp/shibboleth
- Library Catalog: https://almastart.unibo.it/discovery/search?vid=39UBO_INST:VU
- Course Catalog: https://corsi.unibo.it/
- AI Policy: https://www.unibo.it/it/ateneo/statuto-norme-strategie-bilanci/intelligenza-artificiale
- GitHub Organization: https://github.com/unibo
- Privacy Policy: https://www.unibo.it/en/university/privacy-policy-and-legal-notes
- LinkedIn: https://www.linkedin.com/school/unibo/
- Review: [review.yml](review.yml)

## Notes

Every surface listed above was probed live on 2026-09-01 from an unauthenticated client. No vendor contract has been saved under this institution and no OpenAPI has been generated to stand in for one: CKAN, EPrints, OJS, Moodle and DSpace-CRIS contracts are product contracts shared by every deployment of that software.

Absences, stated rather than padded: no OpenAPI, no developer portal, no self-service key issuance, no status page, no `llms.txt`, no `.well-known/security.txt`, and no ORCID identifiers in any metadata the university serves. `api.unibo.it` does not resolve. The institutional generative-AI policy is a real governance artifact but exists only on the Italian surface — the English path returns 404. During this run `dati.unibo.it` stopped answering our client after two successful requests (TCP open, no HTTP response), which reads as an undocumented rate limit on our probing rather than an outage, and is recorded as such.

## Maintainers

- Kin Lane — kin@apievangelist.com
