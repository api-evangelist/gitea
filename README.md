# Gitea (gitea)

Gitea is an open-source, self-hosted Git service and all-in-one DevOps platform written in Go and licensed under the MIT License. It provides Git hosting, code review, team collaboration, an integrated package registry across 24+ formats, issue tracking, project boards, and GitHub-Actions-compatible CI/CD via Gitea Actions. Gitea ships with a comprehensive Swagger 2.0 / OpenAPI-described REST API at `/api/v1/` exposing roughly 300 operations across repositories, users, organizations, issues, packages, notifications, admin, and miscellaneous tags. The project is governed by CommitGo, Inc., which also offers Gitea Enterprise (self-managed, with SSO, audit logs and Kubernetes auto-scaling runners) and Gitea Cloud (single-tenant fully-managed hosting in multiple regions).

**APIs.json:** [apis.yml](https://raw.githubusercontent.com/api-evangelist/gitea/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **x-type:** opensource
- **License:** MIT
- **Governance:** CommitGo, Inc.
- **Primary Language:** Go
- **Inbox issue:** [#903](https://github.com/api-evangelist/inbox/issues/903)

## Tags

Git, Source Control, DevOps, CI/CD, Code Hosting, Open Source, Self Hosted, Package Registry, Issue Tracking, Pull Requests

## APIs

### Gitea REST API
Swagger 2.0-described REST API exposed by every Gitea instance at `/api/v1/`. Approximately 300 operations cover repository, branch, commit, pull request, issue, milestone, label, release, webhook, organization, team, user, package, notification, admin and miscellaneous functionality.

- [Documentation](https://docs.gitea.com/api/)
- [API Reference](https://docs.gitea.com/api/1.26/)
- [Swagger UI](https://demo.gitea.com/api/swagger)
- [OpenAPI (source)](https://demo.gitea.com/swagger.v1.json)
- [OpenAPI (original Swagger 2.0)](openapi/gitea-rest-api-openapi-original.yml)
- [OpenAPI (3.0 converted, title-cased)](openapi/gitea-rest-api-openapi.yml)

### Gitea Actions API
GitHub-Actions-compatible workflow engine embedded in Gitea. The Actions API surface is exposed under the main REST API for managing workflows, runs, jobs, runners, and secrets.

- [Documentation](https://docs.gitea.com/usage/actions/overview)
- [Quickstart](https://docs.gitea.com/usage/actions/quickstart)
- [act_runner](https://gitea.com/gitea/act_runner)

### Gitea Package Registry
Multi-format package registry built into Gitea exposing client protocols for 24 ecosystems including Cargo, Composer, Conan, Conda, Container (OCI), CRAN, Debian, Generic, Go, Helm, Maven, npm, NuGet, Pub, PyPI, RPM, RubyGems, Swift, Terraform, Vagrant, Alpine, Arch, Chef, and more.

- [Documentation](https://docs.gitea.com/usage/packages/overview)

### Gitea Webhooks
Outbound HTTP webhook system delivering JSON event payloads for pushes, pull requests, issues, releases, package events, and more.

- [Documentation](https://docs.gitea.com/usage/webhooks)

### Gitea Cloud Management API
Gitea Cloud management plane for provisioning and operating single-tenant managed Gitea instances. Each provisioned instance exposes the same REST API at `/api/v1/`.

- [Product page](https://about.gitea.com/products/cloud)
- [Pricing](https://about.gitea.com/products/gitea-cloud-pricing/)
- [Console](https://cloud.gitea.com/)

## Common Properties

- [Website](https://about.gitea.com/)
- [Documentation](https://docs.gitea.com/)
- [API Reference](https://docs.gitea.com/api/)
- [Blog](https://blog.gitea.com/)
- [GitHub Organization](https://github.com/go-gitea)
- [GitHub Repository](https://github.com/go-gitea/gitea)
- [Sign Up (Cloud)](https://cloud.gitea.com/)
- [Pricing](https://about.gitea.com/pricing/)
- [Plans (machine-readable)](plans/gitea-plans-pricing.yml)
- [Rate Limits (machine-readable)](rate-limits/gitea-rate-limits.yml)
- [FinOps (machine-readable)](finops/gitea-finops.yml)
- [Status](https://status.gitea.com/)
- [Forum](https://forum.gitea.com/)
- [Discord](https://discord.gg/gitea)
- [JSON-LD Context](json-ld/gitea-context.jsonld)
- [Spectral Rules](rules/gitea-rules.yml)
- [Naftiko Capabilities](capabilities/gitea-capabilities.yml)
- [Vocabulary](vocabulary/gitea-vocabulary.yml)

## SDKs and Integrations

- [Gitea Go SDK](https://gitea.com/gitea/go-sdk)
- [gitea-js (TypeScript / JavaScript)](https://www.npmjs.com/package/gitea-js)
- [py-gitea (Python)](https://pypi.org/project/py-gitea/)
- [Tea CLI](https://gitea.com/gitea/tea)
- [act_runner (Gitea Actions Runner)](https://gitea.com/gitea/runner)
- [Terraform Provider for Gitea](https://github.com/go-gitea/terraform-provider-gitea)
- [Helm Chart for Gitea](https://gitea.com/gitea/helm-gitea)
- [Helm Chart for Gitea Actions](https://gitea.com/gitea/helm-actions)
- [Awesome Gitea (curated list)](https://gitea.com/gitea/awesome-gitea)

## Solutions

- **Gitea (Open Source)** - Free, MIT-licensed self-hosted edition with the complete feature set and unlimited users.
- **Gitea Enterprise** - Commercial self-hosted edition adding SAML SSO, audit logs, Kubernetes auto-scaling runners, priority SLA support ($9.50-$19/user/month, 30-day free trial).
- **Gitea Cloud** - Single-tenant fully-managed Gitea hosted by CommitGo with choice of regions (including a Frankfurt EU region), 24x7 availability, and SOC 2 Type 2 certification.

## Generated Artifacts

| Artifact | Count | Path |
|---|---|---|
| OpenAPI specs | 2 | [openapi/](openapi/) |
| JSON Schema | 16 | [json-schema/](json-schema/) |
| JSON Structure | 16 | [json-structure/](json-structure/) |
| JSON-LD context | 1 | [json-ld/](json-ld/) |
| Operation / entity examples | 23 | [examples/](examples/) |
| Spectral ruleset | 1 | [rules/](rules/) |
| Naftiko capabilities | 1 | [capabilities/](capabilities/) |
| Vocabulary | 1 | [vocabulary/](vocabulary/) |
| Plans / Pricing | 1 | [plans/](plans/) |
| Rate Limits | 1 | [rate-limits/](rate-limits/) |
| FinOps | 1 | [finops/](finops/) |

## Maintainers

- **FN:** Kin Lane
- **Email:** kinlane@gmail.com
- **URL:** https://kinlane.com
