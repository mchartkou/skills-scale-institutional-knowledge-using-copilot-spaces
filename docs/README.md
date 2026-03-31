# OctoAcme Project Management Documentation

## Welcome

This folder contains the complete OctoAcme project management framework—a structured, five-phase methodology designed to deliver customer value through iterative development and clear stakeholder alignment. Whether you're starting a new project, executing current work, or improving team processes, these docs provide the guidance and templates you need.

## OctoAcme Project Management Process Overview

### Core Philosophy

OctoAcme operates on five key principles that guide all project work:

- **Customer-first**: Projects are guided by delivering customer value and usability. Everything we build should solve real customer problems and be easy to use.
- **Iterative delivery**: Work is structured in small, testable increments to maximize learning and progress. We deliver value early and often, not all at once.
- **Clear ownership**: Each initiative has a named Project Manager and Product Lead who coordinate work and outcomes. No ambiguity about who's responsible.
- **Data-informed decisions**: Planning and improvements are based on evidence and key metrics. We measure impact and iterate based on what we learn.
- **Psychological safety**: We encourage feedback, celebrate learning from failures, and conduct blameless retrospectives to drive continuous improvement.

### Five-Phase Lifecycle

OctoAcme projects follow a consistent five-phase progression:

1. **Initiation**: Validate business need, identify stakeholders, create a Project One-pager with problem statement, goals, and success metrics. Decision gate: Is this worth pursuing?
2. **Planning**: Break work into shippable increments, create a prioritized backlog with acceptance criteria, define dependencies, and establish a release timeline. Decision gate: Are we ready to execute?
3. **Execution**: Build, test, and review work using a day-to-day cadence of standups, demos, and tracking via GitHub Projects. Move work through columns: Backlog → Ready → In Progress → In Review → QA → Done.
4. **Release**: Deploy features to production following standardized checklists, smoke tests, and rollback protocols. Announce to stakeholders and verify success metrics.
5. **Retrospective & Continuous Improvement**: Capture learnings, identify what went well and what to improve, and convert insights into actionable improvements for the next cycle.

### Key Roles & Communication

**Core Roles:**
- **Project Manager (PM)**: Coordinates delivery, schedules, risks, and communications. Ensures the project stays on track.
- **Product Manager (PdM)**: Defines outcomes, prioritizes the backlog, and measures success. Owns the product vision and strategy.
- **Developers**: Implement features, collaborate on design and testability, write tests, and maintain quality standards.
- **QA/Testing**: Validate quality and acceptance criteria. Catch issues before they reach production.
- **Stakeholders**: Provide inputs, approvals, and strategic direction.

**Communication Cadence:**
- Daily standups (15 min): Progress, blockers, dependencies
- Weekly PM-PdM sync: Alignment and strategy
- Twice-weekly delivery standups: Team coordination
- Monthly stakeholder updates: Visibility and transparency
- Ad-hoc escalations: When blockers need leadership attention

### Quality & Risk Management

Quality is embedded throughout execution, not bolted on at the end:

- **Testing**: Unit tests for new logic, integration tests where applicable, end-to-end smoke tests for critical flows, and security scanning in CI.
- **Code Review**: Pull requests require at least one approval before merging. Keep PRs small (≤400 lines when possible) with clear issue links and acceptance criteria.
- **Risk Management**: Maintain a living Risk Register reviewed weekly during syncs. Track impact, likelihood, ownership, and mitigation for each risk.
- **Definition of Done**: Each project defines clear standards—what must be true before work is considered complete. Velocity, burndown, and success metrics are tracked via dashboards.

---

## Project Management Documentation Index

Navigate to the detailed guides for each phase and aspect of the OctoAcme methodology:

### Getting Started & Planning
- **[Project Management Overview](octoacme-project-management-overview.md)** — High-level introduction to OctoAcme approach, roles, and key artifacts
- **[Project Initiation Guide](octoacme-project-initiation.md)** — Steps to validate business need, identify stakeholders, and create a Project One-pager
- **[Project Planning Guide](octoacme-project-planning.md)** — How to break work into shippable increments, estimate scope, and plan releases

### Execution & Delivery
- **[Execution & Tracking](octoacme-execution-and-tracking.md)** — Day-to-day team rhythm, PR workflow, quality standards, and blocker escalation
- **[Risks & Communication](octoacme-risks-and-communication.md)** — Risk management, stakeholder communication templates, and escalation paths
- **[Release & Deployment Guide](octoacme-release-and-deployment.md)** — Pre-release requirements, deployment checklist, rollback procedures, and release notes

### Continuous Improvement
- **[Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)** — How to run retrospectives, track action items, and measure improvement over time
- **[Roles & Personas](octoacme-roles-and-personas.md)** — Detailed definitions of PM, Product Manager, Developer, and QA responsibilities and goals

---

## Quick Start

**New to OctoAcme?** Start here:

1. Read the [Project Management Overview](octoacme-project-management-overview.md) to understand the approach and key roles.
2. If you're starting a new project, follow the [Project Initiation Guide](octoacme-project-initiation.md).
3. Familiarize yourself with the [Roles & Personas](octoacme-roles-and-personas.md) to understand your team.
4. Review the [Execution & Tracking](octoacme-execution-and-tracking.md) guide to learn the day-to-day rhythm.

**Starting execution on an existing project?**

1. Check [Project Planning Guide](octoacme-project-planning.md) to understand the plan and backlog.
2. Review [Execution & Tracking](octoacme-execution-and-tracking.md) for daily standups, PR workflow, and quality standards.
3. Keep [Risks & Communication](octoacme-risks-and-communication.md) handy for escalations and status updates.

**Wrapping up and improving?**

1. Use [Release & Deployment Guide](octoacme-release-and-deployment.md) for the production rollout.
2. Run a retrospective following [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md).

---

## Key Artifacts You'll Use

Throughout your project, you'll create and maintain these artifacts:

- **Project One-pager**: Problem statement, goals, success metrics, stakeholders, timeline, risks, and team composition
- **Project Backlog**: Prioritized list of work items with acceptance criteria and estimates
- **Risk Register**: Tracked risks, impact, likelihood, owner, and mitigation plans
- **Definition of Done (DoD)**: Clear standards for what "complete" means on your project
- **Release Notes**: Changes, migration steps, known issues, and rollback information
- **Retrospective Notes**: What went well, what to improve, and action items with owners and due dates

---

## Principles in Practice

### Blocker Escalation Path
When issues arise, we have a clear escalation path:
- **Level 1**: Team-level triage in daily standup
- **Level 2**: PM escalates to Product Lead and dependent teams
- **Level 3**: Sponsor-level escalation for business-impacting issues

### Blameless Incidents & Learning
When things go wrong, we prioritize learning over blame:
- Triage and take immediate action (including rollback if needed)
- Conduct a blameless retrospective to identify root causes
- Convert findings into action items to prevent recurrence

### Continuous Improvement Culture
We measure the impact of improvements, celebrate successes, and iterate on processes just like we do with product. Small, incremental changes compound into significant improvements.

---

## How to Use These Docs

- **Keep docs updated**: As your team's practices evolve, update these documents to reflect current reality.
- **Use templates and checklists**: Copy templates and checklists from these guides into your project repos.
- **Create process issues**: If you identify gaps or improvements needed, create an issue using the [Add/Update Content to Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) template.
- **Personalize for your context**: The OctoAcme framework is a foundation. Adapt it to your team's needs, constraints, and culture.

---

## Questions or Feedback?

If you have questions about these processes or suggestions for improvement, please open an issue or reach out to your Product Lead or Project Manager. We're committed to continuous improvement and value your feedback.

---

*Last updated: 2026-03-31*
