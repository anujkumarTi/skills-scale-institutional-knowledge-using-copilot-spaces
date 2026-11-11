# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises. Roles may be combined or shared to fit a project's size and needs, but each responsibility and decision should have a clearly identified owner.

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

## QA / Test Engineers

### Role Summary
QA / Test Engineers plan and coordinate quality validation so delivered work meets acceptance criteria and is ready for release. This role is especially useful for projects with complex integrations, critical user journeys, or formal quality requirements.

### Responsibilities
- Define an appropriate test approach, including unit, integration, end-to-end, and exploratory testing as needed
- Review acceptance criteria for testability and identify coverage gaps
- Coordinate test execution and record defects, quality risks, and results
- Verify fixes and communicate release-blocking quality concerns

### Goals
- Detect important issues early and provide clear evidence of product quality
- Ensure critical flows and agreed acceptance criteria are validated

### Typical Communication
- Test plans, defect reports, and release-readiness summaries
- Collaboration during refinement, implementation, and test cycles

### Interactions with Existing Roles
- Works with Product Managers to clarify acceptance criteria and expected behavior
- Partners with Developers on testability, test automation, defect triage, and fix verification
- Coordinates coverage, timelines, and quality risks with the Project Manager
- Shares release-readiness findings with the Release / Operations Lead

---

## UX / Product Designers

### Role Summary
UX / Product Designers research user needs and shape accessible, understandable product experiences. Engage this role when a project changes user workflows, introduces new interaction patterns, or needs design research.

### Responsibilities
- Explore user needs and translate findings into workflows, prototypes, and interaction designs
- Define usability and accessibility considerations for proposed experiences
- Validate designs through user feedback or usability testing
- Maintain design artifacts and communicate design decisions and open questions

### Goals
- Make product experiences useful, understandable, and inclusive
- Reduce usability risk before implementation

### Typical Communication
- Research summaries, design reviews, prototypes, and design specifications
- Feedback sessions with users and cross-functional partners

### Interactions with Existing Roles
- Partners with Product Managers to align user needs, product outcomes, and scope
- Collaborates with Developers and Technical Leads to assess feasibility and clarify design intent
- Works with QA / Test Engineers to include usability and accessibility scenarios in validation
- Keeps the Project Manager informed of research or design dependencies that affect milestones

---

## Technical Leads / Architects

### Role Summary
Technical Leads / Architects guide technical design and engineering alignment across a project. This role is useful when work spans multiple components or teams, involves significant technical choices, or introduces integration risk.

### Responsibilities
- Facilitate technical design and document important decisions and trade-offs
- Guide architecture, interfaces, engineering standards, and integration approach
- Identify technical risks, dependencies, and maintainability concerns
- Support Developers with implementation direction and technical problem solving

### Goals
- Deliver a coherent, secure, maintainable technical solution
- Make technical decisions visible and resolve integration issues early

### Typical Communication
- Design proposals, architecture decision records, and technical reviews
- Coordination with engineering contributors and dependent teams

### Interactions with Existing Roles
- Guides Developers while leaving implementation ownership with the appropriate contributors
- Explains feasibility, technical options, and trade-offs to Product Managers to inform scope and prioritization
- Works with Project Managers to surface dependencies, sequencing needs, and technical risks for plans and status reporting
- Coordinates with Security / Privacy Leads and Release / Operations Leads when design choices affect controls or production operations

---

## Security / Privacy Leads

### Role Summary
Security / Privacy Leads advise on security, privacy, and applicable compliance requirements. Involve this role when a project handles sensitive data, changes access or trust boundaries, or has elevated security or privacy risk.

### Responsibilities
- Identify relevant security and privacy requirements and review points
- Assess threats, data handling, and compliance risks within their remit
- Recommend safeguards and review mitigations with the delivery team
- Escalate unresolved high-impact concerns through the agreed security process

### Goals
- Address security and privacy risks early and make required controls verifiable

### Typical Communication
- Risk assessments, review findings, and mitigation guidance
- Security or privacy checkpoints during planning, implementation, and release readiness

### Interactions with Existing Roles
- Advises Developers and Technical Leads on secure design and implementation mitigations
- Works with Product Managers to clarify product requirements and acceptable trade-offs without overriding required controls
- Coordinates security review timing and escalations with the Project Manager
- Shares release-impacting findings with the Release / Operations Lead and follows the security incident process when applicable

---

## Data / Analytics Leads

### Role Summary
Data / Analytics Leads plan instrumentation and measurement so teams can evaluate whether a project achieved its intended outcomes. Engage this role when success depends on product usage, operational data, or other measurable signals.

### Responsibilities
- Translate success metrics into an instrumentation and measurement plan
- Define event, data quality, and reporting requirements with appropriate data governance
- Validate that measurements are available and interpretable after release
- Explain findings, limitations, and trends to the team

### Goals
- Provide trustworthy evidence of project outcomes and support informed iteration

### Typical Communication
- Measurement plans, dashboards, data quality notes, and outcome reviews

### Interactions with Existing Roles
- Partners with Product Managers to define measurable success criteria and interpret results
- Works with Developers to implement and verify instrumentation
- Coordinates data dependencies and reporting milestones with the Project Manager
- Shares post-release signals with Product Managers and the team to inform retrospectives and follow-up work

---

## Release / Operations Leads

### Role Summary
Release / Operations Leads coordinate production readiness and operational handoff. Engage this role for deployments that need operational planning, monitoring, rollback preparation, or coordination with on-call teams.

### Responsibilities
- Confirm deployment prerequisites, operational ownership, and release procedures
- Coordinate monitoring, smoke checks, rollback or mitigation plans, and post-deploy verification
- Ensure operational documentation and support handoffs are ready
- Surface operational risks and incidents through established channels

### Goals
- Make releases observable, recoverable, and supportable in production

### Typical Communication
- Release checklists, deployment plans, operational runbooks, and verification updates
- Coordination with delivery teams and on-call or service owners

### Interactions with Existing Roles
- Coordinates with Project Managers on release timing, dependencies, and stakeholder updates
- Works with Developers and QA / Test Engineers on deployment readiness and post-deploy checks
- Partners with Technical Leads on architecture and operational concerns
- Aligns support handoff and operational communications with Customer Support / Service Representatives

---

## Customer Support / Service Representatives

### Role Summary
Customer Support / Service Representatives bring customer-facing operational needs and feedback into project work. Engage this role when a change affects customer workflows, support contacts, service guidance, or known customer issues.

### Responsibilities
- Share recurring customer questions, reported problems, and service insights during discovery and planning
- Identify support readiness needs and prepare or review customer-facing guidance
- Communicate known issues and escalation routes to relevant support teams
- Bring post-release feedback and emerging issues back to the delivery team

### Goals
- Help customers and support teams understand changes and resolve issues effectively

### Typical Communication
- Support briefs, knowledge-base updates, customer feedback summaries, and issue escalations

### Interactions with Existing Roles
- Shares customer evidence with Product Managers to inform prioritization and validate outcomes
- Coordinates with Project Managers on communication timing, stakeholder impacts, and escalations
- Works with Release / Operations Leads on operational handoffs and known-issue communications
- Provides Developers with clear, actionable reports of customer-impacting defects, and shares validation needs with QA / Test Engineers

---

## Applying These Roles
- Assign roles according to project risk, scope, and team capacity; one person may cover multiple roles, and some projects may not need every persona.
- Make ownership explicit for decisions, deliverables, and handoffs even when responsibilities are combined.
- Involve specialist roles early when their expertise affects scope, acceptance criteria, risk, dependencies, or release readiness.
- Project Managers coordinate the delivery process; Product Managers own product outcomes and priorities. Specialist roles advise and own their defined work, while decisions and escalations follow the team's agreed governance.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
