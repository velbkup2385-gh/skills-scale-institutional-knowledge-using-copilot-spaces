# OctoAcme Project Management Processes

## Welcome

This is the central hub for OctoAcme's project management processes, principles, and guidance. Whether you're starting a new project, planning a release, or running a retrospective, you'll find the processes and templates you need here.

## Our Approach

OctoAcme follows a **customer-first, iterative delivery model** with the following core principles:

- **Customer-first**: Prioritize customer value and usability in all decisions
- **Iterative delivery**: Deliver small, testable increments and gather feedback early
- **Clear ownership**: Each project has a named Project Manager (PM) and Product Lead
- **Data-informed decisions**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback, learning, and continuous improvement

For more details, see [OctoAcme Project Management Overview](octoacme-project-management-overview.md).

## Documentation Map

### Project Lifecycle

Navigate through each phase of a project from concept to completion:

- **[Project Initiation](octoacme-project-initiation.md)** — How to validate and authorize work, align stakeholders, and create a lightweight plan. Use this when a new project idea or feature proposal is ready to be explored.

- **[Project Planning](octoacme-project-planning.md)** — How to turn an approved initiative into an actionable plan and backlog. Includes backlog creation, estimation, and risk identification.

- **[Execution & Tracking](octoacme-execution-and-tracking.md)** — Guidance for managing day-to-day execution and tracking progress toward project milestones. Covers team rhythm, quality standards, and blocker escalation.

- **[Release & Deployment](octoacme-release-and-deployment.md)** — How to standardize releases and deployments to reduce risk and improve observability. Includes pre-release requirements and rollback procedures.

- **[Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)** — How to capture learnings and convert them into actionable improvements. Run retrospectives after sprints, releases, or important milestones.

### Key Processes

Cross-cutting processes that apply throughout the project lifecycle:

- **[Risk Management & Communication](octoacme-risks-and-communication.md)** — How to identify, manage, and communicate risks and dependencies. Includes risk register templates and escalation paths.

- **[Roles & Personas](octoacme-roles-and-personas.md)** — Detailed role descriptions for Project Managers, Product Managers, and Developers, including responsibilities and typical communication patterns.

## Quick Start Guide

**New to OctoAcme?** Follow these steps:

1. **Understand the framework**: Read the [Project Management Overview](octoacme-project-management-overview.md) to learn our principles, roles, and key artifacts.

2. **Starting a new project?** Use the [Project Initiation guide](octoacme-project-initiation.md) to validate the idea and get stakeholder alignment.

3. **Ready to plan?** Follow the [Project Planning guide](octoacme-project-planning.md) to create your backlog, estimate scope, and identify risks.

4. **In active delivery?** Reference [Execution & Tracking](octoacme-execution-and-tracking.md) for day-to-day guidance on standups, PRs, testing, and blocker escalation.

5. **Preparing for release?** Use the [Release & Deployment guide](octoacme-release-and-deployment.md) to prepare your release checklist and deployment plan.

6. **Project complete?** Run a [Retrospective](octoacme-retrospective-and-continuous-improvement.md) to capture learnings and drive continuous improvement.

## Core Roles

| Role | Responsibilities | Key Output |
|------|------------------|-----------|
| **Product Manager** | Defines outcomes, prioritizes backlog, measures success | Roadmap, success metrics, acceptance criteria |
| **Project Manager** | Coordinates delivery, manages schedule and risks, facilitates communication | Project plan, status reports, risk register |
| **Developer** | Implements features, writes tests, collaborates on design | Code, tests, technical documentation |
| **QA/Testing** | Validates quality and acceptance criteria | Test plans, quality reports |

See [Roles & Personas](octoacme-roles-and-personas.md) for detailed role descriptions.

## Key Artifacts

Every OctoAcme project maintains:

- **Project Charter / One-pager** — Problem statement, goals, success metrics, stakeholders, timeline
- **Roadmap and Release Plan** — Phased delivery schedule and milestones
- **Sprint/Iteration Backlog** — Prioritized items with acceptance criteria and estimates
- **Risk Register** — Identified risks, impact, likelihood, mitigation plans, and status
- **Definition of Done** — Shared acceptance criteria for all work (tests, review, documentation, etc.)
- **Release Notes** — Summary of changes, migration steps, known issues
- **Retrospective Notes** — Learnings, action items, and improvements for next iteration

## Communication Cadence

Stay aligned and informed through regular touchpoints:

- **Daily standups** (15 min) — Focus on progress, blockers, and dependencies
- **Weekly PM + PdM sync** — Strategic alignment and decision-making
- **Twice-weekly delivery team meetings** — Planning, reviews, and coordination (or as agreed)
- **Weekly delivery sync** — Show progress, updates, and flagged risks
- **Monthly stakeholder updates** — High-level status and upcoming milestones
- **Sprint/milestone demo** — Review completed work and gather feedback
- **Ad-hoc escalations** — As needed for blockers or decisions

## Checklists for Common Tasks

### Starting a New Project

- [ ] Confirm business need and measurable outcome
- [ ] Identify stakeholders and champions
- [ ] Complete Project One-pager
- [ ] Get Product Lead and Sponsor approval
- [ ] Schedule kickoff meeting
- [ ] Create repo or project board skeleton

### Planning a Project

- [ ] Hold kickoff meeting with stakeholders and delivery team
- [ ] Create prioritized backlog with acceptance criteria
- [ ] Estimate scope using T-shirt sizing or story points
- [ ] Define Definition of Done (DoD)
- [ ] Identify dependencies and integration points
- [ ] Create release plan and milestone map
- [ ] Draft initial test plan and QA approach

### Executing and Tracking

- [ ] Branching and PR conventions documented in repo
- [ ] CI configured for tests and lint
- [ ] Regular demos scheduled
- [ ] Risk register updated weekly
- [ ] Team velocity and burndown tracked
- [ ] Success metrics monitored

### Releasing to Production

- [ ] All acceptance criteria met and PRs merged
- [ ] Passing CI and security scans
- [ ] Release notes drafted
- [ ] Rollback / mitigation plan documented
- [ ] Smoke tests prepared
- [ ] Post-deploy verifications completed
- [ ] Release announced to stakeholders and support

## How to Use These Docs

- **Keep documentation updated**: Project Charters should be updated regularly in your project repo
- **Customize for your context**: Use these templates and processes as a foundation; adapt them to your team's needs
- **Reference in issues and PRs**: Link to relevant process docs when creating issues or discussing PRs
- **Store in .copilot/**: If using Copilot Spaces, copy key docs to `.copilot/` to ground Copilot in your processes
- **Review during retrospectives**: Update and refine these docs based on team feedback and learnings

## Contributing to Process Documentation

We welcome feedback and improvements to these processes. To suggest updates or additions:

1. **Found a gap or improvement?** Create an issue using the ["Add Content to Project Management Process Docs" template](.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml)
2. **Align with stakeholders** to ensure the change is relevant and beneficial
3. **Create a pull request** with the updated documentation
4. **Get feedback from PMs and team leads** before merging

## Questions or Feedback?

If you have questions about any of these processes or feedback on how they're working for your team:

- Raise it in your weekly PM sync
- Add it to the retrospective agenda
- Create an issue in this repo
- Reach out to the Project Lead

---

**Last Updated**: July 2026  
**Maintained By**: OctoAcme Project Management Team
