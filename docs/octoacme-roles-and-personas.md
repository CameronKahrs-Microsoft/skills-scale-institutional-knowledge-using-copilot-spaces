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

## QA / Test Lead

### Role Summary
QA / Test Leads define and drive the quality strategy across planning, execution, and release. They ensure product increments meet acceptance criteria, quality standards, and release readiness expectations.

### Responsibilities
- Define test approach (manual, automated, regression, exploratory)
- Translate acceptance criteria into test scenarios and quality gates
- Coordinate test execution across feature, integration, and release validation
- Track defects, support triage, and drive resolution priorities with the team
- Report quality status and release readiness risks to PMs and stakeholders

### Decision Rights
- Approve or block release readiness based on agreed quality gates
- Set entry/exit criteria for test phases and regression scope
- Escalate unresolved high-severity defects before release

### Key Deliverables / Artifacts
- Test strategy and test plan
- Test cases and test execution reports
- Defect triage logs and quality dashboards
- Release readiness / go-no-go quality recommendation

### Lifecycle Touchpoints
- **Initiation:** Provide initial quality risks and testability concerns for the one-pager and risk list
- **Planning:** Define QA approach, quality gates, and test milestones in the release plan
- **Execution:** Run planned tests, manage defect lifecycle, and publish quality status updates
- **Release:** Lead final validation and provide release quality sign-off recommendation
- **Retrospective:** Identify recurring defect patterns and propose preventive actions

### Interactions and Handoffs
- Works with **Developers** to clarify acceptance criteria, reproduce defects, and verify fixes
- Aligns with **Product Managers** on acceptance quality thresholds and customer-impacting issues
- Coordinates with **Project Managers** on test timelines, risk escalation, and release decisions

---

## UX Designer / User Researcher

### Role Summary
UX Designers / User Researchers ensure solutions are usable, accessible, and aligned to real user needs. They provide research insights and design direction that shape scope and implementation details.

### Responsibilities
- Conduct user research and synthesize insights for product and delivery teams
- Define user journeys, wireframes, and interaction design guidance
- Partner with Product Managers to refine requirements and acceptance criteria
- Validate designs through usability testing and feedback loops
- Promote accessibility and consistency in user experience decisions

### Decision Rights
- Recommend design direction based on user evidence and usability outcomes
- Approve UX acceptance criteria for interaction behavior and accessibility requirements
- Escalate usability risks that may materially affect adoption or customer outcomes

### Key Deliverables / Artifacts
- Research plans, interview notes, and insight summaries
- Personas, journey maps, wireframes, and prototypes
- UX acceptance criteria and accessibility checklist inputs
- Usability test findings and design iteration recommendations

### Lifecycle Touchpoints
- **Initiation:** Validate problem framing with user evidence and identify target user segments
- **Planning:** Produce design artifacts and UX acceptance criteria for prioritized backlog items
- **Execution:** Partner with Developers during implementation and validate interaction outcomes
- **Release:** Support final UX verification and launch communications for user-facing changes
- **Retrospective:** Share user feedback and adoption insights to guide next iterations

### Interactions and Handoffs
- Works with **Product Managers** to translate customer problems into clear experience goals
- Partners with **Developers** to hand off implementable designs and review built experiences
- Coordinates with **Project Managers** to sequence research, design, and delivery milestones

---

## Technical Lead / Architect

### Role Summary
Technical Leads / Architects guide technical direction, architecture decisions, and engineering standards. They ensure solution design supports scalability, maintainability, and delivery goals.

### Responsibilities
- Define solution architecture and key technical patterns
- Evaluate technical options, trade-offs, and implementation risks
- Align engineering work with non-functional requirements (performance, reliability, security)
- Mentor Developers through design and code reviews
- Coordinate technical dependencies and integration strategy across teams

### Decision Rights
- Approve or reject architectural approaches and major technical design changes
- Set engineering standards and technical quality expectations
- Escalate technical risks that threaten timeline, quality, or operability

### Key Deliverables / Artifacts
- Architecture diagrams and technical design documents
- Technical decision records and integration plans
- Non-functional requirement definitions and validation criteria
- Technical risk assessments and mitigation plans

### Lifecycle Touchpoints
- **Initiation:** Assess feasibility, constraints, and technical risk profile for proposed work
- **Planning:** Define architecture baseline, sequencing, and dependency strategy
- **Execution:** Support implementation decisions, reviews, and technical issue resolution
- **Release:** Validate operational readiness, rollout strategy, and support plans
- **Retrospective:** Review architecture outcomes and identify improvements for future delivery

### Interactions and Handoffs
- Works with **Developers** on design clarity, implementation quality, and code health
- Aligns with **Product Managers** on scope trade-offs and technical feasibility impacts
- Partners with **Project Managers** to communicate dependency and risk implications to plans

---

## Release / Deployment Engineer (Site Reliability)

### Role Summary
Release / Deployment Engineers (or SREs) own release execution reliability, deployment safety, and production stability. They ensure changes move to production through repeatable, observable, and low-risk processes.

### Responsibilities
- Define and maintain deployment workflows, runbooks, and rollback procedures
- Coordinate release windows, change control, and environment readiness checks
- Monitor release health, incident indicators, and post-release stabilization
- Improve reliability through automation, observability, and operational hardening
- Partner with delivery roles to reduce deployment risk and mean time to recovery

### Decision Rights
- Approve release execution readiness based on operational criteria
- Pause or roll back deployments when reliability thresholds are breached
- Require remediation actions for recurring release reliability issues

### Key Deliverables / Artifacts
- Release runbook and deployment checklist
- Environment readiness and change approval records
- Release monitoring dashboards and incident summaries
- Post-release validation and stabilization report

### Lifecycle Touchpoints
- **Initiation:** Identify deployment constraints, infrastructure dependencies, and reliability risks
- **Planning:** Define release strategy, rollout method, and operational readiness criteria
- **Execution:** Prepare environments, validate pipelines, and rehearse rollback plans
- **Release:** Execute deployment, monitor production health, and coordinate response actions
- **Retrospective:** Analyze release outcomes and incidents to improve release reliability

### Interactions and Handoffs
- Works with **Developers** to ensure deployment-safe changes and operational observability
- Coordinates with **Project Managers** on release timing, readiness gates, and stakeholder updates
- Aligns with **Product Managers** on release scope, sequencing, and customer-impact communication

---

## Security / Privacy Representative

### Role Summary
Security / Privacy Representatives ensure product and delivery decisions align with security controls, privacy obligations, and risk tolerance. They embed secure-by-design and privacy-by-design practices across the lifecycle.

### Responsibilities
- Identify security and privacy requirements early in project definition and planning
- Perform threat modeling and data handling risk assessments
- Define required controls for access, encryption, logging, and data retention
- Review high-risk changes and track remediation of security/privacy findings
- Support compliance evidence and audit-ready documentation

### Decision Rights
- Require remediation or compensating controls before release of high-risk changes
- Approve security/privacy readiness for launch based on agreed control criteria
- Escalate unresolved critical security or privacy risks to sponsors and leadership

### Key Deliverables / Artifacts
- Security and privacy requirements checklist
- Threat model and risk assessment outputs
- Control validation evidence and remediation tracking
- Release security/privacy sign-off recommendation

### Lifecycle Touchpoints
- **Initiation:** Assess data sensitivity, compliance constraints, and initial risk posture
- **Planning:** Define controls and security/privacy acceptance criteria in backlog and plans
- **Execution:** Review implementation decisions and validate controls during delivery
- **Release:** Confirm critical findings are resolved and readiness criteria are met
- **Retrospective:** Capture lessons from incidents/findings and improve preventive controls

### Interactions and Handoffs
- Works with **Technical Leads/Architects** and **Developers** on secure design and implementation
- Partners with **Product Managers** to align compliance constraints with customer outcomes
- Coordinates with **Project Managers** for risk escalation, tracking, and decision logging

---

## Business Sponsor / Executive Stakeholder

### Role Summary
Business Sponsors / Executive Stakeholders provide strategic direction, funding sponsorship, and final business accountability. They ensure initiatives remain aligned with organizational priorities and expected outcomes.

### Responsibilities
- Define business outcomes, investment rationale, and success expectations
- Provide executive alignment and remove organizational blockers
- Review progress, risks, and trade-offs at key decision points
- Support prioritization decisions when scope, timeline, or budget conflicts arise
- Champion adoption and organizational readiness for delivered outcomes

### Decision Rights
- Approve project initiation, major scope changes, and go/no-go business decisions
- Prioritize funding and resource allocation across competing initiatives
- Accept outcome trade-offs based on business impact and risk

### Key Deliverables / Artifacts
- Business case and sponsorship approval
- Outcome targets and executive success criteria
- Decision records for scope, timeline, and funding trade-offs
- Stakeholder communications and adoption sponsorship plan

### Lifecycle Touchpoints
- **Initiation:** Validate business need, approve charter direction, and confirm sponsorship
- **Planning:** Review proposed scope, milestones, risks, and resourcing assumptions
- **Execution:** Monitor outcomes and remove escalated organizational constraints
- **Release:** Approve go-live from a business readiness and impact perspective
- **Retrospective:** Review outcome realization and sponsor follow-on improvements

### Interactions and Handoffs
- Works with **Product Managers** to align strategy, value targets, and outcome measurement
- Engages **Project Managers** for governance updates, escalations, and decision cadence
- Depends on **Developers** and delivery leads for execution transparency and risk visibility

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
