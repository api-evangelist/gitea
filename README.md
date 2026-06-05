# Gitea (gitea)

Gitea is an open-source, self-hosted Git service and all-in-one DevOps platform written in Go and licensed under the MIT License. It provides Git hosting, code review, team collaboration, an integrated package registry across 24+ formats, issue tracking, project boards, and GitHub-Actions-compatible CI/CD via Gitea Actions. Gitea ships with a comprehensive Swagger 2.0 / OpenAPI-described REST API at /api/v1/ exposing roughly 300 operations across repositories, users, organizations, issues, packages, notifications, admin, and miscellaneous tags. The project is governed by CommitGo, Inc., which also offers Gitea Enterprise (self-managed, with SSO, audit logs and Kubernetes auto-scaling runners) and Gitea Cloud (single-tenant fully-managed hosting in multiple regions).

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/gitea/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/gitea/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- Git
- Source Control
- DevOps
- CI/CD
- Code Hosting
- Open Source
- Self Hosted
- Package Registry
- Issue Tracking
- Pull Requests

## Timestamps

- **Created:** 2026-05-06
- **Modified:** 2026-05-19

## APIs

### Gitea REST API

Swagger 2.0-described REST API exposed by every Gitea instance at /api/v1/. Approximately 300 operations cover repository, branch, commit, pull request, issue, milestone, label, release, webhook, organization, team, user, package, notification, admin and miscellaneous functionality. Authentication is supported via BasicAuth, personal access tokens (Token / AccessToken / AuthorizationHeaderToken), OAuth2 bearer tokens, optional sudo headers/parameters, and TOTP. The same API surface is shipped with Gitea Enterprise and Gitea Cloud.

- **Human URL:** [https://docs.gitea.com/api/](https://docs.gitea.com/api/)
- **Base URL:** `https://gitea.com/api/v1`

#### Tags

- REST
- Git
- Code Hosting
- DevOps

#### Properties

- [Documentation](https://docs.gitea.com/api/)
- [API Reference](https://docs.gitea.com/api/1.26/)
- [Swagger](https://demo.gitea.com/api/swagger)
- [OpenAPI](https://demo.gitea.com/swagger.v1.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [OpenAPI](openapi/gitea-rest-api-openapi-original.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [OpenAPI](openapi/gitea-rest-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/gitea-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/gitea-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Getting Started](https://docs.gitea.com/development/api-usage)
- [Authentication](https://docs.gitea.com/development/oauth2-provider)
- [JSON Schema](json-schema/gitea-rest-api-repository-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/gitea-rest-api-issue-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/gitea-rest-api-pullrequest-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/gitea-rest-api-branch-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/gitea-rest-api-commit-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/gitea-rest-api-release-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/gitea-rest-api-hook-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/gitea-rest-api-organization-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/gitea-rest-api-team-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/gitea-rest-api-user-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/gitea-rest-api-notificationthread-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/gitea-rest-api-package-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/gitea-rest-api-label-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/gitea-rest-api-milestone-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/gitea-rest-api-tag-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/gitea-rest-api-comment-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/gitea-rest-api-repository-structure.json)
- [JSON Structure](json-structure/gitea-rest-api-issue-structure.json)
- [JSON Structure](json-structure/gitea-rest-api-pullrequest-structure.json)
- [JSON Structure](json-structure/gitea-rest-api-branch-structure.json)
- [JSON Structure](json-structure/gitea-rest-api-commit-structure.json)
- [JSON Structure](json-structure/gitea-rest-api-release-structure.json)
- [JSON Structure](json-structure/gitea-rest-api-hook-structure.json)
- [JSON Structure](json-structure/gitea-rest-api-organization-structure.json)
- [JSON Structure](json-structure/gitea-rest-api-team-structure.json)
- [JSON Structure](json-structure/gitea-rest-api-user-structure.json)
- [JSON Structure](json-structure/gitea-rest-api-notificationthread-structure.json)
- [JSON Structure](json-structure/gitea-rest-api-package-structure.json)
- [JSON Structure](json-structure/gitea-rest-api-label-structure.json)
- [JSON Structure](json-structure/gitea-rest-api-milestone-structure.json)
- [JSON Structure](json-structure/gitea-rest-api-tag-structure.json)
- [JSON Structure](json-structure/gitea-rest-api-comment-structure.json)
- [Code Examples](examples/gitea-rest-api-repo-get-example.json)
- [Code Examples](examples/gitea-rest-api-repo-update-example.json)
- [Code Examples](examples/gitea-rest-api-issues-list-example.json)
- [Code Examples](examples/gitea-rest-api-issue-create-example.json)
- [Code Examples](examples/gitea-rest-api-pulls-list-example.json)
- [Code Examples](examples/gitea-rest-api-pull-create-example.json)
- [Code Examples](examples/gitea-rest-api-branches-list-example.json)
- [Code Examples](examples/gitea-rest-api-commits-list-example.json)
- [Code Examples](examples/gitea-rest-api-release-create-example.json)
- [Code Examples](examples/gitea-rest-api-webhook-create-example.json)
- [Code Examples](examples/gitea-rest-api-org-create-example.json)
- [Code Examples](examples/gitea-rest-api-org-repos-list-example.json)
- [Code Examples](examples/gitea-rest-api-user-get-example.json)
- [Code Examples](examples/gitea-rest-api-user-repo-create-example.json)
- [Code Examples](examples/gitea-rest-api-admin-user-create-example.json)
- [Code Examples](examples/gitea-rest-api-notifications-list-example.json)
- [Code Examples](examples/gitea-rest-api-packages-list-owner-example.json)
- [Code Examples](examples/gitea-rest-api-repository-example.json)
- [Code Examples](examples/gitea-rest-api-issue-example.json)
- [Code Examples](examples/gitea-rest-api-pullrequest-example.json)
- [Code Examples](examples/gitea-rest-api-release-example.json)
- [Code Examples](examples/gitea-rest-api-hook-example.json)
- [Code Examples](examples/gitea-rest-api-package-example.json)

### Gitea Actions API

GitHub-Actions-compatible workflow engine embedded in Gitea. The Actions API surface is exposed under the main REST API (/repos/{owner}/{repo}/actions/* and /admin/actions/*) for managing workflows, runs, jobs, runners, and secrets. Actions runners are deployed via the Go-based act_runner project.

- **Human URL:** [https://docs.gitea.com/usage/actions/overview](https://docs.gitea.com/usage/actions/overview)
- **Base URL:** `https://gitea.com/api/v1`

#### Tags

- CI/CD
- Workflows
- Automation

#### Properties

- [Documentation](https://docs.gitea.com/usage/actions/overview)
- [Quickstart](https://docs.gitea.com/usage/actions/quickstart)
- [API Reference](https://docs.gitea.com/usage/actions/comparison)
- [GitHub Repository](https://gitea.com/gitea/act_runner)
- [Postman Collection](collections/gitea-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/gitea-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Gitea Package Registry

Multi-format package registry built into Gitea exposing client protocols for 24 ecosystems including Cargo, Composer, Conan, Conda, Container (OCI), CRAN, Debian, Generic, Go, Helm, Maven, npm, NuGet, Pub, PyPI, RPM, RubyGems, Swift, Terraform, Vagrant, Alpine, Arch, Chef, and more. Packages are scoped per user or organization and addressable under /api/packages/{owner}/{type}.

- **Human URL:** [https://docs.gitea.com/usage/packages/overview](https://docs.gitea.com/usage/packages/overview)
- **Base URL:** `https://gitea.com/api/packages`

#### Tags

- Packages
- Registry
- Artifacts

#### Properties

- [Documentation](https://docs.gitea.com/usage/packages/overview)
- [API Reference](https://docs.gitea.com/usage/packages/cargo)
- [API Reference](https://docs.gitea.com/usage/packages/container)
- [API Reference](https://docs.gitea.com/usage/packages/helm)
- [Postman Collection](collections/gitea-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/gitea-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Gitea Webhooks

Outbound HTTP webhook system delivering JSON event payloads for pushes, pull requests, issues, releases, package events, and more. Webhooks are configurable per repository, organization or instance-wide and are managed through the REST API.

- **Human URL:** [https://docs.gitea.com/usage/webhooks](https://docs.gitea.com/usage/webhooks)

#### Tags

- Webhooks
- Events
- Eventing

#### Properties

- [Documentation](https://docs.gitea.com/usage/webhooks)
- [API Reference](https://docs.gitea.com/usage/webhooks#event-information)
- [Postman Collection](collections/gitea-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/gitea-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Gitea Cloud Management API

Gitea Cloud management plane for provisioning and operating single-tenant managed Gitea instances. Each provisioned instance exposes the same REST API at /api/v1/. The management plane itself does not currently publish a separate machine-readable OpenAPI definition; provisioning is performed via the cloud.gitea.com web console.

- **Human URL:** [https://about.gitea.com/products/cloud](https://about.gitea.com/products/cloud)
- **Base URL:** `https://cloud.gitea.com`

#### Tags

- Cloud
- Management
- Hosted

#### Properties

- [Documentation](https://about.gitea.com/products/cloud)
- [Pricing](https://about.gitea.com/products/gitea-cloud-pricing/)
- [Console](https://cloud.gitea.com/)
- [Postman Collection](collections/gitea-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/gitea-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Arazzo Workflows](arazzo/) — [Arazzo Specification](https://spec.openapis.org/arazzo/latest.html)
- [Website](https://about.gitea.com/)
- [Documentation](https://docs.gitea.com/)
- [API Reference](https://docs.gitea.com/api/)
- [Blog](https://blog.gitea.com/)
- [GitHub Organization](https://github.com/go-gitea)
- [GitHub Repository](https://github.com/go-gitea/gitea)
- [Sign Up](https://cloud.gitea.com/)
- [Pricing](https://about.gitea.com/pricing/)
- [Plans](plans/gitea-plans-pricing.yml)
- [Rate Limits](rate-limits/gitea-rate-limits.yml)
- [Fin Ops](finops/gitea-finops.yml)
- [Terms of Service](https://about.gitea.com/legal/terms-of-service)
- [Privacy Policy](https://about.gitea.com/legal/privacy-policy)
- [Support](https://forum.gitea.com/)
- [F A Q](https://about.gitea.com/about/faq)
- [Release Notes](https://blog.gitea.com/)
- [Changelog](https://github.com/go-gitea/gitea/blob/main/CHANGELOG.md)
- [Status Page](https://status.gitea.com/)
- [Security](https://docs.gitea.com/administration/security)
- [Compliance](https://about.gitea.com/products/cloud)
- [SDK](https://gitea.com/gitea/go-sdk)
- [SDK](https://www.npmjs.com/package/gitea-js)
- [SDK](https://pypi.org/project/py-gitea/)
- [SDK](https://github.com/hypermodeinc/gitea4j)
- [C L I](https://gitea.com/gitea/tea)
- [C L I](https://gitea.com/gitea/runner)
- [GitHub Repository](https://github.com/go-gitea/terraform-provider-gitea)
- [GitHub Repository](https://gitea.com/gitea/helm-gitea)
- [GitHub Repository](https://gitea.com/gitea/helm-actions)
- [Resources](https://gitea.com/gitea/awesome-gitea)
- [Hub](https://discord.gg/gitea)
- [Forum](https://forum.gitea.com/)
- [Spectral Rules](rules/gitea-rules.yml)
- [JSON-LD](json-ld/gitea-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Vocabulary](vocabulary/gitea-vocabulary.yml)
- [Features](undefined)
- [Use Cases](undefined)
- [Integrations](undefined)
- [Solutions](undefined)

## Maintainers

**FN:** Kin Lane
**Email:** kinlane@gmail.com
**URL:** https://kinlane.com
