# ETH Zurich – Swiss Federal Institute of Technology (eth-zurich)

ETH Zurich (Eidgenössische Technische Hochschule Zürich) is a public science and technology university founded in 1855 and ranked #7 in the QS World University Rankings 2025. Its principal public developer footprint is the **ETH Library API Platform** — an Apigee-managed developer portal exposing six documented OpenAPI 3.0 REST APIs over the library's open bibliographic, georeferenced, and research-output data — complemented by the Research Collection OAI-PMH interface and the `eth-library` GitHub organization.

- APIs.json: <https://raw.githubusercontent.com/api-evangelist/eth-zurich/refs/heads/main/apis.yml>
- Run it with Naftiko: <https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=eth-zurich-api-evangelist&utm_content=repo>

## Type

Index / Consumer / 3rd-Party

## Tags

Education, Higher Education, University, Research, Library, Open Data, Switzerland

## APIs

All ETH Library API Platform APIs require a free one-time registration for an API key at the [Developer Portal](https://developer.library.ethz.ch). Shared [OpenAPI/Swagger docs](https://eth-library.github.io/apiplatform-swagger/).

- **ETH Library Discovery API** — Access to 30M+ books, images, series, journals and other materials. [Docs](https://eth-library.github.io/apiplatform-swagger/)
- **ETH Library ETHorama API** — Georeferenced access to digitized documents (E-Pics, E-Rara, E-Periodica, E-Manuscripta, Research Collection). [Docs](https://eth-library.github.io/apiplatform-swagger/)
- **ETH Library Geo Information API** — Points of interest and dossiers from the ETHorama database in GeoJSON. [Docs](https://eth-library.github.io/apiplatform-swagger/)
- **ETH Library Persons API** — Enriched person information (Wikidata, Metagrid, DNB Entityfacts, beacon.findbuch). [Docs](https://eth-library.github.io/apiplatform-swagger/)
- **ETH Zurich Research Collection API** — Bibliographic metadata for publications and research data (v1/v2); also an [OAI-PMH](https://research-collection.ethz.ch/oai/openaire_data) interface. [Docs](https://eth-library.github.io/apiplatform-swagger/)
- **ETH Library Vector API** — Vector-based access to ETH Library data resources. [Docs](https://eth-library.github.io/apiplatform-swagger/)

OpenAPI specifications for these APIs are published at [eth-library/opendata-apis](https://github.com/eth-library/opendata-apis).

## Plans / Rate Limits / FinOps

- Plans & Pricing: [plans/eth-zurich-plans-pricing.yml](plans/eth-zurich-plans-pricing.yml)
- Rate Limits: [rate-limits/eth-zurich-rate-limits.yml](rate-limits/eth-zurich-rate-limits.yml)
- FinOps: [finops/eth-zurich-finops.yml](finops/eth-zurich-finops.yml)

## Timestamps

- Created: 2026-06-03
- Modified: 2026-06-03

## Common Properties

- Website: <https://ethz.ch/en/>
- Developer Portal: <https://developer.library.ethz.ch>
- Documentation: <https://eth-library.github.io/apiplatform-swagger/>
- GitHub: <https://github.com/eth-library>
- Source Code: <https://github.com/eth-library/opendata-apis>
- Open Data: <https://opendata.swiss/en/organization/eth-bibliothek>
- LinkedIn: <https://www.linkedin.com/school/eth-zurich/>
- Authentication: API key via <https://developer.library.ethz.ch>

## Notes

- All listed APIs and properties were verified live (HTTP 200) on 2026-06-03, except the LinkedIn school page, which returns HTTP 999 (LinkedIn's standard bot block) but exists.
- API access requires a free one-time registration to obtain an API key; base/gateway hostnames are not published publicly and so are intentionally omitted (no fabricated endpoints).
- No official ETH-published course catalogue / timetable / SIS API was found. The VVZ course-catalogue APIs that exist are unofficial community projects and were deliberately not cataloged here.

## Maintainers

- Kin Lane — kin@apievangelist.com
