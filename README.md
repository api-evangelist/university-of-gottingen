# University of Göttingen (university-of-gottingen)

The University of Göttingen (Georg-August-Universität Göttingen) is a public research university in Lower Saxony, Germany, ranked #254 in the QS World University Rankings 2025. This repository catalogs its public, machine-readable developer and API footprint, which is delivered mainly through campus partners — the Göttingen State and University Library (SUB Göttingen) and the Göttingen eResearch Alliance.

- APIs.json: https://raw.githubusercontent.com/api-evangelist/university-of-gottingen/refs/heads/main/apis.yml
- Run with Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=university-of-gottingen-api-evangelist&utm_content=repo

## Type

Index / Consumer / 3rd-Party

## Tags

Education, Higher Education, University, Research Data, Digital Library, IIIF, OAI-PMH, Germany

## APIs

- **GRO.data OAI-PMH Metadata** — OAI-PMH harvesting for the GRO.data (Göttingen Research Online) Dataverse research-data repository. Docs: https://data.goettingen-research-online.de/oai?verb=Identify
- **GRO.data Dataverse REST API** — Native Dataverse REST/search API for the GRO.data repository. Docs: https://guides.dataverse.org/en/latest/api/
- **SUB Göttingen IIIF API** — IIIF Image and Presentation API support across SUB Göttingen digital collections (incl. GDZ). Docs: https://www.sub.uni-goettingen.de/en/digital-library/digital-tools/iiif-at-the-goettingen-state-and-university-library/
- **SUB Göttingen TextAPI** — Open TextAPI specification serving text and metadata of digital objects, consumed by the TIDO viewer. Docs: https://www.sub.uni-goettingen.de/en/digital-library/digital-tools/text-viewer-for-digital-objects-tido-textapi/

## Plans

See [plans/university-of-gottingen-plans-pricing.yml](plans/university-of-gottingen-plans-pricing.yml)

## Rate Limits

See [rate-limits/university-of-gottingen-rate-limits.yml](rate-limits/university-of-gottingen-rate-limits.yml)

## FinOps

See [finops/university-of-gottingen-finops.yml](finops/university-of-gottingen-finops.yml)

## Timestamps

- Created: 2026-06-03
- Modified: 2026-06-03

## Common Properties

- Website: https://www.uni-goettingen.de/en/
- GitHub: https://github.com/uni-goettingen
- Source Code: https://github.com/subugoe
- LinkedIn: https://www.linkedin.com/school/university-of-gottingen/
- Authentication (SAML/Shibboleth/OpenID Connect AAI): https://www-portal.gwdg.de/en/services/general-services/sso-aai/

## Notes

- The university has no single official institution-wide developer portal. APIs are published by campus partners.
- The official `uni-goettingen` GitHub org exists but currently has no public repositories; active open-source library code lives under `subugoe`.
- GWDG/AcademicCloud Chat AI (SAIA) offers an OpenAI-compatible API but is operated by GWDG, a shared regional provider serving multiple institutions, so it is referenced as related infrastructure rather than cataloged as a university-owned API.
- An undocumented canteen (mensa) widget endpoint exists but is not an official, supported public API and is excluded.
- All endpoints were probed live on 2026-06-03; statuses are recorded in `review.yml`. No endpoints were fabricated.

## Maintainers

- Kin Lane — kin@apievangelist.com
