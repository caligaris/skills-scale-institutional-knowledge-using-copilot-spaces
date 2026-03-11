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

## Scrum Master

### Role Summary
The Scrum Master serves as a servant-leader for the delivery team, facilitating agile ceremonies, removing impediments, and coaching the team on agile practices to sustain a healthy delivery cadence.

### Responsibilities
- Facilitate sprint planning, daily standups, sprint reviews, and retrospectives
- Identify and remove blockers that slow team velocity
- Coach team members on agile principles and practices
- Shield the team from external interruptions during sprints
- Track sprint health metrics (velocity, burndown) and surface trends

### Goals
- Enable the team to deliver predictably and improve continuously
- Maintain a sustainable pace and healthy team dynamics
- Drive measurable improvements from each retrospective

### Typical Communication
- Daily standups and sprint ceremonies
- Blocker escalation to PM and stakeholders
- Retrospective action-item tracking and follow-up

### Interactions with Existing Roles
| Role | Interaction |
|---|---|
| Project Manager | Aligns on delivery commitments, escalates unresolved blockers |
| Product Manager | Helps refine backlog hygiene and acceptance criteria readiness |
| Developers | Coaches on practices, facilitates self-organization and collaboration |
| QA/Testing | Ensures testing is embedded in the sprint, not bolted on |
| Stakeholders | Facilitates sprint review demos and gathers feedback |

**Lifecycle engagement:** Most active during **Execution & Tracking**; also engaged during **Planning** (ceremonies setup) and **Retrospective**.

---

## UX Designer

### Role Summary
UX Designers are responsible for research-driven user experience design, translating user needs and business goals into intuitive interfaces and interaction patterns that the development team can implement.

### Responsibilities
- Conduct user research, usability testing, and stakeholder interviews
- Create wireframes, prototypes, and high-fidelity design specs
- Define UI/UX requirements and acceptance criteria related to usability
- Collaborate with Product Manager to align design decisions with product vision
- Participate in design reviews and provide feedback on implemented features

### Goals
- Ensure features are usable, accessible, and meet user expectations
- Reduce rework by aligning design intent early in the sprint cycle
- Maintain a consistent design system across the product

### Typical Communication
- Design reviews and critique sessions
- Handoff documentation and annotated prototypes
- Usability test findings and recommendations

### Interactions with Existing Roles
| Role | Interaction |
|---|---|
| Product Manager | Co-defines feature requirements; ensures design reflects user value |
| Developers | Provides design specs and clarifies intent during implementation |
| Project Manager | Flags design-related scope or timeline impacts |
| QA/Testing | Validates that implemented UI matches approved designs |
| Stakeholders | Presents prototypes for early feedback and alignment |

**Lifecycle engagement:** Most active during **Initiation** (discovery), **Planning** (design specs), and **Execution** (handoff and review).

---

## DevOps Engineer

### Role Summary
DevOps Engineers own the continuous integration and deployment pipelines, infrastructure reliability, and operational readiness. They bridge development and operations to ensure fast, safe, and repeatable delivery.

### Responsibilities
- Build and maintain CI/CD pipelines and automation tooling
- Manage cloud infrastructure, environments, and configuration
- Monitor system health, performance, and security posture
- Collaborate on deployment runbooks and rollback procedures
- Implement observability solutions (logging, metrics, alerting)

### Goals
- Enable frequent, low-risk deployments to production
- Reduce manual effort and toil through automation
- Maintain high availability and rapid incident recovery

### Typical Communication
- Infrastructure change reviews and post-incident reports
- Deployment window coordination with PM and release lead
- Runbook documentation and on-call handoffs

### Interactions with Existing Roles
| Role | Interaction |
|---|---|
| Developers | Reviews infrastructure needs, supports local and CI environments |
| Project Manager | Coordinates deployment windows and release readiness |
| QA/Testing | Provides staging environments and test automation infrastructure |
| Stakeholders | Reports on system reliability and deployment outcomes |
| Product Manager | Provides observability data to inform product decisions |

**Lifecycle engagement:** Most active during **Execution & Tracking** (CI/CD) and **Release & Deployment**; also engaged during **Planning** (infra sizing).

---

## Stakeholder Sponsor

### Role Summary
The Stakeholder Sponsor is an executive or senior leader who champions the project, provides strategic direction, secures resources, and resolves high-level escalations. They hold ultimate accountability for project outcomes.

### Responsibilities
- Define and communicate strategic intent and success criteria
- Approve project scope, budget, and major changes
- Remove organizational blockers that cannot be resolved at team level
- Review and endorse key milestones and delivery decisions
- Represent the project in leadership forums

### Goals
- Ensure the project delivers business and strategic value
- Provide timely decisions to keep delivery unblocked
- Align the project to organizational priorities

### Typical Communication
- Executive briefings and milestone reviews (monthly or at key gates)
- Escalation responses (as needed, typically 24–48 hr SLA)
- Approval or sign-off emails/documents for major decisions

### Interactions with Existing Roles
| Role | Interaction |
|---|---|
| Project Manager | Receives status reports; provides escalation resolution |
| Product Manager | Aligns product direction with business strategy |
| Developers | Indirect; hears updates during demos and reviews |
| QA/Testing | Reviews critical quality gates before major releases |
| Stakeholders | Coordinates with peer leaders and aligns cross-org dependencies |

**Lifecycle engagement:** Most active during **Initiation** (charter approval) and **Release** (go/no-go decisions); provides governance throughout.

---

## Support Analyst

### Role Summary
Support Analysts are the voice of the customer post-release. They triage user-reported issues, identify patterns in support requests, and provide actionable feedback to improve product quality and documentation.

### Responsibilities
- Triage and investigate user-reported issues and bug reports
- Escalate confirmed defects to the development team with full context
- Maintain support knowledge base articles and user-facing documentation
- Collect and summarize recurring user pain points for product review
- Participate in release readiness reviews to understand new features

### Goals
- Reduce user friction and time-to-resolution for support requests
- Surface systemic issues early before they escalate
- Provide a feedback loop that improves product quality over time

### Typical Communication
- Support ticket summaries and weekly triage reports to PM/PdM
- Bug reports and reproduction steps for the development team
- Release notes review and knowledge base updates at each release

### Interactions with Existing Roles
| Role | Interaction |
|---|---|
| Product Manager | Provides user feedback data to inform backlog prioritization |
| Developers | Submits detailed bug reports and collaborates on reproduction |
| Project Manager | Reports on open issue volume and SLA risks |
| QA/Testing | Shares field-found defects to improve test coverage |
| Stakeholders | Escalates critical user-impacting issues for awareness |

**Lifecycle engagement:** Most active after **Release & Deployment**; also engaged during **Execution** (QA feedback) and **Retrospective** (post-release analysis).

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

## Related Docs
- [Role Interactions & Ownership (RACI)](./octoacme-role-interactions-and-ownership.md) — cross-functional responsibility matrix
- [Intake & Triage Checklist](./octoacme-intake-and-triage-checklist.md) — checklist for validating and routing incoming work
- [Project Management Overview](./octoacme-project-management-overview.md) — lifecycle, principles, and key artifacts

