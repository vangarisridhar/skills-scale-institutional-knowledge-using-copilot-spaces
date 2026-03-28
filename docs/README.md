# OctoAcme Project Management Docs

Welcome to the OctoAcme Project Management Docs! This folder contains the standardized processes and guidance that enable OctoAcme teams to deliver projects efficiently, predictably, and with continuous improvement.

## Project Management Processes Overview

OctoAcme follows a structured project lifecycle divided into five key phases: **Initiation**, **Planning**, **Execution**, **Release**, and **Close & Retrospective**. 

**During initiation**, teams validate business need by creating a lightweight One-pager that outlines the problem statement, objectives, success metrics, stakeholders, and initial timeline. Once stakeholders approve, the project moves to planning, where work is broken into shippable increments with clear acceptance criteria, dependencies are identified, and a Definition of Done is established. The planning phase culminates in a prioritized backlog and release plan. **During execution**, teams focus on iterative delivery through daily standups, sprint planning, and continuous quality assurance, with progress tracked on a GitHub Projects board (Backlog → Ready → In Progress → In Review → QA → Done). Throughout all phases, OctoAcme emphasizes data-informed decisions, psychological safety, and customer-first prioritization.

**OctoAcme operates with clear ownership** across four primary personas: **Project Managers** coordinate delivery, manage schedules, risks, and communications; **Product Managers** define what should be built, prioritize the roadmap, and measure outcomes; **Developers** implement features with high quality and maintainability; and **QA/Testing** validates acceptance criteria and quality standards. This role clarity is reinforced through a consistent communication cadence: daily standups (15 minutes) focus on progress and blockers, weekly syncs align the PM and Product Manager, twice-weekly standups keep the delivery team synchronized, and monthly stakeholder updates provide visibility. Risk escalation follows a three-level path—team-level triage in standups, PM escalation to Product Lead and dependent teams, and sponsor-level escalation for business-impacting issues.

**Quality and risk management** are embedded throughout execution via unit tests, integration tests, end-to-end smoke tests, security scanning in CI, and manual QA for feature acceptance. A Risk Register tracks potential issues by ID, description, impact, likelihood, owner, and mitigation plan, with risks reviewed at weekly syncs. Before release, teams ensure all acceptance criteria are met, CI and security scans pass, release notes are drafted, and smoke tests are prepared. Deployments follow a staged approach—first to staging with verification, then to production via an automated pipeline when possible—with documented rollback and incident playbooks. After each sprint, release, or milestone, teams conduct a 45–75 minute retrospective to capture learnings and convert them into actionable improvements tracked in the project backlog with clear owners and due dates.

## Process Document Links

Use these guides to understand and implement each phase of OctoAcme project management:

- **[Project Management Overview](octoacme-project-management-overview.md)** — High-level introduction to OctoAcme's approach, principles, core roles, and key artifacts.

- **[Project Initiation Guide](octoacme-project-initiation.md)** — Steps to validate business need, align stakeholders, and authorize work with a lightweight One-pager and decision gate.

- **[Project Planning Guide](octoacme-project-planning.md)** — Turn an approved initiative into an actionable plan with prioritized backlog, acceptance criteria, and release milestones.

- **[Execution & Tracking Guide](octoacme-execution-and-tracking.md)** — Guidance for managing day-to-day execution, sprint rhythm, quality assurance, and blocker escalation.

- **[Risk Management & Communication Guide](octoacme-risks-and-communication.md)** — How to identify, manage, and communicate risks and dependencies throughout the project lifecycle.

- **[Release & Deployment Guide](octoacme-release-and-deployment.md)** — Standardized approach to releasing features to production, including pre-release requirements, deployment checklist, and rollback procedures.

- **[Retrospective & Continuous Improvement Guide](octoacme-retrospective-and-continuous-improvement.md)** — How to capture learnings after each sprint or milestone and convert them into actionable improvements.

- **[Roles and Personas](octoacme-roles-and-personas.md)** — Detailed definitions of key project roles: Developers, Product Managers, and Project Managers.

## Using These Docs

- **For new projects:** Start with the [Project Management Overview](octoacme-project-management-overview.md) and then follow the lifecycle phase guides in order.
- **For role-specific guidance:** Refer to [Roles and Personas](octoacme-roles-and-personas.md) for responsibilities and typical communication patterns.
- **For Copilot Spaces context:** These docs are also available in `.copilot/` to ground Copilot in OctoAcme's standardized practices.
- **For process updates:** Use the [Add Content to Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) issue template to propose improvements.

---

**Last Updated:** 2026-03-28  
**Maintained by:** OctoAcme Project Management Community
