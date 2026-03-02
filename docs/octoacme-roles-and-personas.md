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

---

## Release Manager

### Role Summary
The Release Manager oversees release planning, coordination, and execution. They own the release lifecycle from scheduling through post-deployment verification and incident communication, ensuring a smooth and reliable delivery process.

### Responsibilities
- Schedule and coordinate releases across teams
- Ensure the deployment checklist is completed before each release
- Draft and distribute release notes to stakeholders and support
- Own communication of release status, including incident and rollback notifications
- Maintain and update the release calendar and deployment windows
- Coordinate with QA Lead on test sign-off prior to release

### Goals
- Reduce release risk and deployment failures
- Improve predictability and transparency of the release process
- Ensure every release meets readiness criteria before going to production

### Typical Communication
- Release readiness reviews with Developers, QA Lead, and Project Manager
- Stakeholder announcements before and after each release
- Incident notifications and post-incident summaries when rollbacks occur

### Interactions with Existing Roles
- **Developers**: Verifies PRs are merged and CI passes; coordinates deployment timing
- **Project Managers**: Aligns release schedule with project milestones and risk status
- **Product Managers**: Communicates feature availability and confirms acceptance criteria are met
- **QA Lead**: Requires QA sign-off before production deployment

---

## QA Lead

### Role Summary
The QA Lead owns the quality assurance process for OctoAcme projects. They establish QA plans, lead test case creation, coordinate manual and automated testing, and provide final sign-off on feature acceptance before release.

### Responsibilities
- Establish and maintain the QA plan for each project or release
- Lead test case creation and coverage reviews
- Coordinate manual and automated testing across features
- Provide formal sign-off confirming acceptance criteria are met
- Identify and track defects; work with Developers on resolution
- Collaborate with Developers to improve test coverage in CI

### Goals
- Ensure all features meet acceptance criteria before release
- Increase automated test coverage to reduce manual effort over time
- Provide clear and timely quality feedback to the team

### Typical Communication
- Test plan reviews with Developers and Project Manager
- QA status updates during sprint reviews and release readiness checks
- Defect reports and acceptance sign-off documentation

### Interactions with Existing Roles
- **Developers**: Reviews code for testability; triages and validates defect fixes
- **Project Managers**: Reports QA status and flags blockers that may affect the release schedule
- **Product Managers**: Validates that implemented features align with product requirements and acceptance criteria
- **Release Manager**: Provides formal QA sign-off required before production deployment

---

## Risk Owner

### Role Summary
The Risk Owner oversees risk identification, tracking, and mitigation for key risks listed in the Risk Register. They ensure that each risk has a defined action plan and that mitigation progress is monitored and escalated when needed.

### Responsibilities
- Maintain and update the Risk Register with current status and mitigation actions
- Assign risk mitigation actions to appropriate team members
- Monitor mitigation progress and follow up on overdue actions
- Escalate unresolved or newly emerging risks to the Project Manager
- Coordinate with stakeholders on risk communication when impact is high

### Goals
- Ensure no critical risk is left untracked or without a mitigation plan
- Reduce the likelihood and impact of identified risks through timely action
- Maintain a clear and up-to-date Risk Register as a single source of truth

### Typical Communication
- Weekly Risk Register review with the Project Manager
- Risk status updates in weekly stakeholder reports
- Escalation notifications when risks exceed agreed thresholds

### Interactions with Existing Roles
- **Project Managers**: Provides risk status updates and escalates issues that require PM-level decisions
- **Product Managers**: Communicates risks that may affect scope, timeline, or product goals
- **Developers**: Works with the team to understand technical risks and validate mitigation approaches
- **Release Manager**: Flags risks that could impact release readiness or require deployment postponement

---

## Ownership Map

The table below shows which roles hold primary ownership (R = Responsible, A = Accountable, C = Consulted, I = Informed) across key project lifecycle activities.

| Activity | Developers | Product Managers | Project Managers | Release Manager | QA Lead | Risk Owner |
|---|---|---|---|---|---|---|
| Sprint / Release Planning | C | A | R | C | C | C |
| Feature Development | R | C | I | I | C | I |
| QA Sign-off | C | C | I | C | R/A | I |
| Release Coordination | C | I | C | R/A | C | C |
| Risk Register Updates | C | I | C | C | I | R/A |
| Stakeholder Communication | I | C | R | C | I | C |
| Incident Response | R | I | C | R/A | C | C |
| Retrospectives | R | C | R/A | C | C | C |

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

