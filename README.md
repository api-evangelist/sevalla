# Sevalla (sevalla)

Sevalla is an application, database, and static-site hosting platform-as-a-service by Kinsta, built on Google Cloud Platform and Cloudflare. It lets teams deploy apps from Git or Docker, provision managed databases (PostgreSQL, MySQL, MariaDB, MongoDB, Redis, Valkey), host static sites on a global edge, and run S3-compatible object storage. The public REST API (base https://api.sevalla.com/v3, Bearer API token) exposes 200+ endpoints to manage the entire platform programmatically.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/sevalla/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/sevalla/refs/heads/main/apis.yml)

## Tags

- Hosting
- PaaS
- Cloud
- Deployment
- Databases
- Static Sites
- Object Storage

## Timestamps

- **Created:** 2026-07-01
- **Modified:** 2026-07-01

## APIs

### Sevalla Applications API

Create, list, update, suspend, activate, clone, and delete applications deployed from Git or Docker; manage processes, environment variables, custom and system domains, private ports, TCP proxies, IP restrictions, CDN, and read-only repository access.

- **Human URL:** [https://api-docs.sevalla.com/](https://api-docs.sevalla.com/)
- **Base URL:** `https://api.sevalla.com/v3`

#### Tags

- Applications
- Deployment
- Processes
- Domains

#### Properties

- [Documentation](https://docs.sevalla.com/application-hosting)
- [API Reference](https://api-docs.sevalla.com/)
- [OpenAPI](openapi/sevalla-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/sevalla.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sevalla.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Sevalla Deployments API

Trigger, list, retrieve, cancel, and roll back application and static-site deployments, read deployment logs, and manage deploy hooks for automated CI/CD workflows.

- **Human URL:** [https://api-docs.sevalla.com/](https://api-docs.sevalla.com/)
- **Base URL:** `https://api.sevalla.com/v3`

#### Tags

- Deployments
- Builds
- Rollback
- Logs

#### Properties

- [Documentation](https://docs.sevalla.com/application-hosting/deployments)
- [API Reference](https://api-docs.sevalla.com/)
- [OpenAPI](openapi/sevalla-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/sevalla.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sevalla.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Sevalla Databases API

Provision and manage PostgreSQL, MySQL, MariaDB, MongoDB, Redis, and Valkey databases, with backups, restores, password resets, internal connections, external-access toggles, IP restrictions, and resource metrics.

- **Human URL:** [https://api-docs.sevalla.com/](https://api-docs.sevalla.com/)
- **Base URL:** `https://api.sevalla.com/v3`

#### Tags

- Databases
- PostgreSQL
- MySQL
- Redis
- Backups

#### Properties

- [Documentation](https://docs.sevalla.com/database-hosting)
- [API Reference](https://api-docs.sevalla.com/)
- [OpenAPI](openapi/sevalla-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/sevalla.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sevalla.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Sevalla Static Sites API

Build and deploy Git-backed static sites to a global edge network, with environment variables, custom domains, pretty URLs, cache purging, access logs, and traffic analytics.

- **Human URL:** [https://api-docs.sevalla.com/](https://api-docs.sevalla.com/)
- **Base URL:** `https://api.sevalla.com/v3`

#### Tags

- Static Sites
- Edge
- JAMstack
- CDN

#### Properties

- [Documentation](https://docs.sevalla.com/static-site-hosting)
- [API Reference](https://api-docs.sevalla.com/)
- [OpenAPI](openapi/sevalla-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/sevalla.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sevalla.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Sevalla Object Storage API

Create and manage S3-compatible object storage buckets (powered by Cloudflare R2), rotate access credentials, configure CORS policies and CDN, list and delete objects, and purge the CDN cache.

- **Human URL:** [https://api-docs.sevalla.com/](https://api-docs.sevalla.com/)
- **Base URL:** `https://api.sevalla.com/v3`

#### Tags

- Object Storage
- S3
- Buckets
- Cloudflare R2

#### Properties

- [Documentation](https://docs.sevalla.com/object-storage)
- [API Reference](https://api-docs.sevalla.com/)
- [OpenAPI](openapi/sevalla-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/sevalla.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sevalla.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Sevalla Pipelines API

Model multi-stage promotion pipelines that move applications across environments, add and remove applications from stages, promote between stages, and enable pull-request preview environments.

- **Human URL:** [https://api-docs.sevalla.com/](https://api-docs.sevalla.com/)
- **Base URL:** `https://api.sevalla.com/v3`

#### Tags

- Pipelines
- Environments
- Promotion
- Preview

#### Properties

- [Documentation](https://docs.sevalla.com/pipelines)
- [API Reference](https://api-docs.sevalla.com/)
- [OpenAPI](openapi/sevalla-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/sevalla.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sevalla.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Sevalla Operations API

Operate the platform at runtime - read CPU, memory, storage, request, and status-code metrics, retrieve access and runtime logs, manage webhooks and deliveries, configure usage alerts, and query reference resources such as clusters and process types.

- **Human URL:** [https://api-docs.sevalla.com/](https://api-docs.sevalla.com/)
- **Base URL:** `https://api.sevalla.com/v3`

#### Tags

- Operations
- Metrics
- Logs
- Webhooks

#### Properties

- [Documentation](https://docs.sevalla.com/)
- [API Reference](https://api-docs.sevalla.com/)
- [OpenAPI](openapi/sevalla-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/sevalla.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sevalla.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Sevalla Company and Account API

Manage company users and usage, organize resources into projects, create and rotate API keys with scoped roles and permissions, set global environment variables, and drive device-authorization flows.

- **Human URL:** [https://api-docs.sevalla.com/](https://api-docs.sevalla.com/)
- **Base URL:** `https://api.sevalla.com/v3`

#### Tags

- Company
- Account
- API Keys
- Projects
- Usage

#### Properties

- [Documentation](https://docs.sevalla.com/)
- [API Reference](https://api-docs.sevalla.com/)
- [OpenAPI](openapi/sevalla-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/sevalla.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sevalla.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/sevalla-hosting)
- [LinkedIn](https://www.linkedin.com/company/sevalla)
- [Website](https://sevalla.com/)
- [Documentation](https://docs.sevalla.com/)
- [Plans](plans/sevalla-plans-pricing.yml)
- [Rate Limits](rate-limits/sevalla-rate-limits.yml)
- [Fin Ops](finops/sevalla-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
