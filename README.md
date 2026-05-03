# StepZen

StepZen (now IBM API Connect Essentials) is a GraphQL-as-a-Service platform that enables developers to build, deploy, and manage GraphQL APIs connecting to multiple backends including REST APIs, SQL databases, NoSQL databases, and GraphQL endpoints. APIs are defined declaratively using GraphQL SDL with custom directives like @rest and @dbquery — no resolver code required.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/stepzen/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consuming
- **Access:** 3rd-Party

## Tags

- Backend Integration, GraphQL, API Gateway, REST to GraphQL, IBM, Data Federation

## Timestamps

- **Created:** 2026-03-16
- **Modified:** 2026-05-02

## APIs

### StepZen GraphQL API

GraphQL API platform for connecting to REST, databases, and other backends, automatically generating a GraphQL schema and resolvers from your data sources. Supports @rest, @dbquery, @connector, and @sequence directives.

**Human URL:** [https://stepzen.com/](https://stepzen.com/)

**Base URL:** `https://{account}.stepzen.net/{folder}/{name}/__graphql`

#### Tags

- GraphQL, API Integration, Data Federation, REST, Database

#### Properties

- [Documentation](https://stepzen.com/docs)
- [CLI Reference](https://stepzen.com/docs/cli/cli-commands)
- [GitHub Organization](https://github.com/stepzen-dev)
- [IBM Documentation](https://www.ibm.com/docs/en/stepzen)

### StepZen Admin API

REST API for managing StepZen accounts, deployed GraphQL endpoints, and API keys.

#### Properties

- [OpenAPI](openapi/stepzen-admin-openapi.yml)

## OpenAPI Specs

- [stepzen-admin-openapi.yml](openapi/stepzen-admin-openapi.yml) — Admin API for endpoint and key management

## Rules

- [stepzen-rules.yml](rules/stepzen-rules.yml) — Spectral ruleset enforcing StepZen API conventions

## Capabilities

### Workflow Capabilities

- [graphql-api-management.yaml](capabilities/graphql-api-management.yaml) — GraphQL endpoint lifecycle management (7 MCP tools)

### Shared Definitions

- [shared/stepzen-admin.yaml](capabilities/shared/stepzen-admin.yaml) — StepZen Admin API consumed definition

## JSON Schema

- [stepzen-endpoint-schema.json](json-schema/stepzen-endpoint-schema.json) — Schema for StepZen endpoint objects

## JSON Structure

- [stepzen-endpoint-structure.json](json-structure/stepzen-endpoint-structure.json) — Field structure documentation for endpoints

## JSON-LD

- [stepzen-context.jsonld](json-ld/stepzen-context.jsonld) — JSON-LD context for StepZen entities

## Examples

- [stepzen-list-endpoints-example.json](examples/stepzen-list-endpoints-example.json) — List Endpoints example

## Vocabulary

- [stepzen-vocabulary.yml](vocabulary/stepzen-vocabulary.yml) — Domain vocabulary including GraphQL directives and CLI commands

## Common Properties

- [Portal](https://stepzen.com/)
- [Documentation](https://stepzen.com/docs)
- [Website](https://stepzen.com/)
- [GitHub Organization](https://github.com/stepzen-dev)
- [Dashboard](https://dashboard.ibm.stepzen.com/)
- [IBM Product Page](https://www.ibm.com/products/api-connect)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
