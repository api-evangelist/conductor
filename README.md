# Conductor (conductor)
Conductor allows you to build a complex application using simple and granular tasks that do not need to be aware of or keep track of the state of your application's execution flow. Conductor keeps track of the state, calls tasks in the right order (sequentially or in parallel, as defined by you), retry calls if needed, handle failure scenarios gracefully, and outputs the final result.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/conductor/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Automation, Orchestration, State, Tasks, Workflows

## Timestamps

- **Created:** 2025-01-08
- **Modified:** 2026-04-18

## APIs

### Conductor
Conductor allows you to build a complex application using simple and granular tasks that do not need to be aware of or keep track of the state of your application's execution flow.

**Human URL:** [https://conductor-oss.github.io/conductor/documentation/api/workflow.html](https://conductor-oss.github.io/conductor/documentation/api/workflow.html)

#### Tags:

 - Automation, Orchestration, State, Tasks

#### Properties

- [Documentation](https://conductor-oss.github.io/conductor/documentation/api/workflow.html)
- [OpenAPI](openapi/conductor-conductor-openapi.yml)
- [AsyncAPI](asyncapi/conductor-conductor-asyncapi.yml)
- [JSONSchema](json-schema/workflow-def.json)
- [JSONSchema](json-schema/task-def.json)
- [JSONSchema](json-schema/workflow-execution.json)
- [JSONSchema](json-schema/event-handler.json)
- [JSONLD](json-ld/conductor-context.jsonld)

## Common Properties

- [GitHubRepository](https://github.com/conductor-oss/conductor)

## Features

| Name | Description |
|------|-------------|
| Workflow Orchestration | Define and execute complex workflows with sequential and parallel task execution. |
| Task Management | Register, poll, and update granular task definitions with timeout and retry policies. |
| Event Handling | Create event handlers to trigger workflows or tasks based on external events. |
| Workflow Search | Search and filter workflow executions by status, type, and custom parameters. |
| Fault Tolerance | Automatic retries, pause/resume, and graceful failure handling for long-running workflows. |
| Workflow Lifecycle Control | Pause, resume, restart, retry, and terminate workflows programmatically. |

## Use Cases

| Name | Description |
|------|-------------|
| Microservices Orchestration | Coordinate complex business processes across distributed microservices without tight coupling. |
| Data Pipeline Automation | Build and manage ETL and data processing pipelines with dependency tracking and error recovery. |
| Order Processing | Manage multi-step order fulfillment workflows including payment, inventory, and shipping. |
| CI/CD Pipelines | Orchestrate build, test, and deployment workflows with conditional logic and parallel execution. |

## Integrations

| Name | Description |
|------|-------------|
| Apache Kafka | Trigger workflows and tasks from Kafka events using event handler subscriptions. |
| Amazon SQS | Integrate with SQS for message-driven workflow initiation and task completion. |
| Docker | Run Conductor server and workers in containerized environments for scalable deployment. |
| Orkes Cloud | Use managed Conductor service from Orkes for enterprise-grade orchestration without infrastructure management. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Conductor OpenAPI](openapi/conductor-conductor-openapi.yml)

### AsyncAPI

- [Conductor AsyncAPI](asyncapi/conductor-conductor-asyncapi.yml)

### JSON Schema

- [Workflow Definition Schema](json-schema/workflow-def.json)
- [Task Definition Schema](json-schema/task-def.json)
- [Workflow Execution Schema](json-schema/workflow-execution.json)
- [Event Handler Schema](json-schema/event-handler.json)

### JSON-LD

- [Conductor Context](json-ld/conductor-context.jsonld)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [Conductor API](capabilities/shared/conductor.yaml) — 17 operations for workflow, task, and event handler management

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Workflow Orchestration](capabilities/workflow-orchestration.yaml) | Conductor API | 17 | Backend Developer |

## Vocabulary

- [Conductor Vocabulary](vocabulary/conductor-vocabulary.yaml)

## Rules

- [Conductor Spectral Rules](rules/conductor-spectral-rules.yml)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
