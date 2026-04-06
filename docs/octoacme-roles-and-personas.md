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

---

## UX Designer

### Role Summary
UX Designers own the end-to-end user experience — from early research and wireframing through prototyping, accessibility reviews, and final design handoff. They ensure that what gets built is intuitive and aligned with real user needs.

### Responsibilities
- Conduct user research, interviews, and usability testing
- Create user flows, wireframes, and high-fidelity prototypes
- Run accessibility audits and enforce WCAG standards
- Maintain a shared design system or component library
- Hand off detailed specs and assets to Developers
- Validate implemented features against design intent

### Goals
- Reduce friction for end-users through evidence-based design
- Close the gap between product requirements and actual user behavior
- Ensure consistency across screens, flows, and releases

### Typical Communication
- Design reviews with Developers and Product Managers before sprint work begins
- Usability findings shared with Product Manager and stakeholders
- Async design comments via Figma, GitHub issues, or equivalent tooling

### Interactions
- **With Product Managers:** Co-define user stories, acceptance criteria, and success metrics; bring user research evidence to prioritization conversations.
- **With Developers:** Clarify design intent during implementation, participate in PR reviews for UI components, and sign off on visual/interaction fidelity.
- **With QA Lead:** Provide design specs to inform visual regression and accessibility test cases; review flagged UI defects together.
- **With Business Analyst:** Align on business workflows to ensure designs reflect the intended end-to-end process.

---

## DevOps / SRE

### Role Summary
DevOps/SRE engineers own the reliability, scalability, and security of the delivery pipeline and production environment. They bridge the gap between development and operations to enable fast, safe releases.

### Responsibilities
- Design and maintain CI/CD pipelines and deployment automation
- Define and monitor SLOs, SLIs, and error budgets
- Own infrastructure-as-code, environment provisioning, and secrets management
- Lead on-call rotations and incident response
- Author and maintain runbooks, rollback playbooks, and disaster recovery procedures
- Review architectures for reliability and security concerns

### Goals
- Maximize system uptime and minimize mean time to recovery (MTTR)
- Reduce manual toil through automation
- Ensure releases are safe, observable, and reversible

### Typical Communication
- Async updates in incident channels or on-call tooling
- Reliability reviews as part of sprint planning or release readiness
- Weekly syncs with Project Manager on pipeline health and upcoming release windows

### Interactions
- **With Developers:** Pair on CI/CD configuration, review infrastructure changes, and support local development environment tooling.
- **With Project Managers:** Coordinate deployment windows, communicate pipeline outages, and escalate production risks to the risk register.
- **With QA Lead:** Provide staging environments and deployment automation that support automated and manual testing gates.
- **With Product Managers:** Advise on operational constraints (e.g., downtime windows, capacity limits) that may influence roadmap decisions.

---

## Technical Writer

### Role Summary
Technical Writers document processes, APIs, onboarding guides, user-facing help content, and release notes. They ensure that knowledge is accessible, accurate, and maintained across the project lifecycle.

### Responsibilities
- Author and maintain process docs, runbooks, API references, and onboarding materials
- Write and edit release notes for each release
- Work with subject-matter experts to gather accurate content
- Review docs for completeness, consistency, and clarity
- Identify and flag documentation gaps raised during retrospectives or incidents
- Maintain a docs-as-code workflow (PRs, reviews, versioning)

### Goals
- Reduce knowledge silos and onboarding time
- Ensure every process and feature is discoverable and understandable
- Keep documentation up-to-date with the product and process it describes

### Typical Communication
- Embedded in sprint teams or assigned to releases; attends planning and review meetings
- Async collaboration via PR comments and doc review cycles
- Regular syncs with Project Manager and Product Manager to align on upcoming work

### Interactions
- **With Developers:** Gather technical details for API references, architecture decisions, and runbooks; review accuracy of technical content.
- **With Product Managers:** Align documentation scope with feature releases; co-author user-facing help content.
- **With Project Managers:** Document process decisions, meeting outcomes, and project retrospective learnings.
- **With DevOps/SRE:** Maintain incident runbooks and deployment playbooks in sync with operational procedures.

---

## Business Analyst

### Role Summary
Business Analysts bridge business stakeholders and the delivery team. They gather, document, and validate requirements, ensuring that backlog items accurately reflect business intent before development begins.

### Responsibilities
- Elicit and document business requirements through interviews, workshops, and process mapping
- Translate requirements into user stories and acceptance criteria with Product Managers
- Analyze data and workflows to surface inefficiencies and opportunities
- Maintain a requirements traceability matrix where applicable
- Validate delivered solutions against original business requirements
- Support change management and stakeholder communication

### Goals
- Eliminate ambiguity in requirements before development starts
- Ensure business value is measurable and traceable throughout delivery
- Reduce rework caused by misunderstood requirements

### Typical Communication
- Requirements workshops and discovery sessions with stakeholders
- Backlog refinement sessions with Product Managers and Developers
- Written requirement specs or user stories in the project management tool

### Interactions
- **With Product Managers:** Co-own backlog definition; provide business analysis and data to inform prioritization decisions.
- **With Developers:** Clarify acceptance criteria and edge cases during sprint planning and development; triage requirement questions as they arise.
- **With Project Managers:** Ensure that requirements and scope changes are captured in project plans and risk registers.
- **With Stakeholders/Sponsor:** Facilitate workshops and reviews; serve as the liaison between business needs and delivery team.

---

## QA Lead

### Role Summary
The QA Lead owns the quality strategy for the project. They coordinate manual and automated testing, define acceptance gates, and sign off on feature readiness before release.

### Responsibilities
- Define and maintain the test strategy, test plans, and testing standards
- Coordinate manual and automated test execution across sprints
- Triage, prioritize, and track defect resolution
- Establish and enforce Definition of Done criteria related to quality
- Sign off on feature-level and release-level acceptance
- Drive adoption of test automation and continuous testing in CI

### Goals
- Prevent defect leakage to production
- Maintain comprehensive, maintainable test coverage
- Provide clear, data-backed quality signals to the team and stakeholders

### Typical Communication
- QA status updates in sprint reviews and release readiness meetings
- Defect reports and test result summaries in the project tracking tool
- Async collaboration with Developers on test cases and automation

### Interactions
- **With Developers:** Review acceptance criteria for testability; pair on automated test coverage; jointly triage defects.
- **With Product Managers:** Align on acceptance criteria and quality gates; escalate ambiguous requirements before testing begins.
- **With Project Managers:** Report on test progress, defect trends, and release readiness; flag quality risks in the risk register.
- **With DevOps/SRE:** Integrate automated tests into CI/CD pipelines; coordinate staging environment availability for test runs.
- **With UX Designer:** Validate UI and accessibility against design specs; report visual and interaction defects.

---

## Stakeholders / Sponsor

### Role Summary
Stakeholders and Sponsors represent the business interests of the project. The Sponsor authorizes funding and scope; other stakeholders provide domain expertise, inputs, and approvals. Both groups are accountable for ensuring the project delivers expected business outcomes.

### Responsibilities
- Sponsor: authorize project budget, scope, and major decisions; remove organizational blockers
- Stakeholders: provide business requirements, domain expertise, and timely approvals
- Participate in project initiation and key milestone reviews
- Review and accept deliverables that require business sign-off
- Escalate unresolved issues that fall outside the delivery team's authority

### Goals
- Ensure the project delivers measurable business value
- Maintain visibility into project status and risks without micro-managing delivery
- Enable fast decision-making on scope, budget, and priority trade-offs

### Typical Communication
- Monthly or milestone-based stakeholder briefings from the Project Manager
- Formal sign-off and approval requests at decision gates
- Ad-hoc escalations when risks exceed team-level authority

### Interactions
- **With Project Managers:** Receive regular status reports and risk register summaries; provide decisions and approvals at escalation points.
- **With Product Managers:** Align on product vision, priorities, and trade-offs; validate that business outcomes are being met.
- **With Business Analyst:** Participate in requirements workshops and review/approve documented requirements.
- **With Developers (occasional):** May attend demo/review sessions to validate delivered capabilities against business intent.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Cross-reference the [Role Collaboration RACI](octoacme-roles-raci.md) to understand ownership across project activities.
- Use the [Role Alignment Checklist](octoacme-role-alignment-checklist.md) during project kickoff to confirm each role is staffed and aligned.

