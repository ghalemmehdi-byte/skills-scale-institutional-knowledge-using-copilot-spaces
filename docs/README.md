# OctoAcme Project Management Docs

Welcome! This folder contains OctoAcme’s project management process documentation. It’s designed as a one-stop entry point for new team members and a consistent “single source of truth” for how we run cross-functional projects—from initiation through release and continuous improvement.

OctoAcme’s workflow follows a lightweight lifecycle: **Initiation** (validate the business need, identify stakeholders, define success metrics, and make a go/no-go decision), **Planning** (break work into shippable increments, define acceptance criteria and Definition of Done, estimate, and map milestones/releases), **Execution** (deliver in small increments with disciplined tracking and visible risk management), **Release** (deploy with standardized checklists, verification, and communications), and **Retrospective/Close** (capture learnings and feed improvements back into the backlog and team habits). Key artifacts include the **Project Charter / One-pager**, roadmap and release plan, sprint/iteration backlog, acceptance criteria/DoD, a **risk register**, and retrospective action items.

Roles are intentionally explicit to reduce ambiguity and speed decisions. The **Project Manager (PM)** coordinates delivery, schedules, risks, and communications; the **Product Manager (PdM)** defines outcomes, prioritizes the backlog, and measures success; **Developers** design, implement, and test changes while contributing to estimates and risk mitigation; **QA/Testing** validates quality and acceptance criteria; and **Stakeholders** provide inputs and approvals. These roles show up throughout the lifecycle, especially in kickoff/planning alignment, review/acceptance, and release communications.

Communication and quality practices are embedded into day-to-day execution. Teams use a predictable cadence (daily standups, weekly delivery syncs, and sprint/milestone demos) and track work on a project board with clear states (Backlog → Ready → In Progress → In Review → QA → Done). Quality is enforced through small PRs (<= 400 lines when possible), issue links and acceptance criteria in PRs, CI checks (tests, linting, security scanning), at least one approval before merge (or team policy), and appropriate test coverage (unit tests, integration tests where applicable, and end-to-end smoke tests for critical flows before release). Risks and blockers follow a defined escalation path from team triage to PM/Product Lead and, when needed, sponsor-level escalation.

---

## Process Documents

- [Project Management Overview](octoacme-project-management-overview.md)
- [Project Initiation Guide](octoacme-project-initiation.md)
- [Project Planning](octoacme-project-planning.md)
- [Execution & Tracking](octoacme-execution-and-tracking.md)
- [Risk Management & Communication](octoacme-risks-and-communication.md)
- [Release & Deployment Guide](octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)
- [Roles and Personas](octoacme-roles-and-personas.md)
