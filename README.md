# Org-Wide Technical Decisions
This repository documents organizational technical decisions across projects within the `IainDavis.dev` ecosystem.

## Purpose
These records exist to make our decision-making process transparent, traceable, and durable over time. They provide context for architectural, tooling, and process choices that impact multiple projects or define shared conventions.

## Format
We use the [MADR format](https://adr.github.io/madr/) (Markdown Architectural Decision Records) with light extensions:
- Each decision is stored as a Markdown file under `decisions/`
- Files are numbered and titled, e.g., `0001-title-of-decision.md`
- Frontmatter includes fields like `status`, `date`, and `tags`

## Usage
- This content is published for reference and transparency.
- Please do not reproduce or adapt these records without explicit permission.
- If you have questions about a particular decision, feel free to reach out.

## Status
We are early in the process of collecting and formalizing these decisions. Expect this repository to evolve.

---

## Project-specific ADR collections
Decisions specific to individual projects are stored within those projects, typically in a developer documentation branch.

- [Docodylus ADRs][adrs-docodylus]

<!-- NAMED LINKS -->
[adrs-docodylus]:
    https://github.com/IainDavis-dev/docodylus/tree/dev-docs/docs/adr
    "Docodylus Architectural Decision Records"