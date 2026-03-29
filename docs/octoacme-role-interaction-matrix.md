# OctoAcme — Role Interaction Matrix

This matrix shows how each role participates in key project activities using a lightweight RACI model.

**Legend**
- **R** — Responsible (does the work)
- **A** — Accountable (owns the outcome / approves)
- **C** — Consulted (provides input before the activity)
- **I** — Informed (notified of progress or decisions)

---

## Activity × Role Matrix

| Activity | Developers | Product Managers | Project Managers | QA / Testing | UX Designer | Scrum Master / Agile Coach | Data Analyst | Security Lead | Customer / End User | Stakeholders |
|---|---|---|---|---|---|---|---|---|---|---|
| **Discovery / User Research** | I | A | I | I | R | I | C | C | C | I |
| **Backlog Definition** | C | A/R | C | C | C | C | C | C | I | I |
| **Sprint Planning** | R | C | C | C | I | A/R | I | I | — | I |
| **Implementation** | A/R | I | I | I | C | — | I | C | — | — |
| **Testing / QA** | C | I | I | A/R | C | — | I | C | I | — |
| **Security Review** | C | I | I | I | — | — | — | A/R | — | I |
| **Instrumentation / Analytics** | R | C | I | I | I | — | A/R | C | — | — |
| **Release** | R | A | C | C | I | I | I | C | I | I |
| **Incident Response** | R | I | A | I | — | I | C | R | I | I |
| **Retrospective** | R | C | A/R | C | C | A/R | C | C | — | I |

> **Notes**
> - `—` indicates the role typically has no direct involvement in that activity.
> - Some cells show `A/R` where the same person is both accountable and responsible (common in smaller teams).
> - Adjust ownership to match your team's structure; this matrix is a starting point, not a rigid prescription.

---

## Key Collaboration Touchpoints

| Roles | Primary Touchpoint |
|---|---|
| Product Managers ↔ UX Designer | Discovery sessions, design reviews, acceptance criteria |
| Developers ↔ UX Designer | Implementation review against design specs |
| Developers ↔ Security Lead | Secure coding guidance, vulnerability remediation |
| Project Managers ↔ Scrum Master | Delivery planning, impediment escalation |
| Product Managers ↔ Data Analyst | Metric definition, experiment design |
| Developers ↔ Data Analyst | Instrumentation requirements, data validation |
| QA / Testing ↔ Customer / End User | User acceptance testing (UAT) |
| Project Managers ↔ Stakeholders | Status reporting, escalation, milestone reviews |

---

## Related Documents
- [Roles and Personas](./octoacme-roles-and-personas.md)
- [Definition of Done Checklist](./octoacme-definition-of-done-checklist.md)
- [Project Planning](./octoacme-project-planning.md)
- [Execution & Tracking](./octoacme-execution-and-tracking.md)
