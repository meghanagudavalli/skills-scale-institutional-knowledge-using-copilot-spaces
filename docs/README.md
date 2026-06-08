# OctoAcme Project Management Documentation

Welcome! This README provides an overview of the project management processes used at OctoAcme and serves as a central index to all detailed process documentation.

## OctoAcme Project Management Overview

OctoAcme follows a structured, lifecycle-driven approach to project management that emphasizes stakeholder alignment, iterative delivery, and continuous improvement. The methodology is organized around five core phases: **Initiation** (validating business need and creating a lightweight one-pager), **Planning** (breaking work into shippable increments with clear acceptance criteria), **Execution** (daily standups and sprint-based delivery with automated CI/CD), **Release** (standardized deployment with rollback plans), and **Retrospectives** (capturing learnings and action items). This approach is grounded in principles of customer-first thinking, clear ownership, data-informed decisions, and psychological safety.

OctoAcme defines three primary personas that drive project success: **Project Managers** who coordinate delivery, manage timelines, risks, and stakeholder communications; **Product Managers** who define what should be built, prioritize the backlog, and measure outcomes; and **Developers** who implement features, write tests, and participate in design and code reviews. Each role has clear responsibilities and communication touchpoints, ensuring accountability and alignment across the team. The project management overview emphasizes that "clear ownership" is a core principle, with each project having a named PM and Product Lead.

**Communication and risk management** are central to OctoAcme's execution strategy. The team operates on a consistent cadence including daily standups (focused on progress and blockers), weekly PM-PdM syncs, twice-weekly delivery team standups, and monthly stakeholder updates. Risk management follows a structured lifecycle—identifying risks during planning, assessing impact and likelihood, implementing mitigation strategies, and monitoring status weekly. An escalation path (team → PM → Product Lead → Sponsor) ensures issues are elevated appropriately, with a three-level blocker escalation process supporting rapid resolution.

**Quality assurance and delivery practices** are embedded throughout the project lifecycle. OctoAcme uses GitHub Projects for workflow tracking (Backlog → Ready → In Progress → In Review → QA → Done), requires small pull requests (≤400 lines), enforces automated CI testing and security scanning, and implements a Definition of Done standard across all projects. Release practices include pre-release checklists, smoke tests, release notes, and documented rollback plans. By coupling rigorous quality checks with a blameless retrospective culture, OctoAcme enables teams to maintain high standards while continuously improving their processes and celebrating wins.

## Process Documentation Index

Navigate to any process document below to learn detailed workflows, checklists, and templates:

| Document | Purpose |
|----------|---------|
| [Project Management Overview](./octoacme-project-management-overview.md) | Concise introduction to OctoAcme's approach, core roles, key artifacts, and the high-level project lifecycle |
| [Project Initiation Guide](./octoacme-project-initiation.md) | Initial steps to validate business need, align stakeholders, and create a lightweight plan with the Project One-pager template |
| [Project Planning](./octoacme-project-planning.md) | Turning an approved initiative into an actionable plan, backlog, and release schedule with Definition of Done |
| [Execution & Tracking](./octoacme-execution-and-tracking.md) | Day-to-day execution, team rhythm (standups, demos), workflows, quality practices, and blocker escalation |
| [Risk Management & Communication](./octoacme-risks-and-communication.md) | How to identify, assess, monitor, and communicate risks; stakeholder communication templates and escalation paths |
| [Release & Deployment Guide](./octoacme-release-and-deployment.md) | Standardized release types, pre-release requirements, deployment checklists, and rollback procedures |
| [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) | Running effective retrospectives, tracking action items, and building a continuous improvement culture |
| [Roles & Personas](./octoacme-roles-and-personas.md) | Detailed descriptions of Project Manager, Product Manager, and Developer roles with responsibilities and communication patterns |

## Quick Start for New Team Members

1. **Start here**: Read [Project Management Overview](./octoacme-project-management-overview.md) for a high-level understanding of our approach and core principles.
2. **Find your role**: Check [Roles & Personas](./octoacme-roles-and-personas.md) to understand your responsibilities and how you fit into the process.
3. **For your current phase**: Navigate to the relevant process document:
   - Starting a new project? → [Project Initiation Guide](./octoacme-project-initiation.md)
   - Planning your work? → [Project Planning](./octoacme-project-planning.md)
   - Executing and delivering? → [Execution & Tracking](./octoacme-execution-and-tracking.md)
   - Preparing for release? → [Release & Deployment Guide](./octoacme-release-and-deployment.md)
   - Wrapping up a project? → [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)
4. **Managing risks?** → [Risk Management & Communication](./octoacme-risks-and-communication.md)

## Key Principles

- **Customer-first**: Prioritize customer value and usability in all decisions.
- **Iterative delivery**: Deliver small, testable increments rather than big-bang releases.
- **Clear ownership**: Each project has a named Project Manager and Product Lead with defined responsibilities.
- **Data-informed decisions**: Measure impact and iterate based on evidence.
- **Psychological safety**: Encourage feedback, learning, and continuous improvement.

## How to Use These Docs in Copilot Spaces

If you're using these docs as context in a Copilot Space:
- Store process-specific docs in `.copilot/` to give Copilot enhanced context for project-specific guidance.
- Reference specific sections by line number when asking Copilot questions about processes.
- Keep project charters and one-pagers updated in your project repository for consistency.

## Contributing Updates

To propose changes or additions to these process documents, please create an issue using the [Add Content to Project Management Process Docs](./.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) template.

---

**Last updated**: June 8, 2026  
**Maintained by**: OctoAcme Project Management Team
