# HSEARL RFCs (Request for Comments)

**Languages:** [English](README.md) | [日本語](README.ja.md)

This directory contains Request for Comments (RFCs) for the HSEARL specification. RFCs are design documents that describe new features, processes, or significant changes to the HSEARL framework.

## RFC運用ルール（簡略）

- HSEARLの定義・仕様に関する修正・提案は `RFCs/` に記述する
- 提案の形式は Markdown で、テンプレートに準拠
- 採択済みは `Active`、未定は `Draft` とする

## RFC Process

### 1. Creating an RFC

1. **Choose a number**: Find the next available RFC number (RFC-XXXX)
2. **Use the template**: Copy `RFC-TEMPLATE.md` and rename it to `RFC-XXXX-your-title.md`
3. **Fill in details**: Complete all sections of the template
4. **Set status**: Start with `Draft` status

### 2. Submitting an RFC

1. **Create a pull request** with your RFC document
2. **Include discussion**: Be prepared to engage in community discussion
3. **Address feedback**: Revise the RFC based on community input
4. **Wait for decision**: Maintainers will make the final decision

### 3. RFC Statuses

- **Draft**: Initial proposal, under discussion
- **Active**: Accepted and being implemented
- **Withdrawn**: Withdrawn by the author
- **Rejected**: Rejected after review
- **Superseded**: Replaced by a newer RFC

### 4. RFC Numbering

- RFC numbers are assigned sequentially (RFC-0001, RFC-0002, etc.)
- Numbers are not reused
- Use RFC-XXXX as placeholder until number is assigned

## Current RFCs

### Active RFCs
- [RFC-0001: HSEARL Core Definition](./RFC-0001-hsearl-core-definition.md) - Defines the core HSEARL framework

### Draft RFCs
*(None currently)*

### Template
- [RFC-TEMPLATE.md](./RFC-TEMPLATE.md) - Template for new RFCs

## Guidelines for RFC Authors

### Content Quality
- **Be specific**: Provide detailed technical specifications
- **Include examples**: Show how the proposal works in practice
- **Consider alternatives**: Discuss other approaches and why they weren't chosen
- **Address compatibility**: Explain impact on existing specifications

### Writing Style
- Use clear, technical language
- Structure content logically
- Include code examples where appropriate
- Reference related RFCs and specifications

### Review Process
- **Engage actively**: Respond to comments and questions
- **Be open to feedback**: Consider all suggestions seriously
- **Iterate quickly**: Update the RFC based on feedback
- **Build consensus**: Work toward community agreement

## RFC Review Criteria

Maintainers evaluate RFCs based on:

1. **Technical merit**: Is the proposal technically sound?
2. **Necessity**: Does it solve a real problem?
3. **Compatibility**: Does it maintain backward compatibility?
4. **Completeness**: Is the specification complete and clear?
5. **Community support**: Does the community support the change?

## Getting Help

- **Discussions**: Use [GitHub Discussions](https://github.com/HSEARL/hsearl-spec/discussions) for questions
- **Issues**: Report problems with the RFC process
- **Community**: Join the mailing list at hsearl-dev@googlegroups.com

## Historical Context

RFCs are inspired by the Internet RFC process and adapted for HSEARL specification development. They provide a structured way to propose and discuss changes while maintaining quality and community involvement.