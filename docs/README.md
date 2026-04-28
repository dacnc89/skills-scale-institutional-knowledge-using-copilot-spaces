# OctoAcme Project Management Docs

Welcome to the OctoAcme Project Management documentation. This README provides a concise overview of how OctoAcme runs projects and serves as a starting point for onboarding. For full details, follow the links to each process document below.

---

## Project Management Overview

OctoAcme follows a lightweight, end-to-end lifecycle: **Initiation → Planning → Execution → Release → Retrospective**. The approach is grounded in four core principles: customer-first prioritization, iterative delivery in small increments, clear ownership, and data-informed decision-making. Every project begins with a **Project Charter** that defines the problem, objective, success metrics, and stakeholders before any execution begins.

See: [Project Management Overview](octoacme-project-management-overview.md)

---

## Roles & Personas

Roles are explicitly defined to reduce ambiguity and accelerate coordination:

| Role | Primary Responsibility |
|---|---|
| **Project Manager (PM)** | Plans, tracks timelines, manages risks, and facilitates communications |
| **Product Manager (PdM)** | Defines outcomes, owns the backlog, and measures success |
| **Developer** | Implements features, writes tests, participates in design and code review |
| **QA/Testing** | Validates acceptance criteria and overall quality |
| **Stakeholder** | Provides input, reviews progress, and approves deliverables |

See: [Roles and Personas](octoacme-roles-and-personas.md)

---

## Planning & Execution

During **Planning**, teams break approved scope into shippable increments with acceptance criteria, estimates, a Definition of Done, and mapped dependencies. During **Execution**, work flows through a project board (Backlog → Ready → In Progress → In Review → QA → Done) using a pull-request workflow: keep PRs focused, link to issues, run automated checks, and require at least one approval before merging.

See: [Project Initiation Guide](octoacme-project-initiation.md) · [Project Planning Guide](octoacme-project-planning.md) · [Execution & Tracking](octoacme-execution-and-tracking.md)

---

## Communication & Risk Management

Communication follows a predictable cadence—daily standups, weekly delivery syncs, periodic demos, PM+PdM alignment meetings, and monthly stakeholder updates. Blockers escalate from team triage → PM escalation → sponsor escalation. Risks are tracked in a **Risk Register** and reviewed regularly to identify mitigations before they become blockers.

See: [Risk Management & Communication](octoacme-risks-and-communication.md)

---

## Quality Assurance & Release

Quality is built into the workflow: unit tests cover new logic, integration tests cover key interactions, and end-to-end smoke tests cover critical flows, all backed by security scanning in CI. Releases are categorized (patch/minor/major) and require acceptance criteria to be met, CI/security scans passing, release notes drafted, and a rollback plan documented before deployment. Post-deploy checks and stakeholder announcements complete each release.

See: [Release & Deployment Guide](octoacme-release-and-deployment.md)

---

## Continuous Improvement

After each release or milestone, teams hold a blameless **retrospective** to identify what went well, what can improve, and to produce a small set of owned, time-bound action items. Those items are added to the backlog and reviewed in ongoing PM syncs to ensure learning translates into real process change.

See: [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)

---

*Use these documents as a reference for processes, templates, and expectations throughout your project lifecycle.*
