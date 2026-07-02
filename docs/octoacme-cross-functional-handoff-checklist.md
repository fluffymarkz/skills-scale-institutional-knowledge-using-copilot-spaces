# OctoAcme — Cross-Functional Handoff Checklist

## Purpose
Standardize handoffs between roles to reduce missed requirements, unclear ownership, and avoidable rework.

## When to use
- During transition from initiation -> planning
- Before work moves from ready -> in progress
- Before in review -> QA
- Before QA -> release
- During post-release follow-up

## Handoff Checklist Template

### 1) Context and scope
- [ ] Problem statement and objective are documented
- [ ] Scope boundaries and non-goals are explicit
- [ ] Acceptance criteria are complete and testable
- [ ] Priority and target milestone are confirmed

### 2) Ownership and accountability
- [ ] Accountable owner is named
- [ ] Responsible implementation owner(s) are named
- [ ] Consulted roles are identified for critical decisions
- [ ] Informed stakeholders and update cadence are defined

### 3) Delivery readiness
- [ ] Dependencies are identified and tracked
- [ ] Risks are logged with owner and mitigation plan
- [ ] Estimates are documented and team capacity verified
- [ ] Required environments/access are confirmed

### 4) Quality and operational readiness
- [ ] Test approach (unit/integration/e2e) is documented
- [ ] Security/compliance requirements are reviewed
- [ ] Monitoring/logging/alerts are planned
- [ ] Rollback/mitigation plan is prepared

### 5) Communication and release readiness
- [ ] Stakeholder communication plan is prepared
- [ ] Support/CS enablement notes are drafted
- [ ] Release notes draft is prepared
- [ ] Post-release verification owner is assigned

## Minimum Handoff Record
Capture the following in an issue, PR, or project card:
- Handoff date
- From role -> To role
- Summary of scope and acceptance criteria
- Risks/dependencies with owners
- Links to related docs/issues/PRs

## Escalation Rule
If two or more checklist items remain blocked for more than one working day, escalate through:
Team-level -> PM -> Product Lead -> Sponsor
