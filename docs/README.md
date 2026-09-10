# OctoAcme Project Management Docs

Welcome to the OctoAcme Project Management Framework. This directory contains comprehensive guidance for running projects across all lifecycle stages—from initiation through retrospective. Use this README as your entry point to discover, understand, and apply OctoAcme processes.

## What is OctoAcme?

OctoAcme is a lightweight, customer-first project management framework that enables teams to deliver value iteratively while maintaining clear communication, accountability, and continuous improvement. It's designed for cross-functional teams building product features, services, and integrations.

## Core Principles

- **Customer-First**: Prioritize customer value and usability in all decisions
- **Iterative Delivery**: Deliver small, testable increments and gather feedback early
- **Clear Ownership**: Each project has named roles, responsibilities, and accountability
- **Data-Informed**: Measure impact and iterate based on evidence and metrics
- **Psychological Safety**: Encourage feedback, learning, and blameless problem-solving

## OctoAcme Process Overview

OctoAcme guides projects through five key stages:

| Stage | Purpose | Key Deliverables |
|-------|---------|------------------|
| **Initiation** | Validate business need and align stakeholders | Project One-pager, stakeholder list, high-level timeline |
| **Planning** | Turn an approved initiative into an actionable plan | Prioritized backlog, milestones, Definition of Done, risk register |
| **Execution** | Build, test, and iterate on features day-to-day | Completed features, passing tests, velocity metrics |
| **Release** | Deploy to production with confidence and visibility | Tested features, release notes, verified deployment, post-deployment metrics |
| **Retrospective** | Capture learnings and drive continuous improvements | Action items, documented lessons, updated processes |

## Process Documents

### 1. [OctoAcme Project Management Overview](./octoacme-project-management-overview.md)
**Start here** for an introduction to OctoAcme's approach, core roles, key artifacts, and the project lifecycle at a glance.
- Core roles (PM, Product Manager, Developers, QA)
- Key artifacts and how to use them
- Communication cadence
- High-level lifecycle flow

### 2. [Project Initiation Guide](./octoacme-project-initiation.md)
**Use when** you have a new project idea or feature proposal ready to explore.
- Validate business need and measurable outcomes
- Identify stakeholders and champions
- Create a Project One-pager
- Make a go/no-go decision

### 3. [Project Planning](./octoacme-project-planning.md)
**Use to** turn an approved initiative into an actionable plan with prioritized backlog and milestones.
- Break work into shippable increments
- Create prioritized backlog with acceptance criteria
- Estimate scope and define Definition of Done
- Identify dependencies and create release plan

### 4. [Execution & Tracking](./octoacme-execution-and-tracking.md)
**Use during** day-to-day execution to manage progress, standups, PRs, quality, and blockers.
- Team rhythm: standups, syncs, demos
- Pull request and code review workflow
- Quality and testing standards
- Blocker escalation procedures

### 5. [Risk Management & Communication](./octoacme-risks-and-communication.md)
**Use to** identify, manage, and communicate risks, dependencies, and status updates.
- Risk Register template and lifecycle
- Stakeholder communication strategies
- Weekly status templates
- Escalation paths for blockers and incidents

### 6. [Release & Deployment Guide](./octoacme-release-and-deployment.md)
**Use to** standardize releases and reduce deployment risk with pre-release checklists and rollback procedures.
- Release types (patch, minor, major)
- Pre-release requirements
- Deployment checklist and post-deploy verification
- Rollback and incident playbook

### 7. [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)
**Use after** sprints, milestones, or incidents to capture learnings and drive process improvements.
- Running a retrospective meeting
- Tracking action items and improvements
- Measuring impact of changes
- Fostering continuous improvement culture

### 8. [OctoAcme Personas](./octoacme-roles-and-personas.md)
**Reference guide** for typical roles, responsibilities, and communication patterns.
- Developer responsibilities and goals
- Product Manager role and communication
- Project Manager coordination and skills
- How personas are used in exercises

## Quick Start by Role

### Product Managers
1. Read [Project Management Overview](./octoacme-project-management-overview.md) for context
2. Use [Project Initiation Guide](./octoacme-project-initiation.md) to validate new ideas
3. Follow [Project Planning](./octoacme-project-planning.md) to create prioritized backlog
4. Reference [Risk Management & Communication](./octoacme-risks-and-communication.md) for stakeholder updates

### Project Managers
1. Review [Project Management Overview](./octoacme-project-management-overview.md) for the big picture
2. Use [Project Planning](./octoacme-project-planning.md) to create project plans
3. Follow [Execution & Tracking](./octoacme-execution-and-tracking.md) for day-to-day coordination
4. Rely on [Risk Management & Communication](./octoacme-risks-and-communication.md) for escalations and status reporting
5. Facilitate [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) sessions

### Developers
1. Read [Project Management Overview](./octoacme-project-management-overview.md) to understand the framework
2. Reference [Execution & Tracking](./octoacme-execution-and-tracking.md) during sprint work (standups, PRs, quality standards)
3. Participate in [Project Planning](./octoacme-project-planning.md) for estimation and scope discussion
4. Attend [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) sessions to share feedback

### QA/Testing Teams
1. Review [Project Management Overview](./octoacme-project-management-overview.md) for context
2. Use [Project Planning](./octoacme-project-planning.md) to define test strategy and acceptance criteria
3. Follow [Execution & Tracking](./octoacme-execution-and-tracking.md) for quality and testing standards
4. Use [Release & Deployment Guide](./octoacme-release-and-deployment.md) for pre-release and smoke test procedures

### All Team Members
- Consult [Risk Management & Communication](./octoacme-risks-and-communication.md) for blocker escalation
- Participate in [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) after milestones
- Reference [OctoAcme Personas](./octoacme-roles-and-personas.md) to understand role expectations

## Key Concepts & Definitions

### Definition of Done (DoD)
Agreed-upon criteria that a work item must meet before it's considered complete. Typically includes: code reviewed, tests written, documentation updated, acceptance criteria met.

### Acceptance Criteria
Clear, testable conditions that describe what "done" looks like for a feature or task. Should be defined during planning and validated during execution.

### Risk Register
A living document that tracks identified risks with impact, likelihood, mitigation plans, and status. Reviewed weekly during execution.

### One-Pager
A lightweight document (1 page) that captures: problem statement, objective, success metrics, stakeholders, timeline, and initial risks. Used for initiation and decision-making.

### Story Points / T-Shirt Sizing
Estimation techniques to help teams understand scope and capacity. Used during planning to create realistic commitments.

## Communication Cadence

- **Daily**: Team standups (15 min) — progress, blockers, dependencies
- **2x Weekly**: Delivery team syncs (focused on execution)
- **Weekly**: PM + Product Lead alignment
- **Weekly**: Risk and blocker review
- **Monthly**: Stakeholder updates
- **Ad-hoc**: Escalations and incident communication

## Contributing to Process Docs

The OctoAcme processes evolve based on team feedback and learnings. To propose updates or new process documentation:

1. Use the [Add Content to Project Management Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) issue template
2. Describe the gap, update, or new content needed
3. Provide suggested content if available
4. Link to related discussions or incidents that motivated the change

All process doc updates should:
- Align with OctoAcme's core principles
- Close a documented gap or improve clarity
- Be reviewed with relevant stakeholders before merging

## How Copilot Spaces Uses These Docs

These process documents are optimized for use with **Copilot Spaces**, which allows teams to ground Copilot's knowledge in curated context. By adding these docs to a Copilot Space:

- Get role-specific guidance aligned with OctoAcme processes
- Receive consistent recommendations based on your team's playbook
- Accelerate onboarding with instant access to institutional knowledge
- Maintain a single source of truth for project management practices

For more on Copilot Spaces, see the main [README](../README.md).

## Getting Help

- **New to OctoAcme?** Start with [Project Management Overview](./octoacme-project-management-overview.md)
- **Starting a new project?** Follow the [Project Initiation Guide](./octoacme-project-initiation.md)
- **In the middle of execution?** Reference [Execution & Tracking](./octoacme-execution-and-tracking.md)
- **Need to escalate a blocker?** Check [Risk Management & Communication](./octoacme-risks-and-communication.md)
- **Finishing a milestone?** Run a [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)

---

**Last updated**: 2026-09-10  
**Framework version**: 1.0  
**Maintained by**: OctoAcme Team
