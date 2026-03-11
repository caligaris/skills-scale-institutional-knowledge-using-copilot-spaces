# OctoAcme Project Management Docs

## Overview

OctoAcme's project management approach follows a lightweight, repeatable lifecycle: **Initiation → Planning → Execution → Release → Close/Retrospective**. Work begins when a new idea is ready to be explored, using a short **Project One-pager** to clarify the problem, SMART objective, success metrics, key stakeholders, a rough timeline, and initial risks and dependencies. A decision gate (typically involving the Product Lead and sponsor/stakeholders) confirms that success metrics and priority are clear and that team capacity exists before moving into detailed planning.

Once approved, **Planning** turns the initiative into an actionable backlog and delivery plan. OctoAcme emphasizes breaking work into shippable increments, defining acceptance criteria, estimating scope, and documenting a shared **Definition of Done**. Dependencies and integration points are identified early and tracked alongside a simple **Risk Register** (impact, likelihood, owner, mitigation, status), with a clear expectation that cross-team risks are visible and actively managed throughout the project.

During **Execution & Tracking**, OctoAcme uses a project board (e.g., GitHub Projects) with clear flow states such as Backlog, Ready, In Progress, In Review, QA, and Done. Team rhythm includes short daily standups for progress and blockers, a weekly delivery sync to show progress and surface risks, and demos or reviews at the end of each sprint or milestone. Core roles are explicit: the **Project Manager** coordinates delivery, schedule, risks, and communications; the **Product Manager** defines outcomes and prioritizes; **Developers** implement and test; **QA/Testing** validates quality and acceptance; and **Stakeholders** provide input and approvals.

Quality and release practices are built into the workflow: OctoAcme prefers small pull requests with linked issues and acceptance criteria, requires CI checks (tests, lint, and security scans) before review, and requires at least one approval before merge. Testing expectations scale from unit tests for new logic to integration and end-to-end smoke tests for critical flows, with manual QA used when needed for feature acceptance. Releases use a standardized checklist covering release notes, rollback and mitigation plans, staging smoke tests, post-deploy verification, and stakeholder announcements. Improvement is continuous—retrospectives after sprints, releases, and incidents produce a small number of owned action items that are tracked back in the backlog and revisited in weekly PM/Product alignment.

## Process Documentation

- [Project Management Overview](octoacme-project-management-overview.md)
- [Project Initiation Guide](octoacme-project-initiation.md)
- [Project Planning](octoacme-project-planning.md)
- [Execution & Tracking](octoacme-execution-and-tracking.md)
- [Risk Management & Communication](octoacme-risks-and-communication.md)
- [Release & Deployment Guide](octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)
- [Roles & Personas](octoacme-roles-and-personas.md)
