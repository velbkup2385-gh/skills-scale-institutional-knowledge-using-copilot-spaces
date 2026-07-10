# OctoAcme Project Management Processes

## Welcome

This is the central hub for OctoAcme's project management processes, principles, and guidance. Whether you're starting a new project, planning a release, or running a retrospective, you'll find the processes and templates you need here.

## Our Approach

OctoAcme follows a **customer-first, iterative delivery model** with clear ownership, data-informed decisions, and psychological safety. Our framework is designed to centralize scattered project management knowledge, convert tacit team insights into searchable artifacts, and give all team members equal access to processes, decisions, and rationale.

### Core Principles

- **Customer-first:** Prioritize customer value and usability
- **Iterative delivery:** Deliver small, testable increments
- **Clear ownership:** Each project has a named Project Manager and Product Lead
- **Data-informed decisions:** Measure impact and iterate based on evidence
- **Psychological safety:** Encourage feedback and learning

## Project Management Processes Overview

OctoAcme follows a structured **five-stage project lifecycle**: Initiation, Planning, Execution, Release, and Close & Retrospective. 

During **initiation**, teams validate business needs, align stakeholders, and create a lightweight Project One-pager defining the problem, objectives, success metrics, and initial timeline. Once approved, the **planning** phase breaks work into shippable increments using a prioritized backlog with clear acceptance criteria, estimates, and a Definition of Done. 

**Execution** operates on a sprint-based cadence with daily standups (15 min), weekly delivery syncs, and a project board tracking work through Backlog, Ready, In Progress, In Review, QA, and Done. Pull requests are kept small (≤400 lines when possible), include issue links and acceptance criteria, and require at least one approval before merging. Quality is embedded throughout with unit tests, integration tests, end-to-end smoke tests, and security scanning in CI.

Three core roles drive delivery: **Product Managers** define what to build and own prioritization; **Project Managers** coordinate schedules, risks, and communications; and **Developers** implement features while collaborating on design and quality. Risk registers are maintained and reviewed weekly, with clear escalation paths: team-level triage → PM → Product Lead → Sponsor.

After each sprint, release, or milestone, OctoAcme conducts retrospectives to capture learnings and generate action items with clear owners. This commitment to measuring impact, celebrating improvements, and making iterative changes embodies the organization's dedication to continuous improvement and psychological safety.

## Documentation

### Project Lifecycle

- **[Project Initiation](octoacme-project-initiation.md)** — How to validate and authorize work, align stakeholders, and create a lightweight plan
- **[Project Planning](octoacme-project-planning.md)** — How to turn an approved initiative into an actionable plan and backlog
- **[Execution & Tracking](octoacme-execution-and-tracking.md)** — Guidance for managing day-to-day execution and tracking progress
- **[Release & Deployment](octoacme-release-and-deployment.md)** — How to standardize releases and deployments
- **[Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)** — How to capture learnings and convert them into improvements

### Key Processes

- **[Risk Management & Communication](octoacme-risks-and-communication.md)** — How to identify, manage, and communicate risks and dependencies
- **[Roles & Personas](octoacme-roles-and-personas.md)** — Role descriptions and responsibilities
- **[Project Management Overview](octoacme-project-management-overview.md)** — High-level introduction to OctoAcme's approach, roles, and key artifacts

## Quick Start

1. **Read the overview** — Start with [Project Management Overview](octoacme-project-management-overview.md) to understand our principles and roles
2. **Starting a new project?** — Use the [Project Initiation guide](octoacme-project-initiation.md)
3. **Creating a project plan** — Reference the [Planning guide](octoacme-project-planning.md)
4. **During delivery** — Use [Execution & Tracking](octoacme-execution-and-tracking.md)
5. **Going to production** — Follow the [Release guide](octoacme-release-and-deployment.md)
6. **After a sprint/release** — Run a retrospective using [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)

## Key Artifacts

- Project Charter / One-pager
- Roadmap and Release Plan
- Sprint/Iteration Backlog
- Acceptance Criteria & Definition of Done
- Risk Register
- Retrospective notes and action items

## Core Roles

- **Project Manager (PM):** Coordinates delivery, schedules, risk, communications
- **Product Manager (PdM):** Defines outcomes, prioritizes backlog, measures success
- **Developers:** Implement features, collaborate on design and testability
- **QA/Testing:** Validate quality and acceptance criteria
- **Stakeholders:** Provide inputs and approvals

See [Roles & Personas](octoacme-roles-and-personas.md) for detailed descriptions.

## Communication Cadence

- **Weekly sync** — PM + Product Manager alignment
- **Twice-weekly standups** — Delivery team progress and blockers
- **Monthly updates** — Stakeholder communications
- **Ad-hoc escalations** — As needed for blockers and risks

## Issue Templates

Process improvement proposals and updates to these documentation files should use the [Add Content to Project Management Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) issue template.

## How to Use These Docs

- Keep the Project Charter updated in your project repository
- Reference these guides during project planning and execution
- Use the issue templates to propose updates and improvements
- Add process-specific docs to `.copilot/` if you want Copilot Spaces to use them as context for role-specific guidance
- Make these docs part of your onboarding materials for new team members
