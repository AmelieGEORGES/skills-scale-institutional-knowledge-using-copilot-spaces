# OctoAcme Project Management Docs

Welcome to the OctoAcme Project Management Documentation. This guide provides a central entry point for managing projects using OctoAcme's processes and workflows.

## Overview

OctoAcme operates on five core principles that guide all project execution:
- **Customer-first**: Prioritize customer value and usability
- **Iterative delivery**: Deliver small, testable increments
- **Clear ownership**: Each project has named Project Manager and Product Lead
- **Data-informed decisions**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback and learning

### Key Processes

OctoAcme follows a structured five-phase project lifecycle. Projects move through **Initiation** (validating business need and confirming stakeholder alignment), **Planning** (breaking work into shippable increments with clear acceptance criteria), **Execution** (building and iterating with regular standups, weekly syncs, and embedded quality gates), **Release** (deploying to production through a standardized process with pre-release validation), and **Close & Retrospective** (capturing learnings and driving continuous improvement).

Communication and coordination are embedded throughout OctoAcme's workflows via a consistent cadence: daily 15-minute standups focused on progress and blockers, weekly delivery syncs between PM and Product Manager, twice-weekly team standups, and monthly stakeholder updates. Risk management is treated as an ongoing activity with a formal Risk Register reviewed at weekly syncs and escalated through three levels: team-level triage, PM escalation to Product Lead and dependent teams, and sponsor-level escalation for business-impacting issues. Stakeholder communication uses templated status updates (progress, next steps, risks/blockers, and decisions needed) and follows documented escalation paths to ensure transparency and rapid response.

Quality assurance is integral to OctoAcme's execution model, with multiple validation gates built into the workflow. Development practices include small pull requests (≤400 lines when possible), automated CI testing and linting before review, mandatory code review with at least one approval, and unit/integration tests for new logic. Release processes require all acceptance criteria to be met, passing CI and security scans, drafted release notes, a documented rollback plan, and smoke tests on staging before production deployment. Post-release verification and incident playbooks ensure organizational learning from any production issues.

### Core Roles

Three key roles lead OctoAcme projects:
- **Project Managers** coordinate delivery, manage schedules, risks, and communications
- **Product Managers** define outcomes, prioritize the backlog, and measure success
- **Developers** implement features, collaborate on design, and maintain quality standards

## Documentation by Project Phase

### Starting a New Project

- [Project Management Overview](./octoacme-project-management-overview.md) — Introduction to roles, principles, and the complete project lifecycle
- [Project Initiation](./octoacme-project-initiation.md) — Validate business need, align stakeholders, and create a lightweight plan with decision gates

### Planning and Preparation

- [Project Planning](./octoacme-project-planning.md) — Break work into shippable increments, identify dependencies, define Definition of Done, and create release timelines

### Execution and Tracking

- [Execution & Tracking](./octoacme-execution-and-tracking.md) — Day-to-day execution guidance, team rhythm, quality standards, and blocker escalation procedures
- [Risk Management & Communication](./octoacme-risks-and-communication.md) — Identify and manage risks, maintain a risk register, and communicate with stakeholders

### Release and Deployment

- [Release & Deployment](./octoacme-release-and-deployment.md) — Standardized release process, deployment checklist, release notes template, and rollback procedures

### Learning and Improvement

- [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) — Capture learnings, drive actionable improvements, and track impact

### Reference

- [Roles & Personas](./octoacme-roles-and-personas.md) — Define project roles, responsibilities, goals, and communication patterns for Developers, Product Managers, and Project Managers

## Quick Navigation

- **Getting started with a new project?** → Start with [Project Initiation](./octoacme-project-initiation.md), then move to [Project Planning](./octoacme-project-planning.md)
- **Looking for execution and delivery guidance?** → See [Execution & Tracking](./octoacme-execution-and-tracking.md) and [Risk Management & Communication](./octoacme-risks-and-communication.md)
- **Need to release or deploy?** → Review [Release & Deployment](./octoacme-release-and-deployment.md)
- **Want to improve your process?** → Check [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)
- **Understanding your role and responsibilities?** → See [Roles & Personas](./octoacme-roles-and-personas.md)

## Key Principles for Success

1. **Start with clarity** — Use the Project One-pager to confirm business need, success metrics, and stakeholder alignment before planning
2. **Own your dependencies** — Document cross-team dependencies upfront and escalate risks early
3. **Build quality in** — Write tests, conduct code reviews, and validate early; don't test quality in at the end
4. **Communicate consistently** — Weekly syncs, standups, and status updates keep everyone aligned
5. **Learn and iterate** — Retrospectives are mandatory; capture learnings and feed them back into your process

---

For questions or to contribute improvements to this documentation, please open an issue using the [Add Content to Project Management Process Docs](./.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) template.
