# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

---

## Developers

### Role Summary
Developers design, build, test, and deliver software components. They collaborate with product and project leads to implement features that meet acceptance criteria and quality standards.

### Responsibilities
- Implement features and fixes to meet acceptance criteria
- Write and maintain tests and documentation
- Participate in design and code reviews
- Assist in estimating and planning work
- Help identify technical risks and propose mitigations

### Goals
- Deliver reliable, maintainable code
- Reduce cycle time from idea to production
- Maintain high test coverage and observability

### Typical Communication
- Daily standups and sprint planning
- PR descriptions and code review comments
- Technical design docs when needed

---

## Product Managers

### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics

### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

### Typical Communication
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs

---

## Project Managers

### Role Summary
Project Managers coordinate delivery activities, manage schedules, risks, and communications. They enable the team to deliver on commitments efficiently.

### Responsibilities
- Create and maintain project plans and timelines
- Manage risks, dependencies, and resource constraints
- Facilitate meetings (kickoff, planning, retrospectives)
- Ensure consistent project documentation and status reporting
- Coordinate cross-team and stakeholder communication

### Goals
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders

### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation

---

## QA / Testing

### Role Summary
QA engineers validate that features meet acceptance criteria and quality standards before release. They advocate for quality throughout the delivery lifecycle, not just at the end.

### Responsibilities
- Define and execute test plans (unit, integration, end-to-end, regression)
- Review acceptance criteria in backlog items and flag ambiguities early
- Perform manual QA for feature acceptance when automated coverage is insufficient
- Maintain test environments and test data
- Sign off on release readiness from a quality perspective

### Goals
- Prevent defects from reaching production
- Ensure every release meets the Definition of Done
- Improve test automation coverage over time

### Typical Communication
- Sprint planning: review acceptance criteria and flag testability gaps
- Daily standups: report test status and blockers
- Pre-release: provide sign-off in the [Release Readiness Checklist](octoacme-release-readiness-checklist.md)

---

## Stakeholders

### Role Summary
Stakeholders are individuals or groups with an interest in the project outcome. They provide business requirements, approvals, and feedback throughout the project lifecycle.

### Responsibilities
- Articulate business needs and success metrics during initiation
- Review and approve the Project One-pager and major scope changes
- Participate in sprint reviews and provide timely feedback
- Make decisions when trade-offs between scope, quality, and timeline arise
- Accept (or reject) deliverables against agreed acceptance criteria

### Goals
- Ensure the project delivers the expected business value
- Stay informed of progress, risks, and key decisions
- Enable the team by providing timely inputs and removing external blockers

### Typical Communication
- Monthly stakeholder updates from the PM
- Ad-hoc notifications for High risks or milestone slips (see [Comms Plan](octoacme-stakeholder-comms-plan.md))
- Sprint review / demo attendance

---

## Release Manager

### Role Summary
Release Managers coordinate all release activities end-to-end. They ensure compliance with release checklists, prepare rollback and communication plans, and act as the central liaison between product, engineering, support, and operations for each release.

### Responsibilities
- Own the release calendar and deployment windows
- Drive completion of the [Release Readiness Checklist](octoacme-release-readiness-checklist.md)
- Coordinate go/no-go decisions with PM, PdM, QA, and on-call engineers
- Prepare and distribute release notes and stakeholder announcements
- Manage rollback plans and trigger incident response if a release causes production issues
- Track post-release metrics and feed findings into the retrospective

### Goals
- Deliver releases on schedule with minimal production risk
- Ensure all pre-release quality and operational gates are met
- Maintain clear communication with all stakeholders throughout the release process

### Typical Communication
- Pre-release: go/no-go sync with PM, PdM, and QA
- Release day: status updates to stakeholders and support team
- Post-release: release retrospective notes and action items via [Retro Action-Item Tracker](octoacme-retro-action-items.md)

---

## UX Designer / Researcher

### Role Summary
UX Designers and Researchers own the user experience of the product. They define usability acceptance criteria, conduct user research, and surface insights that inform product decisions and prioritization.

### Responsibilities
- Define UX goals and usability acceptance criteria for features
- Conduct user research, usability testing, and synthesis of findings
- Collaborate with Product Manager and Developers on implementation feasibility and design trade-offs
- Create wireframes, prototypes, and design specs
- Review implemented features against UX acceptance criteria before sign-off
- Surface user feedback and research insights to the team during planning

### Goals
- Ensure the product is intuitive, accessible, and meets user needs
- Reduce rework caused by usability issues discovered late in delivery
- Build a shared understanding of user needs across the team

### Typical Communication
- Sprint planning: share UX requirements and flag feasibility concerns with Developers
- Design reviews: present prototypes and gather feedback from PM and Developers
- Retrospectives: report on usability issues found in testing or production

---

## Support Lead

### Role Summary
The Support Lead represents the voice of support and the customer throughout the project lifecycle. They ensure the team understands real-world customer issues, and that support teams are ready for each release.

### Responsibilities
- Communicate customer pain points, support ticket trends, and escalated issues to the PM and PdM
- Participate in sprint reviews and release planning to assess customer impact
- Ensure support documentation, FAQs, and runbooks are updated before each release
- Brief the support team on new features, known issues, and rollback triggers
- Participate in incident reviews and retrospectives to surface recurring issues
- Provide customer insights that influence backlog prioritization

### Goals
- Minimize support ticket volume caused by product gaps or unclear UX
- Ensure support teams are always ready and informed at release time
- Translate customer feedback into actionable improvements for the product backlog

### Typical Communication
- Pre-release: review release notes and brief support team (coordinated via [Comms Plan](octoacme-stakeholder-comms-plan.md))
- Incident response: represent customer impact during triage
- Retrospectives: share support metrics and recurring customer issues

---

## Security & Compliance Officer

### Role Summary
The Security & Compliance Officer ensures that features and processes meet security standards and regulatory requirements. They work with Developers and PMs to identify and remediate risks before they reach production.

### Responsibilities
- Assess features and architectural changes for security risks and compliance implications
- Define and enforce data handling, privacy, and security requirements
- Review release plans for compliance gates (e.g., regulatory approvals, security sign-off)
- Work with Developers to address security findings from CI scanning and code reviews
- Maintain the security section of the [Risk Register](octoacme-risk-register-template.md)
- Respond to and document security incidents

### Goals
- Prevent security vulnerabilities and compliance violations from reaching production
- Embed security and compliance thinking early in the delivery lifecycle ("shift left")
- Ensure the team can move fast without creating unacceptable risk

### Typical Communication
- Sprint planning: flag security requirements and constraints for planned features
- Pre-release: provide security sign-off in the [Release Readiness Checklist](octoacme-release-readiness-checklist.md)
- Incident response: lead or support security incident triage and remediation

---

## DevOps / Automation Engineer

### Role Summary
DevOps / Automation Engineers enable fast, reliable, and observable software delivery. They own CI/CD pipelines, infrastructure automation, and observability tooling, and work closely with Developers and QA to improve delivery speed and reliability.

### Responsibilities
- Design, build, and maintain CI/CD pipelines and deployment automation
- Manage infrastructure-as-code and environment provisioning
- Implement and maintain observability tooling (dashboards, alerting, logging)
- Work with Developers and QA to ensure automated tests are integrated into the pipeline
- Support release deployments and on-call rotation for production incidents
- Identify and eliminate manual toil through automation

### Goals
- Reduce time from code merge to production deployment
- Increase deployment reliability and rollback speed
- Provide the team with fast feedback loops and high system observability

### Typical Communication
- Sprint planning: surface infrastructure dependencies and capacity constraints
- Release coordination: support the Release Manager during deployments
- Incident response: own infrastructure-level triage and recovery steps

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

