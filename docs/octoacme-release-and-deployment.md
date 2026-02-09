# OctoAcme — Release & Deployment Guide

## Purpose
Standardize how OctoAcme releases features to production to reduce risk and improve observability.

## Release Types
- Patch: hotfixes addressing critical production issues
- Minor: incremental features and improvements
- Major: significant functionality or breaking changes

## Pre-release requirements
- All acceptance criteria met and PRs merged
- Passing CI and security scans (DevOps Engineer verification)
- Release notes drafted (Release Manager coordination)
- Rollback / mitigation plan documented (Release Manager)
- Smoke tests prepared
- Stakeholder sign-off obtained (Stakeholder Representatives)

## Deployment Checklist
- [ ] Deployment window scheduled (if needed) - Release Manager
- [ ] Backup or snapshot (if applicable) - DevOps Engineer
- [ ] Deploy to staging and run smoke tests - DevOps Engineer
- [ ] Deploy to production (automated pipeline preferred) - DevOps Engineer
- [ ] Run post-deploy verifications - Release Manager + DevOps Engineer
- [ ] Announce release to stakeholders and support - Release Manager

See also: [octoacme-release-manager-checklist.md](./octoacme-release-manager-checklist.md) for detailed release management steps.

## Rollback & Incident Playbook
- If a deployment fails or causes a critical issue:
  - Trigger incident response and notify on-call (Release Manager + DevOps Engineer)
  - Rollback to last known-good release if necessary (DevOps Engineer)
  - Triage root cause and capture action items (Release Manager coordination)
  - Communicate incident status to stakeholders (Release Manager)

## Release Notes Template
- Release name / number:
- Date:
- Summary:
- Notable changes:
- Migration steps (if any):
- Known issues:
