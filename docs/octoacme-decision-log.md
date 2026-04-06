# OctoAcme — Decision Log Template

## Purpose
Track significant project decisions, the context behind them, and who made them. A good decision log reduces confusion, prevents re-litigation, and helps onboard new team members quickly.

## When to Log a Decision
Log a decision when it:
- Affects scope, timeline, budget, or team composition
- Involves a trade-off between competing options
- Is likely to be questioned or revisited later
- Has downstream dependencies for other teams or stakeholders

## Decision Log

> Add a new row for each decision. Assign a sequential ID (D-001, D-002, …).

| ID | Date | Decision | Context / Rationale | Options Considered | Owner (Accountable) | Status | Related Links |
|---|---|---|---|---|---|---|---|
| D-001 | YYYY-MM-DD | _Short description of the decision_ | _Why this decision was needed and what led to it_ | _Option A; Option B; Option C_ | _Name / Role_ | Decided / Pending / Superseded | _Issue #, PR #, Doc link_ |
| D-002 | YYYY-MM-DD | | | | | | |

### Status Values
| Status | Meaning |
|---|---|
| **Proposed** | Under discussion; not yet decided |
| **Decided** | Approved and in effect |
| **Pending** | Waiting on more information or sign-off |
| **Superseded** | Replaced by a later decision (reference the new ID) |
| **Deferred** | Postponed; revisit date noted |

## Decision Entry Template (long form)

Use this expanded format for high-impact decisions that need more detail:

```
### D-NNN — <Short Decision Title>
- **Date:** YYYY-MM-DD
- **Owner:** <Name, Role>
- **Status:** Decided

**Context:**
<Describe the situation, problem, or question that required a decision.>

**Decision:**
<State exactly what was decided.>

**Options Considered:**
1. <Option A> — <pros/cons>
2. <Option B> — <pros/cons>
3. <Option C> — <pros/cons>

**Rationale:**
<Why this option was chosen over the alternatives.>

**Consequences / Trade-offs:**
<What is accepted or given up as a result of this decision.>

**Review Date (if applicable):** YYYY-MM-DD
```

## Checklist
- [ ] Decision log linked from the project README or one-pager
- [ ] All team members know where the log lives and how to add entries
- [ ] Decisions reviewed at weekly sync for any new entries
- [ ] Superseded decisions reference their replacement entry

## See Also
- [Roles & Personas](octoacme-roles-and-personas.md) — Identify the accountable owner for each decision
- [RACI Matrix Template](octoacme-raci-matrix.md) — Confirm who should be consulted or informed for each decision type
- [Risk Management & Communication](octoacme-risks-and-communication.md) — Decisions that affect risk posture should be reflected in the risk register
