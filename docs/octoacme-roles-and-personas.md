# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

In addition to the core roles below, these supporting personas often appear in cross-functional project work and help clarify ownership, handoffs, approvals, and delivery coordination.

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

## Technical Leads

### Role Summary
Technical Leads provide technical direction and help the team make sound implementation decisions. They bridge product intent and engineering execution.

### Responsibilities
- Review solution feasibility, architecture, and technical tradeoffs
- Guide implementation approach and non-functional requirements
- Support estimates and identify technical dependencies
- Review complex PRs and technical design proposals
- Escalate technical risks early

### Decision Rights / Ownership
- Own technical direction for the solution space
- Approve or challenge implementation approaches and design tradeoffs
- Do not replace Product Manager ownership of priority or PM ownership of delivery coordination

### Collaboration
- Work with Product Managers and Project Managers on scope tradeoffs and sequencing
- Partner with Developers on implementation details and code reviews
- Align with QA/Testing on testability, risk areas, and release readiness
- Inform Stakeholders about technical constraints and delivery impacts when needed

### Contribution Across the Lifecycle
- Planning: validate feasibility and estimate effort
- Execution: unblock technical issues and review design decisions
- Release: confirm readiness and support go-live risk assessment
- Retrospective: identify engineering improvements and technical follow-ups

---

## Business Analysts

### Role Summary
Business Analysts translate stakeholder needs into clear requirements that teams can build and test against.

### Responsibilities
- Gather and refine business requirements
- Turn broad needs into actionable user stories or acceptance criteria
- Clarify edge cases, assumptions, and business rules
- Support traceability between goals, requirements, and delivery
- Help validate that work meets intended business outcomes

### Decision Rights / Ownership
- Own requirement clarity and completeness
- Recommend acceptance criteria and business rule interpretation
- Do not own prioritization or release decisions

### Collaboration
- Partner with Product Managers to shape problem statements and user stories
- Work with Project Managers to surface scope changes and dependencies
- Support Developers and QA/Testing by answering questions and clarifying expected behavior
- Engage Stakeholders to confirm requirements and resolve ambiguity

### Contribution Across the Lifecycle
- Planning: refine scope and requirements
- Execution: answer questions and update details as needed
- Release: confirm business readiness and acceptance
- Retrospective: capture requirement gaps and process improvements

---

## Design Leads / UX Designers

### Role Summary
Design Leads and UX Designers define the user experience and ensure the solution is usable, coherent, and aligned with customer needs.

### Responsibilities
- Create or refine user flows, wireframes, and interface guidance
- Validate usability and accessibility considerations
- Collaborate on content, interaction patterns, and visual hierarchy
- Support design reviews and feedback cycles
- Help define experience-related acceptance criteria

### Decision Rights / Ownership
- Own user experience recommendations and design artifacts
- Influence interface decisions and usability tradeoffs
- Do not own technical implementation or backlog priority

### Collaboration
- Work with Product Managers to align on customer needs and product goals
- Partner with Developers to ensure designs are implementable
- Coordinate with QA/Testing on UX acceptance criteria and accessibility checks
- Present design choices to Stakeholders when review or approval is needed

### Contribution Across the Lifecycle
- Planning: shape discovery and solution direction
- Execution: iterate on designs and respond to feedback
- Release: confirm the experience matches intent
- Retrospective: identify design process improvements and usability learnings

---

## Release Managers

### Role Summary
Release Managers coordinate release readiness, deployment timing, and communication so changes can move to production safely.

### Responsibilities
- Track release scope, readiness, and dependencies
- Confirm release notes, approvals, and rollout steps are complete
- Coordinate deployment timing with technical and business stakeholders
- Manage go/no-go communication and release checkpoints
- Support rollback or mitigation planning when needed

### Decision Rights / Ownership
- Own release coordination and release readiness tracking
- Can recommend release timing based on readiness and risk
- Do not own product scope or engineering implementation decisions

### Collaboration
- Work with Project Managers to align release plans and milestones
- Partner with Developers and Technical Leads on deployment readiness
- Coordinate with QA/Testing on verification and smoke testing
- Notify Stakeholders about timing, status, and impacts

### Contribution Across the Lifecycle
- Planning: define release windows and milestones
- Execution: track readiness and dependencies
- Release: coordinate deployment and verification
- Retrospective: capture lessons from release issues or delays

---

## Scrum Masters / Delivery Leads

### Role Summary
Scrum Masters and Delivery Leads facilitate team flow, support delivery practices, and help remove blockers so work progresses smoothly.

### Responsibilities
- Facilitate ceremonies and keep delivery rituals effective
- Surface blockers, dependencies, and delivery risks
- Support backlog flow and work-in-progress management
- Encourage healthy team collaboration and continuous improvement
- Help the team maintain predictable delivery cadence

### Decision Rights / Ownership
- Own facilitation of delivery practices and flow improvement
- Can escalate blockers and recommend process adjustments
- Do not own product direction or technical architecture

### Collaboration
- Work with Project Managers on delivery tracking and escalation
- Support Product Managers and Developers in planning and execution
- Coordinate with QA/Testing when work is waiting on validation
- Keep Stakeholders informed when flow issues affect timing

### Contribution Across the Lifecycle
- Planning: support planning readiness and dependency visibility
- Execution: remove impediments and manage flow
- Release: help coordinate cross-functional readiness
- Retrospective: drive action items and improvement follow-through

---

## Support / Operations Representatives

### Role Summary
Support and Operations Representatives bring production, service, and operational perspectives into project work.

### Responsibilities
- Share operational constraints and support readiness needs
- Identify production support impacts, service considerations, and incident patterns
- Help define monitoring, handoff, and runbook requirements
- Participate in release and incident preparedness
- Support post-release review and operational follow-up

### Decision Rights / Ownership
- Own operational readiness inputs and support considerations
- Can flag production risks and support gaps
- Do not own product prioritization or engineering implementation

### Collaboration
- Work with Project Managers on readiness checkpoints and communication
- Partner with Product Managers and Developers on supportability and customer impact
- Coordinate with QA/Testing on production smoke tests and verification
- Inform Stakeholders and incident responders about readiness or service impacts

### Contribution Across the Lifecycle
- Planning: identify support and operational constraints
- Execution: advise on readiness and operational risks
- Release: confirm support coverage and post-deploy monitoring
- Retrospective: contribute incident learnings and operational improvements

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
