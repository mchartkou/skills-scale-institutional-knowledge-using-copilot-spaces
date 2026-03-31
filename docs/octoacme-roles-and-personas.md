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

## Scrum Masters

### Role Summary
Scrum Masters facilitate agile ceremonies, ensure the team is following agreed processes, and remove workflow impediments. They act as servant-leaders, partnering closely with Project Managers, Developers, and QA to maintain delivery cadence.

### Responsibilities
- Facilitate sprint planning, daily standups, sprint reviews, and retrospectives
- Shield the team from external distractions and interruptions
- Identify and remove blockers that slow delivery
- Coach the team on agile practices and continuous improvement
- Track and surface sprint metrics (velocity, burndown) to stakeholders

### Goals
- Enable predictable, sustainable delivery cadence
- Foster a self-organizing, high-performing team
- Continuously improve team processes and reduce waste

### Typical Communication
- Daily standups and sprint ceremonies
- Impediment logs and retrospective action items
- Coordination with Project Managers on risks and dependencies

### How they interact with existing roles
- **Project Managers**: Align on delivery timelines, escalate unresolved blockers, and coordinate cross-team dependencies
- **Developers**: Coach on agile practices, facilitate estimation, and remove technical blockers
- **Product Managers**: Ensure backlog is groomed and prioritized ahead of each sprint
- **QA/Test Engineers**: Coordinate testing activities within sprint cycles to ensure release readiness

---

## UX Designers

### Role Summary
UX Designers lead user research, design workflows, wireframes, and usability validation. They work closely with Product Managers and Developers to translate requirements into intuitive experiences and iterate on feedback.

### Responsibilities
- Conduct user research and gather requirements
- Design wireframes, workflows, and interactive prototypes
- Facilitate usability testing and iterate based on findings
- Document design handoffs and specifications for development
- Maintain a consistent design system and style guide

### Goals
- Deliver intuitive, user-friendly experiences
- Reduce friction and increase user satisfaction
- Support iterative design improvements based on real user data

### Typical Communication
- Design review meetings with Product and Engineering
- Usability test reports and research summaries
- Stakeholder demos and user feedback sessions
- Design handoff documentation (e.g., Figma, Zeplin)

### How they interact with existing roles
- **Product Managers**: Collaborate on feature definition, validate assumptions through user research, and align design priorities with the roadmap
- **Developers**: Provide design specifications and clarify intent during implementation; participate in design review of built features
- **Project Managers**: Communicate design timelines, flag scope changes, and align on delivery milestones

---

## QA/Test Engineers

### Role Summary
QA/Test Engineers own quality assurance strategies, regression testing, and release sign-off. They collaborate with Developers and Product Managers to define acceptance criteria and ensure deliverables meet quality standards before release.

### Responsibilities
- Design and implement automated test suites (unit, integration, end-to-end)
- Execute regression and exploratory testing across releases
- Define and maintain test plans and quality metrics
- Coordinate release sign-off and communicate quality status
- Identify defects early and work with developers on root cause and resolution

### Goals
- Prevent defects from reaching production
- Increase test coverage and reduce manual testing effort
- Enable fast, confident releases through robust automation

### Typical Communication
- Sprint reviews and release readiness meetings
- Bug reports, test results, and quality dashboards
- Collaboration with Developers during code reviews and feature walkthroughs

### How they interact with existing roles
- **Developers**: Review acceptance criteria, flag edge cases early, and collaborate on test coverage during development
- **Product Managers**: Validate features against acceptance criteria and escalate quality risks that may affect release scope
- **Project Managers**: Report on testing progress, release readiness, and quality risks in status updates
- **Scrum Masters**: Surface testing blockers during standups and sprint ceremonies

---

## Business Analysts

### Role Summary
Business Analysts gather project requirements, document business context, and act as a bridge between technical and non-technical stakeholders. They enable Product and Project Managers to align the team around clearly articulated needs and outcomes.

### Responsibilities
- Elicit, document, and validate business and functional requirements
- Create process maps, user stories, and acceptance criteria
- Facilitate requirement workshops and stakeholder interviews
- Identify and document gaps between business needs and current capabilities
- Support change management by communicating the impact of process changes

### Goals
- Ensure requirements are clear, complete, and actionable
- Reduce rework caused by misunderstood or missing requirements
- Bridge communication gaps between business and technical teams

### Typical Communication
- Requirement workshops and stakeholder interviews
- User story documentation and business requirements documents (BRDs)
- Backlog refinement sessions with Product Managers and Developers

### How they interact with existing roles
- **Product Managers**: Translate high-level product goals into detailed requirements; validate that user stories reflect business intent
- **Project Managers**: Provide requirements documentation that informs project planning, scope management, and risk identification
- **Developers**: Clarify requirements during development; review implemented features against documented acceptance criteria
- **UX Designers**: Share business and user research insights to inform design decisions

---

## DevOps Engineers

### Role Summary
DevOps Engineers own deployment pipelines, CI/CD management, and infrastructure reliability. They work with Developers and QA to ensure smooth, repeatable releases and advise the Project Manager on infrastructure risks that may affect delivery timelines.

### Responsibilities
- Design, build, and maintain CI/CD pipelines and deployment automation
- Manage cloud infrastructure, environments, and configuration as code
- Monitor system health, performance, and reliability; respond to incidents
- Enforce security and compliance standards in the deployment process
- Collaborate on release planning to identify and mitigate infrastructure risks

### Goals
- Enable fast, reliable, and repeatable software releases
- Reduce deployment failures and mean time to recovery (MTTR)
- Improve infrastructure scalability, security, and observability

### Typical Communication
- Release planning and deployment coordination meetings
- Incident post-mortems and infrastructure risk reports
- Runbooks, infrastructure documentation, and deployment guides

### How they interact with existing roles
- **Developers**: Provide tooling and pipeline support; collaborate on build and deployment configurations; assist in debugging environment-specific issues
- **QA/Test Engineers**: Maintain stable test environments; support automated test execution in CI pipelines
- **Project Managers**: Communicate infrastructure risks, deployment windows, and environment constraints that affect release timelines
- **Product Managers**: Advise on technical feasibility and release logistics for roadmap items

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

