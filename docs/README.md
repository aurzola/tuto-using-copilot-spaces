# OctoAcme Project Management Docs

Welcome! This README centralizes all key OctoAcme program/project management process documentation and serves as a friendly entry point for new teammates to quickly understand where to find and how to use these documents.

## OctoAcme Project Management Process Overview

OctoAcme employs a structured, lifecycle-based approach to project management that emphasizes stakeholder alignment, iterative delivery, and data-driven decision-making. The framework operates across five distinct phases: **Initiation**, **Planning**, **Execution**, **Release**, and **Closure/Retrospective**.

### Key Workflows & Phases

**Initiation** validates business need and creates a lightweight Project One-pager that captures the problem statement, success metrics, stakeholders, and resource requirements. This serves as a decision gate—work only advances to planning when success metrics are clear, stakeholder agreement is secured, and team availability is confirmed.

**Planning** transforms the approved initiative into an actionable backlog by breaking work into shippable increments, estimating scope, defining a Definition of Done, and creating a release plan with identified dependencies.

**Execution** follows a structured cadence of daily standups (15 minutes), weekly delivery syncs, and sprint-based iterations using a project board with columns spanning Backlog, Ready, In Progress, In Review, QA, and Done. Pull requests are kept small (≤400 lines), include issue links and acceptance criteria, and require at least one approval before merging. Quality is maintained through unit tests, integration tests, end-to-end smoke tests, security scanning, and manual QA when needed.

**Release & Deployment** follows a standardized process with pre-release requirements including passing CI/security scans, drafted release notes, and a documented rollback plan. Deployments proceed through staging with smoke tests before production, followed by post-deploy verification and stakeholder announcement.

**Retrospectives** are held after each sprint, release, or milestone. These timeboxed sessions (45–75 minutes) capture what went well, what could improve, and generate 2–3 prioritized action items with clear owners and due dates.

### Roles & Personas

OctoAcme defines clear roles to ensure accountability and coordination:

- **Project Managers (PMs)** coordinate delivery, manage schedules, risks, and communications
- **Product Managers (PdMs)** define outcomes, prioritize the backlog, and measure success
- **Developers** implement features, collaborate on design, and maintain test coverage
- **QA/Testing** validates quality against acceptance criteria
- **Stakeholders** provide inputs and approvals

### Communication & Risk Management

Communication happens at multiple levels:
- Daily standups and sprint planning
- Weekly PM/PdM syncs
- Twice-weekly standups for the delivery team
- Monthly stakeholder updates
- Ad-hoc escalations as needed

A **Risk Register** is maintained throughout execution, capturing risk ID, description, impact/likelihood, owner, mitigation plan, and status. Risks are assessed during planning and monitored weekly. The organization maintains a formal escalation path for blockers: team-level triage → PM → Product Lead → Sponsor.

## Documentation Index

Below are the detailed process guides. Start with the **Project Management Overview** for a quick reference, then dive into the specific phase you're working on.

### Getting Started
- **[Project Management Overview](./octoacme-project-management-overview.md)** — High-level introduction to how OctoAcme runs projects, core roles, key artifacts, and lifecycle phases

### Phase-Specific Guides
- **[Project Initiation Guide](./octoacme-project-initiation.md)** — Validate business need, align stakeholders, and create a lightweight plan
- **[Project Planning](./octoacme-project-planning.md)** — Break work into shippable increments, estimate scope, and create a release plan
- **[Execution & Tracking](./octoacme-execution-and-tracking.md)** — Manage day-to-day execution, agile workflows, quality assurance, and escalation
- **[Release & Deployment Guide](./octoacme-release-and-deployment.md)** — Standardize releases, deployments, rollback procedures, and release notes

### Cross-Cutting Concerns
- **[Risk Management & Communication](./octoacme-risks-and-communication.md)** — Identify, manage, and communicate risks and dependencies throughout the project lifecycle
- **[Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)** — Capture learnings and convert them into actionable improvements

### Reference
- **[Roles & Personas](./octoacme-roles-and-personas.md)** — Detailed definitions of typical roles and responsibilities used in OctoAcme projects

## How to Use These Docs

1. **For new team members:** Start with the [Project Management Overview](./octoacme-project-management-overview.md) to understand the big picture, then explore phase-specific docs as needed.

2. **For project execution:** Keep the relevant phase guide open as a checklist and reference during your project. Each guide includes templates, checklists, and example artifacts.

3. **Keeping these docs current:** As processes evolve and new best practices emerge, propose updates using the [Add Content to Project Management Process Docs issue template](.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml). All updates should be reviewed with the team to ensure alignment.

4. **Storing project artifacts:** Keep your Project Charter and process documentation in your project repository. Store core docs in `docs/` and consider adding Copilot Space context in `.copilot/` to enable AI-assisted guidance specific to your project.

---

_Last updated: May 2026_  
_Edit this README as new process docs are added or processes evolve!_