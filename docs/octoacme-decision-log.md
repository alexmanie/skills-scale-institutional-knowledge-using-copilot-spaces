# OctoAcme — Decision Log Template

## Purpose
Track key project decisions, the context behind them, and who made them. A decision log reduces re-litigation of settled questions and helps onboard teammates who join mid-project.

## How to use
1. Add a row each time the team makes a significant decision (technical, scope, process, or resourcing).
2. Keep the log in the project repo, wiki, or shared doc.
3. Reference in weekly status updates when decisions affect stakeholders.
4. Link from relevant PRs or issues where the decision applies.

---

## Decision Log

| ID | Date | Decision | Context / Rationale | Alternatives Considered | Owner | Status |
|----|------|----------|---------------------|-------------------------|-------|--------|
| D-01 | YYYY-MM-DD | _(example) Use feature flags for all new features_ | Reduces risk on release; allows gradual rollout | Toggle per-PR vs. flags service | PM | Accepted |
| D-02 | | | | | | |

---

## Field Definitions

| Field | Description |
|-------|-------------|
| **ID** | Unique identifier (e.g., D-01, D-02) |
| **Date** | Date the decision was made |
| **Decision** | Concise statement of what was decided |
| **Context / Rationale** | Why this decision was made; data or constraints that drove it |
| **Alternatives Considered** | Other options that were evaluated and why they were not chosen |
| **Owner** | Role or individual who made or owns the decision |
| **Status** | Accepted / Superseded / Under Review |

---

## Guidance
- Log decisions as they happen — not retroactively where avoidable.
- Keep entries brief; link to longer design docs or meeting notes if needed.
- If a decision is superseded, update the Status and add a note referencing the new decision ID.
- Review the log at sprint close and retrospectives to surface any decisions that need revisiting.

## Owner & Accountability
- **Maintained by:** Project Manager (PM) or designated tech lead
- **Reviewed:** Sprint close and retrospectives
- **Roles reference:** See [Roles and Personas](octoacme-roles-and-personas.md)
