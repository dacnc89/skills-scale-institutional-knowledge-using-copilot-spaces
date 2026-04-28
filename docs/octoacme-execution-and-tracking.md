# OctoAcme — Execution & Tracking

## Purpose
Guidance for managing day-to-day execution and tracking progress toward project milestones.

## Team Rhythm
- Daily standups (15 min) — focus on progress, blockers, dependencies
- Weekly delivery sync — show progress, updates, and flagged risks
- Demo/Review at the end of each sprint or milestone

## Workflows
- Use the project board (e.g., GitHub Projects) with columns: Backlog, Ready, In Progress, In Review, QA, Done
- Pull Request workflow:
  - Small PRs (<= 400 lines when possible)
  - Include issue link and acceptance criteria in PR description
  - Run automated tests and linting in CI before requesting review
  - Require at least one approval before merging (or team-defined policy)

## Quality & Testing
- Unit tests for new logic
- Integration tests where applicable
- End-to-end smoke tests for critical flows before release
- Security scanning in CI
- Manual QA for feature acceptance when needed

## Reporting & Metrics
- Publish a [Weekly Status Update](templates/weekly-status-update-template.md) every week covering accomplishments, next steps, risks, and blockers.
- Track velocity and burndown
- Monitor success metrics identified in the Project One-pager
- Use dashboards for key signals (errors, latency, usage)

## Decision Tracking
- Log every significant decision (architectural, scope, process) in the [Decision Log](templates/decision-log-template.md).
- Reference decision IDs in PRs and issues to provide context for reviewers.

## Blocker Escalation
- Level 1: Team-level triage in daily standup
- Level 2: PM escalates to Product Lead and dependent teams
- Level 3: Sponsor-level escalation for business-impacting issues

## Execution Checklist
- [ ] Branching and PR conventions documented in repo
- [ ] CI configured for tests and lint
- [ ] Regular demos scheduled
- [ ] Risk register updated weekly (see [Risk Register](templates/risk-register-template.md))
- [ ] [Weekly Status Update](templates/weekly-status-update-template.md) published
- [ ] [Decision Log](templates/decision-log-template.md) kept current

---

## Related Resources

- [Project Planning Guide](octoacme-project-planning.md)
- [Risk Management & Communication](octoacme-risks-and-communication.md)
- [Weekly Status Update Template](templates/weekly-status-update-template.md)
- [Decision Log Template](templates/decision-log-template.md)
- [Definition of Ready / Done Checklist](templates/definition-of-ready-done-checklist.md)
- [Templates Index](templates/README.md)
