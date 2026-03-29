# OctoAcme Project Management Processes

A central entry point for all OctoAcme project management process documentation. This README provides a high-level overview of our approach, key roles, communication cadence, and quality practices, along with direct links to the full process docs for each stage.

## Overview

OctoAcme's project management approach is lightweight, iterative, and role-clear, with a consistent set of artifacts used across the project lifecycle. Projects move through five stages:

1. **Initiation** – validate the problem, stakeholders, success metrics, and a rough timeline
2. **Planning** – create an actionable backlog, estimates, dependencies, and a Definition of Done
3. **Execution** – deliver in small increments with strong tracking
4. **Release** – deploy with risk controls and verification
5. **Close/Retro** – capture learnings and convert them into action items

Core artifacts include a Project One-pager/Charter, a prioritized backlog with acceptance criteria, a risk register, release notes, and retrospective action items.

## Roles & Personas

Key personas are explicitly defined to reduce ambiguity and improve ownership:

| Role | Responsibilities |
|---|---|
| **Project Manager (PM)** | Coordinates delivery, schedules, risks, and stakeholder communications |
| **Product Manager/Product Lead** | Defines outcomes, prioritizes work, and measures success |
| **Developers** | Implement, test, document, and participate in estimation and reviews |
| **QA/Testing** | Validates quality and acceptance criteria |
| **Stakeholders/Sponsors** | Provide input and approvals |

This separation of responsibilities supports clear ownership while still encouraging collaboration through shared planning, review, and iterative delivery habits.

## Communication Cadence

Day-to-day execution centers on a predictable team rhythm and transparent workflow tracking. Teams use a project board (e.g., GitHub Projects) with common states: **Backlog → Ready → In Progress → In Review → QA → Done**.

Regular touchpoints include:
- **Daily standups** – surface blockers and dependencies
- **Weekly delivery sync** – broader progress and risk review
- **End-of-sprint demos/reviews** – stakeholder visibility into delivered work
- **Stakeholder updates** – regular PM and product alignment
- **Escalation path** – team triage first, then PM/product leads, then sponsor escalation for business-impacting issues

## Quality Assurance

Quality is built into both the development workflow and the release process.

**Development workflow:**
- Small pull requests linked to issues and acceptance criteria
- Passing CI tests and linting before review
- At least one approval before merging

**Testing practices:**
- Unit tests for new logic
- Integration tests where relevant
- End-to-end smoke tests for critical flows
- CI security scanning and manual QA when needed

**Release requirements:**
- Acceptance criteria completion and passing CI/scans
- Prepared release notes and a rollback/mitigation plan
- Staged deployment and post-deploy verification
- Incident/rollback playbook and blameless retrospectives for continuous improvement

---

## Process Docs Index

- [Project Management Overview](octoacme-project-management-overview.md)
- [Project Initiation Guide](octoacme-project-initiation.md)
- [Project Planning](octoacme-project-planning.md)
- [Execution & Tracking](octoacme-execution-and-tracking.md)
- [Risk Management & Communication](octoacme-risks-and-communication.md)
- [Release & Deployment Guide](octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)
- [Roles & Personas](octoacme-roles-and-personas.md)
