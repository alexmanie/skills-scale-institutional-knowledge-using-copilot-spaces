# OctoAcme — Definition of Done (DoD) Template

## Purpose
Provide a shared, reusable checklist that defines when a backlog item or sprint is considered complete. Teams should agree on their DoD at the start of each project or sprint and update it as practices evolve.

## How to use
1. Copy this template into your project planning doc or sprint notes.
2. Adapt the checklist to your project's tech stack and release cadence.
3. Reference this template in your [Project Planning](octoacme-project-planning.md) doc.
4. Review and update after each retrospective.

---

## Definition of Done — Backlog Item

A backlog item is **Done** when all of the following are true:

### Development
- [ ] Code is implemented and reviewed (at least one approval)
- [ ] Acceptance criteria from the backlog item are met
- [ ] No known regressions introduced
- [ ] Code follows team coding standards and passes linting

### Testing
- [ ] Unit tests written and passing for new logic
- [ ] Integration tests updated or added where applicable
- [ ] Manual QA completed for UI or critical flows
- [ ] Security scanning passes in CI

### Documentation
- [ ] Code comments updated where needed
- [ ] Relevant process or API docs updated
- [ ] PR description includes issue link and summary of changes

### Deployment Readiness
- [ ] Feature flag or toggle in place if not immediately releasing
- [ ] Rollback path understood and documented if risky
- [ ] Merged to the target branch; CI pipeline passes

---

## Definition of Done — Sprint / Milestone

A sprint or milestone is **Done** when all of the following are true:

- [ ] All committed backlog items meet the item-level DoD above
- [ ] Sprint demo/review has been held with stakeholders
- [ ] Velocity and metrics recorded for the sprint
- [ ] Risk register reviewed and updated
- [ ] Retrospective notes captured with at least one action item logged
- [ ] Outstanding items moved to next sprint backlog with updated priority

---

## Owner & Accountability
- **Maintained by:** Project Manager (PM) with input from the full delivery team
- **Reviewed:** Each sprint planning and retrospective
- **Roles reference:** See [Roles and Personas](octoacme-roles-and-personas.md) for role definitions
