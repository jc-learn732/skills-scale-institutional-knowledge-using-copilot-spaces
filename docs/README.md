# OctoAcme — Project Management Process Docs

This folder collects the OctoAcme project management process documentation in one place. Use this README as the central hub to understand our lifecycle, roles, key artifacts, and how to contribute or find the right process guidance.

## Brief overview of OctoAcme project management processes
OctoAcme follows a lightweight, stage-gated lifecycle that moves work from Initiation through Planning, Execution, Release, and Close. Initiation begins with a concise Project One‑pager that captures the problem, objectives, measurable success criteria, stakeholders, and an initial risk list; a decision gate confirms alignment and capacity before moving into planning. Planning turns the approved initiative into a prioritized backlog with acceptance criteria, estimates, a Definition of Done, and a release/milestone map while capturing dependencies and maintaining a Risk Register.

Execution emphasizes predictable, observable delivery: teams use a project board (Backlog → Ready → In Progress → In Review → QA → Done) and a disciplined Pull Request workflow (small PRs, link issues and acceptance criteria, run CI and lint, require approvals). Day‑to‑day cadence includes short daily standups for progress and blockers, weekly delivery syncs for status and escalations, and demos at the end of sprints or milestones. Communication is structured with weekly PM+PdM syncs, regular stakeholder updates, and a clear escalation path from team -> PM -> Product Lead -> Sponsor.

Quality assurance is integrated across the lifecycle: unit and integration tests for new logic, end‑to‑end smoke tests for critical flows, security scanning in CI, and manual QA when needed. Releases are gated by pre‑release checks (passing CI and security scans, release notes, rollback plan), staging smoke tests, and automated deployment pipelines where possible. Post‑release and incident learnings are captured through retrospectives and tracked action items to support continuous improvement.

## Documentation (links)
- [Project Management Overview](docs/octoacme-project-management-overview.md)
- [Project Initiation Guide](docs/octoacme-project-initiation.md)
- [Project Planning](docs/octoacme-project-planning.md)
- [Execution & Tracking](docs/octoacme-execution-and-tracking.md)
- [Risk Management & Communication](docs/octoacme-risks-and-communication.md)
- [Release & Deployment Guide](docs/octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](docs/octoacme-retrospective-and-continuous-improvement.md)
- [Roles & Personas](docs/octoacme-roles-and-personas.md)

## Key process areas (at a glance)
- Initiation: Create a One‑pager, align stakeholders, and confirm go/no‑go for planning.
- Planning: Break work into shippable backlog items with acceptance criteria and DoD; maintain a Risk Register.
- Execution: Use project boards and small, CI‑checked PRs that include acceptance criteria and link to issues.
- Release: Pre‑release checks, staging smoke tests, automated pipelines preferred, and rollback playbooks.
- Continuous Improvement: Run retrospectives, create action items, and track outcomes.

## Quick start — how to use and contribute
- Read the relevant doc linked above for the process you need.
- To propose a change, open an issue using the "Add Content to Project Management Process Docs" template in .github/ISSUE_TEMPLATE/.
- Draft changes as a PR that updates the corresponding file in docs/. Keep changes focused, include rationale, and reference the issue.
- For new documents, leave the "Which process document" field blank in the issue template and explain where the new doc should live.

## Governance & acceptance
- Changes should align with existing process principles and be reviewed by the PM and Product Lead for the affected project area.
- Use the Acceptance Criteria checklist in the issue template to confirm readiness for merging.
