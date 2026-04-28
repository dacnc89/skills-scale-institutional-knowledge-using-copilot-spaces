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

## QA / Testing Engineers

### Role Summary
QA Engineers validate that features meet acceptance criteria and overall quality standards before release. They design test plans, execute manual and automated tests, and act as the last line of defence before changes reach production.

### Responsibilities
- Design and execute test plans (functional, regression, exploratory, performance)
- Maintain and expand automated test suites
- Raise and triage defects with clear reproduction steps
- Validate acceptance criteria sign-off before items move to Done
- Partner with developers on testability and early defect detection

### Goals
- Prevent regressions and ensure a high-quality user experience
- Reduce time-to-detect and time-to-resolve defects
- Continuously improve test coverage and automation

### Typical Communication
- Sprint planning and daily standups
- Defect reports and test summary emails
- QA sign-off comments on GitHub Issues and PRs

---

## Stakeholders

### Role Summary
Stakeholders are individuals or groups with a vested interest in the project outcome. They provide direction, funding, and approval at key decision gates, and consume updates to make informed business decisions.

### Responsibilities
- Provide business context, requirements, and priorities
- Review and approve key deliverables (charter, roadmap, release)
- Participate in periodic demos and status reviews
- Escalate blockers and make time-sensitive business decisions

### Goals
- Ensure the project delivers measurable business value
- Stay informed without being bottlenecks
- Provide timely input to unblock the delivery team

### Typical Communication
- Monthly stakeholder updates and milestone reviews
- Ad-hoc escalation requests when blockers arise
- Release announcements and post-release reviews

---

## RACI Matrix

Use this matrix to clarify ownership across the main project activities. **R** = Responsible, **A** = Accountable, **C** = Consulted, **I** = Informed.

| Activity | PM | PdM | Developer | QA | Stakeholder |
|---|---|---|---|---|---|
| Define problem statement & success metrics | C | **A/R** | I | I | C |
| Create and approve Project Charter | **A/R** | C | I | I | **A** |
| Prioritize & maintain backlog | C | **A/R** | C | C | C |
| Sprint planning & estimation | **A/R** | C | **R** | **R** | I |
| Technical implementation | I | I | **A/R** | C | I |
| Test planning & QA execution | C | C | C | **A/R** | I |
| Risk identification & mitigation | **A/R** | C | C | C | I |
| Weekly status reporting | **A/R** | C | I | I | **I** |
| Deployment approval & release | **A** | C | **R** | **R** | **A** |
| Retrospective facilitation | **A/R** | C | **R** | **R** | I |

> **Key:** A = single accountable owner. Where two roles share accountability (e.g., A/R), one should be designated primary owner per project.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

---

## Related Resources

- [Project Management Overview](octoacme-project-management-overview.md)
- [Project Initiation Guide](octoacme-project-initiation.md)
- [Kickoff Agenda Template](templates/kickoff-agenda-template.md)
- [Templates Index](templates/README.md)

