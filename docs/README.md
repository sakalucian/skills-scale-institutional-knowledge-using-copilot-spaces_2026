# OctoAcme Project Management Docs (README)

## Summary
OctoAcme runs a structured, iterative project-management approach that moves work from initiation through planning, execution, release, and continuous improvement. Projects begin with a lightweight Project One‑pager to capture problem statements, measurable success metrics, stakeholders, and a high-level timeline. After a go/no‑go decision, teams create prioritized backlogs, estimate scope, define a Definition of Done, and map releases and milestones. Key artifacts are maintained in the repo so status and decisions have a single source of truth.

Work is organized around a simple project-board workflow (Backlog → Ready → In Progress → In Review → QA → Done) and a disciplined pull-request process designed to reduce review friction and risk. Pull requests should be small when possible, link to issues and acceptance criteria, and pass CI (tests, linting, and security scans) before reviewers are asked to approve. Planning focuses on shippable increments, clear acceptance criteria, and timeboxed sprint planning so the team pulls work that meets the Definition of Done.

Roles are explicit: Product Managers (PdMs) define outcomes and success metrics and prioritize the backlog; Project Managers (PMs) coordinate schedules, risks, and communications; Developers implement features, write tests and documentation, and participate in reviews; QA/testing validates acceptance criteria and performs manual or automated verification as needed. These persona definitions are used across the docs to clarify ownership for delivery, quality, and communication.

Quality and release practices combine automated and manual checks: unit and integration tests, end-to-end smoke tests for critical flows, CI security scanning, and manual QA where required. Releases follow a checklist and a rollback/playbook to reduce production risk. Risk management uses a lightweight register with escalation paths (team → PM → Product Lead → Sponsor), and retrospectives capture learnings as tracked action items to drive continuous improvement.

## Included Documents
- ./octoacme-project-management-overview.md — High-level approach, roles, key artifacts, and lifecycle.
- ./octoacme-project-initiation.md — How to validate and authorize new projects; one-pager template and initiation checklist.
- ./octoacme-project-planning.md — Planning activities, backlog templates, and sprint planning guidance.
- ./octoacme-execution-and-tracking.md — Team rhythm, workflows, PR conventions, and execution checklist.
- ./octoacme-release-and-deployment.md — Release types, deployment checklist, and rollback playbook.
- ./octoacme-retrospective-and-continuous-improvement.md — Retrospective structure and tracking improvements.
- ./octoacme-risks-and-communication.md — Risk register format, communication templates, and escalation paths.
- ./octoacme-roles-and-personas.md — Role summaries and responsibilities used across the docs.

## How to use
- Read the overview for a high-level orientation.
- Follow the initiation and planning guides when starting a new project.
- Use the execution, release, and retrospective docs during delivery and close-out.
- Keep this README updated as documents evolve; prefer relative links so they render correctly on GitHub.

## Notes
- Keep links relative (e.g., ./octoacme-project-management-overview.md) so they render correctly in the repository.
- Consider adding this README to the repository docs index or linking to it from the project README to improve discoverability.
