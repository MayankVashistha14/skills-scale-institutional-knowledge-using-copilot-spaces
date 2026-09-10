# OctoAcme Project Management Docs

## Overview

OctoAcme runs projects using an iterative, outcome-focused approach with clear roles, lightweight artifacts, and a defined lifecycle: Initiation, Planning, Execution, Release, and Close. Our processes prioritize customer value, incremental delivery, and data-informed decisions while maintaining psychological safety to encourage continuous improvement.

This docs/ folder is the single entry point for the OctoAcme project management guidance — use it to onboard new teammates, align stakeholders, and operate consistently across projects.

## Quick Start for New Team Members

Start with the Project Management Overview to understand core roles, principles, and the project lifecycle. Then read the Project Initiation and Project Planning docs to see how to propose and prepare work. During delivery, use Execution & Tracking and Risks & Communication to run day-to-day work and escalate blockers. Finally, follow the Release & Deployment and Retrospective guides to ship and learn.

## Documentation

### Project Lifecycle
1. [Project Management Overview](octoacme-project-management-overview.md) — Core roles, principles, and lifecycle
2. [Project Initiation](octoacme-project-initiation.md) — Validate needs, align stakeholders, and decide go/no-go
3. [Project Planning](octoacme-project-planning.md) — Backlog, estimates, Definition of Done, and release planning
4. [Execution & Tracking](octoacme-execution-and-tracking.md) — Day-to-day delivery practices, PR workflow, and team rhythm
5. [Release & Deployment](octoacme-release-and-deployment.md) — Pre-release checks, deployment steps, and rollback playbook
6. [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) — Capture learnings and track improvement actions

### Supporting Processes
- [Risk Management & Communication](octoacme-risks-and-communication.md) — Risk register, stakeholder updates, and escalation paths
- [Roles & Personas](octoacme-roles-and-personas.md) — Descriptions of Developers, Product Managers, Project Managers, and other stakeholders

## Key Principles
- Customer-first: prioritize customer value and usability
- Iterative delivery: deliver small, testable increments
- Clear ownership: each project has a named PM and Product Lead
- Data-informed: measure impact and iterate based on evidence
- Psychological safety: encourage feedback and learning

---

## Brief Summary of OctoAcme Project Management Processes

OctoAcme runs projects as iterative, outcome-focused efforts with a clear lifecycle: Initiation (one‑pager, stakeholder alignment, go/no‑go), Planning (kickoff, prioritized backlog, estimates, Definition of Done), Execution (small increments, PRs, CI, reviews), Release (checklists, smoke tests, rollback plan), and Close (retrospectives and action‑item follow up). Core artifacts include the Project One‑pager, roadmap/release plan, sprint backlog, acceptance criteria, and a living Risk Register.

Workflows are standardized to reduce friction and risk. Teams use a project board with columns (Backlog → Ready → In Progress → In Review → QA → Done), a lightweight backlog/item template, and timeboxed sprint planning. The PR workflow emphasizes small, testable changes, linking PRs to issues and acceptance criteria, running automated tests and linters in CI before review, and requiring approvals before merging.

Roles and communication are explicit: Product Manager (defines outcomes and metrics), Project Manager (coordinates delivery, risks, schedules), Developers (implement and test), QA (validate quality), and Stakeholders (input and approvals). Cadence includes daily standups, weekly delivery syncs, sprint demos, and monthly stakeholder updates. Escalation is tiered (team → PM → Product Lead → Sponsor) to surface and resolve blockers quickly.

Quality assurance, release hygiene, and continuous improvement are built into the process. QA expectations include unit and integration tests, end‑to‑end smoke tests for critical flows, security scans in CI, and manual QA as needed. Releases follow pre‑release and deployment checklists and have rollback/incident playbooks. Retrospectives capture learnings and add prioritized action items back into the backlog to ensure improvements are tracked.
