# OctoAcme Project Management — Documentation Overview

This folder contains the process documentation that defines how OctoAcme plans, executes, and ships work. The docs serve as a shared knowledge base for all team members and are intended to be added to a Copilot Space so that Copilot can use them as context when answering process-related questions.

---

## Project Lifecycle

OctoAcme projects follow five phases:

1. **Initiation** — Validate and authorize the work, align stakeholders, and produce a lightweight one-pager with problem statement, goals, success metrics, and initial risks.
2. **Planning** — Break the initiative into a prioritised backlog with acceptance criteria, agree on a release timeline and milestones, and document the Definition of Done.
3. **Execution & Tracking** — Build, test, and iterate via short sprints. Track progress on a project board, run daily standups, and escalate blockers through a clear three-level path.
4. **Release & Deployment** — Verify all acceptance criteria, run smoke tests on staging, deploy through an automated pipeline, and announce the release to stakeholders.
5. **Retrospective & Close** — Capture what went well and what to improve, commit 2–3 action items to the backlog, and follow up on them in subsequent syncs.

---

## Key Roles

| Role | Core Responsibility |
|------|---------------------|
| **Project Manager (PM)** | Coordinates delivery, schedules, risks, and cross-team communication |
| **Product Manager (PdM)** | Owns the product vision, prioritises the backlog, and measures outcomes |
| **Developers** | Design, implement, and test features to meet acceptance criteria |
| **QA / Testing** | Validate quality and acceptance criteria before release |
| **Stakeholders** | Provide inputs, approvals, and receive regular status updates |

See [`octoacme-roles-and-personas.md`](octoacme-roles-and-personas.md) for detailed persona descriptions.

---

## Core Artifacts

- **Project One-pager / Charter** — Problem statement, goals, success metrics, and stakeholder list created during initiation.
- **Roadmap & Release Plan** — Milestone map and release schedule agreed during planning.
- **Sprint / Iteration Backlog** — Prioritised, estimated work items with acceptance criteria and owners.
- **Definition of Done (DoD)** — Team-agreed quality gate that every item must pass before it is considered complete.
- **Risk Register** — Living table of risks with impact, likelihood, owner, and mitigation status.
- **Retrospective Notes** — What went well, what to improve, and the resulting action items.

---

## Communication & Risk Practices

- **Weekly PM + PdM sync** — Alignment on priorities, risks, and upcoming milestones.
- **Twice-weekly standups** — Progress, blockers, and dependency updates for the delivery team.
- **Monthly stakeholder updates** — High-level status, key decisions, and upcoming releases.
- **Weekly status template** — Progress, next steps, risks/blockers, and decisions needed.
- **Risk lifecycle** — Identify → Assess (impact × likelihood) → Mitigate → Monitor; reviewed at every weekly sync.
- **Escalation path** — Team standup → PM → Product Lead → Sponsor; security incidents follow the security incident runbook.

See [`octoacme-risks-and-communication.md`](octoacme-risks-and-communication.md) for templates and escalation details.

---

## Release & Retrospective Flow

**Before a release**, confirm that all acceptance criteria are met, CI and security scans pass, release notes are drafted, and a rollback plan exists. Deploy to staging first, then promote to production via an automated pipeline, run post-deploy verifications, and announce to stakeholders.

**After each sprint or release**, run a timeboxed retrospective (45–75 minutes). Identify 2–3 actionable improvements, assign owners and due dates, and track progress in the backlog. Review outstanding actions in the weekly PM sync to close the loop.

See [`octoacme-release-and-deployment.md`](octoacme-release-and-deployment.md) and [`octoacme-retrospective-and-continuous-improvement.md`](octoacme-retrospective-and-continuous-improvement.md) for checklists and templates.

---

## Document Index

| Document | Description |
|----------|-------------|
| [`octoacme-project-management-overview.md`](octoacme-project-management-overview.md) | High-level principles, roles, artifacts, and lifecycle summary |
| [`octoacme-project-initiation.md`](octoacme-project-initiation.md) | Initiation checklist, one-pager template, and decision gate |
| [`octoacme-project-planning.md`](octoacme-project-planning.md) | Backlog setup, sprint planning, and dependency management |
| [`octoacme-execution-and-tracking.md`](octoacme-execution-and-tracking.md) | Team rhythm, PR workflow, quality standards, and metrics |
| [`octoacme-risks-and-communication.md`](octoacme-risks-and-communication.md) | Risk register format, stakeholder communication, and escalation paths |
| [`octoacme-release-and-deployment.md`](octoacme-release-and-deployment.md) | Release types, deployment checklist, and rollback playbook |
| [`octoacme-retrospective-and-continuous-improvement.md`](octoacme-retrospective-and-continuous-improvement.md) | Retrospective structure, action item template, and improvement culture |
| [`octoacme-roles-and-personas.md`](octoacme-roles-and-personas.md) | Detailed persona definitions for Developers, Product Managers, and Project Managers |

---

## How to Use These Docs

1. **Onboarding** — New team members should start with the [overview](octoacme-project-management-overview.md) and [roles](octoacme-roles-and-personas.md) documents to understand the process and their responsibilities.
2. **Running a project** — Follow the phase-specific documents (initiation → planning → execution → release → retrospective) and use the included checklists and templates.
3. **Copilot Spaces** — Add this `docs/` folder (or specific files) to your Copilot Space so that Copilot can answer process questions with accurate, project-specific context.
4. **Keeping docs current** — Update the relevant document whenever a process changes so that Copilot Spaces always reflects the latest team practices.
