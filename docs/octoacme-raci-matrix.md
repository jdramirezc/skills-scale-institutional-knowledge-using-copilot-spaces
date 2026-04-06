# OctoAcme — RACI Matrix Template

## Purpose
Clarify who is **R**esponsible, **A**ccountable, **C**onsulted, and **I**nformed for each major project activity. Use this template at project kick-off and update it when the team or scope changes.

## RACI Key

| Letter | Meaning |
|---|---|
| **R** | **Responsible** — Does the work |
| **A** | **Accountable** — Owns the outcome; final decision-maker (one per activity) |
| **C** | **Consulted** — Provides input before or during the activity |
| **I** | **Informed** — Receives updates when the activity is complete or status changes |

## RACI Matrix

> Replace or add rows to match your project activities. Add or remove columns to reflect your team composition.

| Activity | Project Manager | Product Manager | Developer | QA Lead | UX/UI Designer | DevOps Engineer | Business Analyst | Stakeholder Champion |
|---|---|---|---|---|---|---|---|---|
| Project initiation & one-pager | A | C | I | I | I | I | C | I |
| Stakeholder alignment | A | C | I | I | I | I | C | R |
| Backlog creation & prioritization | C | A | C | C | C | I | R | I |
| Sprint planning | A | C | R | C | C | C | C | I |
| Requirements workshops | C | A | I | I | C | I | R | C |
| Design review & handoff | I | C | R | I | A | I | I | I |
| Development & code review | I | I | A/R | C | C | C | I | I |
| Test plan & QA execution | C | C | R | A | I | C | I | I |
| CI/CD pipeline & environments | I | I | C | C | I | A/R | I | I |
| Risk register maintenance | A | C | C | C | I | C | C | I |
| Stakeholder status updates | R | C | I | I | I | I | I | A |
| Release go/no-go decision | A | C | C | C | I | C | I | I |
| Deployment to production | C | I | R | C | I | A/R | I | I |
| Post-release retrospective | A | C | R | R | C | C | C | C |
| Decision log maintenance | A | C | C | I | I | I | C | I |

## DRI (Directly Responsible Individual) Quick Reference

For projects that prefer a single DRI model instead of RACI, assign one person per area:

| Area | DRI |
|---|---|
| Delivery schedule & risk | Project Manager |
| Product vision & backlog | Product Manager |
| Technical implementation | Lead Developer |
| Quality & release readiness | QA Lead |
| Design consistency | UX/UI Designer |
| Infrastructure & deployment | DevOps Engineer |
| Requirements clarity | Business Analyst |
| Stakeholder alignment | Stakeholder Champion |

## Checklist

- [ ] RACI reviewed and agreed by team at project kickoff
- [ ] Each activity has exactly one Accountable owner
- [ ] All team members have seen the matrix and acknowledged their roles
- [ ] RACI updated when team composition or scope changes

## See Also
- [Roles & Personas](octoacme-roles-and-personas.md) — Full descriptions of each role
- [Decision Log Template](octoacme-decision-log.md) — Log key decisions and their accountable owners
- [Project Initiation Guide](octoacme-project-initiation.md) — Reference the RACI during kickoff
