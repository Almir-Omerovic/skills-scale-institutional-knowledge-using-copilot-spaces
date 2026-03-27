# OctoAcme — Definition of Done

The Definition of Done (DoD) is a shared, team-agreed checklist that a work item must satisfy before it is considered complete. Referencing a common DoD reduces ambiguity, improves quality consistency, and aligns the team on what "done" means.

This DoD applies to all feature stories and bug fixes unless explicitly scoped differently in the sprint plan.

---

## Code & Implementation
- [ ] Code implemented and peer-reviewed (at least one approval)
- [ ] All acceptance criteria in the story/ticket met
- [ ] No new compiler warnings or linting errors introduced
- [ ] Technical debt introduced is documented in the backlog

## Testing
- [ ] Unit tests written for new logic (target: existing coverage maintained or improved)
- [ ] Integration tests updated where applicable
- [ ] All tests passing in CI on the target branch
- [ ] Manual QA completed (see [Handoff Checklist: Dev → QA](octoacme-handoff-checklist.md#development--qa-handoff))
- [ ] No open critical or high-severity defects (or risk-accepted with documented rationale)

## Security & Compliance
- [ ] Security scan run in CI with no new critical/high findings
- [ ] Sensitive data (secrets, PII) not exposed in code or logs
- [ ] Compliance requirements reviewed if the feature affects regulated data or flows

## Design & Accessibility
- [ ] Implemented UI matches approved design specifications
- [ ] Accessibility requirements met (see Design → Development Handoff in [Handoff Checklist](octoacme-handoff-checklist.md))

## Documentation
- [ ] Code comments and inline documentation updated
- [ ] User-facing documentation updated or tickets created (owner: Technical Writer)
- [ ] API documentation updated if public interfaces changed
- [ ] Release notes entry drafted

## Deployment & Observability
- [ ] Feature deployable via the standard CI/CD pipeline (no manual steps required)
- [ ] Feature flags or rollback mechanisms in place if the change is high-risk
- [ ] Monitoring/alerting updated to cover the new functionality

## Process
- [ ] Story/ticket updated with final status, linked PR, and any follow-up items
- [ ] Stakeholders and Product Manager notified of completion (if required)
- [ ] All items on the [Handoff Checklist](octoacme-handoff-checklist.md) completed before the story moves to Done

---

## Adjusting the DoD
Teams may tighten (but not loosen) this DoD for a specific sprint or project. Any adjustment must be agreed in sprint planning, documented in the sprint notes, and reviewed in the retrospective.

---

## Related Documents
- [Handoff Checklist](octoacme-handoff-checklist.md)
- [Role Interaction Matrix](octoacme-role-interaction-matrix.md)
- [Project Planning](octoacme-project-planning.md)
- [Execution & Tracking](octoacme-execution-and-tracking.md)
