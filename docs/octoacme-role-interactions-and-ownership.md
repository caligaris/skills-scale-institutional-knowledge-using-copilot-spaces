# OctoAcme — Role Interactions & Ownership

## Purpose
This document provides a cross-functional responsibility matrix to clarify who is **Responsible**, **Accountable**, **Consulted**, and **Informed (RACI)** for key project activities across the OctoAcme delivery lifecycle. Use it to reduce ambiguity during handoffs and ensure no activity falls through the gaps.

## How to read this matrix
| Symbol | Meaning |
|---|---|
| **R** | Responsible — does the work |
| **A** | Accountable — owns the outcome; final decision authority |
| **C** | Consulted — provides input before/during the activity |
| **I** | Informed — notified of progress or outcomes |

> Roles: **PM** = Project Manager · **PdM** = Product Manager · **Dev** = Developer · **QA** = QA/Testing · **SM** = Scrum Master · **UX** = UX Designer · **DevOps** = DevOps Engineer · **Sponsor** = Stakeholder Sponsor · **Support** = Support Analyst · **SH** = Stakeholders

---

## Lifecycle RACI Matrix

| Activity | PM | PdM | Dev | QA | SM | UX | DevOps | Sponsor | Support | SH |
|---|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| **Initiation** |
| Define problem statement & success metrics | C | A/R | I | I | I | C | I | C | I | C |
| Stakeholder alignment & charter approval | R | C | I | I | I | I | I | A | I | C |
| Initial risk identification | R | C | C | C | C | I | C | I | I | I |
| Team role assignment | A/R | C | I | I | I | I | I | C | I | I |
| **Planning** |
| Backlog creation & prioritization | C | A/R | C | C | R | C | C | I | C | C |
| Acceptance criteria definition | C | A | R | R | C | R | I | I | I | C |
| Sprint planning & estimation | C | C | R | C | A/R | C | C | I | I | I |
| Definition of Done (DoD) | C | C | R | A/R | C | C | C | I | I | I |
| Release plan & milestones | A/R | C | C | C | C | I | C | C | I | I |
| Infrastructure & environment planning | C | I | C | I | I | I | A/R | I | I | I |
| UX design & prototyping | I | C | C | I | I | A/R | I | I | I | C |
| **Execution & Tracking** |
| Feature implementation | I | I | A/R | C | C | C | C | I | I | I |
| Code reviews & PR approvals | I | I | A/R | C | I | I | C | I | I | I |
| QA / acceptance testing | I | C | C | A/R | I | C | I | I | C | I |
| CI/CD pipeline & automation | I | I | C | C | I | I | A/R | I | I | I |
| Blocker identification & escalation | A/R | C | R | C | R | C | C | I | I | I |
| Sprint ceremonies facilitation | C | C | I | I | A/R | I | I | I | I | I |
| Risk register updates | A/R | C | C | C | C | I | C | I | I | I |
| **Release & Deployment** |
| Pre-release checklist completion | A/R | C | R | R | C | C | R | I | C | I |
| Deployment execution | C | I | C | C | I | I | A/R | I | I | I |
| Go/No-Go decision | C | C | I | C | I | I | C | A | I | C |
| Release notes authoring | C | R | C | C | I | I | I | I | C | I |
| Stakeholder release announcement | A/R | C | I | I | I | I | I | I | I | I |
| **Post-Release & Retrospective** |
| Post-release monitoring | C | I | C | C | I | I | A/R | I | C | I |
| Support triage & issue escalation | I | C | C | C | I | I | C | I | A/R | I |
| User feedback aggregation | I | A/R | I | I | I | C | I | I | R | C |
| Retrospective facilitation | C | C | I | I | A/R | I | I | I | I | I |
| Action-item tracking | A/R | C | C | C | R | I | C | I | I | I |

---

## Key Handoff Points

### Initiation → Planning
- **PM hands off**: approved project charter, stakeholder list, initial risk register
- **PdM hands off**: prioritized problem statements, initial success metrics
- **Sponsor confirms**: go/no-go to enter planning

### Planning → Execution
- **PdM hands off**: prioritized backlog with acceptance criteria
- **UX hands off**: approved design specs and prototypes
- **DevOps hands off**: environment setup and CI/CD pipeline baseline
- **SM confirms**: sprint 1 backlog is sprint-ready per Definition of Done

### Execution → Release
- **QA hands off**: completed test report and sign-off
- **Dev hands off**: all PRs merged, passing CI, release branch cut
- **DevOps hands off**: deployment runbook and rollback plan
- **PM confirms**: release checklist complete, go/no-go with Sponsor

### Release → Post-Release
- **DevOps hands off**: post-deploy monitoring dashboards live
- **PM hands off**: release announcement to stakeholders
- **Support hands off**: knowledge base updated for new features
- **SM schedules**: retrospective within one week of release

---

## Cross-Functional Collaboration Guidelines
- **Design ↔ Engineering**: UX Designers should participate in sprint planning to confirm designs are implementation-ready at least one sprint ahead.
- **QA ↔ DevOps**: Align on test environment availability and automation pipeline gates before sprint start.
- **Support ↔ Product**: Support Analysts join monthly product reviews to surface recurring user pain points.
- **Scrum Master ↔ PM**: Weekly sync to align on delivery health, risks, and any process adjustments needed.
- **Sponsor ↔ PM**: PM provides written status summary before each executive milestone review.

---

## Related Docs
- [Roles & Personas](./octoacme-roles-and-personas.md) — detailed role definitions
- [Intake & Triage Checklist](./octoacme-intake-and-triage-checklist.md) — routing incoming work
- [Project Management Overview](./octoacme-project-management-overview.md) — lifecycle and principles
