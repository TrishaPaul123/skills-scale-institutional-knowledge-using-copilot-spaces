# OctoAcme Project Management Documentation

Welcome to the OctoAcme project management documentation suite. This is your central guide to how we run projects, collaborate as teams, and deliver value to our customers.

## Overview

OctoAcme follows an iterative, customer-first approach to project delivery. We emphasize clear ownership, data-informed decisions, and continuous improvement. Our processes span from initial project conception through post-release retrospectives.

### Core Principles

- **Customer-first:** Prioritize customer value and usability
- **Iterative delivery:** Deliver small, testable increments
- **Clear ownership:** Each project has a named Project Manager and Product Lead
- **Data-informed decisions:** Measure impact and iterate based on evidence
- **Psychological safety:** Encourage feedback and learning

## Project Management Phases & Processes

Our projects follow a structured lifecycle:

### 1. Project Initiation
- **Guide:** [Project Initiation Guide](./octoacme-project-initiation.md)
- **Focus:** Problem validation, stakeholder alignment, business case definition
- **Key Deliverable:** Project One-pager
- **When to use:** Whenever a new project idea or feature proposal is ready to be explored

### 2. Project Planning
- **Guide:** [Project Planning](./octoacme-project-planning.md)
- **Focus:** Scope definition, backlog creation, timeline and milestone planning
- **Key Deliverable:** Prioritized backlog with acceptance criteria
- **When to use:** After initiation approval, to turn the project vision into an actionable plan

### 3. Execution & Tracking
- **Guide:** [Execution & Tracking](./octoacme-execution-and-tracking.md)
- **Focus:** Day-to-day delivery, team rhythm, quality assurance
- **Key Deliverable:** Working software increments, test results
- **When to use:** During active development sprints and iterations

### 4. Release & Deployment
- **Guide:** [Release & Deployment Guide](./octoacme-release-and-deployment.md)
- **Focus:** Pre-release validation, deployment strategy, rollback planning
- **Key Deliverable:** Production release with release notes
- **When to use:** When preparing to ship features to production

### 5. Retrospective & Continuous Improvement
- **Guide:** [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)
- **Focus:** Capturing learnings, action items, process improvements
- **Key Deliverable:** Retrospective notes and improvement actions
- **When to use:** After each sprint, release, or important milestone

## Cross-Cutting Concerns

These processes apply throughout the entire project lifecycle:

### Risk Management & Communication
- **Guide:** [Risk Management & Communication](./octoacme-risks-and-communication.md)
- **Focus:** Identifying and tracking risks, stakeholder communication, escalation paths
- **Key Concepts:**
  - Maintain a risk register with impact/likelihood assessment
  - Regular stakeholder updates at weekly or milestone-based cadence
  - Clear escalation paths (Team → PM → Product Lead → Sponsor)

### Roles & Personas
- **Guide:** [OctoAcme Personas](./octoacme-roles-and-personas.md)
- **Focus:** Definitions of key roles and their responsibilities
- **Key Roles:**
  - **Project Manager:** Coordinates delivery, schedules, risk, communications
  - **Product Manager:** Defines outcomes, prioritizes backlog, measures success
  - **Developers:** Implement features, collaborate on design and testability
  - **QA/Testing:** Validate quality and acceptance criteria

## Project Management Overview

For a comprehensive introduction to how OctoAcme runs projects, see the [Project Management Overview](./octoacme-project-management-overview.md).

This document covers:
- Core roles and responsibilities
- Key artifacts and documentation
- High-level project lifecycle
- Communication cadence and team rhythm

## Communication Cadence

OctoAcme maintains regular synchronization across all project stakeholders:

- **Daily:** Team standups (15 min) — progress, blockers, dependencies
- **Weekly:** 
  - Delivery sync — show progress and flagged risks
  - PM + PdM alignment
- **Bi-weekly:** Standup meetings for delivery team (or as agreed)
- **Monthly:** Stakeholder updates
- **Ad-hoc:** Escalations and incident communication as needed

## Quick Start for New Projects

Follow these steps to launch a new project using OctoAcme processes:

1. **Initiate** — Start with the [Project Initiation Guide](./octoacme-project-initiation.md)
   - Validate business need and create a One-pager
   - Identify stakeholders and align on success criteria
   - Confirm team availability and resource needs

2. **Plan** — Move to [Project Planning](./octoacme-project-planning.md)
   - Hold kickoff meeting with team and stakeholders
   - Create prioritized backlog with acceptance criteria
   - Define release timeline and milestones
   - Document Definition of Done

3. **Execute** — Refer to [Execution & Tracking](./octoacme-execution-and-tracking.md)
   - Run daily standups and weekly delivery syncs
   - Use project board with standard columns (Backlog, Ready, In Progress, In Review, QA, Done)
   - Implement quality practices (unit tests, CI, manual QA)
   - Track velocity and monitor success metrics

4. **Manage Risks** — Use [Risk Management & Communication](./octoacme-risks-and-communication.md)
   - Maintain a risk register throughout the project
   - Update risk status at weekly syncs
   - Follow escalation paths for blockers
   - Provide regular stakeholder communications

5. **Release** — Prepare with the [Release & Deployment Guide](./octoacme-release-and-deployment.md)
   - Ensure all acceptance criteria are met
   - Pass CI and security scans
   - Run smoke tests in staging
   - Deploy to production with rollback plan ready

6. **Retrospect** — Capture learnings with [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)
   - Hold retrospective after sprint or release
   - Identify action items with clear owners and due dates
   - Track improvements and celebrate wins

## Key Artifacts

Throughout the project lifecycle, maintain these key documents:

- **Project Charter / One-pager** — Problem, goal, success metrics, stakeholders, timeline
- **Roadmap and Release Plan** — High-level view of features and release dates
- **Sprint/Iteration Backlog** — Prioritized work items with acceptance criteria
- **Risk Register** — Tracked risks with impact, likelihood, mitigation, and owner
- **Definition of Done** — Shared acceptance criteria for all work items
- **Retrospective Notes** — Learnings and action items for continuous improvement

## Documentation Structure

All OctoAcme process documentation lives in the `docs/` folder:

```
docs/
├── README.md (you are here)
├── octoacme-project-management-overview.md
├── octoacme-project-initiation.md
├── octoacme-project-planning.md
├── octoacme-execution-and-tracking.md
├── octoacme-risks-and-communication.md
├── octoacme-release-and-deployment.md
├── octoacme-retrospective-and-continuous-improvement.md
└── octoacme-roles-and-personas.md
```

For process document updates and improvements, use the [Process Doc Update issue template](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml).

## Using These Docs in Your Project

- **Add to your project repo:** Copy or link to these docs in your project repository under `docs/` or `.copilot/`
- **Reference in Copilot Spaces:** Attach these documents to your Copilot Space for context-aware assistance
- **Customize for your team:** Use these templates as a starting point and adapt them to your team's specific needs
- **Keep them current:** Update process docs regularly to reflect your team's evolving practices

## Getting Help

- **New to OctoAcme?** Start with the [Project Management Overview](./octoacme-project-management-overview.md)
- **Starting a project?** Follow the [Quick Start](#quick-start-for-new-projects) section above
- **Questions about a phase?** Refer to the specific phase guide linked above
- **Need to escalate?** See the [Risk Management & Communication](./octoacme-risks-and-communication.md) guide

---

**Last updated:** 2026-08-11
**Maintained by:** OctoAcme Project Management Team
