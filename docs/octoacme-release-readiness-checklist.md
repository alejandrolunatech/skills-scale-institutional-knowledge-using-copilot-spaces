# OctoAcme — Release Readiness Checklist

Use this checklist before every production release. The Release Manager is responsible for completing and signing off on this document.

---

## Pre-Release Verification

- [ ] All acceptance criteria for included features are met
- [ ] All PRs for this release are merged into the release branch
- [ ] CI pipeline passes (tests, linting, security scans)
- [ ] QA Lead has provided formal sign-off
- [ ] Release notes are drafted and reviewed
- [ ] Rollback / mitigation plan is documented
- [ ] Deployment window is scheduled and communicated to stakeholders

## Staging Verification

- [ ] Release deployed to staging environment
- [ ] Smoke tests executed on staging and passed
- [ ] Any environment-specific configurations verified

## Risk Review

- [ ] Risk Register reviewed; no unmitigated high-impact risks blocking release
- [ ] Risk Owner has confirmed mitigation status for all active risks

## Communication

- [ ] Pre-release notification sent to stakeholders and support
- [ ] On-call engineer identified for deployment window
- [ ] Rollback trigger criteria defined and understood by the team

## Post-Deployment

- [ ] Deployed to production via automated pipeline (preferred)
- [ ] Post-deploy verifications completed
- [ ] Release announcement sent to stakeholders and support
- [ ] Deployment outcome logged (success / partial / rolled back)

---

**Release Manager sign-off:** ___________________________  
**QA Lead sign-off:** ___________________________  
**Date:** ___________________________
