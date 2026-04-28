# Definition of Ready & Definition of Done — [Project Name]

Use these checklists to ensure work items meet a consistent quality bar before they enter a sprint (**Definition of Ready**) and before they are considered complete (**Definition of Done**).

> Agree on these definitions at kickoff and revisit them at each retrospective.

---

## Definition of Ready (DoR)

A backlog item is **Ready** to be pulled into a sprint when ALL of the following are true:

### Story / Requirement
- [ ] Clear, user-focused description (e.g., "As a [role], I want [action] so that [outcome]")
- [ ] Acceptance criteria are written, unambiguous, and testable
- [ ] The item is estimated (story points or T-shirt size)
- [ ] Priority is set and agreed with the Product Manager

### Dependencies & Risks
- [ ] All upstream dependencies are resolved or have a clear owner and timeline
- [ ] Any associated risks are logged in the [Risk Register](risk-register-template.md)
- [ ] No unresolved blocking issues

### Technical Clarity
- [ ] Sufficient technical context for developers to start without ambiguity
- [ ] UI/UX designs or API contracts are available (if applicable)
- [ ] Data migration or infrastructure changes are identified (if applicable)

### GitHub Issue Hygiene
- [ ] Linked to the correct GitHub Project board
- [ ] Labelled appropriately (feature / bug / chore / spike)
- [ ] Assigned to the correct milestone or sprint
- [ ] Linked to any related issues or PRs

---

## Definition of Done (DoD)

A work item is **Done** when ALL of the following are true:

### Implementation
- [ ] All acceptance criteria are met
- [ ] Code is peer-reviewed and approved (minimum one reviewer)
- [ ] No unresolved review comments
- [ ] All automated tests pass in CI (unit, integration, lint, security scan)

### Testing & Quality
- [ ] New logic is covered by unit tests
- [ ] Integration tests added or updated where applicable
- [ ] Manual QA sign-off completed (if required by the feature type)
- [ ] No new critical or high-severity security vulnerabilities introduced

### Documentation
- [ ] Inline code comments added for complex logic
- [ ] Public APIs or configuration changes documented
- [ ] `CHANGELOG` or release notes entry created (if applicable)
- [ ] Related process docs updated (e.g., runbooks, architecture diagrams)

### Deployment Readiness
- [ ] Feature flag or rollback plan documented (if applicable)
- [ ] Deployed to staging and smoke-tested
- [ ] Monitoring and alerting verified (if applicable)

### Closure
- [ ] GitHub Issue closed or moved to **Done** column on the project board
- [ ] Stakeholders notified of completion (if required)
- [ ] Any follow-up items captured as new issues

---

## Project-Specific Additions

<!-- Add any additional DoR or DoD criteria unique to this project below. -->

| Checklist | Additional Criterion | Added By | Date |
|-----------|----------------------|----------|------|
| DoR | | | |
| DoD | | | |

---

## Related Resources

- [Project Planning Guide](../octoacme-project-planning.md)
- [Execution & Tracking](../octoacme-execution-and-tracking.md)
- [Kickoff Agenda Template](kickoff-agenda-template.md)
- [Templates Index](README.md)
