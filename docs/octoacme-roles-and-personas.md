# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

## How to Use These Personas

Use these persona definitions to frame scenarios, shape role-specific Copilot Space guidance, and clarify ownership at every stage of the project lifecycle:

| Lifecycle Phase | Key Roles Involved |
|---|---|
| **Initiation** | Product Manager, Project Manager, Business Analyst, Stakeholders |
| **Planning** | Product Manager, Project Manager, Business Analyst, Developers, UX/UI Designer, Technical Writer |
| **Execution** | Developers, UX/UI Designer, DevOps Engineer, QA/Testing, Technical Writer, Business Analyst |
| **Release** | Developers, DevOps Engineer, QA/Testing, Project Manager, Technical Writer |
| **Retrospective** | All roles |

**Accountability tracking:** Each project artifact or ceremony should have a clearly named **Owner** (decision-maker) and **Contributors** (participants). Use the [Role Interaction Matrix](octoacme-role-interaction-matrix.md) for a full RACI view across key artifacts and ceremonies.

See also: [Handoff Checklist](octoacme-handoff-checklist.md) · [Definition of Done](octoacme-definition-of-done.md)

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

## QA/Testing

### Role Summary
QA/Testing engineers validate that features meet acceptance criteria and quality standards before release. They champion quality throughout the delivery cycle, not just at the end.

### Responsibilities
- Develop and execute test plans, test cases, and automated test suites
- Validate acceptance criteria and Definition of Done compliance
- Identify, document, and track defects through resolution
- Perform exploratory, regression, and performance testing
- Participate in sprint planning to assess testability of requirements

### Goals
- Prevent defects from reaching production
- Provide fast, reliable feedback on feature quality
- Continuously improve test coverage and automation

### Typical Communication
- Sprint demos and review sessions
- Defect reports and test summary reports
- Coordination with Developers and DevOps on test environments

### Interactions
- **Developers:** Collaborate on testability, review acceptance criteria, flag defects early in the cycle.
- **Product Managers:** Confirm acceptance criteria are testable; raise concerns about scope or quality trade-offs.
- **Project Managers:** Report test status and defect metrics; flag blockers that affect release readiness.
- **Stakeholders:** Provide test summaries before key releases; surface risks from open defects.
- **DevOps Engineer:** Coordinate on environment provisioning, CI pipeline test gates, and automated test infrastructure.
- **Technical Writer:** Review release notes for accuracy; flag known issues or limitations.

---

## Stakeholders

### Role Summary
Stakeholders include internal and external parties who have an interest in the project outcome — such as business sponsors, customers, compliance teams, or department leads. They provide input, approvals, and feedback at key milestones.

### Responsibilities
- Provide strategic direction and business requirements
- Review and approve key decisions and deliverables (e.g., scope, release readiness)
- Escalate business-critical issues and constraints
- Participate in demos and milestone reviews

### Goals
- Ensure the project delivers the expected business value
- Maintain visibility into progress, risks, and decisions
- Enable timely decisions that unblock the team

### Typical Communication
- Monthly status updates and milestone reviews
- Executive summaries and risk briefings
- Approval requests for scope or timeline changes

### Interactions
- **Product Managers:** Align on product strategy, priorities, and success metrics.
- **Project Managers:** Receive status updates, risk escalations, and decision requests.
- **Developers:** Participate in demos; provide feedback on delivered features.
- **Business Analyst:** Validate requirements and acceptance criteria during discovery and reviews.
- **QA/Testing:** Review test summaries and sign off on release readiness.

---

## UX/UI Designer

### Role Summary
UX/UI Designers create intuitive, accessible, and visually consistent user interfaces. They bridge user research and engineering, ensuring that products are both usable and technically feasible.

### Responsibilities
- Conduct user research, usability testing, and persona development
- Create wireframes, prototypes, and high-fidelity mockups
- Define and maintain design systems and accessibility standards
- Facilitate design reviews and handoffs with engineering
- Iterate on designs based on QA, stakeholder, and user feedback

### Goals
- Deliver user experiences that are intuitive, accessible, and aligned with product goals
- Reduce rework caused by late-stage design changes
- Maintain a consistent visual language across the product

### Typical Communication
- Design reviews and prototype walkthroughs
- Annotated Figma (or equivalent) files shared with developers
- Usability test reports and design decision logs

### Interactions
- **Developers:** Hand off design specifications, answer Q&A during implementation, review built features against designs.
- **Product Managers:** Collaborate on user stories, personas, and acceptance criteria; align design with product vision and priorities.
- **Project Managers:** Communicate design milestones and flag risks from scope changes or late requirements.
- **QA/Testing:** Provide design specs as acceptance references; review usability defects and visual regressions.
- **Stakeholders:** Present design concepts and prototypes; gather feedback and approvals before development begins.
- **Business Analyst:** Collaborate on user research and requirements to ensure designs address real user needs.

---

## DevOps Engineer

### Role Summary
DevOps Engineers build and maintain the delivery infrastructure that enables teams to ship software reliably and efficiently. They own CI/CD pipelines, cloud environments, and observability tooling.

### Responsibilities
- Design, implement, and maintain CI/CD pipelines and build automation
- Provision and manage cloud infrastructure and deployment environments (dev, staging, production)
- Monitor system health, reliability, and security across environments
- Automate repetitive operational tasks to reduce toil
- Participate in incident response and post-mortem reviews
- Champion security and compliance practices in the delivery pipeline

### Goals
- Maximize deployment frequency and minimize lead time to production
- Ensure high system availability and fast incident recovery
- Reduce manual steps and configuration drift across environments

### Typical Communication
- Infrastructure and deployment status updates in project channels
- Incident reports and post-mortem summaries
- Environment readiness notifications ahead of QA and release windows

### Interactions
- **Developers:** Support local development environments, review infrastructure-as-code, unblock deployment issues.
- **Product Managers:** Provide capacity and constraint inputs that affect release planning.
- **Project Managers:** Report environment readiness, deployment risks, and infrastructure blockers.
- **QA/Testing:** Provision and maintain test environments; integrate automated tests into CI pipelines.
- **Stakeholders:** Communicate deployment windows, maintenance events, and reliability metrics.
- **Technical Writer:** Collaborate on runbooks, deployment guides, and incident playbooks.

---

## Technical Writer

### Role Summary
Technical Writers create clear, accurate, and accessible documentation for developers, end users, and operations teams. They ensure that knowledge is captured and easy to find throughout the project lifecycle.

### Responsibilities
- Author and maintain user guides, API references, runbooks, and process documentation
- Interview subject-matter experts (SMEs) to capture and validate technical content
- Ensure documentation is published, versioned, and discoverable
- Review release notes for completeness and clarity
- Identify and close documentation gaps that create support or onboarding burdens

### Goals
- Reduce time-to-productivity for new team members and end users
- Ensure documentation keeps pace with product changes
- Make institutional knowledge durable and searchable

### Typical Communication
- Documentation review cycles tied to sprint and release milestones
- Collaborative editing in shared wikis or repos
- Feedback loops with support and customer-facing teams

### Interactions
- **Developers:** Interview for technical accuracy; review code comments, READMEs, and API docs.
- **Product Managers:** Align documentation scope with feature releases; confirm user-facing messaging.
- **Project Managers:** Align documentation milestones with release timelines; flag documentation debt.
- **QA/Testing:** Verify accuracy of documented procedures and known issues in release notes.
- **Stakeholders:** Gather requirements for external-facing content; ensure compliance documentation is complete.
- **DevOps Engineer:** Document deployment procedures, runbooks, and environment setup guides.

---

## Business Analyst

### Role Summary
Business Analysts translate business needs into actionable requirements, bridging the gap between stakeholders and delivery teams. They facilitate alignment, reduce ambiguity, and support decision-making throughout the project.

### Responsibilities
- Elicit, analyze, and document business requirements and user stories
- Define use cases, process flows, and acceptance criteria
- Facilitate stakeholder interviews and requirements workshops
- Identify scope gaps, conflicts, and risks in proposed solutions
- Support change management by documenting impacts and transition plans

### Goals
- Ensure requirements are clear, complete, and agreed upon before development begins
- Reduce rework caused by misunderstood or missing requirements
- Improve alignment between business objectives and delivered solutions

### Typical Communication
- Requirements workshops and stakeholder interviews
- Business requirements documents (BRDs) and user story maps
- Acceptance criteria reviews during sprint planning and backlog refinement

### Interactions
- **Product Managers:** Collaborate on roadmap prioritization, problem framing, and success metrics.
- **Developers:** Clarify requirements and acceptance criteria during refinement; validate technical feasibility.
- **Project Managers:** Provide requirements timeline estimates; flag dependency or scope risks.
- **QA/Testing:** Review acceptance criteria to ensure testability; participate in UAT planning.
- **Stakeholders:** Facilitate requirements elicitation; validate proposed solutions align with business goals.
- **UX/UI Designer:** Share user research and process flows to inform design decisions.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Refer to the [Role Interaction Matrix](octoacme-role-interaction-matrix.md) to see how roles collaborate on key artifacts and ceremonies.

