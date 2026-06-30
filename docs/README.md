# OctoAcme Project Management Processes

This guide gives newcomers a quick view of how OctoAcme runs projects across initiation, planning, execution, release, and retrospective improvement.

## Workflow and lifecycle

OctoAcme follows a consistent lifecycle:

1. **Initiation**: validate business need, define success metrics, align stakeholders, and prepare a one-pager with initial risks and role needs.
2. **Planning**: create a prioritized backlog with acceptance criteria, estimate effort, define dependencies, and set release milestones.
3. **Execution & tracking**: deliver in small increments using project board states (Backlog, Ready, In Progress, In Review, QA, Done), regular standups, and sprint or milestone demos.
4. **Release & deployment**: ship with CI/security checks, smoke testing, release notes, and rollback readiness.
5. **Retrospective**: capture lessons learned and convert them into owned, time-bound action items.

## Personas and responsibilities

- **Project Manager (PM)**: coordinates schedules, risks, dependencies, and stakeholder communication.
- **Product Manager (PdM)**: defines outcomes, prioritizes backlog, and tracks success metrics.
- **Developers**: design, implement, test, review, and maintain features.
- **QA/Testing**: validates acceptance criteria and release readiness.
- **Stakeholders/Sponsors**: provide inputs, decisions, and approvals.

## Communication strategy

- Daily standups for delivery visibility and blocker triage.
- Weekly delivery/status syncs for progress, risks, and decisions.
- Milestone-based or regular stakeholder updates from a single source of truth.
- Clear escalation path: Team triage -> PM -> Product Lead -> Sponsor, with dedicated security incident escalation.

## Quality assurance practices

- Definition of Done and explicit acceptance criteria before work is pulled.
- CI linting, automated tests, and security scanning before merge/release.
- Unit, integration, and critical end-to-end smoke testing.
- Manual QA for feature acceptance when needed.
- Post-release verification, rollback planning, and retrospective follow-through.

## Related process documents

- [Project Management Overview](./octoacme-project-management-overview.md)
- [Project Initiation Guide](./octoacme-project-initiation.md)
- [Project Planning](./octoacme-project-planning.md)
- [Execution & Tracking](./octoacme-execution-and-tracking.md)
- [Release & Deployment Guide](./octoacme-release-and-deployment.md)
- [Risk Management & Communication](./octoacme-risks-and-communication.md)
- [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)
- [Roles and Personas](./octoacme-roles-and-personas.md)
