# University of Bologna (university-of-bologna)

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
