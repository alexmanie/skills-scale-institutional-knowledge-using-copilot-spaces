# OctoAcme — Release Readiness Checklist

## Purpose
A reusable checklist to verify that all quality, communication, and operational requirements are met before promoting a release to production. See [Release & Deployment Guide](octoacme-release-and-deployment.md) for full process guidance.

## How to use
1. Open this checklist for each planned release.
2. Complete each section before advancing to the next stage.
3. The PM or Release Owner must sign off before production deployment proceeds.
4. Archive completed checklists (linked from the release PR or release notes) for audit and retrospective reference.

---

## Release Information

| Field | Value |
|-------|-------|
| **Release name / version** | |
| **Release type** | Patch / Minor / Major |
| **Target release date** | YYYY-MM-DD |
| **Release owner** | _(PM or designated Release Lead)_ |
| **Deployment window** | _(e.g., Tuesday 10:00–12:00 UTC)_ |

---

## 1. Code & Quality Gate

- [ ] All planned features / fixes are merged to the release branch
- [ ] All acceptance criteria are verified (QA sign-off obtained)
- [ ] No open P0/P1 bugs assigned to this release
- [ ] CI pipeline passes (build, unit tests, integration tests)
- [ ] Security scanning passes; no critical findings unresolved
- [ ] Code review approvals in place for all merged PRs
- [ ] Definition of Done confirmed for all release items → [DoD Template](octoacme-definition-of-done.md)

## 2. Documentation & Communication

- [ ] Release notes drafted and reviewed
- [ ] Stakeholder communications prepared (release announcement, support notes)
- [ ] Stakeholder comms plan confirms who needs to be notified → [Comms Plan](octoacme-stakeholder-comms-plan.md)
- [ ] Internal runbook / deployment steps documented
- [ ] Known issues section completed in release notes

## 3. Staging Verification

- [ ] Release deployed to staging environment
- [ ] Smoke tests executed on staging and passed
- [ ] Key user flows manually verified on staging
- [ ] Performance baselines checked (no significant regression)
- [ ] Data migration scripts (if any) tested on staging data

## 4. Operational Readiness

- [ ] Rollback plan documented and confirmed with the team
- [ ] On-call rotation confirmed for release window and 24h post-release
- [ ] Monitoring / alerting dashboards reviewed; alert thresholds current
- [ ] Support team briefed on new features and known issues
- [ ] Feature flags configured correctly for production

## 5. Decision Gate — Go / No-Go

| Approver | Role | Decision (Go / No-Go) | Sign-off Date |
|----------|------|-----------------------|---------------|
| | PM | | |
| | Product Manager | | |
| | QA Lead | | |
| | On-call Engineer | | |

> **Rule:** All approvers must confirm **Go** before proceeding to production deployment. Any **No-Go** triggers an immediate review and revised release date.

---

## Post-Release Verification

- [ ] Production deployment completed without errors
- [ ] Post-deploy smoke tests passed in production
- [ ] Key metrics and dashboards showing expected values
- [ ] Release announcement sent to stakeholders
- [ ] Release notes published (changelog, GitHub release, or equivalent)
- [ ] Any post-release incidents logged and triaged

---

## Owner & Accountability
- **Maintained by:** Project Manager (PM) / Release Owner
- **Reviewed:** Each release cycle
- **Roles reference:** See [Roles and Personas](octoacme-roles-and-personas.md)
