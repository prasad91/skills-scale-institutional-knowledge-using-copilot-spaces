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

## Delivery Lead

### Role Summary
Delivery Leads coordinate day-to-day delivery activities across multiple teams, manage cross-team dependencies, track milestone progress, and serve as the primary escalation point for execution blockers. They work closely with Project Managers to ensure delivery cadence and with team leads to remove impediments.

### Responsibilities
- Coordinate daily standup and delivery sync meetings
- Track progress against milestones and sprints
- Identify and escalate cross-team dependencies and blockers
- Manage capacity allocation and resource conflicts
- Monitor delivery metrics (velocity, burndown, cycle time)
- Facilitate integration points between teams

### Goals
- Maintain consistent delivery velocity
- Minimize dependency-driven delays
- Enable teams to sustain high-quality output
- Provide real-time visibility into delivery status

### Typical Communication
- Daily standup facilitation
- Weekly delivery sync with PM and team leads
- Risk and blocker escalation to PM
- Capacity planning with Engineering Managers
- Milestone handoff meetings

---

## Release Manager

### Role Summary
Release Managers own the end-to-end release orchestration process, including release planning, deployment sequencing, validation, and rollback procedures. They coordinate with developers, QA, SRE, and support teams to ensure smooth, low-risk releases.

### Responsibilities
- Create and maintain release schedules and deployment windows
- Coordinate release readiness reviews (code complete, testing, documentation)
- Own release notes and changelog production
- Execute deployment procedures and validate post-deploy stability
- Document and maintain rollback plans and runbooks
- Communicate release status to stakeholders and support teams

### Goals
- Achieve zero-downtime or minimal-impact deployments
- Reduce release-related incidents and rollbacks
- Ensure rapid incident response if issues occur
- Maintain clear communication throughout the release cycle

### Typical Communication
- Pre-release readiness meetings with developers, QA, SRE
- Release status updates to stakeholders and support
- Post-deploy verification with SRE and QA
- Incident escalation and rollback coordination
- Release retrospectives and post-mortems

---

## Site Reliability / Platform Owner (SRE)

### Role Summary
SRE/Platform Owners define production operability requirements, own runbook development, manage incident response protocols, and ensure infrastructure reliability. They work with developers on observability, with Release Managers on deployment readiness, and with Project Managers on operational risks.

### Responsibilities
- Define production readiness and operational acceptance criteria
- Develop and maintain runbooks for common operational scenarios
- Design monitoring, alerting, and observability strategies
- Manage incident response protocols and on-call rotations
- Conduct post-incident analysis and drive continuous improvement
- Advise on capacity planning and scalability requirements
- Participate in deployment planning and rollback procedures

### Goals
- Maintain high system availability and reliability
- Enable rapid detection and resolution of production issues
- Reduce mean time to recovery (MTTR) for incidents
- Build operational knowledge and institutional memory

### Typical Communication
- Pre-release readiness reviews with Release Manager and developers
- Incident response and escalation procedures
- Weekly operational metrics reviews
- Capacity planning sessions with PM and Engineering Managers
- Architectural design reviews for operability concerns

---

## Security & Compliance Owner

### Role Summary
Security & Compliance Owners review security requirements, run security scans and assessments, approve risk mitigations for sensitive changes, and ensure compliance controls are followed. They engage during planning and before release to identify and mitigate security risks.

### Responsibilities
- Review acceptance criteria and designs for security implications
- Perform threat modeling and security assessments
- Run security scanning in CI/CD pipelines
- Approve security mitigations and risk acceptance decisions
- Ensure compliance with regulatory and organizational standards
- Advise developers on secure coding practices
- Escalate residual risks to Product Lead and Sponsor

### Goals
- Prevent security vulnerabilities from reaching production
- Enable compliance with regulatory requirements
- Build security awareness across the team
- Minimize security-related incidents and audit findings

### Typical Communication
- Security review meetings during planning phase
- Pre-release security sign-off
- Vulnerability assessment and remediation planning
- Security training and guidance for developers
- Incident response for security-related issues

---

## UX / Product Designer

### Role Summary
UX/Product Designers drive interaction and visual design, validate usability through research and testing, produce design specifications and assets, and participate in acceptance criteria definition. They collaborate closely with Product Managers on user needs and with developers to ensure implementability.

### Responsibilities
- Conduct user research and usability validation
- Create wireframes, mockups, and high-fidelity designs
- Define interaction patterns and design systems
- Participate in feature acceptance criteria definition
- Validate designs with QA and developers for implementability
- Maintain design documentation and component libraries
- Participate in post-release review of actual user experience

### Goals
- Deliver intuitive, user-centered solutions
- Reduce design-related rework and user confusion
- Build consistent, recognizable product experiences
- Maximize user satisfaction and adoption

### Typical Communication
- Design critique sessions with team
- Weekly alignment with Product Manager on requirements
- Design review with developers before implementation
- QA collaboration on acceptance testing criteria
- Post-release user feedback collection

---

## Data / Measurement Lead

### Role Summary
Data/Measurement Leads define success metrics aligned with project goals, set up tracking and instrumentation, validate data quality, and produce post-release metric analysis. They work with Product Managers to ensure metrics drive decisions and with developers to implement instrumentation.

### Responsibilities
- Define SMART success metrics during planning
- Design data collection and instrumentation strategy
- Implement or configure analytics tracking
- Validate data accuracy and identify quality issues
- Produce weekly metric reports and dashboards
- Conduct post-release impact analysis
- Identify leading indicators for early warning

### Goals
- Enable data-driven decision making throughout the project
- Quantify the impact and value delivered
- Detect issues early through leading indicators
- Build institutional knowledge of what works

### Typical Communication
- Metrics definition workshop during planning
- Weekly metric reviews in stakeholder syncs
- Data quality and instrumentation reviews with developers
- Post-release impact analysis and retrospectives
- Ad-hoc analysis for decision support

---

## Technical Writer / Documentation Owner

### Role Summary
Technical Writers produce end-user documentation, API documentation, runbooks, and release notes. They ensure documentation is discoverable, current, and useful to developers, support teams, and customers. They collaborate with developers to understand features and with Release Managers to ensure release-ready documentation.

### Responsibilities
- Write end-user guides and tutorials
- Create API documentation and code examples
- Develop operational runbooks with SRE and Release Manager
- Maintain product README and architecture documentation
- Ensure documentation is discoverable and searchable
- Update documentation for releases and breaking changes
- Gather feedback from users and support teams

### Goals
- Reduce support burden through clear, accessible documentation
- Enable self-service for users and operational teams
- Maintain documentation quality and accuracy
- Accelerate onboarding for developers and users

### Typical Communication
- Technical discussions with developers on feature details
- Runbook reviews with SRE and Release Manager
- Release note coordination before deployments
- Support team feedback collection
- Documentation quality reviews

---

## Support / Customer Success Liaison

### Role Summary
Support/Customer Success Liaisons represent customer-facing concerns in product and engineering decisions. They triage incoming customer issues, provide feedback on user impact, prepare knowledge base articles, and ensure customer voices are heard in project prioritization.

### Responsibilities
- Triage and prioritize incoming customer issues
- Identify patterns and recurring customer problems
- Provide feedback on customer impact and business priorities
- Reproduce and document customer-reported issues
- Prepare knowledge base articles and troubleshooting guides
- Participate in acceptance testing and usability review
- Represent customer needs in prioritization discussions

### Goals
- Reduce customer-reported issues and support volume
- Improve first-contact resolution rate
- Enable proactive issue identification
- Align product roadmap with customer needs

### Typical Communication
- Weekly customer issue summary to PM and Product Lead
- Participation in planning and prioritization meetings
- Issue reproduction and documentation with developers
- Knowledge base article creation with Technical Writer
- Customer feedback collection and reporting

---

## How these personas are used in the exercise

- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Refer to specific personas when defining responsibilities, escalation paths, and communication patterns in project documentation.
- Use persona interaction maps to identify dependencies and plan handoff points between roles.
