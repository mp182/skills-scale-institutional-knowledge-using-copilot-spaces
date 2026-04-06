# Release Readiness Checklist

Use this checklist before every release to confirm that the team is ready to deploy safely. The **Release Manager** owns this checklist and runs the go/no-go meeting with the **Project Manager**, **QA Lead**, and **DevOps**.

---

## Code & Quality Gates

- [ ] All planned features and fixes for this release are merged
- [ ] CI pipeline is passing (build, lint, unit tests, integration tests)
- [ ] Security scans are passing with no new critical or high vulnerabilities
- [ ] Code coverage meets the project's minimum threshold
- [ ] All open blocking defects are resolved or deferred with documented justification
- [ ] Regression test suite has been executed and results reviewed

## Acceptance & Sign-off

- [ ] All acceptance criteria for included stories are verified by QA
- [ ] UAT (User Acceptance Testing) completed and signed off (if applicable)
- [ ] Product Manager has reviewed and approved the release scope
- [ ] Stakeholder sign-off received for any externally visible changes (if required)

## Documentation & Communication

- [ ] Release notes drafted and reviewed (see [Release & Deployment](../octoacme-release-and-deployment.md))
- [ ] Any migration steps, configuration changes, or breaking changes are documented
- [ ] Customer-facing documentation updated (if applicable)
- [ ] Internal runbooks updated to reflect changes
- [ ] Stakeholder announcement drafted and scheduled

## Deployment Preparation

- [ ] Deployment window confirmed and communicated to the team
- [ ] Deployment pipeline tested in staging environment
- [ ] Smoke tests prepared and assigned to an owner for post-deploy verification
- [ ] Rollback plan documented and validated
- [ ] On-call coverage confirmed for the deployment window
- [ ] Feature flags or incremental rollout strategy configured (if applicable)

## Go/No-Go Decision

| Criterion | Status | Notes |
|---|---|---|
| Quality gates passed | | |
| Acceptance criteria verified | | |
| Release notes approved | | |
| Rollback plan confirmed | | |
| Deployment window confirmed | | |

**Go/No-Go Decision:** ☐ Go &nbsp;&nbsp; ☐ No-Go  
**Decision made by (Release Manager):** _______________  
**Date:** _______________

---

**Owner:** Release Manager  
**Reviewers:** Project Manager, QA Lead, DevOps  
**Reference:** [Roles & Personas](../octoacme-roles-and-personas.md) | [Release & Deployment](../octoacme-release-and-deployment.md)
