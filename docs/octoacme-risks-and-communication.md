# OctoAcme — Risk Management & Communication

## Purpose
Explain how to identify, manage, and communicate risks and dependencies.

## Risk Register
Maintain a simple table with:
- ID
- Description
- Impact (High/Med/Low)
- Likelihood (High/Med/Low)
- Owner
- Mitigation plan
- Status

> For security risks, the **Security Lead** is the designated owner and must be consulted when assessing impact and defining mitigation. Security risks are flagged in the register with a `[SECURITY]` tag and reviewed at every weekly sync.

## Risk Lifecycle
- Identify: during planning and ongoing execution
- Assess: estimate impact and likelihood
- Mitigate: reduced via actions, contingency plans
- Monitor: review at weekly syncs and update status

## Stakeholder Communication
- Identify stakeholder groups and communication needs (e.g., engineering, sales, support)
- Provide regular updates (weekly or milestone-based)
- Use a single source of truth (project README or release doc) for status

## Communication Templates
Weekly Status Template:
- Progress this week:
- Next steps:
- Risks & blockers:
- Ask / decisions needed:

Incident Communication
- Triage summary
- Actions being taken
- Expected timeline
- Post-incident blameless retrospective scheduled

## Escalation Paths
- Team-level -> PM -> Product Lead -> Sponsor
- For security incidents, the **Security Lead** leads triage and response; follow the security incident runbook and notify Security on-call immediately
- Security Lead logs all security risks in the Risk Register and provides regular status updates to Project Managers and stakeholders
- Non-security escalations: Team-level -> Scrum Master / Agile Coach -> Project Manager -> Sponsor
