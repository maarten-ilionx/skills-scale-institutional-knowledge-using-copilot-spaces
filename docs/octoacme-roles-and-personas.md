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

## UX/UI Lead

### Role Summary
The UX/UI Lead drives user-centered design practices across the product. They ensure features meet usability and accessibility standards and bridge the gap between user needs and technical implementation.

### Responsibilities
- Define and maintain UX standards, design patterns, and accessibility guidelines
- Conduct or coordinate user research and usability testing
- Produce wireframes, prototypes, and design specifications
- Review features before acceptance to validate usability
- Advocate for the end user throughout the project lifecycle

### Goals
- Ensure product interfaces are intuitive, accessible, and consistent
- Reduce usability-related defects and post-release redesigns
- Align design decisions with business and user goals

### Typical Communication
- Design reviews and critique sessions with Developers and Product Managers
- Usability test reports and design system updates
- Async feedback via design tools (e.g., Figma comments) and PR reviews

### Interactions with Other Roles
- **Product Manager**: collaborates on feature definition, acceptance criteria, and user research priorities.
- **Developers**: partners during implementation to review UI components, flag deviations from specs, and resolve design-to-code gaps.
- **Project Manager**: flags design-related risks or blockers that may affect timeline; provides estimates for design tasks.

---

## Security Champion

### Role Summary
The Security Champion advocates for secure development practices within the team. They provide guidance on threat modeling, secure coding, and risk mitigation to help the team ship software responsibly.

### Responsibilities
- Identify and document security risks during planning and design
- Review pull requests and architectures for security vulnerabilities
- Guide the team on secure coding standards and dependency management
- Escalate significant security risks to stakeholders
- Stay current on relevant threats, CVEs, and industry best practices

### Goals
- Reduce the number of security vulnerabilities reaching production
- Build a security-aware team culture
- Ensure security is addressed early ("shift-left") rather than as a late-stage gate

### Typical Communication
- Security review notes attached to design docs and PRs
- Risk register updates (partnering with Project Manager)
- Ad-hoc guidance and pairing with Developers on security topics

### Interactions with Other Roles
- **Developers**: provides hands-on guidance during implementation; reviews code for security issues.
- **Product Manager**: advises on security trade-offs that affect scope or prioritization.
- **Project Manager**: contributes security risks and mitigations to the risk register; flags blockers that require escalation.

---

## Support Engineer

### Role Summary
Support Engineers serve as the voice of support and operations within the project team. They anticipate post-release support needs, document troubleshooting guides, and ensure that learnings from incidents are incorporated back into the process.

### Responsibilities
- Document known issues, workarounds, and escalation paths before release
- Review upcoming features from a supportability perspective
- Represent user pain points and recurring issues in planning and retrospectives
- Collaborate on runbooks, FAQs, and support documentation
- Integrate incident learnings into process and product docs

### Goals
- Reduce time-to-resolution for post-release issues
- Minimize avoidable escalations through proactive documentation
- Ensure the support team is prepared on day one of every release

### Typical Communication
- Support readiness reviews before each release
- Incident post-mortems and retrospective input
- Async updates to runbooks and knowledge base articles

### Interactions with Other Roles
- **Developers**: collaborates on diagnosability, logging, and alerting; flags supportability gaps during code review.
- **Product Manager**: shares recurring user pain points that should inform prioritization.
- **Project Manager**: raises support-readiness risks before release; contributes to retrospective action items.

---

## Data Analyst

### Role Summary
Data Analysts translate business goals into measurable metrics, generate actionable insights from data, and inform prioritization and decision-making across the project lifecycle.

### Responsibilities
- Define key metrics and success criteria in partnership with the Product Manager
- Instrument features and validate that analytics are correctly captured
- Produce reports and dashboards to track release outcomes
- Surface data-driven insights to support retrospectives and planning sessions
- Identify trends or anomalies that may signal quality or UX issues

### Goals
- Enable data-informed prioritization and decision-making
- Provide clear visibility into release impact and feature adoption
- Shorten the feedback loop between shipping and learning

### Typical Communication
- Metrics review sessions with Product Manager and Project Manager
- Data reports and dashboards shared at iteration reviews
- Async annotations and alerts for significant data trends

### Interactions with Other Roles
- **Product Manager**: partners on goal-setting, success metrics, and roadmap prioritization informed by data.
- **Developers**: coordinates on analytics instrumentation and data quality.
- **Project Manager**: provides progress metrics and outcome data for stakeholder reporting.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

