# OctoAcme — Role Collaboration RACI Matrix

## Purpose
Map key project activities to roles so that ownership, accountability, consultation, and information flows are unambiguous across the entire project lifecycle.

## RACI Key
| Symbol | Meaning |
|--------|---------|
| **R** | Responsible — does the work |
| **A** | Accountable — owns the outcome; final decision-maker |
| **C** | Consulted — provides input before or during the activity |
| **I** | Informed — kept up to date on progress or decisions |

## Role Abbreviations
| Abbreviation | Role |
|---|---|
| PM | Project Manager |
| PdM | Product Manager |
| Dev | Developers |
| QA | QA Lead |
| UX | UX Designer |
| BA | Business Analyst |
| Ops | DevOps / SRE |
| TW | Technical Writer |
| Stk | Stakeholders / Sponsor |

---

## RACI Matrix

| Activity | PM | PdM | Dev | QA | UX | BA | Ops | TW | Stk |
|---|---|---|---|---|---|---|---|---|---|
| **Initiation** | | | | | | | | | |
| Draft project one-pager / charter | R | C | I | I | C | C | I | I | A |
| Identify and confirm stakeholders | A | C | I | I | I | C | I | I | R |
| Define success metrics | C | A | I | I | C | R | I | I | C |
| Initial risk identification | A | C | C | C | I | C | C | I | I |
| Go / no-go decision | I | C | I | I | I | C | I | I | A |
| **Planning** | | | | | | | | | |
| Sprint / iteration planning | A | C | R | C | C | C | C | I | I |
| Backlog creation and prioritization | C | A | C | C | C | R | I | I | C |
| Write and review acceptance criteria | C | C | R | C | C | A | I | I | I |
| Define Definition of Done | C | A | C | R | C | C | C | I | I |
| Initial test plan / QA strategy | I | C | C | A | I | C | C | I | I |
| Release plan and milestone map | A | C | C | C | I | C | C | I | I |
| **Execution** | | | | | | | | | |
| Feature implementation | I | I | R | C | C | I | C | I | I |
| UX / design review | I | C | C | C | A | I | I | I | I |
| Code review | I | I | A | C | I | I | C | I | I |
| Test execution (manual & automated) | I | I | C | A | C | I | C | I | I |
| Defect triage and resolution | C | C | R | A | C | I | C | I | I |
| Risk register update | A | C | C | C | I | C | C | I | I |
| Weekly status reporting | A | C | I | I | I | I | I | I | I |
| **Release** | | | | | | | | | |
| Release readiness review | A | C | C | C | I | I | C | C | I |
| QA sign-off | I | I | C | A | C | I | C | I | I |
| Deployment to production | C | I | C | I | I | I | A | I | I |
| Smoke testing post-deploy | I | I | C | R | I | I | A | I | I |
| Release notes authoring | C | C | C | C | I | I | I | A | I |
| Stakeholder release announcement | R | C | I | I | I | I | I | C | I |
| Rollback decision | A | C | C | C | I | I | R | I | I |
| **Close & Retrospective** | | | | | | | | | |
| Retrospective facilitation | A | C | R | R | R | R | R | R | I |
| Action item capture and tracking | A | C | C | C | C | C | C | C | I |
| Process documentation update | C | I | I | I | I | I | I | A | I |
| Final stakeholder sign-off / close | R | C | I | I | I | I | I | I | A |

---

## Notes
- A single activity should have exactly one **A** (Accountable). If multiple roles appear as candidates, the Project Manager arbitrates.
- **C** and **I** assignments are defaults; teams can adjust based on project size and structure.
- This matrix covers the activities described in [octoacme-project-initiation.md](octoacme-project-initiation.md), [octoacme-project-planning.md](octoacme-project-planning.md), [octoacme-execution-and-tracking.md](octoacme-execution-and-tracking.md), [octoacme-release-and-deployment.md](octoacme-release-and-deployment.md), and [octoacme-retrospective-and-continuous-improvement.md](octoacme-retrospective-and-continuous-improvement.md).
- For full role descriptions, see [octoacme-roles-and-personas.md](octoacme-roles-and-personas.md).
