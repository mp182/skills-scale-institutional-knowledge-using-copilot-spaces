# QA / Test Plan Template

Use this template to document the test strategy and plan for a project or feature. The **QA Lead** owns this document and should complete it during the Planning phase in collaboration with the **Business Analyst** and **Developers**.

---

## Project / Feature Information

| Field | Value |
|---|---|
| Project / Feature name | |
| Version / Sprint | |
| QA Lead | |
| Date | |
| Status | Draft / In Review / Approved |

---

## 1. Scope

### In Scope
_List the features, user stories, and functionality that will be tested._

- 
- 

### Out of Scope
_List any areas explicitly excluded from this test plan and the reason._

- 
- 

---

## 2. Test Objectives

_Describe what the testing is intended to validate (e.g., functional correctness, performance thresholds, security, accessibility)._

- 
- 

---

## 3. Test Types

| Test Type | Required | Owner | Notes |
|---|---|---|---|
| Unit tests | | Developer | |
| Integration tests | | Developer | |
| API / contract tests | | Developer / QA | |
| Functional / acceptance tests | | QA Lead | |
| Regression tests | | QA Lead | |
| Performance / load tests | | QA Lead / DevOps | |
| Security scans | | DevOps / QA | |
| Accessibility tests | | QA Lead | |
| User Acceptance Testing (UAT) | | Business Analyst | |

---

## 4. Entry and Exit Criteria

### Entry Criteria (testing may begin when)
- [ ] Feature branch is merged and deployed to the test environment
- [ ] Acceptance criteria are documented and agreed
- [ ] Test data and test environment are available
- [ ] Unit and integration tests are passing in CI

### Exit Criteria (testing is complete when)
- [ ] All test cases executed
- [ ] All blocking and critical defects resolved or deferred with justification
- [ ] Defect escape rate is within acceptable thresholds
- [ ] QA Lead sign-off provided to Release Manager

---

## 5. Test Cases Summary

_Link to the full test case suite or list key scenarios here. Organize by user story or feature area._

| ID | Test Scenario | Priority | Expected Result | Status |
|---|---|---|---|---|
| TC-001 | | High | | Not Started |
| TC-002 | | Medium | | Not Started |
| TC-003 | | Low | | Not Started |

---

## 6. Defect Management

- Defects are tracked in: _(e.g., GitHub Issues, Jira)_
- Severity levels: **Critical** → **High** → **Medium** → **Low**
- Blocking defects (Critical/High) must be resolved before the go/no-go meeting
- All defects include: title, steps to reproduce, expected vs. actual result, severity, and assignee

---

## 7. Test Environment

| Environment | URL / Location | Owner | Notes |
|---|---|---|---|
| Development | | Developer | |
| Staging / QA | | QA Lead | |
| Production | | DevOps | |

---

## 8. Risks & Mitigations

| Risk | Impact | Mitigation |
|---|---|---|
| Test environment unavailability | High | Coordinate with DevOps to ensure environment SLA |
| Incomplete acceptance criteria | High | BA and QA Lead review criteria before sprint start |
| Insufficient test data | Medium | Prepare test data set during Planning |

---

## 9. Sign-off

| Role | Name | Date | Approved |
|---|---|---|---|
| QA Lead | | | ☐ |
| Business Analyst | | | ☐ |
| Project Manager | | | ☐ |
| Release Manager | | | ☐ |

---

**Owner:** QA Lead  
**Reviewers:** Business Analyst, Project Manager, Release Manager  
**Reference:** [Roles & Personas](../octoacme-roles-and-personas.md) | [Execution & Tracking](../octoacme-execution-and-tracking.md)
