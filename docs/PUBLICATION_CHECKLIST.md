# Public documentation publication checklist

This checklist applies to public documentation only. It does not authorise private application execution, access to local resources, settings changes or release of private evidence.

## Before opening a pull request

- [ ] Verify the exact documentation scope and approval to share it.
- [ ] Exclude private code, credentials, wallet details, signing data, privileged integration details, internal paths, logs, personal identifiers and private evidence.
- [ ] Review screenshots and attachments for visible identifiers and metadata; include only separately approved assets.
- [ ] Distinguish design objectives, historical milestones, fictional examples and actual observed results.
- [ ] Confirm publication rights and preserve the [rights notice](../LICENSE-NOTICE.md).
- [ ] Check links, headings, readability and consistency with the project status.
- [ ] Use [SECURITY.md](../SECURITY.md) for confidential concerns; never include vulnerabilities in public PRs.
- [ ] Verify public author and committer identity, changed-file list and target branch.

## Before and after publication

- [ ] Obtain explicit maintainer approval of the exact candidate before merging.
- [ ] Preserve branch rules, private source restrictions and existing settings.
- [ ] After an authorised merge, verify the published files and protections.
- [ ] If a sensitive disclosure is suspected, stop publication; do not reproduce it publicly.

This checklist is not proof of application security or readiness. See the [Stage 7 review record](STAGE7_SECURITY_QUALITY_REVIEW.md) and [blank evidence report template](EVIDENCE_REPORT_TEMPLATE.md).

[Return to BrainBot](../README.md)
