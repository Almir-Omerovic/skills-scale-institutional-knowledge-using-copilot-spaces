# OctoAcme — Handoff Checklist

This checklist reduces ambiguity and rework at the critical transition points in the delivery cycle. Complete all items before handing off to the next role or phase. Incomplete items must be documented with a rationale and agreed risk acceptance.

---

## Design → Development Handoff

**Owner:** UX/UI Designer  
**Recipient:** Developers  
**When:** Before a feature enters the sprint backlog for implementation.

### Designer Checklist
- [ ] Final mockups and prototypes are published and linked in the story/ticket
- [ ] All interactive states (hover, error, empty, loading) are included
- [ ] Accessibility requirements (WCAG level, color contrast, keyboard navigation) are noted
- [ ] Design system components used are identified (or new components flagged for creation)
- [ ] Design assets (icons, images) are exported and available in the agreed format
- [ ] Open design questions or known constraints are documented in the ticket

### Developer Confirmation
- [ ] Mockups reviewed and understood before work begins
- [ ] Ambiguous design decisions raised with Designer and resolved
- [ ] Any technical constraints that affect design communicated back to Designer

---

## Development → QA Handoff

**Owner:** Developer  
**Recipient:** QA/Testing  
**When:** Before a feature is moved to the QA column on the project board.

### Developer Checklist
- [ ] Feature branch merged to the target branch and deployed to the test environment
- [ ] All acceptance criteria from the story/ticket are met
- [ ] Unit and integration tests written and passing in CI
- [ ] Known limitations or edge cases documented in the ticket
- [ ] Any environment-specific setup or test data requirements communicated to QA
- [ ] PR description updated with a summary of changes and testing notes

### QA/Testing Confirmation
- [ ] Test environment is accessible and stable
- [ ] Test plan or test cases reviewed against acceptance criteria
- [ ] Regression impact assessed and covered

---

## QA → Release Handoff

**Owner:** QA/Testing  
**Recipient:** Project Manager / DevOps Engineer  
**When:** Before a release is approved to proceed to production.

### QA Checklist
- [ ] All acceptance criteria verified and test cases passed
- [ ] Defects triaged: critical/high issues resolved; remaining defects documented and risk-accepted
- [ ] Regression test suite run and results recorded
- [ ] Performance and security test results reviewed (if applicable)
- [ ] Test summary report completed and shared with Project Manager and Stakeholders

### Project Manager Checklist
- [ ] Release notes drafted and reviewed by Technical Writer
- [ ] Rollback plan documented and communicated to DevOps Engineer
- [ ] Deployment window communicated to stakeholders
- [ ] Go/no-go decision recorded with named approver

### DevOps Engineer Checklist
- [ ] Staging deployment verified with smoke tests
- [ ] Production deployment pipeline reviewed and ready
- [ ] Monitoring and alerting configured for the new release
- [ ] Post-deploy verification plan confirmed

---

## Related Documents
- [Role Interaction Matrix](octoacme-role-interaction-matrix.md)
- [Definition of Done](octoacme-definition-of-done.md)
- [Release & Deployment Guide](octoacme-release-and-deployment.md)
- [Execution & Tracking](octoacme-execution-and-tracking.md)
