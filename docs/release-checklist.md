# Release Checklist (Staging → Production)

Purpose: Lightweight checklist to ensure consistent, safe releases.

- [ ] All PRs for the release merged and linked to release notes
- [ ] CI passed for merged commits (unit, integration, security scans)
- [ ] Smoke tests defined and scheduled for staging
- [ ] Rollback plan documented and tested (if applicable)
- [ ] Post-deploy verification steps defined (health checks, smoke tests)
- [ ] SRE/On-call notified for the window and on-call contact provided
- [ ] Release notes drafted and stakeholder communication plan ready
- [ ] Feature flags / toggles documented and set appropriately
- [ ] Monitoring dashboards and alerts validated
- [ ] Post-release retrospective owner assigned (if needed)

Notes:
- If an automated pipeline is used, ensure the pipeline run ID is recorded in the release notes.
- For hotfix/patch releases, ensure emergency contacts and fast rollback steps are highly visible.
