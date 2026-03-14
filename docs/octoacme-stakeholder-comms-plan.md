# OctoAcme — Stakeholder Communications Plan Template

## Purpose
Ensure all stakeholders receive the right information at the right cadence throughout the project lifecycle. See [Risk Management & Communication](octoacme-risks-and-communication.md) for communication strategy guidance.

## How to use
1. Complete this plan during the Initiation or Planning phase.
2. Confirm with stakeholders that the cadence and channels meet their needs.
3. Review and update at each phase transition and after major changes in scope or team.
4. Store alongside the Project One-pager in the project repo.

---

## Stakeholder Register & Communication Plan

| Stakeholder / Group | Role / Interest | Communication Need | Frequency | Channel | Owner | Notes |
|---------------------|-----------------|-------------------|-----------|---------|-------|-------|
| _(e.g.) Executive Sponsor_ | Decision-maker, budget approval | High-level status, risks, go/no-go | Monthly | Email summary | PM | Escalate blockers immediately |
| _(e.g.) Engineering Team_ | Delivery | Sprint goals, blockers, technical decisions | Daily / Sprint | Standup, Slack, PR comments | PM / Lead Dev | |
| _(e.g.) Sales / GTM_ | Launch readiness | Feature availability, release dates | Bi-weekly | Roadmap update email | PdM | |
| _(e.g.) Support Team_ | Customer impact | Known issues, release notes, rollback triggers | Per release | Release notes, Slack | PM | |
| _(e.g.) End Users / Customers_ | Value delivery | Feature announcements, change notices | Per release | In-app / email | PdM | Coordinate with Marketing |

---

## Field Definitions

| Field | Description |
|-------|-------------|
| **Stakeholder / Group** | Name or team receiving communications |
| **Role / Interest** | Why they are involved; what they care about |
| **Communication Need** | What information they require |
| **Frequency** | How often they need updates |
| **Channel** | Medium for communication (email, Slack, meeting, etc.) |
| **Owner** | Who is responsible for sending the communication |
| **Notes** | Escalation triggers, preferences, or constraints |

---

## Status Update Template (Weekly)

Use this template for regular status emails or posts:

```
Subject: [Project Name] Status Update — Week of YYYY-MM-DD

## Summary
_(One sentence on overall health: Green / Yellow / Red)_

## Progress This Week
- _(Key accomplishments)_

## Next Steps
- _(What the team will work on next)_

## Risks & Blockers
- _(Active risks; ask for decisions or help if needed)_

## Asks / Decisions Needed
- _(Any pending approvals or inputs required from stakeholders)_
```

---

## Escalation Triggers
Immediately notify relevant stakeholders (outside of the regular cadence) when:
- A risk moves to High / High status
- A milestone is projected to slip by more than one sprint
- A production incident affects customers
- A scope change impacts agreed delivery commitments

See [Escalation Paths](octoacme-risks-and-communication.md#escalation-paths) for the full path.

## Owner & Accountability
- **Maintained by:** Project Manager (PM)
- **Reviewed:** Phase transitions and major scope changes
- **Roles reference:** See [Roles and Personas](octoacme-roles-and-personas.md)
