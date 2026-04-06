# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

---

## Developers

### Role Summary
Developers design, build, test, and deliver software components. They collaborate with product and project leads to implement features that meet acceptance criteria and quality standards.

### Responsibilities
- Implement features and fixes to meet acceptance criteria
- Write and maintain tests and documentation
- Participate in design and code reviews
- Assist in estimating and planning work
- Help identify technical risks and propose mitigations

### Goals
- Deliver reliable, maintainable code
- Reduce cycle time from idea to production
- Maintain high test coverage and observability

### Typical Communication
- Daily standups and sprint planning
- PR descriptions and code review comments
- Technical design docs when needed

---

## Product Managers

### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics

### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

### Typical Communication
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs

---

## Project Managers

### Role Summary
Project Managers coordinate delivery activities, manage schedules, risks, and communications. They enable the team to deliver on commitments efficiently.

### Responsibilities
- Create and maintain project plans and timelines
- Manage risks, dependencies, and resource constraints
- Facilitate meetings (kickoff, planning, retrospectives)
- Ensure consistent project documentation and status reporting
- Coordinate cross-team and stakeholder communication

### Goals
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders

### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation

---

## QA Lead

### Role Summary
The QA Lead owns the testing strategy, coordinates manual and automated testing efforts, and serves as the final quality gate before releases ship to production.

### Responsibilities
- Develop and maintain test plans, test cases, and quality acceptance criteria
- Coordinate and execute manual and automated testing (unit, integration, end-to-end)
- Sign off on quality gates prior to each release
- Track and triage defects; work with developers on prioritization and resolution
- Maintain test environments in partnership with DevOps

### Goals
- Prevent regressions and ensure feature quality meets acceptance criteria
- Reduce manual testing burden through automation
- Provide clear release readiness signals to the project team

### Typical Communication
- Sprint planning and grooming: review acceptance criteria with developers and Product Manager
- Daily standup: surface test blockers and defect status
- Pre-release sign-off: written quality summary shared with Project Manager and Product Manager

### Interactions with Existing Roles
| Role | Interaction |
|---|---|
| Developers | Collaborate on test plans; developers hand off builds; QA Lead reviews and reports defects |
| Product Manager | Confirm feature acceptance criteria; validate that delivered features meet user expectations |
| Project Manager | Communicate release readiness status; flag quality risks in the risk register |

---

## UX/UI Designer

### Role Summary
The UX/UI Designer creates user experiences that are intuitive, accessible, and aligned with product goals. They bridge user research and engineering implementation.

### Responsibilities
- Produce user flows, wireframes, and high-fidelity mockups
- Conduct usability reviews and incorporate user feedback
- Collaborate during sprint planning and backlog grooming to surface UX requirements early
- Maintain a design system or style guide for consistency across the product
- Support accessibility reviews and ensure designs meet WCAG guidelines

### Goals
- Deliver interfaces that are usable, accessible, and visually consistent
- Reduce re-work by aligning design with engineering constraints early
- Represent the end-user perspective throughout delivery

### Typical Communication
- Design reviews: share mockups with Product Manager and developers before sprint start
- Backlog grooming: flag UX stories and acceptance criteria for upcoming work
- Async: Figma (or equivalent) comments and design handoff notes for developers

### Interactions with Existing Roles
| Role | Interaction |
|---|---|
| Product Manager | Translate requirements into user flows; validate designs against product vision |
| Developers | Provide design assets and specifications; clarify intent during implementation |
| Project Manager | Flag design dependencies that could affect sprint timelines |

---

## DevOps Engineer

### Role Summary
The DevOps Engineer builds and maintains the infrastructure, automation, and tooling that enables teams to deliver software reliably and quickly.

### Responsibilities
- Design, build, and maintain CI/CD pipelines and deployment automation
- Manage cloud infrastructure, environments, and configuration
- Monitor application reliability, performance, and security in production
- Ensure consistent and reproducible environments across dev, staging, and production
- Support incident response and contribute to post-incident reviews

### Goals
- Maximize deployment frequency and minimize lead time to production
- Reduce mean time to recovery (MTTR) for incidents
- Ensure environments are secure, observable, and cost-efficient

### Typical Communication
- Sprint planning: review infrastructure or tooling needs for upcoming features
- Release planning: confirm deployment readiness and rollback plans with Project Manager
- Incident channels: lead response communication and post-incident write-ups

### Interactions with Existing Roles
| Role | Interaction |
|---|---|
| Developers | Provide CI/CD pipelines; support local development environments and tooling |
| QA Lead | Provision and maintain test environments; support test automation infrastructure |
| Project Manager | Confirm deployment schedules; document rollback and mitigation plans for releases |

---

## Business Analyst

### Role Summary
The Business Analyst bridges business stakeholders and the delivery team by translating high-level goals into clear, actionable requirements.

### Responsibilities
- Facilitate requirement workshops and document business processes
- Translate business needs into user stories with clear acceptance criteria
- Analyze data and process flows to identify gaps and improvement opportunities
- Maintain traceability between business requirements and implemented features
- Support stakeholder sign-off on requirements and acceptance criteria

### Goals
- Ensure the team builds the right thing by clarifying requirements before work begins
- Reduce ambiguity and rework caused by unclear or shifting requirements
- Keep requirements aligned with business priorities throughout delivery

### Typical Communication
- Requirement workshops: facilitate sessions with stakeholders and Product Manager
- Backlog grooming: present refined user stories for team estimation
- Weekly: share requirement status and open questions with Project Manager

### Interactions with Existing Roles
| Role | Interaction |
|---|---|
| Product Manager | Co-own requirement gathering; translate product vision into specific, testable stories |
| Project Manager | Support scope planning; flag requirement risks or open decisions that could affect timelines |
| Developers | Clarify acceptance criteria and business rules during implementation |

---

## Stakeholder Champion

### Role Summary
The Stakeholder Champion represents the interests of key stakeholder groups, ensures their needs are heard, and maintains alignment between the project and broader business goals.

### Responsibilities
- Act as the primary liaison between stakeholder groups and the project team
- Collect, synthesize, and communicate stakeholder feedback
- Attend key project milestones (kickoff, reviews, retrospectives) to represent stakeholder perspective
- Help resolve conflicts between stakeholder priorities and project constraints
- Ensure communications are timely, clear, and relevant to each stakeholder audience

### Goals
- Maintain stakeholder confidence and engagement throughout delivery
- Reduce escalations by surfacing issues and feedback early
- Ensure project outcomes align with business and stakeholder expectations

### Typical Communication
- Kickoff and milestone reviews: represent stakeholder perspective in key meetings
- Weekly: brief stakeholder groups on progress, risks, and decisions
- Ad hoc: channel stakeholder feedback to Product Manager and Project Manager

### Interactions with Existing Roles
| Role | Interaction |
|---|---|
| Project Manager | Share stakeholder concerns, risks, and feedback; coordinate status communications |
| Product Manager | Provide stakeholder input on prioritization and feature trade-offs |
| Developers | Represent end-user and stakeholder context during sprint reviews |

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

## See Also
- [RACI Matrix Template](octoacme-raci-matrix.md) — Assign roles and responsibilities across project activities using the personas above.
- [Decision Log Template](octoacme-decision-log.md) — Track key project decisions and their owners.

