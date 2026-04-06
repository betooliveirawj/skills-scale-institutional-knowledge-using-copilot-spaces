# OctoAcme — Role Alignment Checklist

## Purpose
Use this checklist at project kickoff (and when team composition changes) to confirm that every role is staffed, expectations are clear, and communication channels are in place before delivery work begins.

## When to use
- During the project kickoff meeting
- When onboarding a new team member mid-project
- At the start of a new release cycle if the team roster has changed

---

## 1. Role Staffing

Confirm that a named individual (or team) has been identified for each relevant role:

- [ ] **Project Manager** — named: _______________
- [ ] **Product Manager** — named: _______________
- [ ] **Developers** — named or team: _______________
- [ ] **QA Lead** — named: _______________
- [ ] **UX Designer** — named: _______________ *(if applicable)*
- [ ] **DevOps / SRE** — named: _______________ *(if applicable)*
- [ ] **Technical Writer** — named: _______________ *(if applicable)*
- [ ] **Business Analyst** — named: _______________ *(if applicable)*
- [ ] **Stakeholders / Sponsor** — named: _______________

> If a role is not applicable for this project, mark it N/A and note who, if anyone, absorbs those responsibilities.

---

## 2. Ownership Confirmation

- [ ] The project one-pager / charter has been reviewed by all roles listed above
- [ ] The [RACI matrix](octoacme-roles-raci.md) has been reviewed and any adjustments noted
- [ ] Each role understands which activities they are **Accountable** for
- [ ] Acceptance criteria ownership is agreed (typically: Product Manager + Business Analyst define, QA Lead validates)
- [ ] Risk register ownership is confirmed (typically: Project Manager owns, all roles contribute)

---

## 3. Communication Cadence

- [ ] Standup / daily sync: frequency ___, platform ___
- [ ] Sprint planning: frequency ___, facilitator ___
- [ ] Sprint review / demo: frequency ___, presenter ___
- [ ] Retrospective: frequency ___, facilitator ___
- [ ] Weekly stakeholder update: owner ___, format ___
- [ ] Incident / escalation channel identified: ___
- [ ] Primary documentation home (repo, wiki, etc.) communicated to all roles: ___

---

## 4. Decision-Making Clarity

- [ ] Go/no-go decisions: accountable role confirmed (typically Sponsor / Stakeholder with PM input)
- [ ] Scope change process documented and communicated
- [ ] Escalation path confirmed:
  - Level 1 — Team triage (PM)
  - Level 2 — Product Lead / PdM
  - Level 3 — Sponsor
- [ ] Design / UX sign-off process agreed with UX Designer and Developers
- [ ] Release sign-off process agreed with QA Lead, DevOps/SRE, and PM

---

## 5. Tooling & Access

- [ ] All roles have access to the project board (GitHub Projects or equivalent)
- [ ] All roles have access to the documentation repo / wiki
- [ ] CI/CD pipeline access configured for DevOps/SRE and Developers
- [ ] Design tool access (Figma, etc.) granted to UX Designer and Developers
- [ ] QA tooling and environments available to QA Lead and Developers

---

## 6. Documentation Kick-off

- [ ] Project one-pager completed and stored in `docs/` or repo root
- [ ] Initial risk register created
- [ ] Backlog seeded with prioritized items and acceptance criteria
- [ ] Definition of Done documented
- [ ] Test plan / QA strategy drafted by QA Lead
- [ ] Release notes template in place (see [Release & Deployment Guide](octoacme-release-and-deployment.md))

---

## References
- [OctoAcme Roles & Personas](octoacme-roles-and-personas.md) — full role descriptions and interaction notes
- [Role Collaboration RACI](octoacme-roles-raci.md) — activity-to-role ownership matrix
- [Project Initiation Guide](octoacme-project-initiation.md)
- [Project Planning Guide](octoacme-project-planning.md)
