# HSEARL

[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)
[![Discussions](https://img.shields.io/badge/GitHub-Discussions-green)](https://github.com/HSEARL/hsearl-spec/discussions)
[![RFC Process](https://img.shields.io/badge/RFC-Process-orange)](./RFCs/)

**Languages:** [English](README.md) | [日本語](README.ja.md)

## Overview

This repository defines the core semantics, structure, and extension process of the HSEARL framework.

HSEARL is a framework and collection of technologies for building humans in digital spaces.

HSEARL aims to provide a formal specification for modeling:

- **Cognitive Architectures**: Memory systems, attention mechanisms, and decision-making processes
- **Motivational Dynamics**: Need hierarchies, goal pursuit, and behavioral adaptation
- **Environmental Interactions**: Context-aware responses and ecological constraints
- **Temporal Evolution**: Learning, development, and state transitions over time

The purpose of this project is to solve pure tasks in human activities, and does not address academic philosophy, rationale, or accuracy discussions about what it means to be human.

Currently, implementation using LLMs is assumed, and this can be regarded as the necessary framework and technologies for that purpose.

## Project Scope

This specification repository contains:
- **Core Definitions**: [Fundamental concepts and data structures](hsearl)
- **Extension Mechanisms**: How to add new capabilities while maintaining compatibility
- **Formal Schemas**: Data structure definitions and validation rules
- **Design Documentation**: Architecture guidelines and best practices

## Quick Start

```bash
# Clone the repository
git clone https://github.com/HSEARL/hsearl-spec.git
cd hsearl-spec

# Review core specifications
cd hsearl/

# Check data schemas
cd schemas/
```

## Repository Structure

```
hsearl-spec/
├── hsearl/            # HSEARL framework definitions
│   ├── frame/        # Framework specifications
│   ├── memory/       # Memory systems
│   └── physicality/  # Physicality
├── RFCs/             # Request for Comments (proposals)
├── schemas/          # JSON/YAML schemas
├── docs/             # Additional documentation
│   ├── architecture/ # Architecture guides
│   ├── design/       # Design documents
│   └── glossary.md   # Terms and definitions
├── experimental/     # Experimental features
└── LICENSE, README, etc. # Project files
```

## Key Documents

- 📚 **[Core Specification](./hsearl/)** - HSEARL core concepts
- 📜 **[RFC Process](./RFCs/)** - How to propose changes
- 📖 **[Glossary](./docs/glossary.md)** - Key terms and definitions ([Japanese](./docs/glossary.ja.md))

## Related Projects

- 🧪 **[hsearl-core](https://github.com/HSEARL/hsearl-core)** - Library code and prompt implementations

## Community

- **Discussions**: [GitHub Discussions](https://github.com/HSEARL/hsearl-spec/discussions)
- **Issues**: [Bug reports and feature requests](https://github.com/HSEARL/hsearl-spec/issues)
- **Mailing List**:

## Getting Involved

We welcome contributions! Please submit:
- RFCs for proposing changes
- Issues for bug reports and feature requests
- Pull requests for specification improvements
- Documentation enhancements

## Versioning

This specification follows [Semantic Versioning](https://semver.org/):
- **Major**: Breaking changes to core specifications
- **Minor**: New features, backwards compatible
- **Patch**: Clarifications and corrections

Current version: **0.1.0** (Pre-release)

## License

| Part | License | Commercial Use |
|------|------------|----------|
| hsearl-spec | Apache 2.0 | Free |
| hsearl-core (reference code) | Polyform Noncommercial 1.0.0 | **Prohibited** (requires separate agreement) |

Commercial licensing inquiries → **contact@zeetio.jp**