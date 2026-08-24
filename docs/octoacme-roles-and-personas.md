# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

Project teams may combine responsibilities depending on project size, scope, and risk. The personas below clarify accountability and handoffs; they do not require a separate individual for every role on every project.

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

## QA/Test Lead

### Role Summary
QA/Test Leads define the quality approach for a project and coordinate validation that the delivered work meets acceptance criteria, Definition of Done, and release readiness expectations.

### Responsibilities
- Draft the test strategy and coordinate test execution across iterations
- Validate acceptance criteria with Product Managers and expected behavior with Developers
- Track defects, quality risks, and test coverage gaps
- Support release readiness through smoke tests, regression checks, and defect triage

### Goals
- Catch quality issues before release
- Keep the team aligned on test scope, quality gates, and known risks
- Improve confidence in each shippable increment

### Decision Rights and Accountability
- Accountable for recommending whether quality gates are met
- Escalates unresolved defects or test coverage gaps to the Project Manager and Product Manager
- Does not override product priority or engineering implementation decisions, but informs those decisions with quality evidence

### Artifacts and Lifecycle Touchpoints
- Test plan or QA approach during planning
- Test cases, test results, and defect reports during execution
- Smoke test results and quality sign-off input during release
- Quality lessons learned during retrospective

### Interactions and Handoffs
- Works with Product Managers to clarify acceptance criteria and expected outcomes
- Partners with Developers on testability, automation, defect reproduction, and fixes
- Keeps Project Managers informed about quality risks, blockers, and readiness
- Coordinates with Release/Deployment or Site Reliability Engineers on smoke tests and production verification
- Consults Security/Privacy Representatives when tests cover security or privacy requirements

---

## UX Designer/User Researcher

### Role Summary
UX Designers and User Researchers represent user needs, validate workflows, and help the team design accessible, usable solutions that support the product goals.

### Responsibilities
- Conduct or synthesize user research to inform problem statements and solution options
- Create user journeys, wireframes, prototypes, and usability findings when needed
- Partner with Product Managers on outcomes, priorities, and success metrics
- Collaborate with Developers on feasible, accessible, and consistent experiences

### Goals
- Improve usability and accessibility before implementation is complete
- Reduce rework by validating workflows and assumptions early
- Ensure project decisions stay connected to customer needs

### Decision Rights and Accountability
- Accountable for user experience recommendations and usability evidence
- Recommends design direction, while Product Managers own product priority and Developers own technical implementation details
- Escalates major usability or accessibility risks before release decisions are made

### Artifacts and Lifecycle Touchpoints
- Research notes, personas, journey maps, wireframes, or prototypes during initiation and planning
- Usability findings and design updates during execution
- Accessibility or experience validation input before release
- User feedback themes during retrospective and follow-up planning

### Interactions and Handoffs
- Works with Product Managers to define user problems, acceptance criteria, and success metrics
- Hands validated designs and usability findings to Developers for implementation
- Updates Project Managers on research timing, design dependencies, and decision needs
- Partners with QA/Test Leads on experience-focused test cases
- Aligns with Security/Privacy Representatives when research data or user flows involve sensitive information

---

## Technical Lead/Architect

### Role Summary
Technical Leads and Architects guide technical design, manage major technical trade-offs, and help the delivery team align implementation choices with project scope, quality, and long-term maintainability.

### Responsibilities
- Define or review technical approach, architecture, and integration points
- Identify technical risks, dependencies, and sequencing constraints
- Guide Developers through implementation patterns, code reviews, and technical decisions
- Translate technical trade-offs for Product Managers, Project Managers, and stakeholders

### Goals
- Ensure the solution is reliable, maintainable, and aligned with delivery constraints
- Reduce technical uncertainty before and during execution
- Keep implementation decisions connected to product and release goals

### Decision Rights and Accountability
- Accountable for technical recommendations and architecture decision records when needed
- Sets technical direction within approved scope and constraints
- Escalates trade-offs that affect timeline, cost, security, privacy, or user outcomes to Product Managers and Project Managers

### Artifacts and Lifecycle Touchpoints
- Technical design notes, architecture decision records, and dependency maps during planning
- Code review guidance and technical risk updates during execution
- Operational readiness input before release
- Technical debt and improvement items during retrospective

### Interactions and Handoffs
- Guides Developers on design, implementation, reviews, and technical risk mitigation
- Helps Product Managers understand feasibility, scope trade-offs, and sequencing options
- Gives Project Managers visibility into technical dependencies, blockers, and escalation needs
- Partners with QA/Test Leads on testability and with Release/Deployment or Site Reliability Engineers on operability
- Works with Security/Privacy Representatives to incorporate required controls early

---

## Release/Deployment or Site Reliability Engineer

### Role Summary
Release/Deployment or Site Reliability Engineers support deployment readiness, observability, operational runbooks, rollback preparedness, and production verification.

### Responsibilities
- Prepare or review deployment plans, release checklists, and rollback approaches
- Validate observability, alerting, operational readiness, and support handoffs
- Coordinate deployment windows, smoke tests, and post-deploy verification
- Support incident response and capture operational follow-up items

### Goals
- Reduce release risk and improve recovery options
- Ensure production changes are observable and supportable
- Keep release activities coordinated across delivery, QA, and stakeholders

### Decision Rights and Accountability
- Accountable for operational readiness recommendations and deployment risk input
- May pause or recommend delaying a deployment when rollback, monitoring, or support readiness is insufficient
- Does not own product scope, but informs release timing and risk decisions

### Artifacts and Lifecycle Touchpoints
- Release plan, deployment checklist, runbook, monitoring plan, and rollback plan during planning and release
- Smoke test and post-deploy verification results during release
- Incident notes and operational action items during retrospective

### Interactions and Handoffs
- Works with Developers on deployment automation, configuration, observability, and rollback fixes
- Coordinates with Project Managers on release timing, communication, and risk escalation
- Partners with Product Managers on release scope, known issues, and customer impact
- Collaborates with QA/Test Leads on staging validation, smoke tests, and post-deploy checks
- Involves Security/Privacy Representatives when release activities include sensitive data, access controls, or incident response

---

## Security/Privacy Representative

### Role Summary
Security/Privacy Representatives identify security and privacy requirements, review risks and controls, and help the team address compliance or data protection concerns before release.

### Responsibilities
- Identify security, privacy, compliance, and data-handling requirements
- Review designs, implementation plans, and release readiness for relevant risks
- Recommend controls, mitigations, testing, and documentation
- Support risk acceptance, escalation, or incident response processes when needed

### Goals
- Reduce security and privacy risk throughout the lifecycle
- Ensure requirements are understood early enough to avoid late rework
- Help the team make informed go/no-go decisions for sensitive changes

### Decision Rights and Accountability
- Accountable for security and privacy risk recommendations
- Defines required controls or review criteria for security- or privacy-sensitive work
- Escalates unresolved risks to Project Managers, Product Managers, Technical Leads, and the Business Sponsor/Executive Stakeholder when acceptance decisions are needed

### Artifacts and Lifecycle Touchpoints
- Security and privacy requirements during initiation and planning
- Threat model, privacy review notes, control checklist, or scan findings during execution
- Risk acceptance notes and release readiness input before release
- Security or privacy lessons learned during retrospective

### Interactions and Handoffs
- Works with Product Managers to clarify customer impact, data usage, and policy constraints
- Partners with Developers and Technical Leads on secure design and remediation
- Keeps Project Managers informed about review timing, blockers, and escalation paths
- Coordinates with QA/Test Leads on validation of security and privacy requirements
- Consults Release/Deployment or Site Reliability Engineers on operational controls, monitoring, and incident response readiness

---

## Business Sponsor/Executive Stakeholder

### Role Summary
Business Sponsors or Executive Stakeholders confirm strategic priority, provide resources or approvals, remove escalated impediments, and make business decisions that are outside the delivery team's authority.

### Responsibilities
- Confirm business need, strategic alignment, and success measures
- Provide or approve funding, staffing, and priority trade-offs when needed
- Make or delegate escalated decisions that affect scope, timeline, or risk tolerance
- Receive status, recommendations, and outcomes from Product Managers and Project Managers

### Goals
- Ensure the project supports organizational priorities
- Keep decision-making timely when escalations exceed team authority
- Improve accountability for business outcomes and resource commitments

### Decision Rights and Accountability
- Accountable for sponsor-level go/no-go, funding, and priority decisions
- Owns business risk acceptance when trade-offs exceed Product Manager or Project Manager authority
- Does not manage day-to-day delivery decisions, but resolves escalations and confirms direction

### Artifacts and Lifecycle Touchpoints
- Project one-pager, stakeholder list, and approval decision during initiation
- Funding, staffing, milestone, or priority decisions during planning and execution
- Release communications and outcome reviews during release and retrospective

### Interactions and Handoffs
- Works with Product Managers on strategic outcomes, priority, and success metrics
- Works with Project Managers on escalation paths, status, risks, and decisions needed
- Receives delivery recommendations from Developers, Technical Leads, QA/Test Leads, Release/Deployment or Site Reliability Engineers, and Security/Privacy Representatives through the Product Manager or Project Manager when possible
- Helps resolve cross-functional blockers that affect project commitments

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
