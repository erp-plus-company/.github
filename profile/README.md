# ERP Plus

ERP Plus is a modular ERP platform built with Ruby on Rails using a Modular Monolith architecture based on Rails Engines.

The platform is designed to support long-term growth through strict domain boundaries, multi-tenancy, documented governance, and controlled system evolution.

---

## Architecture

ERP Plus follows:

- Modular Monolith Architecture
- Domain-Driven Design principles
- Rails Engine Isolation
- Multi-Tenancy by Design
- Security by Default
- Documentation First

---

## Core Repositories

### Main Application

ERP Plus Application

https://github.com/erp-plus-company/erp_plus

### Documentation

ERP Plus Documentation

https://github.com/erp-plus-company/erp-plus-docs

### Organization Standards

ERP Plus Organization Standards

https://github.com/erp-plus-company/.github

---

## Documentation

Official platform documentation:

https://erp-plus-company.github.io/erp-plus-docs/

Documentation includes:

- Organization Governance
- System Architecture
- Engine Design
- Product & Delivery Management
- Development Workflows
- Deployment Procedures
- Security Policies
- Architecture Decision Records (ADRs)

---

## Delivery Workflow

ERP Plus separates:

```txt
Planning
 ↓
Implementation
 ↓
Deployment
```

into dedicated systems.

### Planning

Taiga

- Epics
- User Stories
- Tasks
- Issues
- Sprints

### Implementation

GitHub

- Branches
- Commits
- Pull Requests
- Releases

### Deployment

GitHub Actions

Docker

Kamal

---

## Contribution Models

### Internal Contributors

Internal contributors work through:

- Taiga
- GitHub
- CI/CD workflows

### Community Contributors

Community contributors participate through:

- GitHub Issues
- Pull Requests
- Documentation Improvements

No Taiga access is required.

---

## Engineering Principles

ERP Plus prioritizes:

- Explicit Architecture
- Engine Isolation
- Traceability
- Governance
- Security
- Maintainability

---

## License

Apache License 2.0
