# OctoAcme Project Management Documentation

## Overview

This directory contains the standardized project management processes, roles, and best practices used by OctoAcme teams for successful project delivery. OctoAcme follows a structured lifecycle-based approach organized into five distinct phases: **Initiation, Planning, Execution, Release, and Retrospective**. This centralized knowledge hub helps new team members get up to speed, ensures consistency across projects, and captures institutional knowledge that persists even as team members change.

## Quick Start

**New to OctoAcme?** Start with the [Project Management Overview](octoacme-project-management-overview.md) for a high-level introduction to our approach, core roles, and key artifacts.

## Core Project Management Processes

### Overview & Foundations
- [**Project Management Overview**](octoacme-project-management-overview.md) — Core principles (customer-first, iterative delivery, clear ownership, data-informed), roles (PM, PdM, Developers, QA), and the five-phase lifecycle

### Phase 1: Initiation
- [**Project Initiation**](octoacme-project-initiation.md) — Validate business need, align stakeholders, create a lightweight Project One-pager, and make a go/no-go decision

### Phase 2: Planning
- [**Project Planning**](octoacme-project-planning.md) — Break work into shippable increments, establish prioritized backlog with acceptance criteria, estimate scope, identify dependencies, and create release plan

### Phase 3: Execution & Tracking
- [**Execution & Tracking**](octoacme-execution-and-tracking.md) — Day-to-day delivery through project board workflow, daily standups, quality assurance, testing, and blocker escalation

### Phase 4: Release & Deployment
- [**Release & Deployment**](octoacme-release-and-deployment.md) — Pre-release requirements, deployment checklist, rollback playbook, and release notes

### Phase 5: Retrospective & Continuous Improvement
- [**Retrospectives & Continuous Improvement**](octoacme-retrospective-and-continuous-improvement.md) — Capture learnings, track action items, and drive iterative improvements

### Cross-Cutting Concerns
- [**Risk Management & Communication**](octoacme-risks-and-communication.md) — Risk Register, escalation paths, stakeholder communication, and incident playbooks
- [**Roles & Personas**](octoacme-roles-and-personas.md) — Detailed role descriptions, responsibilities, and typical communication for Product Managers, Project Managers, and Developers

## Key Principles

OctoAcme's approach is grounded in five core principles:

1. **Customer-first** — Prioritize customer value and usability in all decisions
2. **Iterative delivery** — Ship small, testable increments rather than waiting for big releases
3. **Clear ownership** — Each project has named PM and Product Lead with explicit responsibilities
4. **Data-informed decisions** — Measure impact and iterate based on evidence
5. **Psychological safety** — Encourage feedback, learning, and continuous improvement

## Key Workflows & Team Rhythm

### Communication Cadence
- **Daily standups (15 min)** — Focus on progress, blockers, and dependencies
- **Weekly PM + PdM sync** — Alignment on priorities and risks
- **Weekly delivery sync** — Show progress, updates, and flagged risks
- **Demo/Review** — End of each sprint or milestone
- **Monthly stakeholder updates** — High-level status to sponsors and stakeholders

### Execution Workflow
Work flows through the project board with these columns: **Backlog → Ready → In Progress → In Review → QA → Done**

- Pull requests should be small (≤ 400 lines when possible)
- Include issue link and acceptance criteria in PR descriptions
- Require at least one approval before merging
- Automated tests and linting run in CI before review

### Quality & Testing
- Unit tests for new logic
- Integration tests where applicable
- End-to-end smoke tests for critical flows before release
- Security scanning in CI
- Manual QA for feature acceptance when needed

### Risk & Escalation
- **Level 1:** Team-level triage in daily standup
- **Level 2:** PM escalates to Product Lead and dependent teams
- **Level 3:** Sponsor-level escalation for business-impacting issues

## How to Use These Docs

- **For project kickoff:** Start with Project Initiation, then move to Project Planning
- **During delivery:** Reference Execution & Tracking for workflow guidance; Risk Management for escalation paths
- **Before release:** Check Release & Deployment for pre-release checklist and rollback plan
- **After milestones:** Use Retrospectives guide to conduct learning sessions and track improvements
- **For onboarding:** New team members should read Project Management Overview and Roles & Personas
- **For continuous improvement:** Link to relevant docs in issue templates and project charters; reference during retrospectives to identify process improvements
- **For Copilot Spaces context:** Add these docs to `.copilot/` to ground Copilot with process-specific guidance

## Key Artifacts

Projects typically produce and maintain these artifacts:

- **Project Charter / One-pager** — Problem, goal, success metrics, stakeholders, timeline, risks
- **Roadmap and Release Plan** — Prioritized milestones and delivery dates
- **Sprint/Iteration Backlog** — Prioritized items with acceptance criteria and estimates
- **Risk Register** — ID, description, impact, likelihood, owner, mitigation, status
- **Definition of Done** — Shared understanding of what "complete" means
- **Release Notes** — Summary of changes, migration steps, known issues
- **Retrospective Notes** — What went well, improvements, action items with owners and due dates

## Process Improvement

These docs are living artifacts. If you identify gaps, improvements, or new practices that should be documented:

1. Open an issue using the **"Add Content to Project Management Process Docs"** template
2. Describe the gap, rationale, and suggested content
3. Submit a pull request with updates
4. Ensure changes align with existing processes and team feedback

For questions or clarifications, reach out to your Product Lead or Project Manager.

---

**Last updated:** August 2026
