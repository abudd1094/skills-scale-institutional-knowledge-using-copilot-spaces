# OctoAcme — Release Manager Checklist

## Purpose
Guide Release Managers through planning, coordinating, and executing releases for OctoAcme projects.

## Release Planning (T-2 weeks)
- [ ] Confirm release scope and deliverables with Product Manager
- [ ] Identify cross-team dependencies and coordinate timelines
- [ ] Review and update release calendar
- [ ] Schedule deployment windows (if needed)
- [ ] Communicate preliminary release timeline to stakeholders
- [ ] Verify all features have acceptance criteria and DoD

## Pre-Release Preparation (T-1 week)
- [ ] Confirm all PRs merged and acceptance criteria met
- [ ] Verify CI/CD pipelines are green and security scans passed
- [ ] Review release notes with Product and Project Managers
- [ ] Coordinate with DevOps on infrastructure readiness
- [ ] Prepare rollback and mitigation plans
- [ ] Brief support teams on new features and known issues
- [ ] Schedule staging deployment and smoke tests

## Staging Validation (T-3 days)
- [ ] Deploy to staging environment
- [ ] Execute smoke tests and validate critical flows
- [ ] Conduct UAT with Stakeholder Representatives
- [ ] Verify integration points and dependencies
- [ ] Address any blocking issues discovered
- [ ] Obtain sign-off from key stakeholders

## Production Deployment (Release Day)
- [ ] Communicate deployment start time to stakeholders
- [ ] Verify production environment readiness
- [ ] Create backup or snapshot (if applicable)
- [ ] Execute production deployment
- [ ] Monitor deployment progress and logs
- [ ] Run post-deployment verification tests
- [ ] Validate critical user flows and integrations

## Post-Deployment (T+1 hour)
- [ ] Confirm all health checks and metrics are green
- [ ] Monitor error rates, latency, and user feedback
- [ ] Announce successful release to stakeholders and support
- [ ] Update release status in project tracking
- [ ] Address any immediate post-deployment issues
- [ ] Document any deviations from deployment plan

## Post-Release Follow-up (T+1 day)
- [ ] Review release metrics and KPIs
- [ ] Gather feedback from stakeholders and support teams
- [ ] Document lessons learned and process improvements
- [ ] Update release runbooks based on experience
- [ ] Schedule retrospective if significant issues occurred
- [ ] Archive release documentation

## Incident Response (If Needed)
- [ ] Trigger incident response process
- [ ] Notify on-call and relevant stakeholders
- [ ] Assess severity and impact
- [ ] Execute rollback if necessary
- [ ] Coordinate hotfix deployment if rollback not viable
- [ ] Document incident timeline and actions taken
- [ ] Schedule post-incident review
