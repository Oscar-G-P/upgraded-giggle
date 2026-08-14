# OctoAcme Project Management Documentation

Welcome to OctoAcme's centralized project management resource library. These documents capture how we initiate, plan, execute, release, and continuously improve projects at OctoAcme. They provide principles, role definitions, workflows, and templates to help teams deliver predictable value.

OctoAcme runs projects through a staged, iterative lifecycle: Initiation → Planning → Execution & Tracking → Release & Deployment → Retrospective. Initiation focuses on a lightweight one-pager to align stakeholders and define success metrics. Planning breaks approved work into prioritized, estimated backlog items with clear acceptance criteria and a Definition of Done. Execution uses a project board (Backlog → Ready → In Progress → In Review → QA → Done), small pull requests, CI and security checks, and a regular team rhythm (daily standups, weekly delivery syncs, and sprint demos) to keep work flowing and blockers visible. Releases require passing CI, smoke tests, release notes, and a rollback plan. After delivery, retrospectives capture learnings and convert them into action items tracked in the backlog.

Key roles are explicitly defined: Product Managers set outcomes and prioritize work; Project Managers coordinate plans, risks, and communications; Developers implement, test, and document features; QA validates acceptance criteria and quality. These role definitions help ensure clear ownership across artifacts such as the project one-pager, backlog items, release notes, and the risk register.

Quality assurance is embedded in the pipeline: unit and integration tests, end-to-end smoke tests for critical flows, manual QA as needed, and security scanning in CI. Risks are tracked in a simple register (ID, impact, likelihood, owner, mitigation) and escalated through defined paths (team → PM → Product Lead → Sponsor). Stakeholder communications use templates and a single source of truth in this docs folder.

## Quick Start / Lifecycle
1. Initiation — create and review Project One-pager
2. Planning — prioritize, estimate, and plan releases
3. Execution & Tracking — implement, test, review, and track progress
4. Release & Deployment — stage, release, verify, and announce
5. Retrospective — capture learnings and convert to backlog items

## Core Documentation
- [OctoAcme Project Management Overview](./octoacme-project-management-overview.md)
- [Project Initiation Guide](./octoacme-project-initiation.md)
- [Project Planning](./octoacme-project-planning.md)
- [Execution & Tracking](./octoacme-execution-and-tracking.md)
- [Risk Management & Communication](./octoacme-risks-and-communication.md)
- [Release & Deployment Guide](./octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)
- [Roles & Personas](./octoacme-roles-and-personas.md)

## For new team members
Start with the Project Management Overview to learn principles and roles, then follow the Quick Start lifecycle to find the phase-specific guidance relevant to your role. Use the backlog templates, acceptance criteria, and risk register described in the linked docs to keep work discoverable and actionable.
