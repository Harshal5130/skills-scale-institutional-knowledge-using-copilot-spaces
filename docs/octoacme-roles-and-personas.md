# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

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

## QA / Testing

### Role Summary
QA / Testing team members validate that features meet acceptance criteria, are defect-free, and satisfy quality standards before release.

### Responsibilities
- Write and execute test plans, test cases, and regression suites
- Coordinate exploratory and user acceptance testing (UAT)
- Report defects and track resolution with Developers
- Validate Definition of Done criteria before items are marked complete
- Provide sign-off for releases

### Goals
- Ensure high product quality and reliability
- Identify defects early to reduce rework cost
- Build confidence in each release through thorough validation

### Typical Communication
- Sprint demos and review sessions
- Defect reports and QA sign-off notes
- Test summary reports shared with Project Managers and Product Managers

---

## User Experience (UX) Designer

### Role Summary
UX Designers advocate for the end user throughout the project lifecycle. They conduct research, define user journeys, and craft intuitive interfaces and interactions.

### Responsibilities
- Conduct user research, interviews, and usability studies
- Define user journeys, personas, and information architecture
- Create wireframes, prototypes, and design specifications
- Advocate for accessibility and usability best practices
- Validate designs through iterative user feedback

### Interactions
- Works with **Product Managers** to translate requirements into user-centred designs and refine acceptance criteria based on research findings
- Collaborates with **Developers** to review implementations against design specs and validate interaction behaviour
- Partners with **QA / Testing** to ensure usability testing is included in test plans and that accessibility standards are verified

### Typical Communication
- Design reviews and critique sessions
- Prototype walkthroughs with Product Managers and Developers
- Usability test summaries shared with the broader team

---

## Scrum Master / Agile Coach

### Role Summary
The Scrum Master / Agile Coach facilitates agile ceremonies, removes blockers, and coaches the team on continuous improvement practices.

### Responsibilities
- Facilitate sprint planning, daily standups, sprint reviews, and retrospectives
- Identify and remove delivery impediments
- Coach the team on agile principles and practices
- Track team health, velocity, and process metrics
- Foster a culture of continuous improvement

### Interactions
- Works closely with **Project Managers** to align on delivery plans, escalate cross-team blockers, and maintain the risk register
- Supports **Developers** by removing technical or organisational impediments and helping the team self-organise
- Coordinates with **Product Managers** to ensure the backlog is well-groomed and sprint goals are clear

### Typical Communication
- Agile ceremony facilitation (standups, planning, retros)
- Impediment logs and escalation notes
- Team health and velocity reports shared with Project Managers

---

## Data Analyst

### Role Summary
Data Analysts gather, interpret, and present data on product usage and team performance to support informed, evidence-based decisions.

### Responsibilities
- Define and track success metrics and KPIs in partnership with Product Managers
- Analyse product usage data, experiment results, and performance trends
- Provide reporting dashboards and data summaries for stakeholders
- Liaise with Developers to ensure correct instrumentation and data collection
- Support Project Managers with delivery metrics and forecasting

### Interactions
- Partners with **Product Managers** on hypothesis definition, experiment design, and outcome measurement
- Liaises with **Developers** to specify data instrumentation requirements and validate data accuracy
- Supports **Project Managers** by supplying delivery and performance metrics for status reporting

### Typical Communication
- Data dashboards and metric reports shared at sprint reviews and stakeholder briefings
- Instrumentation requirements documented as backlog items
- Ad-hoc analysis requests via project channels

---

## Security Lead

### Role Summary
The Security Lead identifies, assesses, and mitigates security risks across the project lifecycle, ensuring the product meets compliance and security standards.

### Responsibilities
- Conduct threat modelling and security risk assessments
- Review features and architecture for security vulnerabilities and compliance requirements
- Define and maintain secure coding guidelines and security acceptance criteria
- Lead incident response for security-related events
- Report security findings and remediation status to stakeholders

### Interactions
- Advises **Developers** on secure coding practices, vulnerability remediation, and security tooling
- Coordinates with **Project Managers** to log security risks in the risk register and track mitigations
- Updates **Product Managers** and stakeholders on security posture, compliance status, and incident findings

### Typical Communication
- Security review sign-offs included in the Definition of Done
- Risk register entries for security risks, reviewed at weekly syncs
- Incident communication and post-incident retrospective notes

---

## Customer / End User

### Role Summary
Customers and End Users provide real-world feedback that validates whether the product solves the intended problem and meets usability expectations.

### Responsibilities
- Participate in discovery interviews, surveys, and usability testing
- Provide feedback on prototypes and beta features
- Validate that proposed solutions meet genuine needs during UAT
- Surface edge cases and unmet requirements from lived experience

### Interactions
- Engaged by **Product Managers** during discovery and research phases to inform problem definition and prioritisation
- Involved by **QA / Testing** in user acceptance testing (UAT) to validate feature completeness and usability
- Feedback loop maintained by **Project Managers** and **Product Managers** through regular check-ins and release communications

### Typical Communication
- User research sessions, surveys, and beta feedback channels
- UAT sign-off notes shared with Product and Project Managers
- Release notes and change communications distributed by the project team

---

## Stakeholders

### Role Summary
Stakeholders are individuals or groups with a vested interest in the project outcome, including executives, business owners, dependent teams, and external partners.

### Responsibilities
- Provide strategic direction, priorities, and constraints
- Review and approve project scope, budget, and key decisions
- Receive regular status updates and raise concerns or changes in business direction
- Participate in milestone reviews and release approvals

### Goals
- Ensure the project delivers expected business value
- Maintain visibility of risks, costs, and timelines
- Enable timely decisions to unblock the team

### Typical Communication
- Weekly or milestone-based status reports from Project Managers
- Escalation notifications for high-impact risks
- Release communications and post-launch summaries

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- See [Role Interaction Matrix](./octoacme-role-interaction-matrix.md) for a view of how roles collaborate across key activities.
- See [Definition of Done Checklist](./octoacme-definition-of-done-checklist.md) for the quality gate each role contributes to.

