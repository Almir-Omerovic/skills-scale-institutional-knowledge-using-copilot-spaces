# OctoAcme Project Management Overview

## Purpose
Provide a concise, shareable introduction to how OctoAcme runs projects so new teammates can quickly understand our approach, roles, and key artifacts.

## Scope
Applies to all cross-functional projects that deliver product features, services, or integrations.

## Principles
- Customer-first: prioritize customer value and usability.
- Iterative delivery: deliver small, testable increments.
- Clear ownership: each project has a named Project Manager (PM) and Product Lead.
- Data-informed decisions: measure impact and iterate based on evidence.
- Psychological safety: encourage feedback and learning.

## Core Roles
- Project Manager (PM): coordinates delivery, schedules, risk, communications.
- Product Manager (PdM): defines outcomes, prioritizes backlog, and measures success.
- Business Analyst (BA): translates business needs into requirements; facilitates alignment.
- Developers: implement features, collaborate on design and testability.
- UX/UI Designer: designs user interfaces and ensures accessibility and usability.
- DevOps Engineer: builds and maintains CI/CD pipelines, environments, and delivery infrastructure.
- QA/Testing: validate quality and acceptance criteria.
- Technical Writer: creates and maintains documentation for users and the delivery team.
- Stakeholders: provide inputs and approvals.

See [Roles & Personas](octoacme-roles-and-personas.md) for full role definitions, and the [Role Interaction Matrix](octoacme-role-interaction-matrix.md) for a RACI view of ownership across artifacts and ceremonies.

## Key Artifacts
- Project Charter / One-pager
- Roadmap and Release Plan
- Sprint/Iteration Backlog
- Acceptance Criteria & [Definition of Done](octoacme-definition-of-done.md)
- [Role Interaction Matrix](octoacme-role-interaction-matrix.md)
- [Handoff Checklist](octoacme-handoff-checklist.md) (design→dev, dev→QA, QA→release)
- Risk Register
- Retrospective notes and action items

## Lifecycle (high-level)
1. Initiation: problem statement, stakeholders, high-level timeline.
2. Planning: scope, resources, milestones, dependencies.
3. Execution: build, test, review, iterate.
4. Release: deploy, verify, announce.
5. Close & Retrospective: capture learnings and next steps.

## Communication Cadence
- Weekly sync between PM + PdM
- Twice-weekly standups for delivery team (or as agreed)
- Monthly stakeholder updates
- Ad-hoc escalations as needed

## How to use these docs
- Keep the Project Charter updated in the project repo.
- Add process-specific docs into `.copilot/` if you want Copilot Spaces to use them as context.
