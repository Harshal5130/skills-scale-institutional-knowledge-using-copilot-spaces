# OctoAcme Project Management Processes

A central entry point for all OctoAcme project management process documentation. This README provides a high-level overview of our approach, key roles, communication cadence, and quality practices, along with direct links to the full process docs for each stage.

## Overview

OctoAcme's project management approach is designed to be lightweight, iterative, and role-clear, with a consistent set of artifacts used across the project lifecycle. Projects move through five stages: **Initiation** (validate the problem, stakeholders, success metrics, and a rough timeline), **Planning** (create an actionable backlog, estimates, dependencies, and a Definition of Done), **Execution** (deliver in small increments with strong tracking), **Release** (deploy with risk controls and verification), and **Close/Retro** (capture learnings and convert them into action items). Core artifacts include a Project One-pager/Charter, a prioritized backlog with acceptance criteria, a risk register, release notes, and retrospective action items.

## Roles & Personas

Key personas are explicitly defined to reduce ambiguity and improve ownership. A **Project Manager (PM)** coordinates delivery, schedules, risks, and stakeholder communications; a **Product Manager/Product Lead** defines outcomes, prioritizes work, and measures success; **Developers** implement, test, document, and participate in estimation and reviews; **QA/Testing** validates quality and acceptance criteria; and **Stakeholders/Sponsors** provide input and approvals. This separation of responsibilities supports clear ownership while still encouraging collaboration through shared planning, review, and iterative delivery habits.

## Communication Cadence

Day-to-day execution centers on a predictable team rhythm and transparent workflow tracking. Teams use a project board (e.g., GitHub Projects) with common states such as **Backlog → Ready → In Progress → In Review → QA → Done**, supported by **daily standups** for surfacing blockers and dependencies, a **weekly delivery sync** for broader progress and risk review, and **end-of-sprint demos/reviews**. Communication is structured with regular PM and product alignment, stakeholder updates, and a clear escalation path: team triage first, then PM/product leads, then sponsor escalation for business-impacting issues.

## Quality Assurance

Quality is built into both the development workflow and the release process. Development expectations include **small pull requests** linked to issues and acceptance criteria, passing **CI tests and linting** before review, and at least one approval before merging. Testing practices include **unit tests** for new logic, **integration tests** where relevant, and **end-to-end smoke tests** for critical flows, as well as CI **security scanning** and manual QA when needed. Releases require acceptance criteria completion, passing CI/scans, prepared release notes, and a rollback/mitigation plan, followed by staged deployment and post-deploy verification, with an incident/rollback playbook and blameless retrospectives to drive continuous improvement.

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
