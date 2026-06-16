# OctoAcme Project Management Docs

This README centralizes the OctoAcme project management process documents and provides a summary of the processes used. Use the links below to navigate each process document.

## OctoAcme Project Management Overview

OctoAcme follows a structured five-phase project lifecycle designed to deliver customer value iteratively while maintaining clear ownership and data-driven decision-making. The process begins with **Initiation**, where new ideas are validated through a lightweight Project One-pager that confirms business need, identifies stakeholders, and establishes success metrics. Once approved, projects move into **Planning**, where work is broken into shippable increments with prioritized backlogs, clear acceptance criteria, and a Definition of Done. The team then executes through iterative sprints with daily standups and weekly delivery syncs, progressing to **Release & Deployment** with rigorous pre-release checks and rollback plans. Finally, teams conduct **Retrospectives** to capture learnings and feed improvements back into future iterations.

OctoAcme operates with clearly defined roles that ensure accountability and collaboration across the delivery chain. **Project Managers** coordinate schedules, manage risks, and facilitate stakeholder communication; **Product Managers** define outcomes, prioritize backlogs, and measure success; **Developers** implement features while contributing to design and risk identification; and **QA/Testing** validates quality against acceptance criteria. Communication is structured and frequent—weekly syncs between PM and Product Lead, twice-weekly team standups, and monthly stakeholder updates establish alignment. An escalation framework (team-level → PM → Product Lead → Sponsor) surfaces blockers quickly without losing momentum.

Day-to-day execution relies on a GitHub Projects board with standardized columns (Backlog, Ready, In Progress, In Review, QA, Done) and disciplined pull request workflows emphasizing small PRs (≤400 lines), automated CI/CD with tests and security scanning, and at least one approval before merge. Quality assurance is comprehensive, including unit tests, integration tests, end-to-end smoke tests for critical flows, and security scanning. Risk management is continuous, with a Risk Register capturing identified issues and reviewed weekly during syncs. OctoAcme treats risk management and communication as interconnected disciplines—the Risk Register lives as a living artifact throughout the project lifecycle, allowing teams to identify, assess, mitigate, and monitor risks in real-time while keeping all stakeholders informed through consistent, transparent reporting.

## Brief Process Summary

- **Initiation:** Capture problem, stakeholders, success metrics, and a lightweight one-pager to decide go/no-go.
- **Planning:** Prioritize work, estimate scope, identify dependencies and risks, and create a release plan.
- **Execution & Tracking:** Daily standups, project board workflow, PR and CI conventions, and regular demos.
- **Release & Deployment:** Pre-release checks, deployment checklist, rollback plan, and release notes.
- **Risk Management & Communication:** Maintain a risk register, monitor regularly, and follow escalation paths.
- **Retrospective & Continuous Improvement:** Capture learnings, create action items, and track improvements.
- **Roles & Personas:** Clear responsibilities for PM, PdM, developers, QA, and stakeholders.

## Process Documents

- [Project Management Overview](octoacme-project-management-overview.md) — Concise introduction to approach, roles, and artifacts
- [Project Initiation Guide](octoacme-project-initiation.md) — One-pager template and initiation checklist
- [Project Planning](octoacme-project-planning.md) — Backlog, estimation, and planning checklist
- [Execution & Tracking](octoacme-execution-and-tracking.md) — Team rhythm, workflows, and execution checklist
- [Risks & Communication](octoacme-risks-and-communication.md) — Risk register and communication templates
- [Release & Deployment](octoacme-release-and-deployment.md) — Deployment checklist and rollback playbook
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) — Retrospective structure and tracking improvements
- [Roles & Personas](octoacme-roles-and-personas.md) — Role summaries and responsibilities
