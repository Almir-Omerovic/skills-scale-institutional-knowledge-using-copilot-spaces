# OctoAcme Project Management Docs

This README is the central entry point for OctoAcme's project management knowledge base. It provides a high-level summary of how OctoAcme plans, executes, and continuously improves its projects, and links directly to all process documents so that new and returning team members can quickly find the guidance they need.

## Project Management Processes Summary

OctoAcme uses a lifecycle-based approach organized around five sequential phases: **Initiation → Planning → Execution → Release → Close/Retrospective**. Work begins with a short project one-pager that captures the problem statement, SMART goals, success metrics, and an initial risk list. This serves as a decision gate to confirm priority, alignment, and team availability before committing resources. Once approved, planning converts the initiative into an actionable backlog with acceptance criteria, a Definition of Done, dependency mapping, and an agreed release plan.

Clear **roles and ownership** keep delivery on track. A **Project Manager (PM)** coordinates timelines, risk management, and communication cadence, while a **Product Manager (PdM)** defines outcomes, owns the backlog, and measures impact. **Developers** implement and test features while collaborating on design and estimates; **QA/Testing** validates quality and acceptance criteria; and **Stakeholders** provide input and approvals. Escalation paths are explicitly defined: issues surface first at team triage, then escalate to the PM/Product Lead or dependent-team leads, and finally to a sponsor for business-impacting decisions.

Day-to-day **execution and tracking** relies on a consistent team rhythm — daily standups, weekly delivery syncs, sprint or milestone demos — and a visible project board with columns: **Backlog → Ready → In Progress → In Review → QA → Done**. Pull requests are kept small (≤ 400 lines when possible), linked to the originating issue and its acceptance criteria, and must pass CI checks (tests and linting) and receive at least one approval before merging. Progress is communicated through weekly status updates using a shared template and delivery dashboards that surface burndown/velocity trends and the success metrics defined in the original one-pager, while a live risk register and dependency log enable continuous monitoring and timely escalation.

**Quality and release readiness** are reinforced throughout delivery. Every change is covered by unit tests, integration tests, and end-to-end smoke tests for critical flows, with security scanning running in CI and manual QA invoked when needed. Releases follow a standardized checklist: acceptance criteria met, CI/security checks green, release notes prepared, rollback/mitigation plan documented; then deploy to staging, validate with smoke tests, deploy to production (automation preferred), verify post-deploy behavior, and announce to stakeholders and support. After each release — and after significant incidents — OctoAcme runs a retrospective (45–75 minutes), selects 2–3 owned action items with due dates and success criteria, and tracks them in the backlog to ensure continuous improvement actually lands.

## Process Docs Index

| Document | Description |
|---|---|
| [Project Management Overview](octoacme-project-management-overview.md) | High-level overview of OctoAcme's project management methodology, phases, and principles |
| [Project Initiation](octoacme-project-initiation.md) | One-pager/charter template, stakeholder mapping, initial risk list, and decision-gate criteria |
| [Project Planning](octoacme-project-planning.md) | Backlog definition, acceptance criteria, Definition of Done, dependency mapping, and milestones |
| [Execution and Tracking](octoacme-execution-and-tracking.md) | Project board workflow, PR standards, team rituals, and progress-reporting cadence |
| [Risks and Communication](octoacme-risks-and-communication.md) | Risk register, escalation paths, communication cadences, status-update template, and incident comms |
| [Release and Deployment](octoacme-release-and-deployment.md) | Release checklist, staging/production deploy process, smoke tests, rollback playbook, and announcements |
| [Retrospective and Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) | Retro format, action-item tracking, and integration with the backlog for follow-through |
| [Roles and Personas](octoacme-roles-and-personas.md) | Detailed responsibilities for PM, PdM, Developers, QA/Testing, and Stakeholders |
