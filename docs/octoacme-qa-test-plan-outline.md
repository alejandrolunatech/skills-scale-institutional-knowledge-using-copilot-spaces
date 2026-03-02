# OctoAcme — QA Test Plan Outline

Use this outline to create a QA test plan for each sprint or release. The QA Lead owns this document.

---

## Scope

- **Release / Sprint:** [name or number]
- **Features included:** [list of features or link to milestone]
- **Out of scope:** [explicitly list anything not covered]

## Test Strategy

- **Unit tests:** Owned by Developers; reviewed for coverage during PR review
- **Integration tests:** Identified by QA Lead and Developers; run in CI
- **End-to-end / smoke tests:** Critical user flows; executed on staging prior to release
- **Manual QA:** Required for acceptance of UI-heavy or complex features; documented below

## Test Cases

| ID | Feature | Test Description | Type | Expected Result | Status |
|---|---|---|---|---|---|
| TC-001 | | | Manual / Automated | | Not started |
| TC-002 | | | Manual / Automated | | Not started |

## Acceptance Criteria Review

- [ ] All acceptance criteria from the Product Manager are mapped to at least one test case
- [ ] Edge cases and error paths are covered

## Defect Tracking

- Defects are logged in the project issue tracker with severity (Critical / High / Medium / Low)
- Critical and High defects must be resolved before QA sign-off
- Medium and Low defects may be deferred with Product Manager and Project Manager approval

## QA Sign-off Criteria

- All test cases executed
- No open Critical or High defects
- Product Manager has reviewed and approved any deferred defects
- QA Lead provides formal sign-off to the Release Manager

---

**QA Lead:** ___________________________  
**Sign-off date:** ___________________________
