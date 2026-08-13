# Scale institutional knowledge using Copilot Spaces

<img src="https://octodex.github.com/images/Professortocat_v2.png" align="right" height="200px" />

Hey rslobrob!

Mona here. I'm done preparing your exercise. Hope you enjoy! 💚

Remember, it's self-paced so feel free to take a break! ☕️

[![](https://img.shields.io/badge/Go%20to%20Exercise-%E2%86%92-1f883d?style=for-the-badge&logo=github&labelColor=197935)](https://github.com/rslobrob/skills-scale-institutional-knowledge-using-copilot-spaces)

---

## OctoAcme Project Management Documentation

This repository contains the complete set of processes, templates, and guidance used by **OctoAcme** to manage projects from initiation through delivery and continuous improvement.

### Quick Start

- **New to OctoAcme?** Start with [OctoAcme Project Management Overview](docs/octoacme-project-management-overview.md) for a concise introduction to our approach, core roles, and key artifacts.
- **Starting a new project?** Follow the [Project Initiation Guide](docs/octoacme-project-initiation.md).
- **Executing a project?** Reference [Execution & Tracking](docs/octoacme-execution-and-tracking.md) for day-to-day workflows and quality practices.
- **Managing risks or stakeholders?** See [Risk Management & Communication](docs/octoacme-risks-and-communication.md).
- **Preparing for release?** Use the [Release & Deployment Guide](docs/octoacme-release-and-deployment.md).
- **Capturing learnings?** Review [Retrospective & Continuous Improvement](docs/octoacme-retrospective-and-continuous-improvement.md).

### Complete Documentation

| Document | Purpose |
|----------|---------|
| [OctoAcme Project Management Overview](docs/octoacme-project-management-overview.md) | High-level introduction to OctoAcme's project management approach, principles, core roles, and lifecycle |
| [OctoAcme Project Initiation Guide](docs/octoacme-project-initiation.md) | Steps to validate business need, align stakeholders, and create a lightweight project one-pager |
| [OctoAcme Project Planning](docs/octoacme-project-planning.md) | Breaking work into shippable increments, estimating scope, defining DoD, and identifying dependencies |
| [OctoAcme Execution & Tracking](docs/octoacme-execution-and-tracking.md) | Day-to-day execution workflows, team rhythm, quality practices, and blocker escalation |
| [OctoAcme Risk Management & Communication](docs/octoacme-risks-and-communication.md) | Risk register maintenance, stakeholder communication strategies, and escalation paths |
| [OctoAcme Release & Deployment Guide](docs/octoacme-release-and-deployment.md) | Pre-release requirements, deployment checklist, rollback planning, and release notes |
| [OctoAcme Retrospective & Continuous Improvement](docs/octoacme-retrospective-and-continuous-improvement.md) | Running retrospectives, tracking action items, and building a continuous improvement culture |
| [OctoAcme Personas](docs/octoacme-roles-and-personas.md) | Detailed role descriptions for Developers, Product Managers, and Project Managers |

### OctoAcme Project Management Summary

#### Overview & Lifecycle

OctoAcme operates a structured, lifecycle-based approach to project management that emphasizes customer value, iterative delivery, and clear ownership. The organization manages projects through five core phases: **Initiation**, **Planning**, **Execution**, **Release**, and **Close & Retrospective**. Each phase is governed by defined artifacts, checklists, and decision gates. Projects begin with an Initiation phase where business need and measurable outcomes are validated through a lightweight One-pager, stakeholder alignment, and a go/no-go decision. Once approved, the team moves into Planning, where work is broken into shippable increments with clear acceptance criteria, priorities, and dependencies documented in a prioritized backlog. This structured foundation ensures that teams have clarity on scope, resources, and milestones before execution begins.

#### Roles & Communication

**Core roles and communication cadence** drive accountability and transparency across OctoAcme projects. The organization designates a **Project Manager** to coordinate delivery, manage schedules and risks, and facilitate stakeholder communication; a **Product Manager** to define customer and business value, prioritize the backlog, and measure outcomes; and **Developers** and **QA teams** to implement and validate features. Communication happens through daily standups (15 minutes), weekly PM and Product Lead syncs, twice-weekly team standups, and monthly stakeholder updates. This multi-layered communication ensures blockers are surfaced quickly and risks are escalated systematically through levels: team triage → PM escalation → Product Lead involvement → sponsor-level escalation for business-impacting issues.

#### Execution & Quality

Execution and quality are tightly integrated throughout OctoAcme's workflow. The team maintains a project board with columns (Backlog, Ready, In Progress, In Review, QA, Done), favors small pull requests (≤400 lines), and enforces automated CI testing and security scanning before review. Quality assurance includes unit tests for new logic, integration tests where applicable, end-to-end smoke tests for critical flows, and manual QA for feature acceptance. Teams track velocity and burndown metrics, monitor success metrics from the Project One-pager, and maintain dashboards for key signals (errors, latency, usage). A formal **Retrospective & Continuous Improvement** phase follows each sprint or release, where teams capture learnings, identify 2–3 prioritized action items, and feed improvements back into subsequent iterations.

#### Release & Risk Management

Release management at OctoAcme is standardized to minimize risk and ensure observability. Before any release (patch, minor, or major), the team verifies that all acceptance criteria are met, PRs are merged, CI and security scans pass, release notes are drafted, and a rollback/mitigation plan is documented. A **Deployment Checklist** guides the release process, including staging verification, production deployment via automated pipeline where possible, post-deploy verification, and stakeholder announcement. This disciplined approach, combined with a **Risk Register** maintained throughout execution and a **Stakeholder Communication Strategy** that keeps all parties informed via weekly status templates and incident playbooks, enables OctoAcme to deliver features reliably while maintaining psychological safety and encouraging continuous learning across the organization.

### Issue Templates

This repository includes issue templates to streamline process improvements and documentation updates:

- [Add/Update Content to Process Docs](.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) — Use this template to propose updates or additions to any process document.

### Contributing

To propose updates or improvements to OctoAcme's project management processes:

1. **Review the relevant process document** to understand current guidance.
2. **Create an issue** using the [Add/Update Content to Process Docs](.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) template.
3. **Provide context** on why the change is needed and the proposed content.
4. **Align with stakeholders** as needed before merging documentation updates.

### Using These Docs in Copilot Spaces

This documentation is optimized for use with GitHub Copilot Spaces. To ground Copilot in OctoAcme's processes:

1. Attach the relevant process doc(s) to your Copilot Space.
2. Ask Copilot for guidance on project management activities (e.g., "What's our process for escalating blockers?" or "Help me create a project one-pager").
3. Reference specific personas or roles when you want role-specific guidance.

---

&copy; 2025 GitHub &bull; [Code of Conduct](https://www.contributor-covenant.org/version/2/1/code_of_conduct/code_of_conduct.md) &bull; [MIT License](https://gh.io/mit)
