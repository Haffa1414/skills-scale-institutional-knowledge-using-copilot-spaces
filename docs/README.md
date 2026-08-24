# OctoAcme Project Management Documentation

## Overview
OctoAcme follows a structured, iterative approach to project management designed to centralize institutional knowledge and make delivery predictable. Projects move through a clear lifecycle — Initiation, Planning, Execution & Tracking, Release & Deployment, and Retrospective & Continuous Improvement — with a focus on delivering small, testable increments, clear ownership, and data-informed decisions.

## Quick Navigation
- [Project Management Overview](./octoacme-project-management-overview.md)
- [Project Initiation Guide](./octoacme-project-initiation.md)
- [Project Planning](./octoacme-project-planning.md)
- [Execution & Tracking](./octoacme-execution-and-tracking.md)
- [Risk Management & Communication](./octoacme-risks-and-communication.md)
- [Release & Deployment Guide](./octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)
- [Roles & Personas](./octoacme-roles-and-personas.md)

## Brief summary of OctoAcme project management processes
OctoAcme runs projects through a clear, iterative lifecycle: Initiation (one‑pager, stakeholder alignment, go/no‑go), Planning (kickoff, prioritized backlog, estimates, Definition of Done), Execution (small PRs, CI, code reviews, project board columns from Backlog to Done), and Release (pre‑release checks, automated deployment, smoke tests, rollback plan), followed by Close & Retrospective. Work is organized into shippable increments with a focus on small, reviewable pull requests and explicit acceptance criteria; teams use a project board to drive day‑to‑day flow and track progress against milestones and velocity metrics.

Roles and responsibilities are explicit. Product Managers define outcomes, prioritize the backlog, and own success metrics; Project Managers coordinate schedules, risks, and communications; Developers implement features, write tests, and participate in reviews; QA validates acceptance criteria via unit, integration, and end‑to‑end smoke tests. The docs also describe persona usage for exercises and encourage clear ownership for risks and action items.

Communication and quality practices are formalized: daily standups for blockers and progress, weekly delivery syncs and PM/PdM check‑ins, regular demos at sprint or milestone end, and monthly stakeholder updates. Quality assurance is enforced through automated testing and security scans in CI, manual QA when needed, and post‑deploy verifications. Risk management uses a lightweight risk register (ID, impact, likelihood, owner, mitigation, status) plus an escalation path (team → PM → Product Lead → Sponsor) and templates for weekly status and release notes to keep stakeholders aligned.

## How to use these docs
- New to OctoAcme? Start with the Project Management Overview for the big picture.
- Starting a new project? Follow: Initiation → Planning → Execution & Tracking.
- Keep your project charter updated in your project repo and add process-specific docs into `.copilot/` if you want Copilot Spaces to use them as context.
