# OctoAcme — Definition of Done (DoD) Checklist

A reusable checklist that teams should verify before marking any feature, story, or release as **Done**. Each item indicates which role(s) typically own or verify it.

> Use this checklist during sprint reviews and as part of release sign-off. Items may be adapted to the scope of the work item (e.g., a small bug-fix may skip the release notes item, but must still pass testing and security checks).

---

## Development Completeness

- [ ] All acceptance criteria are met as defined in the backlog item
  - *Owner: Developer; Verified by: QA / Testing, Product Manager*
- [ ] Code is reviewed and approved via Pull Request (minimum one peer review)
  - *Owner: Developer; Verified by: Developer (reviewer)*
- [ ] Feature branch is merged to the appropriate integration branch with no outstanding conflicts
  - *Owner: Developer*

---

## Testing

- [ ] Unit tests written and passing for all new or changed logic
  - *Owner: Developer; Verified by: QA / Testing*
- [ ] Integration tests updated or created where applicable
  - *Owner: Developer; Verified by: QA / Testing*
- [ ] Regression test suite passes (no new failures introduced)
  - *Owner: QA / Testing*
- [ ] Manual exploratory testing completed for user-facing changes
  - *Owner: QA / Testing*
- [ ] User Acceptance Testing (UAT) sign-off obtained where required
  - *Owner: QA / Testing; Participant: Customer / End User; Notified: Product Manager*

---

## Documentation

- [ ] Inline code comments updated where logic is non-obvious
  - *Owner: Developer*
- [ ] Public API or interface documentation updated (README, OpenAPI spec, etc.)
  - *Owner: Developer; Reviewed by: Product Manager*
- [ ] Process or user-facing documentation updated in `docs/` if behaviour changes
  - *Owner: Developer / Product Manager*

---

## Security

- [ ] Static analysis / security scanning (SAST) passed in CI with no new high/critical findings
  - *Owner: Developer; Verified by: Security Lead*
- [ ] Dependency vulnerability scan completed with no new high/critical CVEs
  - *Owner: Developer; Verified by: Security Lead*
- [ ] Threat model reviewed for significant new features or architectural changes
  - *Owner: Security Lead; Consulted: Developer, Product Manager*
- [ ] Secure coding guidelines followed (input validation, secrets management, auth checks)
  - *Owner: Developer; Verified by: Security Lead*

---

## Accessibility & Usability

- [ ] UI changes reviewed against accessibility standards (WCAG 2.1 AA or equivalent)
  - *Owner: UX Designer; Verified by: Developer, QA / Testing*
- [ ] Usability validated through design review or user testing for significant UX changes
  - *Owner: UX Designer; Consulted: Product Manager*
- [ ] Keyboard navigation and screen-reader compatibility verified for new UI components
  - *Owner: Developer; Verified by: QA / Testing, UX Designer*

---

## Instrumentation & Metrics

- [ ] Success metrics for the feature are defined and agreed
  - *Owner: Product Manager; Supported by: Data Analyst*
- [ ] Analytics events / telemetry instrumented for key user actions
  - *Owner: Developer; Specified by: Data Analyst*
- [ ] Dashboards or monitoring views updated to surface new signals
  - *Owner: Data Analyst; Supported by: Developer*
- [ ] Baseline metrics captured (if applicable) to support A/B or experiment analysis
  - *Owner: Data Analyst; Coordinated with: Product Manager*

---

## Release Notes

- [ ] Release notes or changelog entry drafted describing user-visible changes
  - *Owner: Product Manager; Reviewed by: Project Manager*
- [ ] Breaking changes (API, data schema, config) explicitly documented and communicated
  - *Owner: Developer; Reviewed by: Product Manager, Security Lead*
- [ ] Stakeholder and customer communication prepared (if the change is significant)
  - *Owner: Project Manager; Approved by: Product Manager*

---

## Final Sign-off

| Role | Sign-off |
|---|---|
| Developer | ☐ |
| QA / Testing | ☐ |
| Security Lead | ☐ |
| UX Designer (if UX changes) | ☐ |
| Product Manager | ☐ |
| Project Manager | ☐ |

---

## Related Documents
- [Roles and Personas](./octoacme-roles-and-personas.md)
- [Role Interaction Matrix](./octoacme-role-interaction-matrix.md)
- [Project Planning](./octoacme-project-planning.md)
- [Execution & Tracking](./octoacme-execution-and-tracking.md)
- [Release & Deployment](./octoacme-release-and-deployment.md)
