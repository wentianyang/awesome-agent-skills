# Project Context

## Purpose
**Awesome Agent Skills** is a curated repository of high-quality, structured skills for AI Agents. It serves as a resource for developers to discover, learn, and contribute standard skills that enhance agent capabilities (e.g., File Management, Web Search).

## Tech Stack
- **Languages**: Markdown, Python (scripts), Shell
- **Frameworks**: OpenSpec (for management), Agent-agnostic skills

## Project Conventions

### Code Style
- **Skills**: Each skill must be self-contained in `skills/<skill-name>`.
- **Definition**: Every skill requires a `SKILL.md` with structure: Instructions, Tools, Examples.
- **Documentation**: Use relative paths for all internal links.

### Architecture Patterns
- **Awesome List**: Curated index in `README.md`.
- **Modular Skills**: Isolated directories for each skill capability.

### Testing Strategy
- **Validation**: All changes must pass `openspec validate --strict`.
- **Link Checking**: Verify all relative links in documentation.

### Git Workflow
- **Spec-Driven**: Changes initiated via OpenSpec proposals (`initialize-project`, etc.).
- **Branches**: `main` is protected; use feature branches for proposals.

## Domain Context
AI Agents require structured instructions ("Skills") to perform complex tasks reliably. A "Skill" differs from a prompt by including tool definitions and logic flows.

## Important Constraints
- **Portability**: Skills should be usable across different agent frameworks where possible.
- **Privacy**: No absolute paths or user-specific data in commits.

## External Dependencies
- **OpenSpec**: For project governance and validation.
