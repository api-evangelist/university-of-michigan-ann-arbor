# University of Michigan-Ann Arbor (university-of-michigan-ann-arbor)

The University of Michigan-Ann Arbor is a public research university ranked #21 in the QS World University Rankings 2025 (United States). This repository catalogs the institution's public developer and API footprint as an [APIs.json](https://apisjson.org) provider profile. U-M's API program is led by Information and Technology Services (ITS), whose enterprise API Directory (built on Apigee X) is gated to authenticated U-M members, while the University of Michigan Library publishes public scholarly and research-data infrastructure including the Deep Blue Data REST API and a live Deep Blue Documents OAI-PMH endpoint.

- APIs.json: https://raw.githubusercontent.com/api-evangelist/university-of-michigan-ann-arbor/refs/heads/main/apis.yml
- Run with Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=university-of-michigan-ann-arbor-api-evangelist&utm_content=repo

## Type

- Index / Consumer / 3rd-Party

## Tags

Education, Higher Education, University, Research, Library, Open Data, Institutional Repository, United States

## APIs

- **U-M ITS API Directory** — Enterprise API directory and Apigee X gateway exposing institutional data APIs (teaching & learning, research, clinical care, administration). Gated: requires U-M uniqname, Duo two-factor, and U-M network/VPN. Docs: https://its.umich.edu/data/data-database/api-directory · https://documentation.its.umich.edu/api-directory
- **Deep Blue Data REST API** — Public REST API for the U-M Library's open research-dataset repository (DOI-backed, free public access). Docs: https://deepblue.lib.umich.edu/data/rest-api
- **Deep Blue Documents OAI-PMH** — Live DSpace OAI-PMH metadata harvesting endpoint for the U-M institutional repository. Base: https://backend.production.deepblue-documents.lib.umich.edu/server/oai/request · Docs: https://www.lib.umich.edu/collections/deep-blue-repositories

## Plans / Rate Limits / FinOps

- Plans: [plans/university-of-michigan-ann-arbor-plans-pricing.yml](plans/university-of-michigan-ann-arbor-plans-pricing.yml)
- Rate Limits: [rate-limits/university-of-michigan-ann-arbor-rate-limits.yml](rate-limits/university-of-michigan-ann-arbor-rate-limits.yml)
- FinOps: [finops/university-of-michigan-ann-arbor-finops.yml](finops/university-of-michigan-ann-arbor-finops.yml)

## Timestamps

- Created: 2026-06-03
- Modified: 2026-06-03

## Common Properties

- Website: https://umich.edu · https://www.lib.umich.edu
- Developer Portal: https://its.umich.edu/data/data-database/api-directory
- GitHub: https://github.com/umich · https://github.com/mlibrary
- LinkedIn: https://www.linkedin.com/school/university-of-michigan/
- Authentication: https://its.umich.edu/data/data-database/api-directory/getting-started

## Notes

- The ITS API Directory is an enterprise, members-only program (uniqname + Duo + U-M network/VPN); its individual API endpoints could not be probed anonymously and none were fabricated.
- Several umich.edu pages return HTTP 403 to automated agents (Akamai bot protection) but are real, publicly documented pages confirmed via search.
- The Deep Blue Documents OAI-PMH endpoint was verified live (HTTP 200, valid Identify response). GitHub orgs were verified via the GitHub API.

## Maintainers

- Kin Lane — kin@apievangelist.com
