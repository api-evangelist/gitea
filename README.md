# Gitea

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Gitea is an open-source, self-hosted Git service and all-in-one DevOps platform written in Go and licensed under the MIT License. It provides Git hosting, code review, team collaboration, an integrated package registry across 24+ formats, issue tracking, project boards, and GitHub-Actions-compatible CI/CD via Gitea Actions. Gitea ships with a comprehensive Swagger 2.0 / OpenAPI-described REST API at /api/v1/ exposing roughly 300 operations across repositories, users, organizations, issues, packages, notifications, admin, and miscellaneous tags. The project is governed by CommitGo, Inc., which also offers Gitea Enterprise (self-managed, with SSO, audit logs and Kubernetes auto-scaling runners) and Gitea Cloud (single-tenant fully-managed hosting in multiple regions).

**Areas:** Gitea · Version Control · DevOps · CI/CD · Code Hosting · Open Source · Self-Hosted · Package Registry · Issue Tracking · Pull Requests

## Gitea on APIs.io

Everything profiled for Gitea is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/gitea/](https://apis.io/providers/gitea/)** — or go straight to one of the APIs or properties below.

### APIs (13)

- [Gitea Actions API](https://apis.io/apis/gitea/gitea-actions-api/) — GitHub-Actions-compatible workflow engine embedded in Gitea. The Actions API surface is exposed under the main REST API (/repos/{owner}/{repo}/actions/* and…
- [Gitea Package Registry](https://apis.io/apis/gitea/gitea-package-registry/) — Multi-format package registry built into Gitea exposing client protocols for 24 ecosystems including Cargo, Composer, Conan, Conda, Container (OCI), CRAN,…
- [Gitea Webhooks](https://apis.io/apis/gitea/gitea-webhooks/) — Outbound HTTP webhook system delivering JSON event payloads for pushes, pull requests, issues, releases, package events, and more. Webhooks are configurable…
- [Gitea Cloud Management API](https://apis.io/apis/gitea/gitea-cloud-management-api/) — Gitea Cloud management plane for provisioning and operating single-tenant managed Gitea instances. Each provisioned instance exposes the same REST API at…
- [Gitea Admin API](https://apis.io/apis/gitea/gitea-admin-api/) — The admin API from Gitea — 22 operation(s) for admin.
- [Gitea Issue API](https://apis.io/apis/gitea/gitea-issue-api/) — The issue API from Gitea — 34 operation(s) for issue.
- [Gitea Miscellaneous API](https://apis.io/apis/gitea/gitea-miscellaneous-api/) — The miscellaneous API from Gitea — 12 operation(s) for miscellaneous.
- [Gitea Notification API](https://apis.io/apis/gitea/gitea-notification-api/) — The notification API from Gitea — 4 operation(s) for notification.
- [Gitea Organization API](https://apis.io/apis/gitea/gitea-organization-api/) — The organization API from Gitea — 37 operation(s) for organization.
- [Gitea Package API](https://apis.io/apis/gitea/gitea-package-api/) — The package API from Gitea — 7 operation(s) for package.
- [Gitea Repository API](https://apis.io/apis/gitea/gitea-repository-api/) — The repository API from Gitea — 133 operation(s) for repository.
- [Gitea Settings API](https://apis.io/apis/gitea/gitea-settings-api/) — The settings API from Gitea — 4 operation(s) for settings.
- [Gitea User API](https://apis.io/apis/gitea/gitea-user-api/) — The user API from Gitea — 48 operation(s) for user.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Arazzo workflows (19)

Multi-step workflows that chain operations into a business task.

- [Gitea Bootstrap Repository With Tracking Issue](https://apis.io/arazzos/gitea/gitea-bootstrap-repo-with-tracking-issue-workflow/)
- [Gitea Feature Branch To Merged Pull Request](https://apis.io/arazzos/gitea/gitea-branch-pull-request-merge-workflow/)
- [Gitea Comment And Close Issue](https://apis.io/arazzos/gitea/gitea-comment-and-close-issue-workflow/)
- [Gitea Commit File On New Branch And Open Pull Request](https://apis.io/arazzos/gitea/gitea-commit-file-and-open-pr-workflow/)
- [Gitea Create Branch And Await Availability](https://apis.io/arazzos/gitea/gitea-create-branch-and-await-workflow/)
- [Gitea Draft Then Publish Release](https://apis.io/arazzos/gitea/gitea-draft-then-publish-release-workflow/)
- [Gitea Create Label And Apply To Issue](https://apis.io/arazzos/gitea/gitea-label-create-and-apply-workflow/)
- [Gitea Create Milestone With Tracked Issue](https://apis.io/arazzos/gitea/gitea-milestone-with-issue-workflow/)
- [Gitea Sync Mirror And Confirm Branch](https://apis.io/arazzos/gitea/gitea-mirror-sync-workflow/)
- [Gitea Open And Triage Pull Request](https://apis.io/arazzos/gitea/gitea-open-and-triage-pull-request-workflow/)
- [Gitea Bootstrap Organization With Shared Label](https://apis.io/arazzos/gitea/gitea-org-bootstrap-with-label-workflow/)
- [Gitea Provision Organization Repository With Webhook](https://apis.io/arazzos/gitea/gitea-org-repo-with-webhook-workflow/)
- [Gitea Create Organization With Webhook](https://apis.io/arazzos/gitea/gitea-org-with-webhook-workflow/)
- [Gitea Create Release And Verify By Tag](https://apis.io/arazzos/gitea/gitea-release-and-verify-by-tag-workflow/)
- [Gitea Publish Release With Asset](https://apis.io/arazzos/gitea/gitea-release-with-asset-workflow/)
- [Gitea Create Repository With A Labeled Issue](https://apis.io/arazzos/gitea/gitea-repo-with-labeled-issue-workflow/)
- [Gitea Create Repository With Webhook](https://apis.io/arazzos/gitea/gitea-repo-with-webhook-workflow/)
- [Gitea Report Issue To Existing Repository](https://apis.io/arazzos/gitea/gitea-report-issue-to-existing-repo-workflow/)
- [Gitea Sprint Issue Setup](https://apis.io/arazzos/gitea/gitea-sprint-issue-setup-workflow/)

#### MCP servers (1)

Model Context Protocol servers that expose the API to agents.

- [gitea-mcp](https://apis.io/servers/gitea/gitea-mcp/)

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Gitea Agentic Access](https://apis.io/agentic-access/gitea/gitea-agentic-access/)

#### JSON Schema (16)

The data models the API reads and writes.

- [Branch](https://apis.io/schemas/gitea/gitea-rest-api-branch/)
- [Comment](https://apis.io/schemas/gitea/gitea-rest-api-comment/)
- [Commit contains information generated from a Git commit.](https://apis.io/schemas/gitea/gitea-rest-api-commit/)
- [Hook](https://apis.io/schemas/gitea/gitea-rest-api-hook/)
- [Issue](https://apis.io/schemas/gitea/gitea-rest-api-issue/)
- [Label](https://apis.io/schemas/gitea/gitea-rest-api-label/)
- [Milestone](https://apis.io/schemas/gitea/gitea-rest-api-milestone/)
- [NotificationThread](https://apis.io/schemas/gitea/gitea-rest-api-notificationthread/)
- [Organization](https://apis.io/schemas/gitea/gitea-rest-api-organization/)
- [Package](https://apis.io/schemas/gitea/gitea-rest-api-package/)
- [PullRequest](https://apis.io/schemas/gitea/gitea-rest-api-pullrequest/)
- [Release](https://apis.io/schemas/gitea/gitea-rest-api-release/)
- [Repository](https://apis.io/schemas/gitea/gitea-rest-api-repository/)
- [Tag](https://apis.io/schemas/gitea/gitea-rest-api-tag/)
- [Team](https://apis.io/schemas/gitea/gitea-rest-api-team/)
- [User](https://apis.io/schemas/gitea/gitea-rest-api-user/)

#### JSON Structure (16)

Data models expressed in JSON Structure.

- [Gitea Rest Api Branch Structure](https://apis.io/json-structure/gitea/gitea-rest-api-branch-structure/)
- [Gitea Rest Api Comment Structure](https://apis.io/json-structure/gitea/gitea-rest-api-comment-structure/)
- [Gitea Rest Api Commit Structure](https://apis.io/json-structure/gitea/gitea-rest-api-commit-structure/)
- [Gitea Rest Api Hook Structure](https://apis.io/json-structure/gitea/gitea-rest-api-hook-structure/)
- [Gitea Rest Api Issue Structure](https://apis.io/json-structure/gitea/gitea-rest-api-issue-structure/)
- [Gitea Rest Api Label Structure](https://apis.io/json-structure/gitea/gitea-rest-api-label-structure/)
- [Gitea Rest Api Milestone Structure](https://apis.io/json-structure/gitea/gitea-rest-api-milestone-structure/)
- [Gitea Rest Api Notificationthread Structure](https://apis.io/json-structure/gitea/gitea-rest-api-notificationthread-structure/)
- [Gitea Rest Api Organization Structure](https://apis.io/json-structure/gitea/gitea-rest-api-organization-structure/)
- [Gitea Rest Api Package Structure](https://apis.io/json-structure/gitea/gitea-rest-api-package-structure/)
- [Gitea Rest Api Pullrequest Structure](https://apis.io/json-structure/gitea/gitea-rest-api-pullrequest-structure/)
- [Gitea Rest Api Release Structure](https://apis.io/json-structure/gitea/gitea-rest-api-release-structure/)
- [Gitea Rest Api Repository Structure](https://apis.io/json-structure/gitea/gitea-rest-api-repository-structure/)
- [Gitea Rest Api Tag Structure](https://apis.io/json-structure/gitea/gitea-rest-api-tag-structure/)
- [Gitea Rest Api Team Structure](https://apis.io/json-structure/gitea/gitea-rest-api-team-structure/)
- [Gitea Rest Api User Structure](https://apis.io/json-structure/gitea/gitea-rest-api-user-structure/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Gitea Context](https://apis.io/jsonld/gitea/gitea-context/)

#### Vocabulary (1)

The provider's domain terms, defined.

- [Gitea Vocabulary](https://apis.io/vocabularies/gitea/gitea-vocabulary/)

#### Examples (23)

Example requests and responses.

- [Gitea Rest Api Admin User Create Example](https://apis.io/examples/gitea/gitea-rest-api-admin-user-create-example/)
- [Gitea Rest Api Branches List Example](https://apis.io/examples/gitea/gitea-rest-api-branches-list-example/)
- [Gitea Rest Api Commits List Example](https://apis.io/examples/gitea/gitea-rest-api-commits-list-example/)
- [Gitea Rest Api Hook Example](https://apis.io/examples/gitea/gitea-rest-api-hook-example/)
- [Gitea Rest Api Issue Create Example](https://apis.io/examples/gitea/gitea-rest-api-issue-create-example/)
- [Gitea Rest Api Issue Example](https://apis.io/examples/gitea/gitea-rest-api-issue-example/)
- [Gitea Rest Api Issues List Example](https://apis.io/examples/gitea/gitea-rest-api-issues-list-example/)
- [Gitea Rest Api Notifications List Example](https://apis.io/examples/gitea/gitea-rest-api-notifications-list-example/)
- [Gitea Rest Api Org Create Example](https://apis.io/examples/gitea/gitea-rest-api-org-create-example/)
- [Gitea Rest Api Org Repos List Example](https://apis.io/examples/gitea/gitea-rest-api-org-repos-list-example/)
- [Gitea Rest Api Package Example](https://apis.io/examples/gitea/gitea-rest-api-package-example/)
- [Gitea Rest Api Packages List Owner Example](https://apis.io/examples/gitea/gitea-rest-api-packages-list-owner-example/)
- [Gitea Rest Api Pull Create Example](https://apis.io/examples/gitea/gitea-rest-api-pull-create-example/)
- [Gitea Rest Api Pullrequest Example](https://apis.io/examples/gitea/gitea-rest-api-pullrequest-example/)
- [Gitea Rest Api Pulls List Example](https://apis.io/examples/gitea/gitea-rest-api-pulls-list-example/)
- [Gitea Rest Api Release Create Example](https://apis.io/examples/gitea/gitea-rest-api-release-create-example/)
- [Gitea Rest Api Release Example](https://apis.io/examples/gitea/gitea-rest-api-release-example/)
- [Gitea Rest Api Repo Get Example](https://apis.io/examples/gitea/gitea-rest-api-repo-get-example/)
- [Gitea Rest Api Repo Update Example](https://apis.io/examples/gitea/gitea-rest-api-repo-update-example/)
- [Gitea Rest Api Repository Example](https://apis.io/examples/gitea/gitea-rest-api-repository-example/)
- [Gitea Rest Api User Get Example](https://apis.io/examples/gitea/gitea-rest-api-user-get-example/)
- [Gitea Rest Api User Repo Create Example](https://apis.io/examples/gitea/gitea-rest-api-user-repo-create-example/)
- [Gitea Rest Api Webhook Create Example](https://apis.io/examples/gitea/gitea-rest-api-webhook-create-example/)

#### Collections (12)

Postman and Open Collection request collections.

- [Gitea admin API](https://apis.io/collections/gitea/open-gitea-admin-api/)
- [Gitea admin issue API](https://apis.io/collections/gitea/open-gitea-issue-api/)
- [Gitea admin miscellaneous API](https://apis.io/collections/gitea/open-gitea-miscellaneous-api/)
- [Gitea admin notification API](https://apis.io/collections/gitea/open-gitea-notification-api/)
- [Gitea admin organization API](https://apis.io/collections/gitea/open-gitea-organization-api/)
- [Gitea admin package API](https://apis.io/collections/gitea/open-gitea-package-api/)
- [Gitea admin repository API](https://apis.io/collections/gitea/open-gitea-repository-api/)
- [Gitea API](https://apis.io/collections/gitea/open-gitea-rest-api/)
- [Gitea admin settings API](https://apis.io/collections/gitea/open-gitea-settings-api/)
- [Gitea admin user API](https://apis.io/collections/gitea/open-gitea-user-api/)
- [Gitea API](https://apis.io/collections/gitea/postman-gitea-rest-api/)
- [Gitea API](https://apis.io/collections/gitea/postman-gitea-rest-api-openapi-original/)

#### Overlays (10)

OpenAPI overlays, including conversational phrasing for each operation.

- [Gitea Admin Api Phrasing Overlay](https://apis.io/overlays/gitea/gitea-admin-api-phrasing-overlay/)
- [Gitea Issue Api Phrasing Overlay](https://apis.io/overlays/gitea/gitea-issue-api-phrasing-overlay/)
- [Gitea Miscellaneous Api Phrasing Overlay](https://apis.io/overlays/gitea/gitea-miscellaneous-api-phrasing-overlay/)
- [Gitea Notification Api Phrasing Overlay](https://apis.io/overlays/gitea/gitea-notification-api-phrasing-overlay/)
- [Gitea Organization Api Phrasing Overlay](https://apis.io/overlays/gitea/gitea-organization-api-phrasing-overlay/)
- [Gitea Package Api Phrasing Overlay](https://apis.io/overlays/gitea/gitea-package-api-phrasing-overlay/)
- [Gitea Repository Api Phrasing Overlay](https://apis.io/overlays/gitea/gitea-repository-api-phrasing-overlay/)
- [Gitea Rest Api Overlay](https://apis.io/overlays/gitea/gitea-rest-api-overlay/)
- [Gitea Settings Api Phrasing Overlay](https://apis.io/overlays/gitea/gitea-settings-api-phrasing-overlay/)
- [Gitea User Api Phrasing Overlay](https://apis.io/overlays/gitea/gitea-user-api-phrasing-overlay/)

#### Governance rules (3)

Spectral rulesets for the provider's contracts.

- [Gitea — gitea rules](https://apis.io/rules/gitea/gitea-gitea-spectral-rules/)
- [Gitea — jsonschema rules](https://apis.io/rules/gitea/gitea-jsonschema-spectral-rules/)
- [Gitea API Rules](https://apis.io/rules/gitea/gitea-rules/)

#### Security (4)

Authentication, trust centre, and vulnerability disclosure.

- [Gitea Authentication](https://apis.io/security/gitea/gitea-authentication/)
- [Gitea Domain Security](https://apis.io/security/gitea/gitea-domain-security/)
- [Gitea Trust Center](https://apis.io/security/gitea/gitea-trust-center/)
- [Gitea Vulnerability Disclosure](https://apis.io/security/gitea/gitea-vulnerability-disclosure/)

#### OAuth scopes (1)

The permissions the API asks for.

- [Gitea Scopes](https://apis.io/scopes/gitea/gitea-scopes/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Gitea Plans Pricing](https://apis.io/plans/gitea/gitea-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Gitea Rate Limits](https://apis.io/rate-limits/gitea/gitea-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Gitea Finops](https://apis.io/finops/gitea/gitea-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://about.gitea.com/)
- [Documentation](https://docs.gitea.com/)
- [API reference](https://docs.gitea.com/api/)
- [Pricing](https://about.gitea.com/pricing/)
- [Support](https://forum.gitea.com/)
- [Changelog](https://github.com/go-gitea/gitea/blob/main/CHANGELOG.md)
- [Blog](https://blog.gitea.com/)
- [Security](https://docs.gitea.com/administration/security)
- [Compliance](https://about.gitea.com/products/cloud)
- [Terms of service](https://about.gitea.com/legal/terms-of-service)
- [Privacy policy](https://about.gitea.com/legal/privacy-policy)
- [GitHub](https://github.com/go-gitea)
- [Status](https://status.gitea.com/)

## API Evangelist rating

**Kin Score 65.5** — strong · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 64.3 |
| Contract quality | 60.6 |
| Contract governance | 31.8 |
| Operational transparency | 42.1 |
| Developer ergonomics | 79.8 |
| Access clarity | 47.4 |

**Agent readiness 31.0** — agent-ready

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | documented (partial credit) |
| MCP Server | — |
| Auth Clarity | served (partial credit) |
| Idempotency | — |
| Error Semantics | derived (partial credit) |
| OpenAPI Examples | documented (partial credit) |
| Rate Limit Signal | derived (partial credit) |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | served (partial credit) |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | partial |
| Operation Distinctiveness | mostly |

**Regulatory alignment 37.3** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/gitea/](https://apis.io/providers/gitea/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Gitea: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/gitea/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
