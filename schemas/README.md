# HSEARL Schemas

This directory contains formal schema definitions for HSEARL data structures in various formats.

## Available Schemas

### JSON Schema
- **[hsearl-core.schema.json](./hsearl-core.schema.json)** - Core HSEARL data model
- **[hsearl-state.schema.json](./hsearl-state.schema.json)** - State representation schema
- **[hsearl-config.schema.json](./hsearl-config.schema.json)** - Configuration schema
- **[hsearl-events.schema.json](./hsearl-events.schema.json)** - Event and message schemas

### YAML Schema
- **[hsearl-core.schema.yaml](./hsearl-core.schema.yaml)** - Core model (YAML format)
- **[hsearl-config.schema.yaml](./hsearl-config.schema.yaml)** - Configuration (YAML format)

### Protocol Buffers
- **[hsearl.proto](./proto/hsearl.proto)** - Protocol buffer definitions
- **[hsearl-streaming.proto](./proto/hsearl-streaming.proto)** - Streaming protocol

### GraphQL
- **[hsearl.graphql](./graphql/hsearl.graphql)** - GraphQL schema for HSEARL APIs

## Usage

### Schema Structure Example

```json
{
  "$schema": "http://json-schema.org/draft-07/schema#",
  "title": "HSEARL Core Data Model",
  "type": "object",
  "properties": {
    "agent_id": {
      "type": "string",
      "description": "Unique identifier for the HSEARL agent"
    },
    "state": {
      "$ref": "#/definitions/AgentState"
    }
  },
  "required": ["agent_id", "state"]
}
```

### Data Format Example

```yaml
# Example HSEARL agent configuration
agent_id: "hsearl-001"
state:
  cognitive:
    working_memory:
      capacity: 7
      decay_rate: 0.1
  motivational:
    active_goals: ["explore", "learn"]
    need_levels:
      safety: 0.8
      social: 0.6
```

## Schema Versioning

- Schemas are versioned alongside specifications
- Breaking changes increment major version
- New optional fields increment minor version
- Clarifications increment patch version

## Contributing

When updating schemas:
1. Maintain backward compatibility when possible
2. Update all format variants (JSON, YAML, etc.)
3. Update specification documentation
4. Submit via RFC process for major changes

## Tools

- **[validators/](./validators/)** - Schema validation utilities
- **[generators/](./generators/)** - Code generation from schemas
- **[converters/](./converters/)** - Format conversion tools