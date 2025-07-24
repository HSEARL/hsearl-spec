# HSEARL Specifications

This directory contains the formal specifications for the HSEARL framework.

## Structure

- **[core/](./core/)** - Core framework definitions and fundamental concepts
- **[extensions/](./extensions/)** - Standard extensions that build upon the core
- **[experimental/](./experimental/)** - Experimental features under development

## Specification Format

Each specification document follows this structure:

1. **Overview** - High-level description and purpose
2. **Definitions** - Formal definitions of concepts and data structures
3. **Semantics** - Behavioral rules and constraints
4. **Examples** - Illustrative use cases
5. **Conformance** - Requirements for implementation

## Version Management

Specifications are versioned independently:
- Core specs use MAJOR.MINOR.PATCH versioning
- Extensions reference the core version they depend on
- Experimental features are unversioned until stabilized

## Contributing

To propose changes to specifications:
1. Submit an RFC in the `/RFCs/` directory
2. Participate in community discussion
3. Upon approval, submit a PR with the specification changes

See [CONTRIBUTING.md](../CONTRIBUTING.md) for detailed guidelines.