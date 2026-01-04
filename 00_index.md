# Adoption Architect Planning Hub

*Detailed reference with diagrams and tables. For a cleaner blog-style overview, see [README.md](README.md).*

---

## Document Index

| # | Document | Purpose | Status |
|---|----------|---------|--------|
| 01 | [Mission and Role](01_mission_and_role.md) | Role definition, clarity vs. action framework | ✅ Complete |
| 02 | [Product Context](02_product_context.md) | Product state, limitations, roadmap | ✅ Complete |
| 03 | [Positioning and Moat](03_positioning_and_moat.md) | Differentiation, competitive landscape | ✅ Complete |
| 04 | [GTM Motion](04_gtm_motion.md) | GTM imperatives, field readiness, objection handling | ✅ Complete |
| 05 | [Adoption Patterns](05_adoption_patterns.md) | App archetypes, use case taxonomy | ✅ Complete |
| 06 | [Partnership Ecosystem](06_partnership_ecosystem.md) | FE teams, ISVs, SIs, IDE partnerships | ✅ Complete |
| 07 | [Question Framework](07_question_framework.md) | Questions answered for planning | ✅ Complete |
| 08 | [Hypotheses and Beliefs](08_hypotheses_and_beliefs.md) | Personal hypotheses with data validation plan | ✅ Complete |
| 09 | [Strategic Inputs](09_strategic_inputs.md) | Synthesized outcomes, scope, control surface | ✅ Complete |
| 10 | [Action Plan](10_action_plan.md) | 3-6-12 month plan with owners, timelines | ✅ Complete |
| 11 | [Strategic Gaps](11_strategic_gaps.md) | Critical gaps and recommendations | ✅ Complete |
| 12 | [Traceability Matrix](12_traceability.md) | Hypothesis → Action → Validation mapping | ✅ Complete |

---

## Document Relationships

```
┌─────────────────────────────────────────────────────────────────┐
│                    DOCUMENT ARCHITECTURE                        │
├─────────────────────────────────────────────────────────────────┤
│                                                                 │
│   FOUNDATION                                                    │
│   ──────────                                                    │
│   01_mission ──► 02_product ──► 03_moat ──► 04_gtm             │
│        │              │             │           │               │
│        └──────────────┴─────────────┴───────────┘               │
│                           │                                     │
│                           ▼                                     │
│   PATTERNS                                                      │
│   ────────                                                      │
│   05_adoption ◄──────────────────────► 06_partnerships          │
│        │                                     │                  │
│        └─────────────────┬───────────────────┘                  │
│                          │                                      │
│                          ▼                                      │
│   SYNTHESIS                                                     │
│   ─────────                                                     │
│   07_questions ──► 08_hypotheses ──► 09_inputs                  │
│                          │                │                     │
│                          ▼                ▼                     │
│   EXECUTION                                                     │
│   ─────────                                                     │
│   10_action_plan ◄────► 11_gaps ◄────► 12_traceability          │
│                                                                 │
└─────────────────────────────────────────────────────────────────┘
```

---

## Quick Reference: The Adoption Architect Framework

```
┌─────────────────────────────────────────────────────────────────┐
│                    ADOPTION ARCHITECT                           │
├─────────────────────────────────────────────────────────────────┤
│                                                                 │
│   CLARITY                              ACTION                   │
│   ───────                              ──────                   │
│   • BU+1 Newsletters                   • Platform Programs      │
│   • Loss Analysis                      • Enablement Content     │
│   • Aggregated Blockers                • Voice to PM            │
│   • Adoption Cohorts                   • Expert Guidance        │
│                                                                 │
│                    ↓           ↓                                │
│              REPEATABLE PLAYBOOKS AT SCALE                      │
│                                                                 │
└─────────────────────────────────────────────────────────────────┘
```

---

## North Star Metrics (Phased)

| Phase | North Star | Definition |
|-------|------------|------------|
| **3-6 months** | Strategic Wins | Decisive account wins with Apps delivering clear business value |
| **6-9 months** | Attach Rates | SKU and use case attach driven by Apps |
| **12+ months** | Coverage | Unique accounts with production Apps deployed |

---

## Key Hypotheses

| ID | Hypothesis | Priority | Status |
|----|------------|----------|--------|
| H1 | Apps as Tip of the Spear | 🔴 Critical | ⬜ Not tested |
| H2 | Ecosystem Synergy Is the Moat | 🟡 Important | ⬜ Not tested |
| H3 | FE Enablement Is Critical Blocker | 🔴 Critical | ⬜ Not tested |
| H4 | Three Archetypes Drive 80% | 🟡 Important | ⬜ Not tested |
| H5 | SI Partnerships Counter Palantir | 🟡 Important | ⬜ Not tested |
| H6 | Metrics Will Align BU Leaders | 🔴 Critical | ⬜ Not tested |
| H7 | Net-New Focus Is Right | 🟢 Validate | ⬜ Not tested |

See [08_hypotheses_and_beliefs.md](08_hypotheses_and_beliefs.md) for details and [12_traceability.md](12_traceability.md) for validation plan.

### Hypothesis Decision Timeline

| Decision Point | Hypotheses | Key Question |
|----------------|------------|--------------|
| **Month 3** | H3, H6 | Is enablement working? Do BU leaders buy metrics? |
| **Month 6** | H1, H4, H7 | Is attach rate positive? Do archetypes hold? Is net-new winning? |
| **Month 9** | H2, H5 | Is moat real? Is SI pilot working? |

---

## Critical Gaps (Resolve Immediately)

| Gap | Description | Owner |
|-----|-------------|-------|
| Gap 1 | No baseline data for hypothesis validation | Adoption Architect |
| Gap 2 | Attach rate metrics not defined or accepted | Adoption Architect |
| Gap 3 | Field enablement content does not exist | Adoption Architect |
| Gap 4 | Lighthouse account selection not formalized | Adoption Architect |

See [11_strategic_gaps.md](11_strategic_gaps.md) for full gap analysis.

---

## Month 1 Priorities

| Week | Priority | Deliverable | Tests Hypothesis | Document |
|------|----------|-------------|------------------|----------|
| W1 | Lighthouse accounts | Finalize list of 10-15 accounts | H1, H4 | [10_action_plan.md](10_action_plan.md) |
| W1 | Operating rhythm | Launch Apps Adoption Council | All | [10_action_plan.md](10_action_plan.md) |
| W2 | Enablement | Draft security patterns | H3 | [10_action_plan.md](10_action_plan.md) |
| W2 | Data | FE confidence survey baseline | H3 | [12_traceability.md](12_traceability.md) |
| W3 | Metrics | Draft attach rate definition | H6 | [09_strategic_inputs.md](09_strategic_inputs.md) |
| W4 | Alignment | Exec briefing deck for SVP/VPs | H6 | [10_action_plan.md](10_action_plan.md) |

### Month 1 Focus: Testing H3 and H6
- **H3 (FE Enablement):** Baseline FE confidence, draft enablement content
- **H6 (Metrics Align BUs):** Draft attach rate definition, begin exec alignment

---

## How to Use This Hub

### The Hypothesis → Action → Validation Flow

```
08_hypotheses ──► 10_action_plan ──► 12_traceability
     │                  │                  │
     │                  │                  │
  What you           Actions that      Decision points
  believe            test it           and pivots
```

### Navigation Guide

1. **Start here** for navigation and quick reference
2. **[08_hypotheses](08_hypotheses_and_beliefs.md)** — What you believe and why
3. **[10_action_plan](10_action_plan.md)** — Week-by-week execution (now shows which hypothesis each action tests)
4. **[12_traceability](12_traceability.md)** — Decision points and pivot strategies
5. **[11_gaps](11_strategic_gaps.md)** — What's missing and how to fix it
6. **Update documents** as you learn—this is a living system

### Weekly Review Checklist

- [ ] Check action plan for this week's deliverables
- [ ] Update hypothesis status in [08_hypotheses](08_hypotheses_and_beliefs.md) as data comes in
- [ ] Review traceability for upcoming decision points
- [ ] Update gaps as they're resolved

---

*Last Updated: January 2026*
