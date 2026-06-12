# OctoAcme Project Management Docs

Welcome to the OctoAcme Project Management documentation library. This README provides an index and brief overview of OctoAcme's project management processes to help you quickly understand our approach and find the full details you need.

## Quick Overview of OctoAcme Project Management

OctoAcme uses a structured, lifecycle-driven approach to project management that emphasizes customer value, iterative delivery, and clear ownership. The organization follows five primary phases:

1. **Initiation** — Validate business need and align stakeholders through a lightweight One-pager
2. **Planning** — Break work into shippable increments with acceptance criteria and a prioritized backlog
3. **Execution** — Manage day-to-day delivery through sprint-based workflows and daily standups
4. **Release** — Standardize deployment with pre-release checklists and rollback plans
5. **Retrospective** — Capture learnings and drive continuous improvement

### Key Principles

- **Customer-first**: Prioritize customer value and usability
- **Iterative delivery**: Deliver small, testable increments
- **Clear ownership**: Each project has a named Project Manager (PM) and Product Lead
- **Data-informed decisions**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback and learning

### Core Roles

- **Project Managers** — Coordinate schedules, risks, and communications while facilitating cross-team alignment
- **Product Managers** — Define what should be built by prioritizing the backlog and measuring outcomes
- **Developers** — Implement features collaboratively, write tests, and identify technical risks
- **QA/Testing** — Validate quality and acceptance criteria

### Communication & Execution

- **Communication cadence**: Weekly syncs between PM and Product Manager, twice-weekly standups for delivery teams, monthly stakeholder updates
- **Execution workflow**: Use GitHub Projects (or similar boards) with defined columns (Backlog → Ready → In Progress → In Review → QA → Done)
- **Quality standards**: Small PRs (≤400 lines), required approvals, unit/integration/smoke tests, security scanning in CI, and manual QA as needed
- **Risk management**: Continuous identification, assessment, and monitoring with three-level escalation paths (team triage → PM → sponsor)
- **Continuous improvement**: Retrospectives after each sprint or release with tracked action items

## Process Documentation Index

Click below to view the complete process guide for each phase:

| Phase | Document | Purpose |
|-------|----------|---------|
| Overview | [OctoAcme Project Management Overview](./octoacme-project-management-overview.md) | Introduction to OctoAcme's approach, roles, and key artifacts |
| Initiation | [Project Initiation Guide](./octoacme-project-initiation.md) | Validate business need and authorize work with a One-pager |
| Planning | [Project Planning](./octoacme-project-planning.md) | Break work into shippable increments with backlog and timeline |
| Execution | [Execution & Tracking](./octoacme-execution-and-tracking.md) | Manage daily delivery, PR workflow, quality, and blocker escalation |
| Risk & Communication | [Risk Management & Communication](./octoacme-risks-and-communication.md) | Identify, manage, and communicate risks and dependencies |
| Release | [Release & Deployment Guide](./octoacme-release-and-deployment.md) | Standardize releases and deployments to production |
| Improvement | [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) | Capture learnings and drive improvements |
| Roles | [Roles & Personas](./octoacme-roles-and-personas.md) | Detailed role definitions and responsibilities |

## How to Contribute

Have feedback, improvements, or want to add content to these process docs? Please use the [**Add Content to Project Management Process Docs**](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) issue template to submit your suggestion.

When creating an update request, include:
- Which document you're updating (or if it's a new document)
- A summary of the new content
- Why this update is needed
- Suggested content (optional)

---

**Last updated**: June 2026  
**Owner**: OctoAcme Project Management Team
