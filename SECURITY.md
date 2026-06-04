# Security Policy

## Supported Versions

ERP Plus is under active development.

Security fixes are applied to the currently maintained codebase.

---

## Reporting a Vulnerability

Do not disclose security vulnerabilities through:

- Public GitHub Issues
- Pull Requests
- Discussions
- Documentation repositories

Security vulnerabilities must be reported privately through:

- GitHub Security Advisories
- Direct communication with ERP Plus maintainers

Include whenever possible:

- Vulnerability description
- Potential impact
- Reproduction steps
- Affected components
- Suggested mitigation

---

## Security Practices

ERP Plus incorporates multiple security controls, including:

- Brakeman static analysis
- Dependabot dependency monitoring
- Protected branches
- Secret isolation
- CI security validation
- Pull Request reviews
- Account and tenant isolation

---

## Internal Security Workflow

For internal contributors:

```txt
Security Finding
        ↓
Private Assessment
        ↓
Mitigation Plan
        ↓
Implementation
        ↓
Review
        ↓
Deploy
```

Security vulnerabilities should not be tracked through public GitHub Issues.

---

## Disclosure Policy

ERP Plus follows a responsible disclosure model.

After investigation and remediation:

- Maintainers may publish a security advisory
- Impacted users may be notified
- Mitigation guidance may be released

Responsible disclosure is appreciated.

---

## Scope

This policy applies to:

- ERP Plus Host Application
- ERP Plus Engines
- ERP Plus Documentation repositories
- Shared organization repositories
