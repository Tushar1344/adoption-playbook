# Personal Hypotheses and Beliefs

*This document captures your core beliefs about what will drive Apps adoption success. Each hypothesis should be testable and backed by data.*

**Related Documents:** [Traceability Matrix](12_traceability.md) | [Action Plan](10_action_plan.md) | [Strategic Inputs](09_strategic_inputs.md)

---

## Hypothesis Framework

```
┌─────────────────────────────────────────────────────────────────┐
│                    HYPOTHESIS → DATA → ACTION                   │
├─────────────────────────────────────────────────────────────────┤
│                                                                 │
│   HYPOTHESIS          DATA TO VALIDATE         ACTION IF TRUE   │
│   ──────────          ────────────────         ──────────────   │
│   What you believe    Evidence needed          What you'd do    │
│   to be true          to confirm/deny          if confirmed     │
│                                                                 │
└─────────────────────────────────────────────────────────────────┘
```

---

## Hypothesis 1: Apps as Tip of the Spear

### Belief
> Apps can serve as the entry point to land workloads across ETL, DW, ML, AI Agents, and Operational use cases—driving influenced revenue that exceeds direct Apps revenue.

### Why You Believe This
- Apps position closer to business value than infrastructure
- Apps are visible to business users, unlocking new budget sources
- Apps act as a "container" for multiple workloads

### Data Needed to Validate

| Data Point | Source | Status |
|------------|--------|--------|
| Attach rate: % of Apps customers who expand to other SKUs | SFDC + Product telemetry | ⬜ Not collected |
| Time-to-expansion: Days from Apps adoption to new SKU | Product telemetry | ⬜ Not collected |
| Influenced ACV: Revenue from workloads in Apps accounts | Finance + SFDC | ⬜ Not collected |
| Comparison: Expansion rate Apps vs. non-Apps accounts | Analytics team | ⬜ Not collected |

### Risks If Wrong
- Apps becomes a distraction from core revenue
- Field loses trust in "influenced revenue" narrative
- Investment in Apps GTM doesn't pay off

### Validation Evidence (Field Signal)

| Date | Source | Evidence Type | Finding | Implication |
|------|--------|---------------|---------|-------------|
| Jan 2026 | Field SA | Product gaps | Security gaps (public URLs, firewall, ingress/egress) block external-facing apps | Tip-of-spear motion limited to internal apps until gaps addressed |
| Jan 2026 | Field SA | Product gaps | Scaling limitations (vertical only) | High-traffic app use cases blocked |
| Jan 2026 | Field SA | Product gaps | Cost controls (fixed 24x7) | Cost objections may limit expansion |

**Implication for H1:** The "tip of spear" motion may be **constrained to specific use case types** (internal apps, moderate traffic) until product gaps are resolved. Adjust positioning accordingly.

### Cross-References

| Document | Relevant Section | How It Connects |
|----------|------------------|-----------------|
| [04_gtm_motion.md](04_gtm_motion.md) | Apps as Tip of the Spear | Defines the GTM narrative this hypothesis supports |
| [09_strategic_inputs.md](09_strategic_inputs.md) | Attach Rate Measurement | Metrics definitions to validate this hypothesis |
| [10_action_plan.md](10_action_plan.md) | Phase 2: Month 4 | Attach rate tracking implementation |
| [12_traceability.md](12_traceability.md) | H1 Row | Full traceability chain |
| [02_product_context.md](02_product_context.md) | Detailed Gap Inventory | Product limitations that constrain this hypothesis |

---

## Hypothesis 2: Ecosystem Synergy Is the Moat

### Belief
> The combination of Lakebase + Governance + AI creates a defensible moat that accelerates adoption—customers who use all three have higher retention and expansion.

### Why You Believe This
- Synergies reduce integration complexity
- Unified governance is an executive priority
- Co-located AI is a developer preference

### Data Needed to Validate

| Data Point | Source | Status |
|------------|--------|--------|
| Correlation: Multi-product usage vs. retention | Product telemetry | ⬜ Not collected |
| Correlation: Multi-product usage vs. expansion | SFDC + telemetry | ⬜ Not collected |
| Customer quotes on "why Databricks for Apps" | Win/loss interviews | ⬜ Not collected |
| Competitive win rate: Apps vs. hyperscaler apps | SFDC competitive field | ⬜ Not collected |

### Risks If Wrong
- Customers may prefer best-of-breed over integrated
- Feature gaps in individual products undermine synergy story
- Moat is theoretical, not experienced by customers

### Cross-References

| Document | Relevant Section | How It Connects |
|----------|------------------|-----------------|
| [03_positioning_and_moat.md](03_positioning_and_moat.md) | The Databricks Apps Moat | Defines the positioning this hypothesis supports |
| [03_positioning_and_moat.md](03_positioning_and_moat.md) | The Flywheel Effect | Describes how synergy accelerates adoption |
| [05_adoption_patterns.md](05_adoption_patterns.md) | Fit Assessment Questions | Qualification criteria based on ecosystem usage |
| [12_traceability.md](12_traceability.md) | H2 Row | Full traceability chain |

---

## Hypothesis 3: Field Enablement Is the Critical Blocker

### Belief
> The primary reason Apps isn't scaling faster is that Field Engineering lacks the skills and confidence to have app architecture conversations—not product limitations.

### Why You Believe This
- FE is strong on Data/ML, weak on app patterns
- Apps Cookbook is insufficient ("doesn't show what good looks like")
- Similar GTM motions (new products) have required heavy enablement

### Data Needed to Validate

| Data Point | Source | Status |
|------------|--------|--------|
| FE confidence survey: Comfort with Apps conversations | FE survey | ⬜ Not collected |
| Apps conversations per FE per quarter | Activity tracking | ⬜ Not collected |
| Win rate: Enabled FE vs. non-enabled FE | SFDC + training records | ⬜ Not collected |
| FE feedback: "Why aren't you pitching Apps?" | Qualitative interviews | ⬜ Not collected |

### Risks If Wrong
- Enablement investment doesn't move adoption
- Real blocker is product limitations or market timing
- FE pushback is rational (product isn't ready)

### Validation Evidence (Field Signal)

| Date | Source | Evidence Type | Finding | Implication |
|------|--------|---------------|---------|-------------|
| Jan 2026 | Field SA | Product gaps | Security/governance gaps are REAL and SPECIFIC: no public URLs, no firewall, no ingress/egress, CVE concerns | FE concerns about security are **product gaps**, not just enablement gaps |
| Jan 2026 | Field SA | Product gaps | Complex model serving deployment | FE needs product improvement, not just training |
| Jan 2026 | Field SA | Enablement need | "Need guides" for GPU/custom hardware config | Validates enablement gap for customization |

**Implication for H3:** This hypothesis needs **refinement**. The blocker is **BOTH enablement AND product gaps**:
- Enablement gap: FE needs patterns, guides, confidence-building
- Product gap: Security limitations are real blockers that training can't solve

**Updated Belief:** FE enablement is necessary but not sufficient. Must be paired with honest positioning around product limitations.

### Cross-References

| Document | Relevant Section | How It Connects |
|----------|------------------|-----------------|
| [04_gtm_motion.md](04_gtm_motion.md) | Field Readiness Assessment | Documents the current FE capability gap |
| [09_strategic_inputs.md](09_strategic_inputs.md) | Field Enablement Priorities | 90-day training sprint to test this hypothesis |
| [09_strategic_inputs.md](09_strategic_inputs.md) | Top Blockers | Detailed product gaps that limit enablement impact |
| [10_action_plan.md](10_action_plan.md) | Phase 1: Month 2 | Enablement sprint actions |
| [11_strategic_gaps.md](11_strategic_gaps.md) | Gap 5: Product Gaps | Specific gaps from field signal |
| [12_traceability.md](12_traceability.md) | H3 Row | Full traceability chain |

---

## Hypothesis 4: Three App Archetypes Drive 80% of Adoption

### Belief
> The majority of successful Apps adoption falls into three patterns: Business Cockpits, Deeply Vertical Apps, and Horizontal Platform Apps—and we should build playbooks for each.

### Why You Believe This
- Pattern recognition from existing wins
- Each archetype has distinct buyer and value prop
- Focused playbooks > generic enablement

### Data Needed to Validate

| Data Point | Source | Status |
|------------|--------|--------|
| Classification of top 20 Apps customers by archetype | Customer research | ⬜ Not collected |
| Revenue distribution by archetype | SFDC + product telemetry | ⬜ Not collected |
| Win rate by archetype | SFDC analysis | ⬜ Not collected |
| Customer satisfaction by archetype | NPS/CSAT data | ⬜ Not collected |

### Risks If Wrong
- Archetypes are too coarse or too fine
- Missing an archetype that's actually driving adoption
- Playbooks don't transfer across accounts

### Cross-References

| Document | Relevant Section | How It Connects |
|----------|------------------|-----------------|
| [05_adoption_patterns.md](05_adoption_patterns.md) | App Archetypes Seeing Traction | Full definition of each archetype |
| [09_strategic_inputs.md](09_strategic_inputs.md) | App Archetype Targeting | Targeting signals for each archetype |
| [10_action_plan.md](10_action_plan.md) | Phase 2: Month 5 | Playbook development by archetype |
| [12_traceability.md](12_traceability.md) | H4 Row | Full traceability chain |

---

## Hypothesis 5: SI Partnerships Can Counter Palantir's FDE Motion

### Belief
> By partnering with App-first SIs, we can achieve Palantir-like solution delivery at scale without building an internal FDE army—and at lower cost to customers.

### Why You Believe This
- SIs have delivery capacity we don't have
- App-first SIs already have relevant skills
- Palantir's model is expensive and not scalable for all segments

### Data Needed to Validate

| Data Point | Source | Status |
|------------|--------|--------|
| SI-delivered Apps: Time-to-value vs. internal delivery | Project tracking | ⬜ Not collected |
| SI-sourced pipeline: Quality and conversion rate | SFDC | ⬜ Not collected |
| Customer satisfaction: SI-delivered vs. internal | CSAT data | ⬜ Not collected |
| SI partner profitability: Are they making money? | Partner team | ⬜ Not collected |

### Risks If Wrong
- SIs don't have the skills or incentive
- Quality control becomes a problem
- SI model doesn't work for strategic accounts

### Cross-References

| Document | Relevant Section | How It Connects |
|----------|------------------|-----------------|
| [06_partnership_ecosystem.md](06_partnership_ecosystem.md) | System Integrators (SIs) | SI partnership strategy |
| [03_positioning_and_moat.md](03_positioning_and_moat.md) | Palantir | Competitive context for FDE motion |
| [10_action_plan.md](10_action_plan.md) | Phase 3: Month 7-9 | SI pilot launch |
| [12_traceability.md](12_traceability.md) | H5 Row | Full traceability chain |

---

## Hypothesis 6: Influenced Revenue Metrics Will Align BU Leaders

### Belief
> If we can define and track Apps attach rates and influenced revenue, BU leaders will invest in Apps GTM because they'll see the downstream impact on their core products.

### Why You Believe This
- BU leaders are rational—they follow the money
- Current problem is lack of visibility, not lack of impact
- Other platform companies use influenced revenue successfully

### Data Needed to Validate

| Data Point | Source | Status |
|------------|--------|--------|
| BU leader feedback on proposed metrics | Stakeholder interviews | ⬜ Not collected |
| Historical correlation: Apps → other SKU adoption | Analytics | ⬜ Not collected |
| Comparison to how other BUs measure influence | Internal benchmarking | ⬜ Not collected |
| Finance approval of influenced revenue methodology | Finance team | ⬜ Not collected |

### Risks If Wrong
- BU leaders don't buy the methodology
- Influenced revenue is too squishy to drive behavior
- Metrics create misaligned incentives

### Cross-References

| Document | Relevant Section | How It Connects |
|----------|------------------|-----------------|
| [04_gtm_motion.md](04_gtm_motion.md) | Attach Rate Metrics | Metric definitions |
| [09_strategic_inputs.md](09_strategic_inputs.md) | Attach Rate Measurement | Priority order for definitions |
| [09_strategic_inputs.md](09_strategic_inputs.md) | Control Surface | Field comp plans as influence target |
| [10_action_plan.md](10_action_plan.md) | Phase 1: Month 2, Week 8 | BU leader alignment on metrics |
| [12_traceability.md](12_traceability.md) | H6 Row | Full traceability chain |

---

## Hypothesis 7: Net-New Apps (Not Migration) Is the Right Focus

### Belief
> We should focus on net-new application development, not legacy app migration—because our platform is optimized for this and trying to migrate Java/.NET apps will fail.

### Why You Believe This
- Product limitations (legacy framework support coming FY27)
- Competitive positioning is weaker for migration
- Net-new lets us lead with AI/Lakebase differentiation

### Data Needed to Validate

| Data Point | Source | Status |
|------------|--------|--------|
| Win rate: Net-new vs. migration opportunities | SFDC | ⬜ Not collected |
| Customer satisfaction: Net-new vs. migration | CSAT | ⬜ Not collected |
| Time-to-value: Net-new vs. migration | Implementation data | ⬜ Not collected |
| Pipeline composition: % net-new vs. migration | SFDC | ⬜ Not collected |

### Risks If Wrong
- Missing a large migration market
- Customers want migration path before committing to net-new
- Competitors win migration and lock us out

### Cross-References

| Document | Relevant Section | How It Connects |
|----------|------------------|-----------------|
| [02_product_context.md](02_product_context.md) | Product Limitations | Documents why migration is not ready |
| [02_product_context.md](02_product_context.md) | Current Sweet Spot | Defines net-new positioning |
| [05_adoption_patterns.md](05_adoption_patterns.md) | Use Case Qualification | Question 1 on net-new vs migration |
| [12_traceability.md](12_traceability.md) | H7 Row | Full traceability chain |

---

## Add Your Hypotheses

### Hypothesis 8: [Your Belief]

**Belief:**
> *(What do you believe to be true?)*

**Why You Believe This:**
- *(Evidence or intuition)*

**Data Needed to Validate:**

| Data Point | Source | Status |
|------------|--------|--------|
| | | ⬜ |

**Risks If Wrong:**
- *(What happens if this is wrong?)*

**Cross-References:**

| Document | Relevant Section | How It Connects |
|----------|------------------|-----------------|
| | | |

---

## Hypothesis Prioritization

| Hypothesis | Confidence | Impact if True | Data Availability | Priority |
|------------|------------|----------------|-------------------|----------|
| H1: Tip of Spear | Medium | Very High | Low | 🔴 Critical |
| H2: Ecosystem Moat | High | High | Medium | 🟡 Important |
| H3: FE Enablement Blocker | High | High | Low | 🔴 Critical |
| H4: Three Archetypes | Medium | Medium | Low | 🟡 Important |
| H5: SI vs. FDE | Low | High | Low | 🟡 Important |
| H6: Influenced Revenue Metrics | Medium | Very High | Medium | 🔴 Critical |
| H7: Net-New Focus | High | Medium | Medium | 🟢 Validate |

---

## Data Collection Roadmap

### Phase 1: Quick Wins (30 days)
- [ ] FE confidence survey (H3)
- [ ] Top 20 customer archetype classification (H4)
- [ ] BU leader interviews on metrics (H6)

### Phase 2: Foundational (60 days)
- [ ] Build attach rate tracking (H1)
- [ ] Multi-product correlation analysis (H2)
- [ ] Win/loss by opportunity type (H7)

### Phase 3: Advanced (90 days)
- [ ] SI partnership performance tracking (H5)
- [ ] Influenced revenue methodology with Finance (H6)
- [ ] Expansion cohort analysis (H1, H2)

---

## Hypothesis Status Summary

| Hypothesis | Status | Last Tested | Result |
|------------|--------|-------------|--------|
| H1: Tip of Spear | ⬜ Not tested | - | - |
| H2: Ecosystem Moat | ⬜ Not tested | - | - |
| H3: FE Enablement Blocker | ⬜ Not tested | - | - |
| H4: Three Archetypes | ⬜ Not tested | - | - |
| H5: SI vs. FDE | ⬜ Not tested | - | - |
| H6: Influenced Revenue Metrics | ⬜ Not tested | - | - |
| H7: Net-New Focus | ⬜ Not tested | - | - |

*Update this table as hypotheses are validated or invalidated.*

---

*Last Updated: January 2026*
