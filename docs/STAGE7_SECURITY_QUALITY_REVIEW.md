# Stage 7 — Security and publication quality checklist

**Status:** Public documentation proposal for review, not an independent application audit.

## Verified public repository baseline (17 November 2026)

- The active `main` ruleset prevents deletion and force pushes; it does not require PR review or passing checks.
- Issues and Discussions are disabled; existing issue templates are not an open support route.
- Public documentation describes a historical PC 3.5.0–3.5.3 frozen development line, **not** a production-ready or distributed application.
- The public testing cases are fictional and unexecuted; no actual pass/fail evidence is published.
- `SECURITY.md` describes private vulnerability reporting, but the live GitHub setting requires independent verification.

## Publication safeguards

- Keep application code, privileged integration details, credentials, personal identity, internal paths and private test evidence outside this repository.
- Distinguish interface responsibilities from backend authority; do not imply BrainBot grants T-Bot trading or signing permissions.
- Avoid screenshots showing usernames, local file paths, machine identifiers, access tokens or private content.
- Describe unverified permissions, failure handling and access controls as design objectives, not completed assurance.
- Review Markdown links, headings and mobile readability before publication.
- Use pull requests and verify public commit identity; do not bypass owner approval for merges.

## Owner-only security checks — separate approval required

| Item | Review question | Status |
| --- | --- | --- |
| Main branch | Can mandatory PRs be enforced without blocking the sole maintainer? | Not configured |
| Vulnerability reporting | Does GitHub's live private-reporting feature match SECURITY.md? | Not independently verified |
| Secret scanning | Are scanning and push protection available and enabled? | Not independently verified |
| Access | Are repository apps, collaborators and token permissions least-privilege? | Not reviewed |
| Documentation checks | Can a read-only, no-secrets Markdown/link workflow be safely designed? | Proposal only |
| Community | Is there a controlled, verified joining route that does not expose private infrastructure? | Direct route pending |

## Future public evidence

Only independently reviewed, disclosure-approved, non-sensitive evidence may be presented as actual testing. Include test scope, expected versus observed outcome, date, provenance, limitations and explicit unknowns. A historical version milestone is not itself proof of testing or certification.

## Boundary

This file does not change settings, install or run software, grant contributor access, publish an invite, authorise trading or alter any private system.
