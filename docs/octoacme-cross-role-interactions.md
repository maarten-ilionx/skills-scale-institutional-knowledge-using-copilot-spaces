# OctoAcme Cross-Role Interaction Guide

This document maps key responsibilities and collaboration touchpoints across each phase of the OctoAcme project lifecycle.
Use it alongside [`octoacme-roles-and-personas.md`](./octoacme-roles-and-personas.md) to understand who does what, when, and with whom.

---

## Lifecycle Phases

| Phase | Description |
|-------|-------------|
| **Initiation** | Define problem, identify stakeholders, align on high-level goals |
| **Planning** | Scope features, estimate effort, establish milestones and risk register |
| **Execution** | Build, test, review, and iterate |
| **Release** | Deploy, verify, communicate launch |
| **Retrospective** | Capture learnings, update docs, drive continuous improvement |

---

## RACI-Lite: Who Does What, When

> **Key:** R = Responsible · A = Accountable · C = Consulted · I = Informed

| Activity | Project Manager | Product Manager | Developer | UX/UI Lead | Security Champion | Support Engineer | Data Analyst |
|----------|:-:|:-:|:-:|:-:|:-:|:-:|:-:|
| **INITIATION** | | | | | | | |
| Define problem statement & goals | C | A/R | I | C | I | I | C |
| Identify stakeholders | A/R | R | I | I | I | C | I |
| Define success metrics | C | A/R | I | C | I | I | R |
| Assess initial risks | A/R | C | C | I | R | C | I |
| **PLANNING** | | | | | | | |
| Scope features & acceptance criteria | C | A/R | C | R | C | C | C |
| Estimate effort and create timeline | A/R | C | R | R | C | C | I |
| Threat modeling & security review | C | I | C | I | A/R | I | I |
| Design wireframes & UX specs | I | C | C | A/R | I | I | I |
| Define analytics instrumentation plan | I | R | C | I | I | I | A/R |
| Update risk register | A/R | C | C | I | R | C | I |
| **EXECUTION** | | | | | | | |
| Implement features | I | I | A/R | C | C | I | I |
| UX/design review of implementation | I | C | R | A/R | I | I | I |
| Security review of code & architecture | I | I | R | I | A/R | I | I |
| Validate analytics instrumentation | I | C | R | I | I | I | A/R |
| Manage blockers and dependencies | A/R | C | R | C | C | C | I |
| Status reporting to stakeholders | A/R | C | I | I | I | I | C |
| **RELEASE** | | | | | | | |
| Release readiness sign-off | A/R | R | R | R | R | R | C |
| Deploy to production | C | I | A/R | I | C | C | I |
| Post-deploy verification | C | C | A/R | C | C | R | C |
| Stakeholder launch communication | A/R | R | I | I | I | I | I |
| Support team briefing & runbook review | C | C | I | I | C | A/R | I |
| **RETROSPECTIVE** | | | | | | | |
| Facilitate retrospective | A/R | C | R | C | C | C | C |
| Share data/metrics review | C | R | I | I | I | I | A/R |
| Document incident/support learnings | C | C | C | I | C | A/R | C |
| Update process docs & action items | A/R | C | C | C | C | C | I |

---

## Key Collaboration Touchpoints

### Initiation → Planning
- **Product Manager + Data Analyst**: align on success metrics before scope is finalized.
- **Security Champion + Project Manager**: perform initial risk assessment; add findings to the risk register.
- **UX/UI Lead + Product Manager**: review problem statement to surface UX constraints early.

### Planning → Execution
- **UX/UI Lead + Developers**: hand off design specs; establish shared acceptance criteria for UI components.
- **Security Champion + Developers**: complete threat model and agree on secure coding expectations.
- **Data Analyst + Developers**: agree on instrumentation requirements and data schemas.

### Execution → Release
- **Support Engineer + Developers**: validate runbooks and troubleshooting guides before release.
- **Security Champion**: confirm outstanding security findings are resolved or accepted with documented risk.
- **UX/UI Lead**: final usability review; sign off on UX acceptance criteria.

### Release → Retrospective
- **Data Analyst + Product Manager**: review release metrics and feature adoption data.
- **Support Engineer**: share post-release incident and support ticket trends.
- **Project Manager**: close the loop on risks and action items from the previous retrospective.

---

## Quick Reference: Who to Contact

| Need | Primary Contact | Loop In |
|------|----------------|---------|
| Feature scope or priority change | Product Manager | Project Manager |
| Timeline or dependency concern | Project Manager | Product Manager |
| Security guidance or vulnerability | Security Champion | Project Manager, Developer lead |
| UX/design feedback | UX/UI Lead | Product Manager |
| Post-release incident | Support Engineer | Developer, Project Manager |
| Metrics or analytics question | Data Analyst | Product Manager |
| Stakeholder communication | Project Manager | Product Manager |

---

*See also: [`octoacme-roles-and-personas.md`](./octoacme-roles-and-personas.md) · [`octoacme-risks-and-communication.md`](./octoacme-risks-and-communication.md)*
