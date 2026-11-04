# OctoAcme Project Management Docs

This folder contains OctoAcme's project management processes, roles, and working guidance. Use this README as an entry point to understand the lifecycle and find the detailed process documents.

## Process overview

OctoAcme manages work through initiation, planning, execution, release, and retrospective. Initiation validates the business need, identifies stakeholders and success measures, and produces a project one-pager, an initial timeline, and a risk list. After alignment and confirmation of team availability, planning turns the approved initiative into prioritized, estimated work with acceptance criteria, a Definition of Done, identified dependencies, and agreed milestones.

During execution, teams deliver small increments and track progress on a project board. Developers implement and test the work; Product Managers define outcomes and priorities; Project Managers coordinate schedules, risks, dependencies, and communication; QA/Testing validates quality and acceptance criteria; and stakeholders provide input and approvals. Regular standups, delivery syncs, demos, and visible status updates keep teams aligned. Blockers escalate from team-level triage through the PM and Product Lead, with sponsor-level escalation for business-impacting issues.

Quality is integrated into development and release. Pull requests should be small where practical, reference issues and acceptance criteria, and pass automated tests and linting before review. Teams use unit and applicable integration tests, smoke tests for critical flows, CI security scanning, and manual QA when needed. Before release, acceptance criteria and checks must pass, with release notes, smoke tests, and a rollback or mitigation plan prepared. Retrospectives after sprints, releases, milestones, or incidents turn lessons into owned, time-bound improvement actions.

## Documentation index

The links below are relative to this README. Add new documents in this list as the `docs/` collection grows.

- [Project Management Overview](octoacme-project-management-overview.md) — principles, lifecycle, roles, artifacts, and communication cadence.
- [Project Initiation](octoacme-project-initiation.md) — validate and authorize new work and prepare the initial project one-pager.
- [Project Planning](octoacme-project-planning.md) — scope, backlog, estimates, Definition of Done, risks, dependencies, and milestones.
- [Execution and Tracking](octoacme-execution-and-tracking.md) — team rhythm, project board, PR workflow, quality practices, reporting, and blocker escalation.
- [Risk Management and Communication](octoacme-risks-and-communication.md) — risk lifecycle, stakeholder updates, communication templates, and escalation paths.
- [Release and Deployment](octoacme-release-and-deployment.md) — release readiness, deployment checklist, rollback guidance, and release notes.
- [Retrospective and Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) — run retrospectives and track measurable improvement actions.
- [Roles and Personas](octoacme-roles-and-personas.md) — responsibilities, goals, and communication patterns for project roles.
