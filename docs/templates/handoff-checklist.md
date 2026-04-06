# Handoff Checklist

Use this checklist to ensure clean handoffs between project phases and between roles. Incomplete handoffs are a common source of defects, delays, and miscommunication. The **outgoing owner** completes this checklist; the **incoming owner** reviews and confirms receipt.

---

## Requirements → Development Handoff
_From: Business Analyst → To: Development Team_

- [ ] All user stories have documented acceptance criteria
- [ ] Stories meet the team's Definition of Ready
- [ ] Design mockups or wireframes linked (if applicable)
- [ ] Technical constraints or dependencies noted in each story
- [ ] BA available for clarification questions during the sprint
- [ ] QA Lead has reviewed acceptance criteria for testability
- [ ] Stories are in the sprint backlog with estimates

**Handoff confirmed by (BA):** _______________ &nbsp; **Date:** _______________  
**Received by (Dev Lead):** _______________ &nbsp; **Date:** _______________

---

## Development → QA Handoff
_From: Development Team → To: QA Lead_

- [ ] Feature is deployed to the QA/staging environment
- [ ] Unit and integration tests are passing in CI
- [ ] PR is merged and build is stable
- [ ] Developer has completed a basic smoke test of the feature
- [ ] Known issues or edge cases noted for QA awareness
- [ ] Test data or setup instructions provided (if needed)
- [ ] Acceptance criteria confirmed as implemented

**Handoff confirmed by (Dev Lead):** _______________ &nbsp; **Date:** _______________  
**Received by (QA Lead):** _______________ &nbsp; **Date:** _______________

---

## QA → Release Manager Handoff
_From: QA Lead → To: Release Manager_

- [ ] All test cases executed and results documented
- [ ] All blocking defects resolved or deferred with justification
- [ ] Exit criteria from the QA/Test Plan are met
- [ ] QA sign-off provided in the release readiness checklist
- [ ] Known issues (if any) documented with severity and business impact
- [ ] Release notes reviewed for accuracy by QA

**Handoff confirmed by (QA Lead):** _______________ &nbsp; **Date:** _______________  
**Received by (Release Manager):** _______________ &nbsp; **Date:** _______________

---

## Release → Stakeholder Handoff
_From: Release Manager → To: Project Stakeholder / Business_

- [ ] Deployment completed successfully
- [ ] Post-deploy smoke tests passed
- [ ] Release notes published and distributed
- [ ] Stakeholder announcement sent
- [ ] Support team briefed (if applicable)
- [ ] Monitoring dashboards reviewed; no critical alerts
- [ ] Project Manager notified of successful release

**Handoff confirmed by (Release Manager):** _______________ &nbsp; **Date:** _______________  
**Received by (Stakeholder / PM):** _______________ &nbsp; **Date:** _______________

---

**Reference:** [Roles & Personas](../octoacme-roles-and-personas.md) | [Release Readiness Checklist](release-readiness-checklist.md) | [QA Test Plan](qa-test-plan-template.md)
