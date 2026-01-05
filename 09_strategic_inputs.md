# Strategic Inputs: Synthesized View

*This document synthesizes all inputs into an actionable reference for planning.*

---

## North Star Metrics (Phased)

```
┌─────────────────────────────────────────────────────────────────┐
│                    METRICS PYRAMID                              │
├─────────────────────────────────────────────────────────────────┤
│                                                                 │
│                      12+ MONTHS                                 │
│                    ┌───────────┐                                │
│                    │ COVERAGE  │                                │
│                    │ Unique    │                                │
│                    │ Accounts  │                                │
│                    └─────┬─────┘                                │
│                          │                                      │
│                    6-9 MONTHS                                   │
│               ┌──────────────────┐                              │
│               │   ATTACH RATES   │                              │
│               │   SKU + Use Case │                              │
│               │   Expansion      │                              │
│               └────────┬─────────┘                              │
│                        │                                        │
│                   3-6 MONTHS                                    │
│          ┌─────────────────────────┐                            │
│          │    STRATEGIC WINS       │                            │
│          │    Decisive account     │                            │
│          │    wins proving value   │                            │
│          └─────────────────────────┘                            │
│                                                                 │
│  Earlier phases MUST succeed for later phases to be meaningful  │
│                                                                 │
└─────────────────────────────────────────────────────────────────┘
```

| Phase | North Star | Definition | Why This Sequence |
|-------|------------|------------|-------------------|
| **3-6 months** | Strategic Wins | Decisive account wins with Apps delivering clear business value | Proves hypothesis, gets exec buy-in |
| **6-9 months** | Attach Rates | SKU and use case attach driven by Apps | Validates "tip of spear" positioning |
| **12+ months** | Coverage | Unique accounts with production Apps deployed | Scales proven motion |

### Metrics Tied to Adoption Motions

Different metrics apply to different customer profiles and adoption motions. See [05_adoption_patterns.md](05_adoption_patterns.md) for full framework.

| Phase | Metric | Primary Motion | Customer Profile | Focus |
|-------|--------|----------------|------------------|-------|
| **P1 (M1-3)** | Strategic Wins | **Quality** | Business outcome-oriented, Enterprise | Few apps, deep implementation |
| **P2 (M4-6)** | Attach Rates | **Both** | Transitional | Expansion validation |
| **P3 (M7-12)** | Coverage | **Quantity** | Developer-centric, Digital Native | Many apps, dev experience |

**Key Insight:** 
- **Quality motion** (few apps, deep) drives **Strategic Wins** and **Retention**
- **Quantity motion** (many apps, lightweight) drives **Coverage** and **Developer Adoption**

### Motion-Specific Metrics

| Motion | Primary Metrics | Secondary Metrics |
|--------|-----------------|-------------------|
| **Quality** | Strategic Wins, Retention Rate, Active Users per App | Business Value Documented, PS Engagement |
| **Quantity** | Coverage, Apps Created, Active Developers | IDE Integration Usage, Self-serve Completion |

### Current Reality (Data Signal)

| Metric | Current State | Root Cause |
|--------|---------------|------------|
| Retention | Low | Motion-customer mismatch |
| Active Users per App | Low (power law) | Most apps are low-value |
| Distribution | Power law | Quality apps drive value |

**Implication:** Without intentional motion design, apps default to low-value patterns. Must match motion to customer profile.

---

## Scope and Stakeholders

### Primary Stakeholders

| Level | Role | Engagement Goal |
|-------|------|-----------------|
| **SVP** | Field Engineering Leadership | Executive sponsorship for change |
| **VP** | Vertical FE Leaders | Vertical-specific adoption motion |

### Verticals in Scope

| Vertical | Abbrev | Notes |
|----------|--------|-------|
| Manufacturing | MFG | |
| Retail | RTL | |
| Health and Life Sciences | HLS | Regulated—security/compliance critical |
| Financial Services | FSI | Regulated—security/compliance critical |
| Digital Natives | DN | Often more mature, faster adopters |

### Geographic Scope

**Global** - No regional restrictions

---

## Control Surface

### Control vs. Impact Matrix

```
┌─────────────────────────────────────────────────────────────────┐
│                  CONTROL vs IMPACT MATRIX                       │
├─────────────────────────────────────────────────────────────────┤
│                                                                 │
│   HIGH     │ INFLUENCE ZONE          │ POWER ZONE              │
│   IMPACT   │ (Low Control/High Impact)│ (High Control/High Impact)
│            │                          │                         │
│            │ • Product roadmap        │ • Playbooks/guides      │
│            │ • Field comp plans       │ • Enablement content    │
│            │ • Pricing decisions      │ • Adoption metrics      │
│            │ • SI/ISV contracts       │ • Loss analysis         │
│            │ • Marketing campaigns    │ • PM feedback synthesis │
│            │                          │ • Discovery workshops   │
│            │ → Need influence strategy│ → Own and execute       │
│            │                          │                         │
│   ─────────┼──────────────────────────┼─────────────────────────│
│            │                          │                         │
│   LOW      │ MONITOR ZONE            │ EFFICIENCY ZONE          │
│   IMPACT   │ (Low Control/Low Impact) │ (High Control/Low Impact)│
│            │                          │                         │
│            │ • Headcount decisions    │ • Meeting logistics     │
│            │ • Tool/platform choices  │ • Doc formatting        │
│            │ • Org restructures       │ • Report frequency      │
│            │                          │                         │
│            │ → Watch, don't invest    │ → Automate/delegate     │
│            │                          │                         │
│            └──────────────────────────┴─────────────────────────│
│                    LOW CONTROL              HIGH CONTROL         │
│                                                                 │
└─────────────────────────────────────────────────────────────────┘
```

### Detailed Control-Impact Assessment

| Area | Control | Impact | Quadrant | Your Strategy |
|------|---------|--------|----------|---------------|
| **Playbooks & Best Practices** | 🟢 High | 🟢 High | POWER | Own end-to-end, prioritize quality |
| **Enablement Content** | 🟢 High | 🟢 High | POWER | Create, iterate based on field feedback |
| **Adoption Metrics/Dashboards** | 🟢 High | 🟢 High | POWER | Build credibility through data |
| **Loss Analysis** | 🟢 High | 🟢 High | POWER | Make visible, drive accountability |
| **PM Feedback Synthesis** | 🟢 High | 🟢 High | POWER | Structured, timely, actionable |
| **Discovery Workshops** | 🟢 High | 🟢 High | POWER | Design, pilot, scale |
| **Messaging/Narrative** | 🟡 Medium | 🟢 High | INFLUENCE | Partner with Marketing, validate with field |
| **Product Roadmap** | 🔴 Low | 🟢 High | INFLUENCE | Data-backed PM feedback, strategic wins as proof |
| **Field Comp Plans** | 🔴 Low | 🟢 High | INFLUENCE | Exec sponsorship, attach rate data |
| **Pricing Decisions** | 🔴 Low | 🟢 High | INFLUENCE | Customer feedback, competitive intel |
| **SI/ISV Contracts** | 🔴 Low | 🟡 Medium | INFLUENCE | Partner team relationship, success stories |
| **Marketing Campaigns** | 🔴 Low | 🟡 Medium | INFLUENCE | Provide content, customer stories |
| **Headcount** | 🔴 Low | 🔴 Low | MONITOR | Accept constraint, optimize within it |

### Influence Strategies for High-Impact / Low-Control Areas

| Area | Why It Matters | Influence Lever | Specific Actions |
|------|----------------|-----------------|------------------|
| **Product Roadmap** | Scalability/cost gaps block adoption | Data-backed PM feedback | Weekly blocker synthesis, loss analysis with attribution |
| **Field Comp Plans** | Reps won't sell what doesn't pay | Exec sponsorship + attach data | Prove influenced revenue, propose Apps attach incentive |
| **Pricing Decisions** | Cost objections kill deals | Customer feedback loop | Document competitive losses, quantify price sensitivity |
| **Messaging/Narrative** | Field needs consistent story | Strategic wins as proof | Package wins into marketing-ready stories |
| **SI/ISV Contracts** | Scale requires partners | Success stories | Build 1-2 SI lighthouse successes, share with partner team |

### Influence Escalation Path

```
┌─────────────────────────────────────────────────────────────────┐
│                  INFLUENCE ESCALATION PATH                      │
├─────────────────────────────────────────────────────────────────┤
│                                                                 │
│   LEVEL 1: DATA                                                 │
│   ─────────────                                                 │
│   Present evidence: metrics, loss analysis, customer quotes     │
│   "Here's what we're seeing in the field..."                    │
│                        │                                        │
│                        ▼                                        │
│   LEVEL 2: PROPOSAL                                             │
│   ─────────────────                                             │
│   Offer specific recommendation with expected impact            │
│   "Based on data, we recommend X, expecting Y outcome..."       │
│                        │                                        │
│                        ▼                                        │
│   LEVEL 3: EXEC SPONSORSHIP                                     │
│   ─────────────────────────                                     │
│   Engage SVP/VP to champion the change                          │
│   "We've aligned with [Exec] who supports this change..."       │
│                        │                                        │
│                        ▼                                        │
│   LEVEL 4: STRATEGIC WIN                                        │
│   ──────────────────────                                        │
│   Prove impact with customer success, then generalize           │
│   "We did this with [Customer], here's the result..."           │
│                                                                 │
└─────────────────────────────────────────────────────────────────┘
```

### Critical Influence Priorities (Next 90 Days)

| Priority | Area | Current State | Target State | Influence Action |
|----------|------|---------------|--------------|------------------|
| **1** | Product Roadmap (Scalability/Cost) | Feedback fragmented | Structured PM intake | Weekly blocker synthesis to PM |
| **2** | Field Comp Plans | No Apps incentive | Apps attach in comp | Prove attach rate, propose to FE leadership |
| **3** | Messaging/Narrative | Varies by rep | Consistent "tip of spear" | Package 3 strategic wins into talk track |

### What Success Looks Like

| Area | 6-Month Outcome | Evidence |
|------|-----------------|----------|
| **Product Roadmap** | 2+ features prioritized based on your feedback | PM credits adoption team input |
| **Field Comp Plans** | Apps attach recognized in comp discussion | FE leadership socializes concept |
| **Messaging** | "Tip of spear" narrative used consistently | Hear it in field calls, see it in decks |

---

## Top Blockers (Prioritized)

| Rank | Blocker | Type | Urgency | Your Action |
|------|---------|------|---------|-------------|
| **1** | Scalability + Cost Controls | Product Gap | 🔴 Critical | PM feedback, manage field expectations |
| **2** | Security/Compliance for AI Apps | Product + Enablement Gap | 🔴 Critical | PM feedback + create patterns |
| **3** | App Architecture Uncertainty | Enablement Gap | 🟡 Important | Reference architectures (not urgent) |
| **4** | Observability Gaps | Product Gap | 🟡 Important | PM feedback, workarounds |

### Blocker 1: Scalability + Cost Controls (Field Signal Detail)

| Specific Gap | Impact | Field Quote/Context |
|--------------|--------|---------------------|
| Vertical scaling only | Can't handle burst workloads | "No horizontal scaling" |
| Fixed 24x7 pricing | Cost unpredictable, blocks cost-sensitive deals | "Fixed price for 24x7" |
| No horizontal scaling | Limits distributed architecture patterns | Field SA feedback |

**Your Action:** Synthesize into PM feedback with specific use cases blocked.

### Blocker 2: Security/Compliance (Field Signal Detail)

| Specific Gap | Impact | Field Quote/Context |
|--------------|--------|---------------------|
| No public URLs without Databricks login | Blocks external-facing apps | "Deploying apps to public URL" |
| No firewall for external apps | Can't safely expose to internet | "Don't have a firewall" |
| No ingress/egress controls | Compliance blocker for FSI, HLS | "Ingress/Egress controls" |
| CVE protection unclear | Security teams block adoption | "Are we able to protect customers?" |
| File system security | App server hardening concerns | "Securing app servers" |

**Your Action:** Escalate security cluster to PM as #1 priority. Also create enablement content for workarounds.

### Blocker 3: Architecture Uncertainty (Enablement Gap)

| Specific Gap | Impact | Resolution |
|--------------|--------|------------|
| No GPU/custom hardware guides | Developers unsure how to configure | Create configuration guides |
| Complex model serving | Friction deploying standard models | Document patterns |
| Lakebase-only database | Can't connect external DBs | Document limitation + workarounds |
| No custom domains | Can't brand customer-facing apps | Document limitation |

**Your Action:** Prioritize configuration guides and model serving patterns in enablement content.

### Blocker 4: Observability Gaps (Field Signal Detail)

| Specific Gap | Impact | Field Quote/Context |
|--------------|--------|---------------------|
| Infrastructure observability only | Can't analyze user behavior | "Access patterns, user sessions" |
| No user session tracking | Can't troubleshoot user issues | Field SA feedback |
| No access pattern analytics | Can't optimize app performance | Field SA feedback |

**Your Action:** Lower priority, but include in PM feedback synthesis.

### Blocker 5: GTM Alignment Gaps (Full Funnel)

| Specific Gap | Impact | Field Signal |
|--------------|--------|--------------|
| FE doesn't identify Apps opportunities | Missed pipeline | Full-funnel gap starts at identification |
| No guided selling triggers | FE doesn't know what to listen for | No framework for opportunity recognition |
| Industry leads not aligned on Apps use cases | No vertical-specific playbooks | Use cases vary by industry |
| Marketing events don't feature Apps demos | Low awareness, no "I want that!" moments | Events are key for exec visibility |
| EBCs don't include Apps positioning | Strategic customers don't see Apps | Execs need to see Apps in action |
| No internal hackathon momentum | FE not building Apps skills | "Month of Apps" proven model |

**Your Action:** This is a high-control area. Work with Industry Leads, Marketing, and EBC team to close these gaps.

### Blocker Resolution Strategy

| Blocker | Short-term (90 days) | Mid-term (6 months) |
|---------|----------------------|---------------------|
| **Scalability/Cost** | Set expectations, position for right use cases | Product delivers app spaces improvements |
| **Security/Compliance** | PM escalation + create security patterns playbook | Mandatory training for regulated verticals |
| **Architecture** | Configuration guides, model serving patterns | Full reference architectures |
| **Observability** | Document limitation, suggest workarounds | Product improvement |
| **GTM Alignment** | Guided selling triggers, industry lead alignment | Event presence, EBC coverage, hackathons |

---

## Field Enablement Priorities

### 90-Day Training Sprint

| Topic | Priority | Format | Owner |
|-------|----------|--------|-------|
| Security/governance patterns | 🔴 High | Playbook + workshop | Adoption Architect |
| App discovery workshop | 🔴 High | Interactive workshop | Adoption Architect + Enablement |
| Competitive talk track | 🔴 High | One-pager + role-play | Adoption Architect |
| Reference architectures | 🟡 Medium | Documentation | Adoption Architect |
| Cost/scaling guidance | 🟡 Medium | FAQ + decision tree | Adoption Architect + PM |

### Enablement Sequencing

```
Week 1-4:   Security/governance patterns (regulated verticals first)
Week 5-8:   App discovery workshop (all verticals)
Week 9-12:  Competitive talk track (all verticals)
Ongoing:    Reference architectures, cost guidance (as product matures)
```

---

## Adoption Targeting Framework

### App Archetype Targeting

| Archetype | Target Signal | Customer Profile | Priority |
|-----------|---------------|------------------|----------|
| **Business Cockpit** | Unity Catalog adoption | Established lakehouse, business stakeholder interest | 🔴 High |
| **Deep Vertical** | AI adoption signals | Strategic lighthouse, needs beachhead, analytical maturity | 🔴 High |
| **Horizontal** | Small teams OR large business presence | Platform productivity, new persona expansion | 🟡 Medium |

### Lighthouse Account Selection Criteria

| Signal | Why It Matters |
|--------|----------------|
| **Strat Hunter designation** | Pre-qualified strategic importance |
| **High platform adoption** | Data gravity creates Apps opportunity |
| **Strong data gravity** | More data = more Apps use cases |
| **AI maturity** | Deep vertical app opportunity |
| **Strong partner ecosystem** | SI/ISV can accelerate delivery |

---

## Attach Rate Measurement

### Definition Hierarchy (Priority Order)

| Priority | Definition | Credibility | Trackability |
|----------|------------|-------------|--------------|
| **1** | App-led deals where Apps was primary value narrative in MEDDICC notes / SFDC fields | 🟢 High | 🟡 Medium |
| **2** | Apps opportunity sourced, plus downstream workload expansion within 2 quarters | 🟢 High | 🟢 High |
| **3** | Apps deployed in account AND uses feature X (Lakebase / Unity / model serving) within 90 days | 🟡 Medium | 🟢 High |

### BU Leader Alignment Strategy

**Principle:** Credibility > Trackability

1. Start with Definition #1 (qualitative, high credibility)
2. Build tracking for Definition #2 and #3 in parallel
3. Once data exists, shift to quantitative definitions
4. Always supplement with strategic win narratives

---

## Operating Cadence

### Existing Forums

| Forum | Frequency | Participants | Purpose |
|-------|-----------|--------------|---------|
| Cross-functional sync | Weekly | PM + Field + Specialists | Adoption signals, blockers |
| Leadership briefing | Regular | Product + Field leaders | Metrics, loss analysis, strategic wins |

### Proposed: Apps Adoption Council

| Element | Design |
|---------|--------|
| **Frequency** | Weekly (30-45 min) |
| **Participants** | PM lead, FE vertical reps, Adoption Architect, Enablement |
| **Standing Agenda** | 1) Strategic wins update, 2) Blocker triage, 3) Enablement gaps, 4) PM feedback queue |
| **Output** | Weekly summary to FE leadership |

---

## Tip of the Spear Narrative

### One-Sentence Positioning

> "Apps are Tip of the Spear for platform adoption: Apps can serve as the entry point and container to land workloads across ETL, DW, ML, AI Agents, and Operational use cases—driving influenced revenue, expanding growth rate of other SKUs, and far exceeding direct Apps revenue."

### Narrative Flow

```
┌─────────────────────────────────────────────────────────────────┐
│                    TIP OF THE SPEAR                             │
├─────────────────────────────────────────────────────────────────┤
│                                                                 │
│   ENTRY POINT          CONTAINER           EXPANSION            │
│   ───────────          ─────────           ─────────            │
│   Apps land the        Apps bundle         Apps drive           │
│   conversation         workloads           influenced           │
│   with business                            revenue              │
│                                                                 │
│   "Here's a cockpit    "To power this      "Now they need       │
│   for your business"   app, we use..."     ETL, DW, ML..."      │
│                                                                 │
│   ┌─────────┐         ┌─────────┐         ┌─────────┐          │
│   │  APPS   │ ──────► │  ETL    │ ──────► │   DW    │          │
│   └─────────┘         │  AI     │         │   ML    │          │
│                       │  Agents │         │  Agents │          │
│                       └─────────┘         └─────────┘          │
│                                                                 │
│   Result: Influenced revenue >> Direct Apps revenue             │
│                                                                 │
└─────────────────────────────────────────────────────────────────┘
```

---

*Last Updated: January 2026*

