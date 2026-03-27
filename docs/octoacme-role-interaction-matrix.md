# OctoAcme — Role Interaction Matrix

This matrix provides a RACI-like view of how each role contributes to key artifacts and ceremonies across the project lifecycle. Use it to clarify ownership, reduce handoff ambiguity, and ensure accountability.

**Legend**

| Symbol | Meaning |
|---|---|
| **R** | Responsible — does the work |
| **A** | Accountable — final decision-maker / sign-off |
| **C** | Consulted — provides input before decisions |
| **I** | Informed — kept up to date |

---

## Artifacts

| Artifact | Project Manager | Product Manager | Business Analyst | Developer | UX/UI Designer | DevOps Engineer | QA/Testing | Technical Writer | Stakeholders |
|---|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| Project Charter / One-pager | A | R | C | I | I | I | I | I | C |
| Roadmap & Release Plan | C | A | C | C | C | C | C | I | I |
| Sprint Backlog | R | A | C | C | C | I | C | I | I |
| User Stories & Acceptance Criteria | C | A | R | C | C | I | C | I | C |
| Wireframes & Design Specs | I | C | C | C | R/A | I | C | I | I |
| Technical Design Docs | I | I | C | R/A | C | C | C | I | I |
| CI/CD Pipeline & Environments | I | I | I | C | I | R/A | C | I | I |
| Test Plan | C | C | C | C | C | C | R/A | I | I |
| Release Notes | C | C | I | C | I | C | C | R/A | I |
| API & User Documentation | I | C | I | C | I | I | C | R/A | I |
| Risk Register | R/A | C | C | C | I | C | C | I | I |
| Retrospective Notes | R | C | C | C | C | C | C | I | I |

---

## Ceremonies

| Ceremony | Project Manager | Product Manager | Business Analyst | Developer | UX/UI Designer | DevOps Engineer | QA/Testing | Technical Writer | Stakeholders |
|---|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| Project Kickoff | R/A | R | R | C | C | C | C | C | C |
| Sprint Planning | A | R | C | R | C | I | C | I | I |
| Daily Standup | A | I | I | R | R | R | R | I | I |
| Backlog Refinement | C | A | R | R | C | I | C | I | I |
| Design Review | I | C | C | C | R/A | I | C | I | I |
| Sprint Demo / Review | R | A | C | R | R | C | R | C | C |
| QA Sign-off | C | C | I | C | I | C | R/A | I | I |
| Release Readiness Review | A | C | I | C | I | C | C | I | C |
| Stakeholder Briefing | R/A | R | C | I | I | I | I | I | C |
| Retrospective | R/A | C | C | C | C | C | C | I | I |

---

## Related Documents
- [Roles & Personas](octoacme-roles-and-personas.md)
- [Handoff Checklist](octoacme-handoff-checklist.md)
- [Definition of Done](octoacme-definition-of-done.md)
- [Project Planning](octoacme-project-planning.md)
- [Execution & Tracking](octoacme-execution-and-tracking.md)
