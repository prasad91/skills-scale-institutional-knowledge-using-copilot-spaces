# OctoAcme Project Management Docs

This README centralizes the OctoAcme project management process documents and provides a comprehensive overview of the processes used. Use the links below to access each process document.

## OctoAcme Project Management Processes Overview

OctoAcme uses a structured, lifecycle-based approach to project management that emphasizes customer value, iterative delivery, and clear ownership. The methodology is organized around five core phases: **Initiation** (validating business need and aligning stakeholders), **Planning** (breaking work into shippable increments with defined acceptance criteria), **Execution** (day-to-day delivery with quality gates), **Release** (standardized deployment with risk mitigation), and **Retrospective** (capturing learnings for continuous improvement). This phased approach ensures that projects move through clear decision gates before advancing, with the Project One-pager serving as the foundational artifact that captures problem statement, success metrics, stakeholders, and initial risk assessment.

The organizational structure relies on three core roles working in interdependent partnership: **Project Managers** coordinate schedules, manage risks, and facilitate communication across teams; **Product Managers** define what should be built, prioritize the backlog, and measure outcomes; and **Developers** implement features while contributing to design, testing, and risk identification. This role clarity prevents confusion and ensures accountability. Each project also engages stakeholders and QA/testing specialists as needed. The communication cadence is deliberately structured with daily standups (15 minutes, focused on blockers), weekly delivery syncs showing progress and flagged risks, weekly PM-to-PdM alignment, and monthly stakeholder updates—creating transparency without creating meeting overhead.

Execution and quality are managed through rigorous workflows and checklists. OctoAcme uses GitHub Projects for visible backlog management (columns: Backlog, Ready, In Progress, In Review, QA, Done) and enforces small pull requests (≤400 lines when possible) with required automated testing, linting, and at least one approval before merge. Quality gates include unit tests, integration tests, end-to-end smoke tests, and security scanning in CI, with manual QA for feature acceptance when needed. Risk management is continuous—captured in a Risk Register during planning and updated weekly during syncs, with a three-level escalation path (team → PM → Product Lead → Sponsor) for blockers and incidents.

Release and deployment are treated as controlled, observable processes with clear pre-release requirements (passing CI, drafted release notes, documented rollback plans) and post-deployment verification. The retrospective phase systematically captures what went well and what could improve, with action items tracked in the backlog and reviewed weekly. This closed-loop design—from initiation through retrospective—embeds learning into the process and enables OctoAcme to evolve its practices continuously while maintaining high standards for delivery quality and stakeholder alignment.

## Quick Process Summary

- **Initiation**: Capture problem, stakeholders, success metrics, and a lightweight one-pager to decide go/no-go.
- **Planning**: Prioritize work, estimate scope, identify dependencies and risks, and create a release plan.
- **Execution & Tracking**: Daily standups, project board workflow, PR and CI conventions, and regular demos.
- **Release & Deployment**: Pre-release checks, deployment checklist, rollback plan, and release notes.
- **Risk Management & Communication**: Maintain a risk register, monitor regularly, and follow escalation paths.
- **Retrospective & Continuous Improvement**: Capture learnings, create action items, and track improvements.
- **Roles & Personas**: Clear responsibilities for PM, PdM, developers, QA, and stakeholders.

## Process Documents

- [**Project Management Overview**](octoacme-project-management-overview.md) — Concise introduction to OctoAcme's approach, core roles, key artifacts, and high-level lifecycle
- [**Project Initiation Guide**](octoacme-project-initiation.md) — One-pager template, minimum deliverables, and initiation checklist to validate and authorize work
- [**Project Planning**](octoacme-project-planning.md) — Backlog creation, estimation, dependency management, and planning checklist
- [**Execution & Tracking**](octoacme-execution-and-tracking.md) — Team rhythm, project board workflows, PR conventions, quality gates, and execution checklist
- [**Risks & Communication**](octoacme-risks-and-communication.md) — Risk register template, risk lifecycle, stakeholder communication strategies, and escalation paths
- [**Release & Deployment**](octoacme-release-and-deployment.md) — Release types, pre-release requirements, deployment checklist, and rollback playbook
- [**Retrospective & Continuous Improvement**](octoacme-retrospective-and-continuous-improvement.md) — Retrospective structure, tracking improvements, and action item management
- [**Roles & Personas**](octoacme-roles-and-personas.md) — Role summaries and responsibilities for PM, Product Manager, Developers, QA, and Stakeholders

## Using These Docs

- **New to OctoAcme?** Start with [Project Management Overview](octoacme-project-management-overview.md) for a high-level introduction.
- **Starting a new project?** Follow the [Project Initiation Guide](octoacme-project-initiation.md) and [Project Planning](octoacme-project-planning.md).
- **Managing day-to-day delivery?** Reference [Execution & Tracking](octoacme-execution-and-tracking.md) and [Risks & Communication](octoacme-risks-and-communication.md).
- **Preparing for release?** Use [Release & Deployment](octoacme-release-and-deployment.md).
- **Improving processes?** Review [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md).
- **Understanding roles?** Consult [Roles & Personas](octoacme-roles-and-personas.md) to clarify responsibilities.

## Keeping Docs Current

These process documents are living artifacts. To propose updates, improvements, or new content:

1. Open an issue using the [Add Content to Project Management Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) template.
2. Describe the gap, improvement, or new content needed.
3. Engage stakeholders and the team for feedback.
4. Submit a pull request with your proposed changes for review.
