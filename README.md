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
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

The University of Bologna (Alma Mater Studiorum - Università di Bologna) is the oldest university in the Western world and a leading Italian research institution, ranked #133 in the QS World University Rankings 2025. This repository catalogs its public developer and API footprint as an APIs.json provider profile for the api-evangelist network. The footprint centers on open data and open scholarship: a CKAN-based open data portal and an EPrints institutional repository exposing OAI-PMH.

- APIs.json: https://raw.githubusercontent.com/api-evangelist/university-of-bologna/refs/heads/main/apis.yml
- Run with Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=university-of-bologna-api-evangelist&utm_content=repo

## Type

- Index / Consumer / 3rd-Party

## Tags

Education, Higher Education, University, Open Data, Research, Italy, Europe

## APIs

- **University of Bologna Open Data (CKAN API)** — CKAN Action API over institutional datasets. Docs: https://docs.ckan.org/en/latest/api/ · Portal: https://dati.unibo.it/
- **AMS Acta Institutional Repository (OAI-PMH)** — EPrints 3.4.x OAI-PMH 2.0 metadata harvesting. Docs: https://amsacta.unibo.it/cgi/oai2?verb=Identify · Repository: https://amsacta.unibo.it/

## Plans / Rate Limits / FinOps

- Plans: [plans/university-of-bologna-plans-pricing.yml](plans/university-of-bologna-plans-pricing.yml)
- Rate Limits: [rate-limits/university-of-bologna-rate-limits.yml](rate-limits/university-of-bologna-rate-limits.yml)
- FinOps: [finops/university-of-bologna-finops.yml](finops/university-of-bologna-finops.yml)

## Timestamps

- Created: 2026-06-03
- Modified: 2026-06-03

## Common Properties

- Website: https://www.unibo.it/en
- GitHub: https://github.com/unibo
- LinkedIn: https://www.linkedin.com/school/unibo/
- Developer Portal: https://dati.unibo.it/
- Review: [review.yml](review.yml)

## Notes

All listed APIs were verified live on 2026-06-03: the CKAN Action API returned a valid JSON response (success:true, ~33 datasets) and AMS Acta returned a valid OAI-PMH Identify response. No unified API developer portal, signup flow, course/SIS API, or status page was found; administrative and identity systems are gated behind institutional credentials. No endpoints were fabricated.

## Maintainers

- Kin Lane — kin@apievangelist.com
