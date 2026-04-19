# 2020 Police Brutality (2020-police-brutality)
This repository accumulates and contextualizes evidence of police brutality during the 2020 George Floyd protests. The goal is to assist journalists, politicians, prosecutors, activists and concerned individuals who can use the evidence accumulated here for political campaigns, news reporting, public education and prosecution of criminal police officers.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/2020-police-brutality/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Brutality, Civil Rights, Policing, Public Data

## Timestamps

- **Created:** 2024-11-13
- **Modified:** 2026-04-19

## APIs

### 2020 Police Brutality API
This repository accumulates and contextualizes evidence of police brutality during the 2020 George Floyd protests. Data is available as JSON and CSV files from the data_build branch, including geolocation, tags, dates, and source links for each incident.

**Human URL:** [https://github.com/2020PB/police-brutality/tree/data_build](https://github.com/2020PB/police-brutality/tree/data_build)

#### Tags:

 - Brutality, Civil Rights, Incidents, Policing

#### Properties

- [Documentation](https://github.com/2020PB/police-brutality/tree/data_build)
- [OpenAPI](openapi/2020-police-brutality-openapi.yml)
- [JSONSchema](json-schema/2020-police-brutality-incident-schema.json)
- [JSONSchema](json-schema/2020-police-brutality-incident-collection-schema.json)
- [JSON-LD](json-ld/2020-police-brutality-context.jsonld)

## Common Properties

- [GitHubOrganization](https://github.com/2020PB)
- [GitHubRepository](https://github.com/2020PB/police-brutality)
- [Documentation](https://github.com/2020PB/police-brutality/blob/main/README.md)

## Features

| Name | Description |
|------|-------------|
| Incident Documentation | Documented evidence of police brutality with descriptions, dates, locations, and source links |
| Location Data | GPS geolocation coordinates for each incident, enabling geographic analysis |
| Tag Classification | Categorical tags classifying incident types (foam-bullet, tear-gas, pepper-spray, etc.) |
| Multiple Data Formats | Data available in JSON (v1 and v2) and CSV formats for different use cases |
| Source Verification | Each incident includes links to source documentation for verification |
| Open Data | MIT licensed open dataset available for public use |

## Use Cases

| Name | Description |
|------|-------------|
| Journalism and Reporting | Investigative journalists use incident data for news reporting on police conduct |
| Legal Proceedings | Prosecutors and civil rights attorneys use evidence for criminal and civil cases |
| Academic Research | Researchers study patterns in police use of force during protests |
| Policy Advocacy | Activists and policymakers use data to support police reform campaigns |
| Public Education | Organizations use the data to educate the public about police brutality |
| Geographic Analysis | Researchers map incidents by location to identify geographic patterns |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [2020 Police Brutality API](openapi/2020-police-brutality-openapi.yml)

### JSON Schema

- [Incident Schema](json-schema/2020-police-brutality-incident-schema.json)
- [Incident Collection Schema](json-schema/2020-police-brutality-incident-collection-schema.json)

### JSON Structure

- 2 JSON Structure files (json-structure.org format)

### JSON-LD

- [2020 Police Brutality Context](json-ld/2020-police-brutality-context.jsonld)

### Examples

- 2 example JSON files

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [2020 Police Brutality API](capabilities/shared/2020-police-brutality.yaml) — 3 operations for incident data access

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [2020 Police Brutality Incident Research](capabilities/2020-police-brutality-incident-research.yaml) | 2020 Police Brutality API | 3 | Journalist, Researcher, Legal Professional, Activist |

## Vocabulary

- [2020 Police Brutality Vocabulary](vocabulary/2020-police-brutality-vocabulary.yaml) — Unified taxonomy mapping 1 resource, 1 action, 1 workflow, and 4 personas across operational (OpenAPI) and capability (Naftiko) dimensions

## Rules

- [2020 Police Brutality Spectral Rules](rules/2020-police-brutality-spectral-rules.yml) — 18 rules across 8 categories enforcing API documentation conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
