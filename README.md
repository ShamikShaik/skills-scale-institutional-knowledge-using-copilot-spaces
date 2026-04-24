# Scale institutional knowledge using Copilot Spaces

<img src="https://octodex.github.com/images/Professortocat_v2.png" align="right" height="200px" />

Hey ShamikShaik!

Mona here. I'm done preparing your exercise. Hope you enjoy! 💚

Remember, it's self-paced so feel free to take a break! ☕️

[![](https://img.shields.io/badge/Go%20to%20Exercise-%E2%86%92-1f883d?style=for-the-badge&logo=github&labelColor=197935)](https://github.com/ShamikShaik/skills-scale-institutional-knowledge-using-copilot-spaces/issues/1)

---

&copy; 2025 GitHub &bull; [Code of Conduct](https://www.contributor-covenant.org/version/2/1/code_of_conduct/code_of_conduct.md) &bull; [MIT License](https://gh.io/mit)

# OctoAcme Project Management Docs

Welcome! This README introduces OctoAcme's structured approach to project management and serves as a single entry point for all process documentation.

## Project Management Process Summary

OctoAcme operates a structured yet iterative project management approach designed to deliver customer value while maintaining clarity and psychological safety across teams. The project lifecycle follows five key phases: **Initiation**, **Planning**, **Execution**, **Release**, and **Close & Retrospective**. During initiation, teams validate business need and align stakeholders around a lightweight Project One-pager that captures the problem statement, goals, success metrics, and initial timeline. This gate ensures go/no-go decisions are made with clear success criteria before committing resources. Once approved, the planning phase breaks work into shippable increments with prioritized backlogs, acceptance criteria, and a Definition of Done that guides quality standards throughout execution.

OctoAcme emphasizes **clear ownership** through three core personas: **Project Managers** coordinate schedules, risks, and communications; **Product Managers** define what to build and prioritize the roadmap based on customer value; and **Developers** implement features while collaborating on design and testability. Supporting roles include QA/Testing teams who validate quality and acceptance criteria, and Stakeholders who provide inputs and approvals. Communication follows a predictable cadence: daily 15-minute standups focus on progress and blockers, weekly PM-PdM syncs align strategy, twice-weekly delivery team standups track execution, and monthly stakeholder updates provide visibility. This rhythm ensures dependencies surface early and escalations follow a clear path from team level → PM → Product Lead → Sponsor.

During execution, teams use GitHub Projects with standardized columns (Backlog, Ready, In Progress, In Review, QA, Done) to maintain transparency. Pull requests are kept small (≤400 lines when possible) with linked issues and clear acceptance criteria; CI automation runs tests and linting before review, and at least one approval is required before merging. Quality assurance includes unit tests, integration tests, end-to-end smoke tests for critical flows, and security scanning in CI. Risk management is continuous: teams identify risks during planning, assess impact and likelihood, implement mitigations, and monitor status at weekly syncs. A simple Risk Register captures ID, description, impact, probability, owner, and mitigation plan—enabling proactive escalation of blockers and dependencies.

Releases are standardized by type (Patch, Minor, Major) with pre-release checklists covering acceptance criteria verification, passing CI/security scans, rollback plans, and smoke tests. Post-deployment verification and stakeholder announcements complete the deployment workflow. After each sprint, release, or milestone, teams conduct retrospectives (45–75 minutes) to capture what went well, what can improve, and identify 2–3 prioritized action items with clear owners and due dates. These improvements are fed back into the project backlog, creating a continuous learning loop. This approach—grounded in customer-first principles, iterative delivery, data-informed decisions, and psychological safety—enables OctoAcme to scale institutional knowledge across teams while maintaining consistent, repeatable execution.

## Process Documentation

The following documents provide detailed guidance on each stage of the OctoAcme project management lifecycle:

- **[Project Management Overview](octoacme-project-management-overview.md)** — Introduction to OctoAcme's core principles, roles, artifacts, and communication cadence.
- **[Project Initiation Guide](octoacme-project-initiation.md)** — Steps to validate business need, align stakeholders, and decide go/no-go for planning.
- **[Project Planning](octoacme-project-planning.md)** — Breaking work into shippable increments, creating backlogs, estimating scope, and identifying dependencies.
- **[Execution & Tracking](octoacme-execution-and-tracking.md)** — Day-to-day execution, team rhythms, pull request workflow, quality assurance, and blocker escalation.
- **[Release & Deployment Guide](octoacme-release-and-deployment.md)** — Standardized release types, pre-release requirements, deployment checklist, and rollback procedures.
- **[Risk Management & Communication](octoacme-risks-and-communication.md)** — Risk identification, assessment, monitoring, and stakeholder communication strategies.
- **[Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)** — Capturing learnings, running effective retrospectives, and converting improvements into action items.
- **[Roles and Personas](octoacme-roles-and-personas.md)** — Detailed descriptions of Project Managers, Product Managers, Developers, and other key roles.

## How to Use These Docs

- **New to OctoAcme?** Start with the [Project Management Overview](octoacme-project-management-overview.md) to understand the big picture, then navigate to specific process docs as needed.
- **Running a project?** Keep your project charter or one-pager in your project repository and reference the relevant process docs throughout your lifecycle.
- **Integrating with Copilot Spaces?** Add process-specific docs to `.copilot/` if you want Copilot to use them as context for project-specific guidance.
- **Contributing improvements?** These are living documents. Use the [Add Content to Project Management Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) issue template to propose updates.

---

**Last Updated:** 2026-04-24  
**Maintained by:** OctoAcme Program Management Team
