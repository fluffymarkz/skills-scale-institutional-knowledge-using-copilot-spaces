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

### Interaction with Existing Roles
- With Product Managers: clarify acceptance criteria and trade-offs before implementation.
- With Project Managers: share progress and risks; coordinate delivery and dependencies.

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

### Interaction with Existing Roles
- With Developers: align on implementation scope and acceptance criteria.
- With Project Managers: align priorities with timeline, risks, and stakeholder expectations.

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

### Interaction with Existing Roles
- With Product Managers: align delivery plans to product outcomes and priorities.
- With Developers: remove blockers, coordinate dependencies, and ensure clarity on milestones.

---

## UX Designer / Product Designer

### Role Summary
UX Designers/Product Designers own user experience and interaction design to ensure solutions are usable, accessible, and aligned with customer needs.

### Responsibilities
- Conduct lightweight discovery and usability validation
- Produce wireframes, prototypes, and design specifications
- Partner with Product Managers on problem framing and acceptance criteria
- Support Developers with implementation-ready design guidance

### Goals
- Improve usability, accessibility, and customer satisfaction
- Reduce design-related rework during implementation
- Ensure consistent user experience across features

### Typical Communication
- Design reviews and sprint planning sessions
- Prototype walkthroughs with cross-functional stakeholders
- Ongoing PR and implementation clarification with Developers

### Interaction with Existing Roles
- With Product Managers: refine user problems and prioritize UX outcomes.
- With Developers: clarify design intent, edge cases, and acceptance details.
- With Project Managers: align design deliverables to milestones and dependencies.

---

## Engineering Manager / Technical Lead

### Role Summary
Engineering Managers/Technical Leads provide technical direction, delivery oversight, and engineering quality standards across the project lifecycle.

### Responsibilities
- Define technical approach, architecture guardrails, and sequencing
- Support estimation, dependency planning, and risk mitigation
- Coach Developers and ensure maintainable code quality
- Partner on incident response and retrospective follow-through

### Goals
- Deliver resilient, scalable, maintainable systems
- Improve engineering predictability and quality
- Reduce technical risk and production incidents

### Typical Communication
- Technical design discussions and architecture reviews
- Iteration planning and dependency/risk syncs
- Incident reviews and corrective action follow-ups

### Interaction with Existing Roles
- With Project Managers: align engineering capacity and commitments.
- With Product Managers: evaluate scope/speed/quality trade-offs.
- With Developers: unblock implementation and uphold standards.

---

## QA Engineer / Test Lead

### Role Summary
QA Engineers/Test Leads drive test strategy and quality assurance to reduce defects and improve release confidence.

### Responsibilities
- Define test plans aligned to acceptance criteria and risk
- Coordinate integration and end-to-end testing with defect triage
- Recommend release-readiness quality gates
- Track quality trends and lead improvement actions

### Goals
- Increase release confidence and reduce escaped defects
- Improve test coverage for critical user flows
- Shorten validation feedback loops

### Typical Communication
- Test planning and defect triage sessions
- Release-readiness reviews with cross-functional teams
- Quality metrics updates in weekly syncs

### Interaction with Existing Roles
- With Developers: reproduce defects, verify fixes, and improve coverage.
- With Product Managers: validate expected behavior and acceptance criteria.
- With Project Managers: surface quality risks for go/no-go decisions.

---

## DevOps / SRE

### Role Summary
DevOps/SRE roles ensure reliable build, deployment, and runtime operations with strong observability and resilience practices.

### Responsibilities
- Maintain CI/CD pipelines and deployment standards
- Define monitoring, alerting, and operational readiness checks
- Support rollback planning and incident response
- Improve performance, reliability, and release automation

### Goals
- Improve deployment reliability and mean time to recovery (MTTR)
- Increase operational visibility and response effectiveness
- Reduce manual release steps and operational risk

### Typical Communication
- Release readiness and deployment coordination meetings
- Incident channels and post-incident reviews
- Platform and reliability updates during team syncs

### Interaction with Existing Roles
- With Developers: embed logs/metrics/runbooks early in delivery.
- With Project Managers: align deployment windows and dependencies.
- With Product Managers: provide feasibility and release-risk input.

---

## Security / Compliance Specialist

### Role Summary
Security/Compliance Specialists embed security and compliance requirements into planning, implementation, and release workflows.

### Responsibilities
- Perform threat/risk assessments and define mitigations
- Review security controls in design and implementation
- Guide compliance evidence and policy alignment
- Participate in incident postmortems for security-relevant events

### Goals
- Reduce security vulnerabilities and compliance gaps
- Increase confidence in secure delivery practices
- Improve response readiness for security incidents

### Typical Communication
- Security reviews during planning and design
- Risk and mitigation updates in project syncs
- Compliance evidence check-ins before release milestones

### Interaction with Existing Roles
- With Developers: advise on secure coding and remediation priorities.
- With Project Managers: escalate and track security risks.
- With Product Managers: align security requirements with scope/timeline.

---

## Customer Support / Customer Success Representative

### Role Summary
Customer Support/Success representatives bring customer-facing insights into planning and validate operational readiness for launches.

### Responsibilities
- Provide recurring customer pain points and adoption feedback
- Prepare support enablement content for releases
- Help define known-issue communication and escalation routing
- Monitor post-release customer impact signals

### Goals
- Improve customer experience during and after releases
- Reduce time to resolution for customer-reported issues
- Ensure launch readiness for support-facing teams

### Typical Communication
- Stakeholder updates for launch preparation
- Feedback loops with Product Managers and Developers
- Post-release summaries of customer sentiment and issue patterns

### Interaction with Existing Roles
- With Product Managers: inform prioritization using customer impact data.
- With Project Managers: coordinate launch communications and dependencies.
- With Developers: relay reproducible issues and customer context.

---

## Data Analyst / Analytics Partner

### Role Summary
Data Analysts/Analytics Partners define and measure success metrics, enabling evidence-based decisions throughout planning, execution, and release.

### Responsibilities
- Translate objectives into measurable KPIs and instrumentation requirements
- Build dashboards and recurring insight summaries
- Evaluate outcomes after releases and retrospectives
- Recommend experiments or iteration opportunities from data

### Goals
- Improve decision quality with reliable metrics
- Increase visibility into delivery outcomes and value realization
- Strengthen continuous improvement with measurable feedback

### Typical Communication
- KPI alignment sessions during initiation/planning
- Weekly reporting and trend reviews
- Retrospective support with outcome analysis

### Interaction with Existing Roles
- With Product Managers: define success metrics and decision thresholds.
- With Project Managers: support status reporting with trend data.
- With Developers: clarify tracking requirements and data quality checks.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
