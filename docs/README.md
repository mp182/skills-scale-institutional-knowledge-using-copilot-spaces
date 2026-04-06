# OctoAcme Project Management Docs

This folder contains the process documentation for OctoAcme's project management framework. These docs are the authoritative reference for how OctoAcme initiates, plans, executes, releases, and improves projects.

---

## Overview

OctoAcme follows an iterative, customer-first delivery model. Projects are owned by a named **Project Manager (PM)** working in partnership with a **Product Manager (PdM)**, a **development team**, and key **stakeholders**. Decisions are data-informed, work is delivered in small testable increments, and learnings are captured after every milestone.

The framework covers the full project lifecycle — from validating a business idea through to deploying to production and running a retrospective — with clear ownership, communication cadences, and quality gates at each stage.

Key practices include:
- Lightweight project charters and one-pagers at initiation
- Prioritized, estimated backlogs with a Definition of Done before work begins
- Daily standups, weekly delivery syncs, and monthly stakeholder updates during execution
- Structured risk registers and escalation paths throughout the project
- A standardized deployment checklist and rollback plan at release
- Blameless retrospectives after every sprint, release, or incident

---

## Process Documents

| Document | Description |
|---|---|
| [Project Management Overview](octoacme-project-management-overview.md) | Principles, core roles, key artifacts, and the project lifecycle at a glance |
| [Project Initiation](octoacme-project-initiation.md) | How to validate and authorize a new project, align stakeholders, and create a lightweight plan |
| [Project Planning](octoacme-project-planning.md) | How to turn an approved initiative into an actionable backlog, release plan, and milestone map |
| [Execution & Tracking](octoacme-execution-and-tracking.md) | Day-to-day team rhythm, PR workflow, quality standards, and blocker escalation |
| [Risks & Communication](octoacme-risks-and-communication.md) | Risk register format, risk lifecycle, stakeholder communication templates, and escalation paths |
| [Release & Deployment](octoacme-release-and-deployment.md) | Release types, pre-release requirements, deployment checklist, and rollback playbook |
| [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) | How to run retrospectives, track action items, and build a continuous improvement culture |
| [Roles & Personas](octoacme-roles-and-personas.md) | Responsibilities, goals, and communication patterns for all project roles, including the RACI matrix |

---

## Templates & Checklists

Reusable templates and checklists are stored in the [`templates/`](templates/) folder.

| Template | Description |
|---|---|
| [Requirements Checklist](templates/requirements-checklist.md) | Validate requirements completeness and handoff readiness |
| [QA / Test Plan Template](templates/qa-test-plan-template.md) | Document the test strategy, scope, test cases, and sign-off criteria |
| [Release Readiness Checklist](templates/release-readiness-checklist.md) | Confirm all gates are met before deploying to production |
| [Stakeholder Review Checklist](templates/stakeholder-review-checklist.md) | Prepare and document structured phase-gate reviews |
| [Handoff Checklist](templates/handoff-checklist.md) | Ensure clean, accountable handoffs between roles and phases |

---

## How to Use These Docs

1. **New to the team?** Start with the [Project Management Overview](octoacme-project-management-overview.md) for a quick orientation, then review [Roles & Personas](octoacme-roles-and-personas.md) to understand your responsibilities and how your role fits into the RACI matrix.
2. **Starting a new project?** Follow the [Project Initiation](octoacme-project-initiation.md) guide to validate the idea and get stakeholder alignment before moving into planning.
3. **In delivery?** Use [Execution & Tracking](octoacme-execution-and-tracking.md) for day-to-day guidance and [Risks & Communication](octoacme-risks-and-communication.md) for managing risk and keeping stakeholders informed.
4. **Preparing a release?** Follow the [Release & Deployment](octoacme-release-and-deployment.md) checklist and ensure a rollback plan is documented.
5. **Wrapping up?** Run a retrospective using the [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) guide and feed action items back into the backlog.
6. **Updating or adding a process doc?** Use the [Add/Update Content issue template](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) to track the change.

---

## Quick-Start Flow

```
Initiation → Planning → Execution & Tracking → Release & Deployment → Retrospective
```

| Stage | Key Output | Reference |
|---|---|---|
| **Initiation** | Project one-pager, stakeholder list, go/no-go decision | [Project Initiation](octoacme-project-initiation.md) |
| **Planning** | Prioritized backlog, Definition of Done, release plan | [Project Planning](octoacme-project-planning.md) |
| **Execution** | Working software, updated risk register, regular demos | [Execution & Tracking](octoacme-execution-and-tracking.md) |
| **Release** | Deployed feature, release notes, stakeholder announcement | [Release & Deployment](octoacme-release-and-deployment.md) |
| **Retrospective** | Action items logged and tracked in the backlog | [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) |
