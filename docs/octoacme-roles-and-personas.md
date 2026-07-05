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

## Additional Personas (Proposed Additions)

### Technical Program Manager (TPM)
Role Summary:
- TPMs coordinate complex technical delivery that spans multiple teams or domains.

Responsibilities:
- Coordinate cross-team technical delivery and integrated timelines
- Resolve cross-team dependencies and drive technical decisions
- Facilitate technical risk reviews and trade-off discussions
- Track end-to-end delivery milestones and blockers

Goals:
- Ensure timely, coordinated delivery of multi-team initiatives
- Reduce cross-team friction and rework
- Surface technical risks early

Typical Interaction:
- Partners with PM/PdM for milestone alignment
- Works with Engineering Managers, Architects, and Developers to unblock issues
- Escalates architecture or dependency risks to Product Lead or engineering leadership

---

### Delivery Lead
Role Summary:
- Responsible for day-to-day orchestration of a release or sprint’s delivery pipeline.

Responsibilities:
- Enforce Definition of Done and release readiness criteria
- Monitor readiness for demos, QA, and releases
- Coordinate readiness gating and verification steps
- Track delivery progress against plan and surface impediments

Goals:
- Smooth, predictable execution of planned work
- Reduce release friction and last-minute issues

Typical Interaction:
- Works closely with Project Manager for scheduling
- Coordinates with QA for acceptance gating
- Aligns with Release Manager for deployment readiness

---

### Release Manager
Role Summary:
- Owns release planning, execution, and post-release verification.

Responsibilities:
- Plan release windows and coordinate deployment activities
- Prepare rollback/mitigation plans and release notes
- Coordinate staging and production verifications and smoke tests
- Communicate release status to stakeholders

Goals:
- Safe, observable, and well-communicated releases
- Minimize production incidents and recovery time

Typical Interaction:
- Coordinates with CI/CD engineers and SREs
- Works with PM/PdM on release timing and stakeholder communications
- Partners with Product Ops for distribution of release notes and announcements

---

### Product Operations (Product Ops)
Role Summary:
- Operates release communications, templates, dashboards, and process hygiene.

Responsibilities:
- Maintain project templates, dashboards, and artifact discoverability
- Run release communications and status distribution
- Provide reporting and metrics support for retrospectives
- Maintain process artifacts and onboarding materials

Goals:
- Improve cross-team visibility and reduce administrative friction
- Keep process artifacts current and discoverable

Typical Interaction:
- Supports PM/PdM with status reports and dashboards
- Works with Release Manager to publish release notes
- Collects metrics and feedback for retrospectives

---

### UX Researcher / Designer (Product Design)
Role Summary:
- Drives user research, design validation, and UX acceptance criteria.

Responsibilities:
- Conduct user research and usability testing
- Define UX acceptance criteria and provide design assets/specs
- Validate implemented features against UX expectations

Goals:
- Ensure designs meet user needs and are testable
- Reduce UX-related rework after implementation

Typical Interaction:
- Works with PdM to translate research into requirements
- Collaborates with Developers and QA to validate implementation

---

### Site Reliability Engineer (SRE) / Ops Engineer
Role Summary:
- Focuses on production reliability, runbooks, and operational readiness.

Responsibilities:
- Define runbooks and production readiness checks
- Monitor SLIs/SLOs and set operational thresholds
- Participate in incident response and post-incident reviews
- Advise on deployment safety and capacity planning

Goals:
- Maintain production reliability and reduce incident recurrence
- Ensure operational readiness for releases

Typical Interaction:
- Collaborates with Developers and Release Manager on deployment safety
- Works with PM on operational risk items and scheduling

---

### Business Analyst (BA)
Role Summary:
- Translates business needs into clear, testable requirements.

Responsibilities:
- Clarify requirements and map stakeholders to acceptance criteria
- Break down business requirements into backlog items
- Validate that acceptance criteria are measurable and testable

Goals:
- Reduce scope ambiguity and rework
- Improve alignment between business stakeholders and delivery teams

Typical Interaction:
- Partners with PdM and PM to refine scope
- Works with QA to ensure acceptance criteria are testable

---

## Guidance for Adding Personas
- Each persona entry should include: Role Summary, Responsibilities, Goals, and Typical Interaction.
- Include examples of handoffs and RACI-style accountability where practical.
- Keep entries concise; link to deeper role-specific runbooks or templates when available.
