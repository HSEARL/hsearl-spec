# HSEARL Documentation

This directory contains supplementary documentation for the HSEARL specification project.

## Contents

### Core Documentation
- **[Glossary](./glossary.md)** - Definitions of key terms and concepts
- **[Architecture Overview](./architecture/)** - High-level system design

### Guides
- **[Getting Started Guide](./guides/getting-started.md)** - Quick introduction to HSEARL
- **[Specification Guide](./guides/specification.md)** - Understanding HSEARL specifications
- **[Extension Guide](./guides/extensions.md)** - Creating HSEARL extensions

### Design Documents
- **[Design Principles](./design/principles.md)** - Core design philosophy
- **[Architecture Decisions](./design/adr/)** - Architecture Decision Records
- **[Rationale](./design/rationale.md)** - Why HSEARL is designed this way

## Navigation

- **Specifications**: See [`/specs/`](../specs/) for formal specifications
- **Schemas**: See [`/schemas/`](../schemas/) for data structure definitions
- **RFCs**: See [`/RFCs/`](../RFCs/) for proposals

## Contributing

To contribute documentation:
1. Follow the [style guide](./style-guide.md)
2. Use clear, concise language
3. Include examples where helpful
4. Keep documents focused on a single topic
5. Update the glossary for new terms

## Documentation Standards

### File Naming
- Use lowercase with hyphens: `my-document.md`
- Be descriptive but concise
- Group related documents in subdirectories

### Document Structure
1. Clear title and purpose
2. Table of contents for long documents
3. Logical section organization
4. Cross-references to related content
5. Examples and diagrams where appropriate

### Writing Style
- Active voice preferred
- Present tense for current behavior
- Define acronyms on first use
- Link to glossary for technical terms
- Use consistent terminology

## Building Documentation

Documentation can be built into various formats:

```bash
# Generate HTML documentation
make docs-html

# Generate PDF documentation
make docs-pdf

# Validate documentation
make docs-validate
```

## Translations

Community translations are welcome. See [translations/](./translations/) for available languages and contribution guidelines.