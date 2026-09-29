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

### Lifecycle Touchpoints
- Planning: estimate and validate technical feasibility
- Execution: implement, review, and iterate
- Testing: collaborate on acceptance criteria and test scenarios
- Release: prepare release notes and deployment verification

### Key Artifacts
- Pull requests and code reviews
- Implementation design docs
- Test suites and test results
- Release verification checklist

### Collaboration
- Works closely with: Technical Lead/Architect, QA/Test Lead, Product Manager
- Escalates technical blockers to: Technical Lead/Architect or Project Manager
- Receives guidance from: Technical Lead/Architect on design; Product Manager on priorities

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

### Lifecycle Touchpoints
- Initiation: define problem, success metrics, and stakeholders
- Planning: prioritize backlog and define acceptance criteria
- Execution: validate progress against success metrics; manage scope
- Release: prepare customer communications and monitor adoption
- Retrospective: analyze impact against metrics; feed learnings to next cycle

### Key Artifacts
- Project One-pager and charter
- Roadmap and backlog prioritization
- Acceptance criteria and user stories
- Success metrics and dashboards
- Release notes and customer communications

### Collaboration
- Works closely with: UX/UI Design Lead, Developers, Project Manager, Customer Support
- Escalates prioritization conflicts to: Sponsor or leadership
- Receives feedback from: Customer Support/Success on adoption and usability

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

### Lifecycle Touchpoints
- Initiation: facilitate kickoff and align stakeholders
- Planning: build timeline, identify dependencies, track risks
- Execution: remove blockers, manage scope, escalate risks
- Release: coordinate deployment activities and communication
- Retrospective: facilitate learning session and track action items

### Key Artifacts
- Project charter and timeline
- Risk register and dependency map
- Project board and status dashboards
- Meeting notes and decision logs
- Retrospective notes and action item tracker

### Collaboration
- Works closely with: All roles; central coordinator
- Escalates to: Sponsor or leadership for resource/priority conflicts
- Receives input from: Technical Lead/Architect on feasibility; QA on quality gates; all roles on risks and blockers

---

## QA/Test Lead

### Role Summary
QA/Test Leads own the quality strategy and execution for a project. They work with Developers, Product Managers, and stakeholders to define, plan, and execute testing that validates acceptance criteria and product quality before release.

### Responsibilities
- Define test strategy and approach (unit, integration, end-to-end, regression)
- Create and maintain test plans and test cases aligned with acceptance criteria
- Coordinate acceptance and regression testing
- Identify and document defects and quality issues
- Partner with Developers on test automation and coverage
- Validate quality gates before release
- Prepare and execute smoke tests and post-deployment verifications

### Goals
- Ensure features meet acceptance criteria before release
- Detect and prevent defects from reaching production
- Maintain and improve product quality over time
- Build confidence in product reliability and usability

### Typical Communication
- Sprint planning and kickoff meetings
- Test plan and strategy reviews
- Defect triage and closure discussions
- Pre-release quality gate reviews
- Retrospectives on test effectiveness

### Lifecycle Touchpoints
- Planning: collaborate on acceptance criteria and test strategy
- Execution: execute test plans; report defects; re-test fixes
- QA gate: validate quality gates before release approval
- Release: prepare and execute smoke tests and post-deploy verification

### Key Artifacts
- Test strategy and test plan
- Test cases and test scripts
- Defect log and regression matrix
- Quality metrics and coverage reports
- Pre-release quality gate checklist

### Collaboration
- Works closely with: Developers (test automation, coverage), Product Manager (acceptance criteria), Project Manager (timeline impact)
- Escalates to: Project Manager if quality gate not met or critical defects found
- Receives guidance from: Product Manager on acceptance criteria; Developers on technical details

---

## UX/UI or Design Lead

### Role Summary
Design Leads translate customer needs and business requirements into intuitive, usable workflows and interfaces. They collaborate with Product Managers, Developers, and stakeholders to validate designs and ensure usability throughout the product lifecycle.

### Responsibilities
- Conduct user research and usability testing
- Create wireframes, mockups, and design specifications
- Validate designs with stakeholders and users
- Collaborate with Developers on implementation feasibility and trade-offs
- Ensure design consistency and accessibility standards
- Support QA and Customer Support with design rationale and edge cases

### Goals
- Deliver intuitive, accessible user experiences
- Reduce usability friction and support costs
- Build customer confidence and satisfaction through good design

### Typical Communication
- Design reviews and feedback sessions
- Kickoff and planning meetings to understand requirements
- Ongoing collaboration with Developers on implementation
- Usability testing and user research findings
- Design system and pattern documentation

### Lifecycle Touchpoints
- Initiation: understand customer needs and success metrics
- Planning: create design specifications and validate with stakeholders
- Execution: review implementation against design; support iteration
- QA: provide design rationale and edge-case guidance to testers
- Release: prepare design documentation for support teams

### Key Artifacts
- User research findings and personas
- Wireframes and mockups
- Design specifications and design system
- Usability test results and recommendations
- Design documentation for handoff to support

### Collaboration
- Works closely with: Product Manager (prioritization), Developers (feasibility), QA (usability validation)
- Escalates to: Product Manager for scope/priority trade-offs
- Receives feedback from: User research; QA and Customer Support on usability issues

---

## Technical Lead/Architect

### Role Summary
Technical Leads guide technical direction, design decisions, and feasibility for a project. They work with Developers, Product Managers, and other leads to identify technical risks, propose solutions, and ensure architecture aligns with business goals.

### Responsibilities
- Evaluate technical feasibility and propose architecture or design approaches
- Make or influence key technical decisions and document rationale
- Identify technical risks and propose mitigations
- Review design and code for quality and alignment with standards
- Mentor Developers and support estimation
- Partner with Security/Compliance Lead on security and compliance requirements
- Guide integration and dependency management

### Goals
- Ensure technical soundness and long-term maintainability
- Reduce technical risk and rework
- Accelerate delivery through clear technical direction

### Typical Communication
- Design reviews and architecture discussions
- Planning sessions for technical estimates and feasibility
- Code reviews and technical mentoring
- Risk and dependency discussions in standups and syncs
- Technical decision documentation

### Lifecycle Touchpoints
- Planning: validate technical feasibility; guide estimation; identify dependencies
- Execution: guide design decisions; review for quality; mentor team
- Testing: partner on test approach and automation strategy
- Release: review release readiness from technical perspective

### Key Artifacts
- Technical design documents and architecture diagrams
- Decision logs and rationale
- Risk register entries and mitigation plans
- Code review summaries and technical standards
- Technical dependency map

### Collaboration
- Works closely with: Developers (mentoring, code review), Project Manager (feasibility, risks), Security/Compliance Lead (security review)
- Escalates to: Project Manager or Product Manager for resource or priority conflicts impacting feasibility
- Receives input from: Developers on implementation challenges; Security/Compliance Lead on requirements

---

## Security/Compliance Lead

### Role Summary
Security/Compliance Leads ensure that projects meet security, privacy, and regulatory requirements. They work with Technical Leads, Developers, and Product Managers to identify requirements, review designs and implementations, and validate compliance before release.

### Responsibilities
- Identify security, privacy, and regulatory requirements for the project
- Review technical designs and code for security vulnerabilities
- Conduct or coordinate security testing and assessments
- Review risk mitigations for security and compliance risks
- Approve release from a security and compliance perspective
- Provide security guidance and training to the team
- Manage incident response and post-incident reviews for security issues

### Goals
- Prevent security breaches and compliance violations
- Embed security into the development process
- Build customer trust through secure, compliant products

### Typical Communication
- Security review meetings and design walkthroughs
- Risk assessments and compliance checklists
- Security testing results and remediation tracking
- Security incident reports and post-incident reviews
- Compliance and security guidance documentation

### Lifecycle Touchpoints
- Planning: identify security and compliance requirements; assess risk
- Execution: review designs and code; validate security controls
- QA: coordinate security testing and vulnerability assessments
- Release: approve release from security and compliance perspective
- Incident response: lead triage and remediation

### Key Artifacts
- Security and compliance requirements checklist
- Security and privacy design reviews
- Vulnerability and remediation log
- Security testing results and approvals
- Post-incident review and action items

### Collaboration
- Works closely with: Technical Lead/Architect (design review), Developers (code review), Project Manager (risk tracking), Release/Operations Lead (deployment controls)
- Escalates to: Project Manager or leadership for unresolved security issues or compliance violations
- Receives input from: Technical Lead/Architect on design; Developers on implementation; Stakeholders on regulatory requirements

---

## Release/Operations or SRE Lead

### Role Summary
Release/Operations Leads manage deployment readiness, operational handoff, and post-release support. They work with Developers, QA, Technical Leads, and support teams to ensure smooth, reliable releases and rapid incident response.

### Responsibilities
- Plan and coordinate deployment activities
- Prepare and validate runbooks and operational procedures
- Manage release notes and deployment communication
- Monitor deployed systems and respond to operational issues
- Coordinate rollback and incident response
- Track observability, metrics, and alerting
- Document lessons learned and operational improvements

### Goals
- Ensure smooth, reliable releases with minimal downtime
- Detect and respond to issues quickly
- Build operational confidence and team resilience

### Typical Communication
- Deployment planning and scheduling
- Runbook and operational procedure reviews
- Release readiness checklists and go/no-go decisions
- Incident response and post-incident reviews
- Operational metrics and alerting discussions

### Lifecycle Touchpoints
- Planning: identify operational dependencies and deployment strategy
- Execution: prepare runbooks and deployment procedures
- QA: coordinate smoke tests and post-deploy verification
- Release: execute deployment, monitor, and coordinate rollback if needed
- Incident response: lead triage, communication, and remediation

### Key Artifacts
- Deployment plan and release notes
- Runbooks and operational procedures
- Rollback plan and incident playbook
- Observability and alerting configuration
- Post-incident review and action items

### Collaboration
- Works closely with: Developers (deployment details), QA (smoke tests), Technical Lead/Architect (architectural concerns), Security/Compliance Lead (security controls)
- Escalates to: Project Manager or leadership for deployment hold-ups or critical incidents
- Receives input from: All team members on operational concerns and post-deployment feedback

---

## Customer Support/Success Representative

### Role Summary
Customer Support/Success Representatives bring customer perspective and feedback into the project lifecycle. They help ensure that features are usable, that customer-impacting risks are understood, and that support readiness is planned before and after release.

### Responsibilities
- Identify customer needs and pain points
- Provide feedback on feature usability and customer impact
- Prepare support materials and knowledge base articles
- Coordinate support readiness before release
- Monitor post-release customer feedback and issues
- Escalate customer-impacting bugs or issues
- Help prioritize improvements based on customer feedback

### Goals
- Ensure customer satisfaction and adoption
- Reduce support costs through good design and documentation
- Build customer advocacy and long-term retention

### Typical Communication
- Feature kickoff and planning meetings
- Support readiness planning and documentation reviews
- Customer feedback and metrics sharing
- Post-release customer issue triage and escalation
- Retrospective input on customer impact

### Lifecycle Touchpoints
- Planning: provide customer insights and support readiness strategy
- Execution: validate design usability; prepare support materials
- QA: test common support scenarios and edge cases
- Release: prepare support team; monitor customer issues
- Retrospective: share customer feedback and adoption metrics

### Key Artifacts
- Customer feedback and needs assessment
- Support readiness checklist and FAQ
- Knowledge base and documentation
- Customer issue log and resolution tracking
- Customer adoption and satisfaction metrics

### Collaboration
- Works closely with: Product Manager (prioritization), Developers (usability issues), QA (test scenarios), Design Lead (UX feedback)
- Escalates to: Product Manager or Project Manager for customer-impacting issues or risks
- Receives input from: Customers; all team members on feature details and support readiness

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Reference the lifecycle touchpoints and collaboration patterns to understand when and how roles interact across the project lifecycle.
- Use the key artifacts to understand what information each role owns and contributes to the project.
