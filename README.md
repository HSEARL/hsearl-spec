# HSEARL Specification

[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)
[![Discussions](https://img.shields.io/badge/GitHub-Discussions-green)](https://github.com/HSEARL/hsearl-spec/discussions)
[![RFC Process](https://img.shields.io/badge/RFC-Process-orange)](./RFCs/)

**Languages:** [English](README.md) | [日本語](README.ja.md)

## Overview

This repository defines the core semantics, structure, and extension process of the HSEARL (Human Semantic & Ecological Adaptive Representation Language) framework — a semantic skeleton for representing and simulating human cognition, motivation, and adaptation.

HSEARL provides a formal specification for modeling:
- **Cognitive Architectures**: Memory systems, attention mechanisms, and decision-making processes
- **Motivational Dynamics**: Need hierarchies, goal pursuit, and behavioral adaptation
- **Environmental Interactions**: Context-aware responses and ecological constraints
- **Temporal Evolution**: Learning, development, and state transitions over time

## Project Scope

This specification repository contains:
- **Core Definitions**: Fundamental concepts and data structures
- **Extension Mechanisms**: How to add new capabilities while maintaining compatibility
- **Formal Schemas**: Data structure definitions and validation rules
- **Design Documentation**: Architecture guidelines and best practices

## Quick Start

```bash
# Clone the repository
git clone https://github.com/HSEARL/hsearl-spec.git
cd hsearl-spec

# Review core specifications
cd specs/

# Check data schemas
cd schemas/
```

## Repository Structure

```
hsearl-spec/
├── specs/              # Formal specifications
│   ├── core/          # Core framework definitions
│   ├── extensions/    # Standard extensions
│   └── experimental/  # Experimental features
├── RFCs/              # Request for Comments (proposals)
├── schemas/           # JSON/YAML schemas
├── docs/              # Additional documentation
│   ├── architecture/  # Architecture guides
│   └── glossary.md   # Terms and definitions
└── .github/           # Project management
```

## Key Documents

- 📚 **[Core Specification](./specs/core/)** - Fundamental HSEARL concepts
- 📜 **[RFC Process](./RFCs/)** - How to propose changes
- 🏛️ **[Governance](./GOVERNANCE.md)** - Decision-making process
- 🔒 **[Security Policy](./SECURITY.md)** - Vulnerability reporting
- 📝 **[Contributing Guide](./CONTRIBUTING.md)** - How to contribute
- 📖 **[Glossary](./docs/glossary.md)** - Key terms and definitions

## Related Projects

- 🧪 **[hsearl-core](https://github.com/HSEARL/hsearl-core)** - Reference implementation
- 📊 **[hsearl-eval](https://github.com/HSEARL/hsearl-eval)** - Evaluation framework
- 🔧 **[hsearl-tools](https://github.com/HSEARL/hsearl-tools)** - Development utilities

## Community

- **Discussions**: [GitHub Discussions](https://github.com/HSEARL/hsearl-spec/discussions)
- **Issues**: [Bug reports and feature requests](https://github.com/HSEARL/hsearl-spec/issues)
- **Mailing List**: hsearl-dev@googlegroups.com

## Getting Involved

We welcome contributions! Please see our [Contributing Guide](./CONTRIBUTING.md) for details on:
- Submitting RFCs
- Reporting issues
- Specification improvements
- Documentation enhancements

## Versioning

This specification follows [Semantic Versioning](https://semver.org/):
- **Major**: Breaking changes to core specifications
- **Minor**: New features, backwards compatible
- **Patch**: Clarifications and corrections

Current version: **0.1.0** (Pre-release)

## License

This project is licensed under the Apache License 2.0 - see the [LICENSE](./LICENSE) file for details.
