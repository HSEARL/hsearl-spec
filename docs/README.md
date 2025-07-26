# HSEARL Documentation

**Languages:** [English](README.md) | [日本語](README.ja.md)

This directory contains supplementary documentation for the HSEARL specification project. It serves as the central hub for architecture references, guides, design notes, and translation support.

---

## Structure Overview

### Core Architecture

* **[Overview (Ver.2)](./architecture/overview-v2.md)** – Full model definition, including the 6 parameters and interdependencies
* **[Glossary](./glossary.md)** – Definitions of key terms and system vocabulary

### Component Guides

* **[Cognitive (認知型)](../specs/core/cognitive.md)** – Information processing tendencies (MBTI-based)
* **[Motivational (動機型)](../specs/core/motivational.md)** – Core desires and fears (Enneagram-based)
* **[Reactive (反応型)](../specs/core/reactive.md)** – Defense and expression patterns (Tritype-based)
* **[Affective Wiring (育ち)](../specs/core/affective.md)** – Emotional imprint from childhood context
* **[Role Layer (ロール)](../specs/core/roles.md)** – Externalized behavioral adaptation

### Usage & Strategy

* **[Getting Started](./guides/getting-started.md)** – Quick intro to HSEARL usage
* **[Specification Guide](./guides/specification.md)** – Specification format and usage logic
* **[Extension Modules](./guides/extensions.md)** – Building auxiliary background filters (age, culture, etc.)

### Design Documents

* **[Design Principles](./design/principles.md)** – Structural and philosophical foundation
* **[Architecture Decisions](./design/adr/)** – Decision logs for key design shifts
* **[Interpretation Notes](./design/rationale.md)** – Theoretical rationales and justification
* **[Status Notes](./status.md)** – Current working hypotheses, focal parameters, and temporary rules

### Translations

* **[Glossary (Japanese)](./ja/glossary.md)** – 日本語用語集

---

## Navigation

* **Formal Specs** → [`/specs/`](../specs/)
* **Schemas** → [`/schemas/`](../schemas/)
* **RFCs** → [`/RFCs/`](../RFCs/)

---

## Contribution Guidelines

1. Follow the [style guide](./style-guide.md)
2. Keep documents modular and focused
3. Include diagrams, examples, and glossary links
4. Use present tense and active voice
5. Define acronyms and reference related content

---

## Documentation Standards

### File Naming

* Use lowercase with hyphens: `cognitive.md`, `overview-v2.md`
* Place topic-specific docs under appropriate folders

### Structure Template

1. Clear title and objective
2. Table of contents for long files
3. Logical sectioning with examples
4. Cross-links between related concepts

### Style Norms

* Active voice, present tense
* Consistent technical vocabulary
* Acronym definitions on first use

---

## Build & Validate

```bash
make docs-html     # Generate HTML
make docs-pdf      # Generate PDF
make docs-validate # Check formatting
```

---

Feel free to propose changes, additions, or translations via GitHub Issues or Pull Requests.
