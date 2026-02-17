# OctoAcme Project Management Docs

Welcome to OctoAcme's project management documentation! This folder centralizes OctoAcme's project management processes for easy discoverability, making team knowledge searchable, versioned, and accessible to all.

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

- [Project Management Overview](octoacme-project-management-overview.md)
- [Project Initiation Guide](octoacme-project-initiation.md)
- [Project Planning](octoacme-project-planning.md)
- [Execution & Tracking](octoacme-execution-and-tracking.md)
- [Risk Management & Communication](octoacme-risks-and-communication.md)
- [Release & Deployment Guide](octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)
- [Roles and Personas](octoacme-roles-and-personas.md)

---

For updates, use the issue template in `.github/ISSUE_TEMPLATE/`. To bring a new process, propose a file in this folder.
