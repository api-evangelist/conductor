# Conductor

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

Conductor allows you to build a complex application using simple and granular tasks that do not need to be aware of or keep track of the state of your application's execution flow. Conductor keeps track of the state, calls tasks in the right order (sequentially or in parallel, as defined by you), retry calls if needed, handle failure scenarios gracefully, and outputs the final result.

**Areas:** Automation · Orchestration · States · Task · Workflows

## Conductor on APIs.io

Everything profiled for Conductor is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/conductor/](https://apis.io/providers/conductor/)** — or go straight to one of the APIs or properties below.

### APIs (6)

- [Conductor Admin API](https://apis.io/apis/conductor/conductor-admin-api/) — Administrative and health check APIs
- [Conductor Event API](https://apis.io/apis/conductor/conductor-event-api/) — APIs for managing event handlers
- [Conductor Metadata - Task API](https://apis.io/apis/conductor/conductor-metadata-task-api/) — APIs for managing task definitions
- [Conductor Metadata - Workflow API](https://apis.io/apis/conductor/conductor-metadata-workflow-api/) — APIs for managing workflow definitions
- [Conductor Task API](https://apis.io/apis/conductor/conductor-task-api/) — APIs for polling and updating tasks
- [Conductor Workflow API](https://apis.io/apis/conductor/conductor-workflow-api/) — APIs for managing workflow executions

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### AsyncAPI (1)

Event-driven and webhook contracts.

- [Conductor Events API](https://apis.io/asyncapis/conductor/conductor-conductor-asyncapi/)

#### Event channels (12)

Individual events and webhooks the provider emits.

- [task.canceled](https://apis.io/channels/conductor/task-canceled/)
- [task.completed](https://apis.io/channels/conductor/task-completed/)
- [task.failed](https://apis.io/channels/conductor/task-failed/)
- [task.in_progress](https://apis.io/channels/conductor/task-in-progress/)
- [task.scheduled](https://apis.io/channels/conductor/task-scheduled/)
- [task.timed_out](https://apis.io/channels/conductor/task-timed-out/)
- [workflow.completed](https://apis.io/channels/conductor/workflow-completed/)
- [workflow.failed](https://apis.io/channels/conductor/workflow-failed/)
- [workflow.paused](https://apis.io/channels/conductor/workflow-paused/)
- [workflow.started](https://apis.io/channels/conductor/workflow-started/)
- [workflow.terminated](https://apis.io/channels/conductor/workflow-terminated/)
- [workflow.timed_out](https://apis.io/channels/conductor/workflow-timed-out/)

#### GraphQL (1)

GraphQL schemas.

- [Moved to /providers/conductor/](https://apis.io/graphqls/conductor/conductor-graphql/)

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Conductor Agentic Access](https://apis.io/agentic-access/conductor/conductor-agentic-access/)

#### JSON Schema (19)

The data models the API reads and writes.

- [EventHandler](https://apis.io/schemas/conductor/conductor-conductor-event-handler/)
- [EventHandlerAction](https://apis.io/schemas/conductor/conductor-conductor-event-handler-action/)
- [SearchResultTaskSummary](https://apis.io/schemas/conductor/conductor-conductor-search-result-task-summary/)
- [SearchResultWorkflowSummary](https://apis.io/schemas/conductor/conductor-conductor-search-result-workflow-summary/)
- [SkipTaskRequest](https://apis.io/schemas/conductor/conductor-conductor-skip-task-request/)
- [StartWorkflowRequest](https://apis.io/schemas/conductor/conductor-conductor-start-workflow-request/)
- [Task](https://apis.io/schemas/conductor/conductor-conductor-task/)
- [TaskDef](https://apis.io/schemas/conductor/conductor-conductor-task-def/)
- [TaskExecLog](https://apis.io/schemas/conductor/conductor-conductor-task-exec-log/)
- [TaskResult](https://apis.io/schemas/conductor/conductor-conductor-task-result/)
- [TaskSummary](https://apis.io/schemas/conductor/conductor-conductor-task-summary/)
- [Workflow](https://apis.io/schemas/conductor/conductor-conductor-workflow/)
- [WorkflowDef](https://apis.io/schemas/conductor/conductor-conductor-workflow-def/)
- [WorkflowSummary](https://apis.io/schemas/conductor/conductor-conductor-workflow-summary/)
- [WorkflowTask](https://apis.io/schemas/conductor/conductor-conductor-workflow-task/)
- [EventHandler](https://apis.io/schemas/conductor/event-handler/)
- [TaskDef](https://apis.io/schemas/conductor/task-def/)
- [WorkflowDef](https://apis.io/schemas/conductor/workflow-def/)
- [WorkflowExecution](https://apis.io/schemas/conductor/workflow-execution/)

#### JSON Structure (15)

Data models expressed in JSON Structure.

- [Conductor Conductor Event Handler Action Structure](https://apis.io/json-structure/conductor/conductor-conductor-event-handler-action-structure/)
- [Conductor Conductor Event Handler Structure](https://apis.io/json-structure/conductor/conductor-conductor-event-handler-structure/)
- [Conductor Conductor Search Result Task Summary Structure](https://apis.io/json-structure/conductor/conductor-conductor-search-result-task-summary-structure/)
- [Conductor Conductor Search Result Workflow Summary Structure](https://apis.io/json-structure/conductor/conductor-conductor-search-result-workflow-summary-structure/)
- [Conductor Conductor Skip Task Request Structure](https://apis.io/json-structure/conductor/conductor-conductor-skip-task-request-structure/)
- [Conductor Conductor Start Workflow Request Structure](https://apis.io/json-structure/conductor/conductor-conductor-start-workflow-request-structure/)
- [Conductor Conductor Task Def Structure](https://apis.io/json-structure/conductor/conductor-conductor-task-def-structure/)
- [Conductor Conductor Task Exec Log Structure](https://apis.io/json-structure/conductor/conductor-conductor-task-exec-log-structure/)
- [Conductor Conductor Task Result Structure](https://apis.io/json-structure/conductor/conductor-conductor-task-result-structure/)
- [Conductor Conductor Task Structure](https://apis.io/json-structure/conductor/conductor-conductor-task-structure/)
- [Conductor Conductor Task Summary Structure](https://apis.io/json-structure/conductor/conductor-conductor-task-summary-structure/)
- [Conductor Conductor Workflow Def Structure](https://apis.io/json-structure/conductor/conductor-conductor-workflow-def-structure/)
- [Conductor Conductor Workflow Structure](https://apis.io/json-structure/conductor/conductor-conductor-workflow-structure/)
- [Conductor Conductor Workflow Summary Structure](https://apis.io/json-structure/conductor/conductor-conductor-workflow-summary-structure/)
- [Conductor Conductor Workflow Task Structure](https://apis.io/json-structure/conductor/conductor-conductor-workflow-task-structure/)

#### JSON-LD (2)

Linked-data contexts for the provider's vocabulary.

- [Conductor Conductor Context](https://apis.io/jsonld/conductor/conductor-conductor-context/)
- [Conductor Context](https://apis.io/jsonld/conductor/conductor-context/)

#### Vocabulary (1)

The provider's domain terms, defined.

- [conductor API Vocabulary](https://apis.io/vocabularies/conductor/conductor-vocabulary/)

#### Examples (15)

Example requests and responses.

- [Conductor Conductor Event Handler Action Example](https://apis.io/examples/conductor/conductor-conductor-event-handler-action-example/)
- [Conductor Conductor Event Handler Example](https://apis.io/examples/conductor/conductor-conductor-event-handler-example/)
- [Conductor Conductor Search Result Task Summary Example](https://apis.io/examples/conductor/conductor-conductor-search-result-task-summary-example/)
- [Conductor Conductor Search Result Workflow Summary Example](https://apis.io/examples/conductor/conductor-conductor-search-result-workflow-summary-example/)
- [Conductor Conductor Skip Task Request Example](https://apis.io/examples/conductor/conductor-conductor-skip-task-request-example/)
- [Conductor Conductor Start Workflow Request Example](https://apis.io/examples/conductor/conductor-conductor-start-workflow-request-example/)
- [Conductor Conductor Task Def Example](https://apis.io/examples/conductor/conductor-conductor-task-def-example/)
- [Conductor Conductor Task Example](https://apis.io/examples/conductor/conductor-conductor-task-example/)
- [Conductor Conductor Task Exec Log Example](https://apis.io/examples/conductor/conductor-conductor-task-exec-log-example/)
- [Conductor Conductor Task Result Example](https://apis.io/examples/conductor/conductor-conductor-task-result-example/)
- [Conductor Conductor Task Summary Example](https://apis.io/examples/conductor/conductor-conductor-task-summary-example/)
- [Conductor Conductor Workflow Def Example](https://apis.io/examples/conductor/conductor-conductor-workflow-def-example/)
- [Conductor Conductor Workflow Example](https://apis.io/examples/conductor/conductor-conductor-workflow-example/)
- [Conductor Conductor Workflow Summary Example](https://apis.io/examples/conductor/conductor-conductor-workflow-summary-example/)
- [Conductor Conductor Workflow Task Example](https://apis.io/examples/conductor/conductor-conductor-workflow-task-example/)

#### Collections (7)

Postman and Open Collection request collections.

- [Conductor Admin API](https://apis.io/collections/conductor/open-conductor-admin-api/)
- [Conductor API](https://apis.io/collections/conductor/open-conductor-conductor/)
- [Conductor Admin Event API](https://apis.io/collections/conductor/open-conductor-event-api/)
- [Conductor Admin Metadata - Task API](https://apis.io/collections/conductor/open-conductor-metadata-task-api/)
- [Conductor Admin Metadata - Workflow API](https://apis.io/collections/conductor/open-conductor-metadata-workflow-api/)
- [Conductor Admin Task API](https://apis.io/collections/conductor/open-conductor-task-api/)
- [Conductor Admin Workflow API](https://apis.io/collections/conductor/open-conductor-workflow-api/)

#### Governance rules (3)

Spectral rulesets for the provider's contracts.

- [Conductor — asyncapi rules](https://apis.io/rules/conductor/conductor-asyncapi-spectral-rules/)
- [Conductor — jsonschema rules](https://apis.io/rules/conductor/conductor-jsonschema-spectral-rules/)
- [Conductor API Rules](https://apis.io/rules/conductor/conductor-spectral-rules/)

#### Security (1)

Authentication, trust centre, and vulnerability disclosure.

- [Conductor Domain Security](https://apis.io/security/conductor/conductor-domain-security/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Conductor Plans Pricing](https://apis.io/plans/conductor/conductor-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Conductor Rate Limits](https://apis.io/rate-limits/conductor/conductor-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Conductor Finops](https://apis.io/finops/conductor/conductor-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://conductor-oss.github.io)
- [Blog](https://orkes.io/blog/)

## API Evangelist rating

**Kin Score 40.5** — developing · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 57.1 |
| Contract quality | 69.3 |
| Contract governance | 27.3 |
| Operational transparency | 39.5 |
| Developer ergonomics | 11.9 |
| Access clarity | 7.9 |

**Agent readiness 17.6** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | — |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | — |
| Rate Limit Signal | derived (partial credit) |
| Event Surface Described | derived (partial credit) |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | — |
| Operation Distinctiveness | distinct |

**Regulatory alignment 10.8** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/conductor/](https://apis.io/providers/conductor/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Conductor: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/conductor/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
