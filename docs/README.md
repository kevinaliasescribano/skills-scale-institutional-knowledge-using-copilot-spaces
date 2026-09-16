# OctoAcme Project Management Docs

This folder contains OctoAcme's project management processes, templates, checklists, and role guidance. The docs describe the lifecycle we follow—initiation, planning, execution, release, and continuous improvement—and provide actionable guidance for delivering work reliably across cross-functional teams.

## Overview of OctoAcme project management processes

OctoAcme operates an iterative, customer-focused lifecycle. Initiation captures the problem, stakeholders, success metrics, and a lightweight one-pager to decide whether work should move into planning. Planning turns approved initiatives into a prioritized backlog with acceptance criteria, estimates, dependencies, a Definition of Done, and a release/milestone plan. Execution uses project boards to manage flow, a disciplined pull request process (small PRs, acceptance criteria, CI gates), and a steady delivery cadence (daily standups, weekly delivery syncs, demos).

## Quality, release, and improvement practices

Quality assurance combines automated unit and integration tests, CI security scanning, and smoke tests for critical flows, with manual QA as needed. Releases follow a checklist-based deployment process with rollback/playbook steps and post-deploy verification. After delivery or incidents, retrospectives capture learnings and convert them into a small set of owned action items tracked in the backlog to drive continuous improvement.

## Roles and communication

Clear roles support execution: Product Managers define outcomes and success metrics, Project Managers coordinate schedules, risks, and stakeholder communications, Developers implement and test, and QA validates acceptance criteria. Communication cadence includes short daily standups for blockers and progress, weekly PM–PdM syncs, sprint/milestone demos, and regular stakeholder updates. Risks are tracked in a simple register and escalated through defined ownership paths when needed.

## Process documents

- docs/octoacme-project-management-overview.md
- docs/octoacme-project-initiation.md
- docs/octoacme-project-planning.md
- docs/octoacme-execution-and-tracking.md
- docs/octoacme-risks-and-communication.md
- docs/octoacme-release-and-deployment.md
- docs/octoacme-retrospective-and-continuous-improvement.md
- docs/octoacme-roles-and-personas.md

## Getting started

1. Read the Project Management Overview to understand principles and roles.
2. If you have a new idea, follow Project Initiation to create a one-pager and decide whether to move into planning.
3. Use Project Planning and Execution & Tracking to prepare and deliver work; follow Release & Deployment when shipping to production.
4. Add or update docs using the repository's issue template: .github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml

## Contributing

To propose additions or edits, open an issue using the "Add Content to Project Management Process Docs" template and include the suggested text and rationale. Maintainers will review and merge approved updates.
