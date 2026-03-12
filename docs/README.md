# OctoAcme Project Management Docs

Welcome! This folder contains OctoAcme’s project management process documentation. It’s designed as a one-stop entry point for new team members and a consistent single source of truth for how we run cross-functional projects—from initiation through release and continuous improvement.

OctoAcme’s workflow follows a lightweight lifecycle: **Initiation** (validate the business need, identify stakeholders, define success criteria, and decide go/no-go), **Planning** (break work into shippable increments, define acceptance criteria and Definition of Done, estimate, and map milestones/releases), **Execution & Tracking** (deliver iteratively using a project board and a predictable team rhythm while managing risks/dependencies), **Release & Deployment** (ship with standardized pre-release requirements, deployment checklists, and post-deploy verification), and **Retrospective & Continuous Improvement** (capture learnings, define a small set of action items with owners/dates, and track follow-through in the backlog).

Roles and responsibilities are explicit to reduce ambiguity and speed up decisions. The **Project Manager (PM)** coordinates delivery, schedules, risks, and communications; the **Product Manager (PdM)** defines outcomes, prioritizes the backlog, and measures success; **Developers** design, build, test, and help identify technical risks; **QA/Testing** validates acceptance criteria and quality; and **Stakeholders** provide inputs and approvals. The docs in this folder use these personas consistently to clarify ownership across the lifecycle.

Communication and quality practices are embedded into day-to-day delivery. Teams follow a cadence of standups, weekly delivery syncs, and end-of-sprint/milestone demos, and use a project board with clear workflow states (Backlog → Ready → In Progress → In Review → QA → Done). Quality is reinforced via small PRs (<= 400 lines when possible), issue links + acceptance criteria in PR descriptions, CI checks (tests, linting, security scans) before review, required approvals before merge, and appropriate test coverage (unit tests for new logic, integration tests when applicable, and end-to-end smoke tests for critical flows before release). Risks are tracked in a risk register and escalated from team triage to PM/Product Lead and, when necessary, sponsor-level escalation.

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
