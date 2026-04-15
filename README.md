# .github — Organization Infrastructure

This repository contains shared configuration, policies, and community health files for the organization.

## Purpose

The `.github` repository acts as a centralized layer for:
- Contribution standards
- Issue and pull request templates
- Security policies
- Support guidelines
- Organization-wide defaults

These files are automatically applied to all repositories that do not define their own equivalents.

## Included Resources

### Community Health Files
- `CONTRIBUTING.md` — Contribution guidelines
- `CODE_OF_CONDUCT.md` — Community standards
- `SECURITY.md` — Vulnerability reporting policy
- `SUPPORT.md` — Support and communication channels

### Templates
- Issue templates
- Pull request templates
- Discussion templates (if enabled)

### Automation (optional)
- Shared GitHub Actions workflows
- Reusable CI/CD components

## Design Principles

This repository follows:
- Consistency across projects
- Minimal duplication
- Clear contribution pathways
- Security-first approach
- Transparency by default

## Scope

This repository does NOT contain product code.

All product-related development happens in dedicated repositories such as:
- `pai-kernel`


## Notes

If a repository defines its own version of any file (e.g., `CONTRIBUTING.md`), it overrides the default provided here.

---

For organization overview, see:  
👉 `/profile/README.md`
