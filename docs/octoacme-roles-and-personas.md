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

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

---

## Additional Personas

To reduce ambiguity in cross-functional handoffs and to capture operational responsibilities that surface repeatedly in projects, add the following personas. Each entry includes primary responsibilities and key interactions with existing roles.

- Technical Lead
  - Responsibilities: Provide technical direction and architecture decisions; review designs for scalability and maintainability; ensure code quality and technical debt management; mentor engineers; make trade-off recommendations when technical constraints affect scope.
  - Interactions: Works closely with Developers on implementation details, with PM for feasibility and timelines, with PdM on product/technical trade-offs, and with QA to ensure testability and acceptance criteria can be validated.

- UX Researcher
  - Responsibilities: Plan and run research and usability tests; synthesize user insights and translate them into actionable acceptance criteria; provide validation for design choices.
  - Interactions: Partners with PdM and Product Designers to shape requirements and acceptance criteria; shares findings with Developers and QA to guide implementation and test scenarios.

- Release Manager
  - Responsibilities: Coordinate release windows and cutovers; validate release readiness (merged PRs, passing CI, security scans, rollback plans); own release notes and stakeholder communications; run or approve production deployments when needed.
  - Interactions: Coordinates with PM and Platform Engineer for deployment scheduling, with QA for sign-off on release criteria, and with Stakeholder Representatives for announcements and communications.

- Platform Engineer / SRE
  - Responsibilities: Maintain CI/CD pipelines and environments; own observability, alerts, runbooks, and incident response for platform components; improve system reliability and automation.
  - Interactions: Works with Developers to improve deployability and observability, partners with Release Manager on rollout strategy, and supports On-call/Support during incidents.

- Data Analyst
  - Responsibilities: Define and track success metrics, build dashboards, validate experiment results and releases against acceptance metrics, and support data-driven decisions.
  - Interactions: Works with PdM to define measurable outcomes, with Developers to ensure instrumentation and telemetry are implemented, and with PM to report progress and outcomes.

- Documentation Owner (Process / Docs Owner)
  - Responsibilities: Maintain process and project documentation within docs/ and .copilot/; ensure templates and issue/PR templates are current; own onboarding content for processes; schedule periodic reviews and updates.
  - Interactions: Coordinates with PM for updates to process docs, with Developers and QA for technical documentation, and with Stakeholder Representatives for externally-facing content.

### Adoption notes
- Assign an owner for each persona at project kickoff (may be a named person or role). Document owner in the project README.
- Use the Documentation Owner to coordinate periodic reviews (suggest quarterly) and to shepherd changes through the repository issue template flow (.github/ISSUE_TEMPLATE).
- For small teams where some personas are combined, explicitly list combined responsibilities so nothing is missed.

### How this improves outcomes
- Clarifies who owns cross-cutting concerns (releases, reliability, research, metrics, docs).
- Reduces ambiguity during handoffs and escalations; speeds decision-making.
- Improves onboarding and lowers single-person risks by documenting duties.
- Enables better measurement and accountability for success criteria.
