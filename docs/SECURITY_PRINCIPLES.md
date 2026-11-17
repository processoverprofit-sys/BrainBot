# Public security and privacy principles

**Scope:** Intended design objectives for public engineering discussion, not an implementation audit or assurance claim.

BrainBot's public descriptions emphasise local-first operation, controlled access, user control and separation of responsibilities. The following requirements translate those priorities into discussion points. They do not describe private security mechanisms or establish that the application satisfies them.

| ID | Intended requirement |
| --- | --- |
| BP-01 | Access to a local resource should be limited to an approved purpose and necessary authority. |
| BP-02 | An interface request should not independently grant backend authority. |
| BP-03 | Missing, denied or uncertain required permission should not be silently treated as granted. |
| BP-04 | Private information should not be exposed through public documentation or unnecessary user-visible output. |
| BP-05 | Failed or uncertain operations should not be represented as confirmed successes. |
| BP-06 | BrainBot should preserve the independent authorisation boundaries of other projects, including T-Bot. |

These identifiers belong to this public document only. They are not internal requirement identifiers or a published operational policy.

## Preliminary concerns

| Concern | Intended control objective |
| --- | --- |
| Excessive permissions | Limit authority and keep responsibilities distinct. |
| Ambiguous or invalid requests | Validate required conditions before acting. |
| Unnecessary disclosure | Restrict information to its approved purpose and audience. |
| Misleading interface state | Distinguish confirmed results from errors and uncertainty. |
| Cross-project authority confusion | Keep user interaction separate from trading or signing authority. |

This is not an exhaustive threat model. Local-first design alone does not guarantee security or privacy; implementation, dependencies, configuration and operating conditions matter.

## Security reporting

For security concerns about this public repository, follow [SECURITY.md](../SECURITY.md). Do not publish sensitive findings or independently test private systems. This document grants no access or testing permission.

See [illustrative testing](TESTING.md) for proposed ways to express these objectives as testable cases.

[Return to BrainBot](../README.md)
