# Release Readiness Checklist — [Project Name] v[X.Y.Z]

Complete all items in this checklist before triggering a production deployment. The Release Manager (typically the PM or Tech Lead) signs off once all boxes are checked.

**Release type:** Patch / Minor / Major  
**Target release date:** YYYY-MM-DD  
**Release manager:** @username  
**Tech lead:** @username  

---

## 1. Code & Review

- [ ] All planned issues and PRs are merged to the release branch
- [ ] No open, in-scope PRs remain unreviewed or unmerged
- [ ] All code changes have received at least one peer review and approval
- [ ] No unresolved comments on merged PRs that affect correctness or security

## 2. Testing & Quality

- [ ] All automated tests pass in CI (unit, integration, lint)
- [ ] Security scanning completed with no new critical or high findings
- [ ] End-to-end smoke tests pass on staging
- [ ] Manual QA sign-off completed for user-facing features
- [ ] Regression testing completed (if applicable for the release type)
- [ ] Performance testing completed (if applicable for the release type)

## 3. Acceptance Criteria

- [ ] All acceptance criteria for in-scope items are verified and signed off
- [ ] Product Manager has reviewed and approved the feature set
- [ ] Any known limitations or intentional exclusions are documented

## 4. Documentation

- [ ] Release notes drafted and reviewed (`CHANGELOG` or release doc)
- [ ] API documentation updated (if applicable)
- [ ] User-facing documentation updated (if applicable)
- [ ] Runbooks updated to reflect any infrastructure or configuration changes

## 5. Deployment Preparation

- [ ] Deployment window confirmed with on-call and stakeholders
- [ ] Environment-specific configuration changes reviewed and staged
- [ ] Database migrations tested on a staging environment (if applicable)
- [ ] Feature flags configured correctly for the release
- [ ] Rollback plan documented and verified:
  - Rollback trigger criteria: <!-- e.g., error rate > 1%, P50 latency > Xms -->
  - Rollback steps: <!-- link to runbook or describe steps -->
  - Rollback owner: @username

## 6. Observability & Monitoring

- [ ] Monitoring dashboards and alerts are in place for key signals
- [ ] On-call rotation confirmed and briefed on the release
- [ ] Runbook or playbook linked from the monitoring alert

## 7. Communication

- [ ] Release announcement drafted for stakeholders and support team
- [ ] Support team briefed on new features, known issues, and FAQs
- [ ] External changelog or blog post prepared (if applicable for major releases)

## 8. Post-Deploy Verification Plan

- [ ] Post-deploy smoke test steps documented
- [ ] Success criteria for "release is healthy" defined:
  - <!-- e.g., zero P0/P1 incidents in first 24 hours, error rate < X% -->
- [ ] Owner assigned for post-deploy monitoring window: @username

---

## Sign-Off

| Role | Name | Approved | Date |
|------|------|----------|------|
| Release Manager | | ☐ | |
| Tech Lead | | ☐ | |
| Product Manager | | ☐ | |
| QA Lead | | ☐ | |

---

## Related Resources

- [Release & Deployment Guide](../octoacme-release-and-deployment.md)
- [Risk Register (RAID) Template](risk-register-template.md)
- [Definition of Done Checklist](definition-of-ready-done-checklist.md)
- [Templates Index](README.md)
