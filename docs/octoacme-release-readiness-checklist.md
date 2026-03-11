# OctoAcme Release Readiness Checklist

Use this checklist before every production release to ensure all roles have completed their responsibilities.
Work through each section in order; block the release if any mandatory item is unresolved.

---

## 1. Product & Scope

- [ ] All planned features meet documented acceptance criteria.
- [ ] Any descoped items are recorded in the backlog with rationale.
- [ ] Product Manager has signed off on the release scope.

## 2. Quality & Testing

- [ ] All automated tests pass in the CI pipeline.
- [ ] Manual/exploratory testing is complete for high-risk areas.
- [ ] No open P0/P1 (critical) bugs are unresolved.
- [ ] Definition of Done is met for all delivered items.

## 3. UX/Design

- [ ] UX/UI Lead has reviewed the implementation against design specs.
- [ ] Accessibility requirements are met (keyboard navigation, contrast ratios, screen-reader labels).
- [ ] Any known UX deviations are documented and accepted by Product Manager.

## 4. Security

- [ ] Security Champion has reviewed the release for outstanding vulnerabilities.
- [ ] All critical and high-severity security findings are resolved or have an accepted risk statement.
- [ ] Dependencies have been updated and scanned for known CVEs.
- [ ] Secrets and credentials are not hardcoded; environment config is validated.

## 5. Analytics & Observability

- [ ] Analytics instrumentation is verified (events fire correctly in staging).
- [ ] Dashboards and alerts are updated to reflect new features.
- [ ] Data Analyst has confirmed the metrics baseline is captured pre-release.

## 6. Support Readiness

- [ ] Support Engineer has reviewed the release and updated runbooks.
- [ ] Known issues and workarounds are documented in the knowledge base.
- [ ] Support team has been briefed on new features and expected change in ticket volume.
- [ ] Escalation paths for new features are defined.

## 7. Deployment & Operations

- [ ] Deployment runbook is up to date and reviewed by the on-call team.
- [ ] Rollback plan is documented and tested where feasible.
- [ ] Feature flags / toggles are configured correctly.
- [ ] Post-deploy smoke test checklist is ready.

## 8. Communication & Stakeholders

- [ ] Release notes are written and reviewed.
- [ ] Stakeholder communication (email / announcement) is drafted and approved.
- [ ] Project Manager has confirmed go/no-go with all sign-off owners.
- [ ] Release date and time are confirmed with all impacted teams.

---

## Sign-Off

| Role | Name | Sign-Off Date | Notes |
|------|------|:---:|-------|
| Project Manager | | | |
| Product Manager | | | |
| Developer Lead | | | |
| UX/UI Lead | | | |
| Security Champion | | | |
| Support Engineer | | | |

---

*See also: [`octoacme-cross-role-interactions.md`](./octoacme-cross-role-interactions.md) · [`octoacme-release-and-deployment.md`](./octoacme-release-and-deployment.md)*
