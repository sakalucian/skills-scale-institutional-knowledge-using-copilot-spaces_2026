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

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

---

# Additional Personas

This section adds commonly used supporting and cross-functional personas to the OctoAcme roles reference. Each persona includes a short Role Summary, Responsibilities, Typical Communication / Interaction with existing roles, and suggested success criteria.

## Technical Lead (Tech Lead)

### Role Summary
Senior engineer responsible for the design and technical direction of a feature, subsystem, or project area.

### Responsibilities
- Own architecture and design decisions for assigned scope
- Review complex PRs and provide technical guidance
- Approve significant technical trade-offs and design patterns
- Mentor and coach developers on implementation and best practices
- Identify and help mitigate technical risks

### Typical Communication / Interaction
- Works with Developers to translate design into code and resolve technical issues
- Partners with Product Manager on feasibility and technical constraints
- Coordinates with Project Manager on delivery risks and timelines
- Collaborates with QA on test strategies for complex features

### Success Criteria
- Systems meet defined reliability and performance targets
- Architectural decisions documented and communicated
- Reduced number of rework cycles due to design gaps

## Engineering Manager (EM)

### Role Summary
People and delivery manager for an engineering team or squad.

### Responsibilities
- Capacity planning and resource allocation
- Performance coaching and career development
- Hiring and team growth decisions
- Escalation of team-level risks and impediments
- Balance technical debt management with roadmap commitments

### Typical Communication / Interaction
- Coordinates with Project Manager on resourcing and timelines
- Works with Product Manager on prioritization and trade-offs
- Aligns with Tech Lead on execution approach and standards

### Success Criteria
- Team meets delivery commitments with sustainable velocity
- Reduced burnout and improved retention metrics
- Clear development and growth plans for team members

## Release Manager

### Role Summary
Coordinates release planning, deployment windows, and rollback/mitigation plans.

### Responsibilities
- Manage release schedule and coordinate cross-team release readiness
- Validate release readiness (checklists, smoke tests, rollbacks)
- Coordinate stakeholders (support, infra, comms) for releases
- Own post-release verifications and learnings

### Typical Communication / Interaction
- Interfaces with Project Manager, SRE/Platform, QA, and Product Marketing for announcements
- Works with Developers to verify deployment automation and runbooks

### Success Criteria
- Releases have clear rollback plans and minimal production incidents
- Post-release verifications completed within defined SLAs

## UX Researcher / Designer

### Role Summary
Owns user research, interaction design, and usability validation for features.

### Responsibilities
- Run user research and usability testing
- Produce interaction designs, prototypes, and design specs
- Define UX acceptance criteria and success metrics
- Collaborate in validating usability during QA and release stages

### Typical Communication / Interaction
- Partner with Product Manager on user needs and prioritization
- Handoff designs and specs to Developers
- Collaborate with QA for UX acceptance tests

### Success Criteria
- Improved usability metrics and reduced user-reported issues
- Design artifacts available and referenced in implementation

## SRE / Platform Engineer

### Role Summary
Ensures reliability, observability, and operational readiness of systems.

### Responsibilities
- Define SLOs and implement monitoring/alerting
- Contribute to runbooks and incident response playbooks
- Capacity planning and performance tuning
- Support deployments and on-call incident response

### Typical Communication / Interaction
- Work with Developers on instrumentation and observability
- Coordinate with Release Manager on deployment safety and canary strategies
- Advise Project Manager on operational risks

### Success Criteria
- Meet SLOs and reduce incident count/severity
- Faster MTTD/MTTR in incidents

## Business Analyst (BA)

### Role Summary
Translates stakeholder needs into clear requirements and acceptance criteria.

### Responsibilities
- Refine requirements and maintain traceability
- Clarify edge cases and functional/non-functional needs
- Assist in stakeholder interviews and acceptance testing

### Typical Communication / Interaction
- Partner with Product Manager on backlog clarity and requirements
- Work with Developers and QA to ensure requirements are implementable and testable

### Success Criteria
- Reduced rework due to ambiguous requirements
- Faster cycle time from requirement to implementation

## Security & Compliance Liaison

### Role Summary
Point of contact for security, privacy, and compliance requirements.

### Responsibilities
- Perform threat modeling and security reviews
- Ensure compliance controls are considered and implemented
- Validate security testing and escalate regulatory risks

### Typical Communication / Interaction
- Work with Tech Lead and SRE on secure architecture
- Coordinate with Project Manager on compliance timelines and risks
- Collaborate with QA for security testing inclusion

### Success Criteria
- Security reviews completed before release
- No regressions in compliance posture

## Customer Support / Customer Success Liaison

### Role Summary
Represents post-release customer feedback and operational issues.

### Responsibilities
- Triage customer-reported issues and identify patterns
- Provide context and impact for prioritization of fixes
- Prepare knowledge base articles and support playbooks

### Typical Communication / Interaction
- Feed customer feedback into Product Manager prioritization
- Coordinate with Release Manager on customer-facing communications
- Work with Developers for triage and fixes

### Success Criteria
- Faster turnaround on customer-reported issues
- Clear support documentation and fewer repeat incidents
