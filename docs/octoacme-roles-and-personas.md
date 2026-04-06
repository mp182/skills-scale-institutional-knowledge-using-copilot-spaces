# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

---

## Table of Contents

- [Developers](#developers)
- [Product Managers](#product-managers)
- [Project Managers](#project-managers)
- [Business Analyst](#business-analyst)
- [Release Manager](#release-manager)
- [Quality Assurance (QA) Lead](#quality-assurance-qa-lead)
- [Project Stakeholder](#project-stakeholder)
- [Role Collaboration Matrix (RACI)](#role-collaboration-matrix-raci)
- [How these personas are used in the exercise](#how-these-personas-are-used-in-the-exercise)

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

## Business Analyst

### Role Summary
The Business Analyst acts as the bridge between business stakeholders and the delivery team. They are responsible for eliciting, documenting, and validating requirements so that the team builds the right solution.

### Responsibilities
- Gather and document business requirements through interviews, workshops, and process mapping
- Translate stakeholder needs into clear user stories and acceptance criteria
- Maintain a requirements traceability matrix to ensure all needs are addressed
- Identify process gaps and recommend improvements
- Facilitate requirement sign-off with stakeholders and the Product Manager
- Support UAT (User Acceptance Testing) planning and execution
- Act as a point of contact for requirement clarifications during development

### Goals
- Ensure the delivered solution meets documented business needs
- Reduce rework caused by unclear or incomplete requirements
- Improve handoff quality between stakeholders and the delivery team

### Typical Communication
- Requirements review sessions with stakeholders and Product Manager
- Story-writing workshops with developers and QA Lead
- Regular check-ins with Project Manager on scope changes

---

## Release Manager

### Role Summary
The Release Manager owns the planning, coordination, and communication of all release activities. They ensure that deployments are scheduled, well-communicated, and meet quality standards before reaching production.

### Responsibilities
- Create and maintain the release calendar and release plan
- Coordinate go/no-go decisions with Project Manager, QA Lead, and DevOps
- Ensure all pre-release requirements (acceptance criteria, CI checks, security scans) are met
- Draft and distribute release notes and stakeholder communications
- Manage the deployment window and monitor the release in progress
- Maintain rollback plans and ensure the team is prepared to execute them
- Facilitate post-release verification and coordinate incident response if needed

### Goals
- Deliver stable, predictable releases with minimal disruption
- Provide clear and timely communication to all affected parties
- Continuously reduce release risk through improved processes and automation

### Typical Communication
- Weekly release planning syncs with Project Manager and QA Lead
- Go/no-go meeting with Project Manager, QA Lead, and DevOps before each release
- Release announcements and post-deploy status updates to stakeholders

---

## Quality Assurance (QA) Lead

### Role Summary
The QA Lead owns the quality strategy for the project. They define test plans, manage defect triage, and ensure that quality is built into every stage of the delivery lifecycle — not just at the end.

### Responsibilities
- Define and maintain the test strategy and test plan for the project
- Write and review test cases aligned to acceptance criteria
- Coordinate test execution (unit, integration, UAT, regression) across the team
- Triage and track defects, escalating blocking issues to the Project Manager
- Partner with the Business Analyst to validate that acceptance criteria are testable
- Work with the Release Manager to confirm release readiness before each deployment
- Champion quality practices (shift-left testing, code coverage, automation)
- Participate in retrospectives and feed quality improvement actions into the backlog

### Goals
- Prevent defects from reaching production through proactive quality gates
- Maintain clear, up-to-date test coverage across all features
- Reduce defect escape rate and improve time-to-detect issues

### Typical Communication
- Daily standups and sprint ceremonies with the delivery team
- Defect triage meetings with developers and Business Analyst
- Go/no-go review with Release Manager and Project Manager

---

## Project Stakeholder

### Role Summary
Project Stakeholders represent the interests of a business unit, customer group, or project sponsor. They provide strategic direction, review deliverables, and approve key phase transitions. Their engagement is essential for validating that the project delivers real business value.

### Responsibilities
- Provide business context, priorities, and strategic direction at project initiation
- Review and approve project charters, requirements, and major deliverables
- Participate in phase-gate reviews and approve go/no-go decisions where required
- Supply timely feedback on prototypes, demos, and release candidates
- Escalate business-level risks or constraint changes to the Project Manager
- Support organizational change management and adoption of the delivered solution

### Goals
- Ensure the project delivers measurable business value
- Maintain visibility into project progress and risk without day-to-day involvement
- Enable fast, informed decisions at key phase transitions

### Typical Communication
- Monthly stakeholder updates from the Project Manager
- Phase-gate review meetings at the end of Initiation, Planning, and before Release
- Ad-hoc briefings when risks, scope changes, or decisions require stakeholder input

---

## Role Collaboration Matrix (RACI)

**Key:** R = Responsible | A = Accountable | C = Consulted | I = Informed

| Activity | Project Manager | Product Manager | Business Analyst | Developers | QA Lead | Release Manager | Stakeholder |
|---|---|---|---|---|---|---|---|
| Define project charter / one-pager | A | C | C | I | I | I | C |
| Stakeholder alignment and approval | A | C | C | I | I | I | A |
| Requirements gathering | I | C | R/A | C | C | I | C |
| Backlog prioritization | C | A | C | C | I | I | I |
| Sprint / iteration planning | A | C | C | R | C | I | I |
| Write acceptance criteria | C | R | R | C | C | I | I |
| Development and implementation | I | I | C | R/A | C | I | I |
| Test planning and execution | C | I | C | C | R/A | C | I |
| Defect triage | C | I | C | R | A | C | I |
| Release planning | A | C | I | I | C | R | I |
| Go/no-go decision | A | C | I | I | C | C | C |
| Deployment | C | I | I | C | C | R/A | I |
| Release communication | A | I | I | I | I | R | I |
| Phase-gate approval | C | C | C | I | I | I | A |
| Retrospective facilitation | R/A | C | C | C | C | C | I |

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- The RACI matrix above helps teams quickly identify who is responsible, accountable, consulted, or informed for each key project activity.

