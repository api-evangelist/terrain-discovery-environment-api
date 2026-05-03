# Terrain Discovery Environment API

Terrain is the primary REST API gateway for CyVerse's Discovery Environment (DE), an open-source data science workbench for life sciences. Terrain validates user authentication via Keycloak JWT tokens and orchestrates calls to backend microservices covering filesystem operations, application management, data analysis, metadata annotation, notifications, and persistent identifier management.

**Type:** Company  
**Portal:** https://cyverse.org/Science-APIs  
**Documentation:** https://docs.cyverse.org/services/api_overview/  
**GitHub:** https://github.com/cyverse-de/terrain  
**Discovery Environment:** https://de.cyverse.org  

## APIs

### Terrain API
The main REST entry-point for the CyVerse Discovery Environment. Handles JWT authentication and coordinates calls to iRODS filesystem, app execution, analysis jobs, metadata, and notification services.

- **Base URL:** `https://de.cyverse.org/terrain`
- **Authentication:** Keycloak Bearer JWT / X-Iplant-De-Jwt header
- **Documentation:** https://docs.cyverse.org/services/api_overview/
- **OpenAPI Spec:** [openapi/terrain-openapi.yml](openapi/terrain-openapi.yml)

## Artifacts

| Type | Files |
|------|-------|
| OpenAPI Specs | [openapi/](openapi/) |
| Spectral Rules | [rules/terrain-rules.yml](rules/terrain-rules.yml) |
| Capabilities | [capabilities/](capabilities/) |
| JSON Schema | [json-schema/](json-schema/) |
| JSON Structure | [json-structure/](json-structure/) |
| JSON-LD | [json-ld/terrain-discovery-environment-api-context.jsonld](json-ld/terrain-discovery-environment-api-context.jsonld) |
| Examples | [examples/](examples/) |
| Vocabulary | [vocabulary/terrain-vocabulary.yml](vocabulary/terrain-vocabulary.yml) |

## Capabilities

### Workflow Capabilities
- **[data-science-workflow.yaml](capabilities/data-science-workflow.yaml)** — Unified workflow for CyVerse bioinformatics and data science: filesystem management, app discovery, job submission, metadata, sharing, and notifications (12 tools)

### Shared Per-API Definitions
- **[shared/terrain.yaml](capabilities/shared/terrain.yaml)** — Terrain API: filesystem, apps, analyses, metadata, sharing, notifications (12 tools)

## Tags

Bioinformatics, Data Science, Life Sciences, Filesystem, iRODS, Cloud Computing, Open Source, CyVerse, Research Computing, Open Science

## Maintainers

**FN:** Kin Lane  
**Email:** kin@apievangelist.com
