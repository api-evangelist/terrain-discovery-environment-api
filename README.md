# Terrain Discovery Environment API (terrain-discovery-environment-api)

Terrain is the primary REST API gateway for CyVerse's Discovery Environment (DE), an open-source data science workbench. Terrain validates user authentication via Keycloak/JWT and orchestrates calls to backend microservices covering filesystem operations, application management, data analysis, metadata annotation, notifications, and persistent identifier management.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/terrain-discovery-environment-api/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/terrain-discovery-environment-api/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Bioinformatics
- Data Science
- Life Sciences
- Filesystem
- Cloud Computing
- Open Source

## Timestamps

- **Created:** 2026-03-16
- **Modified:** 2026-05-19

## APIs

### Terrain API

The Terrain API is the main entry-point REST service for the CyVerse Discovery Environment. It handles authentication via Keycloak JWT tokens and orchestrates calls to backend services for filesystem management, app execution, data analysis, metadata, notifications, and more.

- **Human URL:** [https://cyverse.org/Science-APIs](https://cyverse.org/Science-APIs)
- **Base URL:** `https://de.cyverse.org/terrain`

#### Tags

- Bioinformatics
- Filesystem
- Data Analysis
- Applications
- Notifications

#### Properties

- [Documentation](https://docs.cyverse.org/services/api_overview/)
- [Swagger U I](https://de.cyverse.org/terrain/docs)
- [Repository](https://github.com/cyverse-de/terrain)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/terrain-discovery-environment-api/refs/heads/main/openapi/terrain-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/terrain.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/terrain.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Portal](https://cyverse.org/Science-APIs)
- [Documentation](https://docs.cyverse.org)
- [Repository](https://github.com/cyverse-de/terrain)
- [Portal](https://de.cyverse.org)
- [Webinar](https://cyverse.org/webinar_TerrainAPI)
- [Authentication](https://docs.cyverse.org/services/getting_started/)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
