# OctoAcme Project Management Documentation

Welcome to the OctoAcme project management knowledge base. This repository centralizes our institutional knowledge for Copilot Spaces and serves as the single source of truth for how we run projects at OctoAcme.

## How to Use These Docs

- **New to OctoAcme?** Start with the [Project Management Overview](https://github.com/abudd1094/skills-scale-institutional-knowledge-using-copilot-spaces/blob/main/docs/octoacme-project-management-overview.md) to understand our principles, roles, and lifecycle.
- **Starting a project?** Follow the [Project Initiation](https://github.com/abudd1094/skills-scale-institutional-knowledge-using-copilot-spaces/blob/main/docs/octoacme-project-initiation.md) and [Project Planning](https://github.com/abudd1094/skills-scale-institutional-knowledge-using-copilot-spaces/blob/main/docs/octoacme-project-planning.md) guides.
- **Managing delivery?** Refer to [Execution and Tracking](https://github.com/abudd1094/skills-scale-institutional-knowledge-using-copilot-spaces/blob/main/docs/octoacme-execution-and-tracking.md) for daily workflows and quality practices.
- **Need role clarity?** Check [Roles and Personas](https://github.com/abudd1094/skills-scale-institutional-knowledge-using-copilot-spaces/blob/main/docs/octoacme-roles-and-personas.md) for responsibilities and communication patterns.
- **Copilot Spaces users:** Add relevant process docs to your `.copilot/` directory to give Copilot context about your team's practices.

## Overview

OctoAcme follows a structured yet iterative project management approach designed to deliver customer value quickly while maintaining quality and transparency. Our methodology revolves around five core lifecycle phases: **Initiation, Planning, Execution, Release, and Close & Retrospective**. Each project begins with a lightweight one-pager that defines the problem, success metrics, and stakeholders, then progresses through planning where work is broken into shippable increments with clear acceptance criteria. During execution, teams work from a shared project board with columns for Backlog, Ready, In Progress, In Review, QA, and Done, ensuring visibility and smooth handoffs across the delivery pipeline.

Our team rhythm centers on frequent, focused communication. Teams hold **daily standups** (15 minutes) to surface blockers and dependencies, **weekly delivery syncs** to review progress and manage risks, and **sprint or milestone demos** to validate outcomes with stakeholders. The Project Manager and Product Manager align weekly on priorities and escalations, while broader stakeholder updates occur monthly or at key milestones. Communication follows standardized templates—weekly status reports capture progress, next steps, risks, and decisions needed, while the risk register serves as a living document reviewed and updated each week. This cadence ensures the team stays aligned without creating meeting overhead.

Quality is built into every step of our workflow through disciplined engineering practices and clear release gates. Developers submit **small pull requests** (ideally ≤ 400 lines) that link to issues and include acceptance criteria in the description. Before merging, each PR must pass automated CI checks (unit tests, linting, security scans) and receive at least one peer approval. The Definition of Done ensures features meet functional, quality, and observability standards before moving to QA or production. Releases require all acceptance criteria to be met, passing CI and security scans, documented release notes, a rollback plan, and successful smoke tests. If issues arise, teams follow a structured incident response with blameless retrospectives to capture learnings.

Cross-functional collaboration is enabled by clearly defined personas and ownership. **Project Managers** coordinate delivery, manage schedules and risks, and maintain transparency through consistent documentation and status reporting. **Product Managers** define what to build, prioritize the backlog, and validate that delivered features achieve measurable customer and business outcomes. **Developers** implement features, write tests, participate in code reviews, and help identify technical risks. **QA/Testing** validates quality and acceptance criteria, ensuring releases meet production standards. **Business Analysts** bridge business and technical teams, gathering requirements and ensuring solutions align with business objectives. **UX Designers** advocate for user experience, conducting research and ensuring customer-centric design. **Stakeholder Representatives** provide feedback and validation from end-user perspectives. **Release Managers** coordinate release timelines and deployment communication, while **DevOps Engineers** own CI/CD pipelines and infrastructure reliability. After each sprint, release, or incident, teams conduct **retrospectives** to reflect on what went well and what could improve, converting insights into 2–3 prioritized action items tracked in the backlog. This continuous improvement mindset, combined with our focus on iterative delivery, psychological safety, and data-informed decisions, drives both team effectiveness and customer impact.

## Process Documents

### Core Project Lifecycle
- [Project Management Overview](https://github.com/abudd1094/skills-scale-institutional-knowledge-using-copilot-spaces/blob/main/docs/octoacme-project-management-overview.md) — Principles, roles, artifacts, and lifecycle at a glance
- [Project Initiation](https://github.com/abudd1094/skills-scale-institutional-knowledge-using-copilot-spaces/blob/main/docs/octoacme-project-initiation.md) — Validate the idea and align stakeholders
- [Project Planning](https://github.com/abudd1094/skills-scale-institutional-knowledge-using-copilot-spaces/blob/main/docs/octoacme-project-planning.md) — Turn initiatives into actionable backlogs and timelines
- [Execution and Tracking](https://github.com/abudd1094/skills-scale-institutional-knowledge-using-copilot-spaces/blob/main/docs/octoacme-execution-and-tracking.md) — Daily workflows, PR practices, and quality standards
- [Release and Deployment](https://github.com/abudd1094/skills-scale-institutional-knowledge-using-copilot-spaces/blob/main/docs/octoacme-release-and-deployment.md) — Release checklists, deployment steps, and rollback procedures
- [Retrospective and Continuous Improvement](https://github.com/abudd1094/skills-scale-institutional-knowledge-using-copilot-spaces/blob/main/docs/octoacme-retrospective-and-continuous-improvement.md) — Capture learnings and track action items

### Supporting Practices
- [Risks and Communication](https://github.com/abudd1094/skills-scale-institutional-knowledge-using-copilot-spaces/blob/main/docs/octoacme-risks-and-communication.md) — Risk register, stakeholder updates, and escalation paths
- [Roles and Personas](https://github.com/abudd1094/skills-scale-institutional-knowledge-using-copilot-spaces/blob/main/docs/octoacme-roles-and-personas.md) — Responsibilities and communication patterns for all team roles

### Checklists and Templates
- [Business Analysis Checklist](https://github.com/abudd1094/skills-scale-institutional-knowledge-using-copilot-spaces/blob/main/docs/octoacme-business-analysis-checklist.md) — Requirements gathering and validation guide
- [Release Manager Checklist](https://github.com/abudd1094/skills-scale-institutional-knowledge-using-copilot-spaces/blob/main/docs/octoacme-release-manager-checklist.md) — Comprehensive release coordination steps

## Questions or Feedback?

This documentation is a living resource. If you have suggestions, questions, or want to propose updates, please open an issue or reach out to the Project Management team.
