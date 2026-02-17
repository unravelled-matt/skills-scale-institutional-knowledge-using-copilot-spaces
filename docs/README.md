# OctoAcme Project Management Docs

Welcome to OctoAcme's centralized project management documentation! This collection of process guides captures our institutional knowledge and makes it accessible to every team member through Copilot Spaces.

By centralizing our project management knowledge in Copilot Spaces, we ensure that critical processes, decisions, and workflows are searchable, versioned, and accessible to all team members—not locked in individual minds or scattered across emails and chat threads.

## Purpose

- Centralize scattered project management knowledge in Copilot Spaces
- Convert tacit team insights into searchable, versioned artifacts
- Give all team members equal access to processes, decisions, and rationale
- Extract, refine, and standardize workflows collaboratively
- Accelerate onboarding and reduce single-person dependency risk
- Enable consistent, repeatable project execution

## Summary of Project Management Processes

OctoAcme employs a structured, iterative project management approach centered on customer value and continuous improvement. The organization follows a five-phase lifecycle: **Initiation**, **Planning**, **Execution**, **Release**, and **Retrospective**. Each phase has clearly defined deliverables and decision gates. Projects begin with a lightweight **Project One-pager** that articulates the problem statement, success metrics, stakeholders, and initial risk assessment. Once approved by the Product Lead and sponsor, initiatives move into detailed planning where work is decomposed into prioritized backlog items with acceptance criteria, estimates, and a Definition of Done. Throughout execution, teams maintain transparency through project boards (typically GitHub Projects) organized into workflow columns from Backlog through Done, ensuring all work items are visible and trackable.

The OctoAcme framework defines three primary **personas**: **Developers** build and test features while maintaining code quality and documentation; **Product Managers** define the vision, prioritize the roadmap based on customer and business value, and measure outcomes; and **Project Managers** coordinate delivery, manage schedules and risks, facilitate meetings, and maintain stakeholder communication. Each role has distinct responsibilities but collaborates closely—Product Managers set the "what" and "why," Project Managers orchestrate the "when" and "how," and Developers execute the "how" with technical excellence. This clear ownership model reduces ambiguity and enables efficient decision-making across cross-functional teams.

**Communication and risk management** form the backbone of OctoAcme's execution model. Teams follow a regular cadence including daily 15-minute standups, weekly delivery syncs, and end-of-sprint demos. Project Managers maintain a **Risk Register** tracking identified risks with impact/likelihood assessments, owners, and mitigation plans, which are reviewed weekly. Stakeholder updates follow a consistent template covering progress, next steps, blockers, and decisions needed. The organization uses a three-level **escalation path**: team-level triage in standups, PM escalation to Product Leads and dependent teams, and sponsor-level escalation for business-critical issues. This structured communication ensures alignment while preventing surprise escalations.

**Quality assurance and deployment practices** emphasize automation and risk mitigation. Teams implement unit tests, integration tests, and end-to-end smoke tests for critical flows, with security scanning integrated into CI pipelines. Pull requests are kept small (≤400 lines when possible), must include issue links and acceptance criteria, and require at least one approval before merging. Releases are categorized as Patch (hotfixes), Minor (incremental features), or Major (significant changes), each with corresponding pre-release checklists covering CI validation, smoke testing in staging, rollback plans, and stakeholder notifications. The process concludes with **retrospectives** after each sprint or milestone, where teams identify 2-3 actionable improvements with clear owners and due dates, fostering a culture of continuous learning and iterative process refinement. All project artifacts—from charters to risk registers to retrospective action items—are version-controlled in repositories, making OctoAcme's institutional knowledge searchable, shareable, and maintainable.

## OctoAcme Process Documents

- <a href="octoacme-project-management-overview.md">Project Management Overview</a>
- <a href="octoacme-project-initiation.md">Project Initiation Guide</a>
- <a href="octoacme-project-planning.md">Project Planning</a>
- <a href="octoacme-execution-and-tracking.md">Execution &amp; Tracking</a>
- <a href="octoacme-risks-and-communication.md">Risk Management &amp; Communication</a>
- <a href="octoacme-release-and-deployment.md">Release &amp; Deployment Guide</a>
- <a href="octoacme-retrospective-and-continuous-improvement.md">Retrospective &amp; Continuous Improvement</a>
- <a href="octoacme-roles-and-personas.md">Roles and Personas</a>

---

**Contributing:** To update any of these process documents, please use the issue template in `.github/ISSUE_TEMPLATE/` to propose changes. To suggest a new process document, create an issue proposing the new file in the docs folder.
