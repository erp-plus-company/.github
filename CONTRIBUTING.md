# Contributing to ERP Plus

Thank you for contributing to ERP Plus.

## Principles

ERP Plus follows:

- Modular Monolith Architecture
- Rails Engine Isolation
- Documentation First
- Security by Default

## Contribution Models

ERP Plus supports two contributor types.

### Internal Contributors

Internal contributors use:

- GitHub
- Taiga

Work is tracked through User Stories and Tasks managed in Taiga.

### External Contributors

External contributors use:

- GitHub Issues
- Pull Requests

External contributors do not require access to Taiga.

Official planning remains managed internally through Taiga.

## Development Workflow

Issue
→ Feature Branch
→ Pull Request
→ Review
→ Merge

## Branch Naming

Examples:

feature/erp_users/invitation-flow

fix/erp_inventory/stock-calculation

docs/architecture/update-engine-map

## Pull Requests

Every Pull Request should:

- include a clear description
- reference related issues
- include tests when applicable
- update documentation when necessary

## Engine Rules

Business logic must remain inside engines.

Cross-engine coupling is prohibited unless explicitly documented through public interfaces.

## Additional Documentation

For architecture standards, engine boundaries, and development workflows, see:

https://erp-plus-company.github.io/erp-plus-docs/
