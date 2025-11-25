# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises. Use these entries to clarify ownership, handoffs, and communication touchpoints.

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

### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation

---

## Additional Personas (recommended additions)

Each persona entry below includes Responsibilities and Interactions to make handoffs and accountability explicit.

### Technical Lead / Engineering Manager
Responsibilities:
- Provide technical direction and architecture guidance
- Make or recommend architecture trade-offs
- Review and approve major design proposals
- Coach and mentor developers; support capacity planning

Interactions:
- Works with PM/PdM on technical feasibility and trade-offs
- Partners with Developers on design and implementation
- Coordinates with QA and DevOps on testability and operational readiness

### UX Designer / Researcher
Responsibilities:
- Lead user and usability research
- Produce wireframes, prototypes, and design specifications
- Validate solutions through usability testing

Interactions:
- Collaborates with PdM to define user needs and success criteria
- Hands off design artifacts to Developers; reviews implemented UI
- Works with QA on acceptance criteria for UX and accessibility

### DevOps / Platform Engineer
Responsibilities:
- Build and maintain CI/CD pipelines and infrastructure
- Ensure deployment automation, reliability, and observability
- Maintain platform and operational best practices

Interactions:
- Works with Developers to enable deployments and runbooks
- Partners with Release Manager for deployment windows and rollback plans
- Supports incident triage and post-incident remediation

### Security Lead / Security Engineer
Responsibilities:
- Lead security reviews, threat models, and vulnerability triage
- Provide secure-coding guidance and checklist enforcement
- Coordinate security testing and compliance activities

Interactions:
- Reviews designs and PRs for security concerns
- Escalates high-risk findings to PM/PdM and stakeholders
- Works with DevOps to remediate infrastructure vulnerabilities

### Data Analyst / Data Engineer
Responsibilities:
- Define and instrument success metrics and dashboards
- Ensure data pipelines and data quality for analytics
- Support experiments and measurement plans

Interactions:
- Works with PdM to set and track success metrics
- Provides analysis for planning, retrospectives, and decision-making
- Partners with Developers on instrumentation and schema design

### Release Manager
Responsibilities:
- Coordinate release schedules and run release checklists
- Manage stakeholder communications and release notes
- Ensure rollback and mitigation plans are in place

Interactions:
- Liaisons between PM, DevOps, QA, and Support during releases
- Signals readiness and coordinates go/no-go for production deployments

### Support / Incident Manager
Responsibilities:
- First-line triage for customer-facing incidents
- Communicate incident status to stakeholders and customers
- Produce post-incident reports and follow-ups

Interactions:
- Notifies PM/Product Lead for business-impacting incidents
- Works with DevOps and Security for resolution and root cause analysis
- Feeds recurring issues into backlog prioritization

### Product Operations / Program Manager
Responsibilities:
- Coordinate cross-project priorities and bottlenecks
- Maintain reporting, tooling, and process improvements
- Track organizational-level dependencies and capacity

Interactions:
- Works with PMs and PdMs to align roadmaps and capacity
- Surfaces organizational impediments to leadership

### Accessibility Advocate
Responsibilities:
- Ensure accessibility requirements and testing are part of delivery
- Perform assistive-technology checks and remediation guidance

Interactions:
- Works with Designers, Developers, and QA to meet accessibility standards

---

## How to use these persona definitions
- For each project, list which personas are assigned or consulted and name the person(s).
- Include backups where single-person dependency exists.
- Document key handoff moments (e.g., design handoff, release readiness, incident ownership).

---
