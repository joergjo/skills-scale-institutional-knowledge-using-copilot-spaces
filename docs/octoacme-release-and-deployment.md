# OctoAcme — Release & Deployment Guide

## Purpose
Standardize how OctoAcme releases features to production to reduce risk and improve observability.

## Roles
Release activities require coordination across multiple roles:
- **Release Manager**: Plans releases, coordinates activities, and manages release communications. See [Roles & Personas](octoacme-roles-and-personas.md#release-manager) for details.
- **DevOps/Platform Engineer**: Executes deployments, monitors systems, and manages infrastructure. See [Roles & Personas](octoacme-roles-and-personas.md#devops--platform-engineer) for details.
- **QA/Testing**: Provides release sign-off and validates acceptance criteria.
- **Support/Customer Success**: Prepares customer communications and handles release-related inquiries.

For artifact ownership during releases, see the [Role-to-Artifact Ownership Matrix](octoacme-role-to-artifact-ownership.md).

## Release Types
- Patch: hotfixes addressing critical production issues
- Minor: incremental features and improvements
- Major: significant functionality or breaking changes

## Pre-release requirements
- All acceptance criteria met and PRs merged
- Passing CI and security scans
- Release notes drafted
- Rollback / mitigation plan documented
- Smoke tests prepared

## Deployment Checklist
- [ ] Deployment window scheduled (if needed)
- [ ] Backup or snapshot (if applicable)
- [ ] Deploy to staging and run smoke tests
- [ ] Deploy to production (automated pipeline preferred)
- [ ] Run post-deploy verifications
- [ ] Announce release to stakeholders and support

## Rollback & Incident Playbook
- If a deployment fails or causes a critical issue:
  - Trigger incident response and notify on-call
  - Rollback to last known-good release if necessary
  - Triage root cause and capture action items

## Release Notes Template
- Release name / number:
- Date:
- Summary:
- Notable changes:
- Migration steps (if any):
- Known issues:
