# OctoAcme — Risk Register Template

## Purpose
A reusable risk register template for capturing, assessing, and tracking project risks. See [Risk Management & Communication](octoacme-risks-and-communication.md) for process guidance.

## How to use
1. Copy the table below into your project risk register (e.g., a GitHub issue, project wiki, or spreadsheet).
2. Populate one row per identified risk.
3. Review and update during weekly delivery syncs.
4. Escalate High-impact / High-likelihood risks immediately to the PM and Product Lead.

---

## Risk Register

| ID | Description | Impact (H/M/L) | Likelihood (H/M/L) | Owner | Mitigation Plan | Status | Last Updated |
|----|-------------|----------------|--------------------|-------|-----------------|--------|--------------|
| R-01 | _(example) Third-party API deprecation_ | H | M | PM | Evaluate alternatives; add abstraction layer | Open | YYYY-MM-DD |
| R-02 | | | | | | | |

---

## Field Definitions

| Field | Description |
|-------|-------------|
| **ID** | Unique identifier (e.g., R-01, R-02) |
| **Description** | Clear summary of the risk event |
| **Impact** | Business/delivery impact if the risk occurs: High / Medium / Low |
| **Likelihood** | Probability the risk will materialize: High / Medium / Low |
| **Owner** | Named person (role or individual) responsible for monitoring and mitigating |
| **Mitigation Plan** | Specific actions to reduce likelihood or impact |
| **Status** | Open / In Progress / Mitigated / Closed |
| **Last Updated** | Date the row was last reviewed |

---

## Risk Lifecycle
1. **Identify** — surface risks during planning and execution
2. **Assess** — assign Impact and Likelihood scores
3. **Mitigate** — define and execute mitigation actions
4. **Monitor** — review at weekly syncs; update status
5. **Close** — mark as Mitigated or Closed when no longer active

## Escalation
- **High / High risks** → escalate immediately to PM and Product Lead
- **Unresolved after two syncs** → escalate to Sponsor
- See [Risk Management & Communication](octoacme-risks-and-communication.md#escalation-paths) for full escalation paths

## Owner & Accountability
- **Maintained by:** Project Manager (PM)
- **Reviewed:** Weekly delivery sync
- **Roles reference:** See [Roles and Personas](octoacme-roles-and-personas.md)
