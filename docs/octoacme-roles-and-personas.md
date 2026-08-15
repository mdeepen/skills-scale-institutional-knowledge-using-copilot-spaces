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

## Additional Personas (proposed additions)

Below are proposed additional personas to add to docs/octoacme-roles-and-personas.md. Each persona entry includes a short role summary, responsibilities, and how they interact with existing roles.

### Release Manager
Role Summary
- Coordinates release schedules and execution, ensures release readiness, and owns rollback/mitigation plans.

Responsibilities
- Maintain the release checklist and release calendar
- Coordinate staging and production deployments
- Approve go/no-go for releases based on defined criteria
- Own rollback and mitigation plans and communicate them to stakeholders
- Coordinate release communication and post-release verification

Interactions
- Works closely with Project Manager (scheduling), Engineering Lead (technical readiness), QA Lead (test sign-off), DevOps (deployment execution), and Product Manager (release scope and timing).

### Engineering Lead / Tech Lead
Role Summary
- Provides technical direction and makes architecture decisions; mentors the engineering team and drives technical risk mitigation.

Responsibilities
- Define architecture and technical approach for features
- Make tradeoff decisions with product and project leads
- Mentor and review engineers' work and designs
- Identify and mitigate technical risks and blockers
- Ensure code quality and maintainability

Interactions
- Collaborates with Product Manager for trade-offs, with QA Lead for testability, with DevOps for deployment considerations, and with Project Manager to surface schedule impacts.

### UX Researcher / Designer
Role Summary
- Validates user needs, informs product direction with research, and defines UX-related acceptance criteria.

Responsibilities
- Conduct user research and usability testing
- Produce designs, interaction specs, and prototypes
- Define UX acceptance criteria and accessibility checks
- Participate in design reviews and handoffs to engineering

Interactions
- Works with Product Manager to align on user outcomes, with Developers to clarify implementation details, and with QA to ensure UX acceptance criteria are testable.

### QA Lead / Test Owner
Role Summary
- Owns test strategy and QA sign-off for releases and major changes.

Responsibilities
- Define test strategy (manual, automated, regression)
- Manage test environments and automation priorities
- Coordinate test plans and acceptance criteria verification
- Provide QA sign-off for releases

Interactions
- Coordinates with Developers for bug fixes and automation, with Release Manager for release readiness, and with Project Manager to schedule QA cycles.

### DevOps / Platform Engineer
Role Summary
- Maintains CI/CD pipelines, environments, and platform reliability; enables smooth deployments and observability.

Responsibilities
- Maintain and evolve CI/CD pipelines and infrastructure-as-code
- Ensure environment parity and manage deployment tooling
- Implement observability and monitoring best practices
- Support incident response and runbook creation

Interactions
- Works with Release Manager for deployment execution, Engineering Lead for platform requirements, Security Liaison for secure configurations, and On-call/Support Lead during incidents.

### Security Liaison
Role Summary
- Ensures security considerations are integrated into the lifecycle and coordinates vulnerability reviews.

Responsibilities
- Run security reviews and threat modeling for features
- Coordinate vulnerability scanning and remediation tracking
- Provide security guidance and acceptance criteria
- Escalate high-risk findings as needed

Interactions
- Works closely with Engineering Lead and DevOps for remediation, with Product Manager to consider security tradeoffs, and with Project Manager for scheduling fixes.

### Analytics / Measurement Owner
Role Summary
- Defines telemetry and success metrics; ensures data is in place to evaluate outcomes.

Responsibilities
- Define metrics, dashboards, and instrumentation plans
- Validate telemetry implementations and measurement integrity
- Support experiment tracking and analysis
- Advise on metric-based acceptance criteria

Interactions
- Works with Product Manager to define success metrics, with Engineers to implement instrumentation, and with PM to ensure metric readiness for releases.

### On-call / Support Lead
Role Summary
- Responsible for production incident triage, runbooks, and post-incident follow-up.

Responsibilities
- Triage production incidents and coordinate immediate response
- Maintain runbooks and escalation paths
- Coordinate incident communications and postmortem activities
- Track action items from incidents

Interactions
- Coordinates with DevOps and Engineering Lead during incidents, with Project Manager and Product Manager for stakeholder updates, and with Release Manager if rollbacks are required.

### Stakeholder Representative
Role Summary
- Represents business or cross-functional stakeholder interests and participates in prioritization and acceptance.

Responsibilities
- Provide business context and approvals for scope and acceptance
- Help prioritize requests and provide timely feedback
- Participate in scheduled stakeholder reviews and demos

Interactions
- Works with Product Manager and Project Manager on prioritization and acceptance, and with the team for clarifications and approvals.

---

## Implementation suggestions
- For each persona include: a short summary, key responsibilities, decision rights (where applicable), and primary interactions with existing roles.
- Consider adding a simple RACI (Responsible, Accountable, Consulted, Informed) matrix for cross-cutting activities (releases, incidents, security reviews, analytics tracking) to make accountability explicit.
- Keep entries concise and include links to runbooks or templates where applicable.
