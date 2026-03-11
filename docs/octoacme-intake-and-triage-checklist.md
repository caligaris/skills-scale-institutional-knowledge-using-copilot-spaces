# OctoAcme — Intake & Triage Checklist

## Purpose
Provide a lightweight, repeatable checklist for evaluating incoming work requests — whether they arrive as feature requests, bug reports, technical improvements, or stakeholder asks — and routing them to the right owner and lifecycle stage.

## When to use
- A new idea or request arrives outside of a planned sprint or roadmap cycle
- A bug or incident requires prioritization against ongoing work
- A stakeholder brings an unplanned ask that may affect scope or timelines

---

## Step 1 — Capture the Request

Use this template when logging a new incoming item:

```
- Title:
- Submitted by (role/name):
- Date received:
- Type: [ ] Feature  [ ] Bug  [ ] Improvement  [ ] Technical Debt  [ ] Other
- Brief description (what is the ask?):
- Expected outcome / definition of done:
- Urgency: [ ] Critical (blocks production)  [ ] High  [ ] Medium  [ ] Low
- Supporting materials (links, screenshots, logs):
```

---

## Step 2 — Initial Triage Checklist

Complete within **one business day** of receipt.

### Completeness
- [ ] Request has a clear problem statement or user story
- [ ] Expected outcome or success criteria are stated
- [ ] Submitter has been identified and is reachable for follow-up

### Impact Assessment
- [ ] Customer or business impact is understood (high / medium / low)
- [ ] Number of users or systems affected is estimated
- [ ] Dependencies on other teams or systems are identified

### Priority Signals
- [ ] Urgency level assigned (Critical / High / Medium / Low)
- [ ] If Critical: incident process triggered and on-call engaged
- [ ] If High: PM and PdM notified within 4 hours

### Routing
- [ ] Assigned to correct owner (see table below)
- [ ] Added to the appropriate backlog, board, or queue
- [ ] Submitter notified of assignment and expected timeline

---

## Routing Guide

| Request Type | Primary Owner | Consulted | Informed |
|---|---|---|---|
| Product feature request | Product Manager (PdM) | Project Manager, UX Designer | Developers, Stakeholders |
| Bug report (production) | Developer (on-call) | DevOps Engineer, QA/Testing | PM, PdM, Support Analyst |
| Bug report (non-production) | QA/Testing | Developer | PM, PdM |
| Security vulnerability | DevOps Engineer | Developer, PM | Sponsor, PdM |
| Infrastructure / reliability | DevOps Engineer | Developer | PM |
| UX / usability issue | UX Designer | PdM, Developer | PM, QA |
| Support escalation | Support Analyst | PdM, Developer | PM, Stakeholders |
| Process improvement | Project Manager / Scrum Master | Team | Sponsor, Stakeholders |

---

## Step 3 — Planning Readiness Gate

Before adding the item to a sprint backlog, confirm all of the following:

### Definition of Ready
- [ ] User story or task description is clear and agreed upon
- [ ] Acceptance criteria are defined and testable
- [ ] Dependencies and blockers are identified and either resolved or tracked
- [ ] Effort estimate provided (story points or T-shirt size)
- [ ] Design assets or specs are available (if applicable — UX Designer sign-off)
- [ ] Infrastructure requirements identified (if applicable — DevOps Engineer confirmed)
- [ ] Test approach or test cases drafted (QA sign-off)
- [ ] No unresolved blockers from external teams

---

## Step 4 — Post-Resolution Checklist

After the work is completed and deployed:

- [ ] Submitter or reporter notified of resolution
- [ ] Support Analyst briefed on resolution and knowledge base updated (if user-facing)
- [ ] Retrospective backlog item created if the issue revealed a systemic gap
- [ ] Metrics or success criteria validated against expected outcome

---

## Escalation Paths

| Situation | Escalate to | Timeline |
|---|---|---|
| Unresolved blocker in triage | Project Manager | Same day |
| Conflicting priorities (PdM vs. PM) | Stakeholder Sponsor | Within 24 hours |
| Security issue not being actioned | DevOps Lead + PM | Immediately |
| Scope creep from a new request | PdM for backlog review | Next planning session |

---

## Related Docs
- [Roles & Personas](./octoacme-roles-and-personas.md) — role definitions and responsibilities
- [Role Interactions & Ownership (RACI)](./octoacme-role-interactions-and-ownership.md) — who owns what across the lifecycle
- [Project Initiation Guide](./octoacme-project-initiation.md) — for larger, project-level intake
- [Execution & Tracking](./octoacme-execution-and-tracking.md) — blocker escalation and sprint workflows
