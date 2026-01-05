# GTM Motion: Databricks Apps

## Strategic GTM Imperative

### Apps as "Tip of the Spear"

Apps can serve as the entry point to land workloads across the Databricks platform:

```
┌─────────────────────────────────────────────────────────────────┐
│                    APPS AS TIP OF THE SPEAR                     │
├─────────────────────────────────────────────────────────────────┤
│                                                                 │
│                         ┌──────────┐                            │
│                         │   APPS   │ ← Entry Point              │
│                         └────┬─────┘                            │
│                              │                                  │
│              ┌───────────────┼───────────────┐                  │
│              ▼               ▼               ▼                  │
│        ┌─────────┐     ┌─────────┐     ┌─────────┐              │
│        │   ETL   │     │   DW    │     │   ML    │              │
│        └─────────┘     └─────────┘     └─────────┘              │
│              │               │               │                  │
│              └───────────────┼───────────────┘                  │
│                              ▼                                  │
│                    ┌─────────────────┐                          │
│                    │    AI AGENTS    │                          │
│                    └─────────────────┘                          │
│                              │                                  │
│                              ▼                                  │
│                    ┌─────────────────┐                          │
│                    │   OPERATIONAL   │                          │
│                    │    USE CASES    │                          │
│                    └─────────────────┘                          │
│                                                                 │
│  Apps act as a CONTAINER for workloads →                        │
│  Influenced revenue + deep product adoption                     │
│                                                                 │
└─────────────────────────────────────────────────────────────────┘
```

### GTM Value of Apps-Led Motion

| Benefit | Description |
|---------|-------------|
| **Influenced Revenue** | Apps pull through ETL, DW, ML, AI Agent workloads |
| **Business Value Positioning** | Apps are visible to business users, not just data teams |
| **New Funding Sources** | Unlock budget from business units, not just IT/Data |
| **Deep Adoption** | Apps drive sustained platform usage |

---

## Attach Rate Metrics (To Be Defined)

To measure influenced revenue, we need alignment on:

| Metric | Definition | Owner |
|--------|------------|-------|
| **Apps Attach Rate** | % of accounts with Apps that expand to other SKUs | TBD |
| **Influenced ACV** | Revenue from workloads pulled through by Apps | TBD |
| **Workload Velocity** | Time from Apps adoption to additional SKU adoption | TBD |

**Action Required:** Align with BU leaders on how to measure and forecast product impact.

---

## Field Readiness Assessment

### Current State

| Capability | Readiness |
|------------|-----------|
| Data Engineering conversations | ✅ Ready |
| Data Modeling conversations | ✅ Ready |
| Governance conversations | ✅ Ready |
| **Backend app design patterns** | ❌ Not Ready |
| **Frontend app design patterns** | ❌ Not Ready |
| **App architecture best practices** | ❌ Not Ready |

### The Gap

**Databricks Field Engineering is equipped to handle Data Engineering, Modeling, and Governance conversations but isn't readily equipped to handle application (backend and frontend) design patterns and best practices conversations.**

### Current Enablement Assets

| Asset | Coverage | Gap |
|-------|----------|-----|
| **Apps Cookbook** | Simple examples only | Does not show "what good looks like" |
| **Architecture guidance** | Limited | No reference architectures |
| **Demo assets** | Basic | No industry-specific demos |

---

## Sales Objection Framework: Money, Mindshare, Maturity

Field teams raise three consistent objections to pushing new products:

### Objection 1: Money
> "Will this product make money for me?"

| Objection | Response |
|-----------|----------|
| "Apps revenue is too small" | Focus on **influenced revenue** not direct revenue |
| "I can't forecast Apps" | Apps attach rate shows predictable expansion |
| "My comp is tied to core products" | Apps accelerate core product adoption |

**Key Metric:** Attach rate and influenced ACV

---

### Objection 2: Mindshare
> "Too many products to position—why lead with Apps?"

| Objection | Response |
|-----------|----------|
| "I have too many products to pitch" | Apps is a **container** for other workloads—one pitch, multiple SKUs |
| "Customers don't ask for Apps" | Apps positions us closer to **business value** |
| "Data teams don't care about apps" | Apps unlock **business team** budget and sponsorship |

**Key Message:** Apps-led selling = Solutions Selling. One conversation, multiple workloads.

---

### Objection 3: Maturity
> "My customer isn't ready, or the product doesn't fit."

| Objection | Response |
|-----------|----------|
| "Customer isn't mature enough" | Identify **maturity indicators** for Apps readiness |
| "Product doesn't fit their needs" | Qualify based on **use case fit**, not product features |
| "They're a legacy Java shop" | Position for **net-new** apps, not migration (yet) |

**Key Tool:** Customer maturity assessment + use case qualification framework

---

### Objection 4: Product Limitations (Field Signal: Jan 2026)
> "The product has gaps that block my customer's use case."

These objections come from real field signal. Honest positioning is critical.

| Objection | Current Reality | Response |
|-----------|-----------------|----------|
| "Can Apps scale horizontally?" | **No.** Vertical scaling only. | Position for **moderate-traffic internal apps**. For high-burst workloads, recommend waiting or using hybrid architecture. |
| "Can we deploy public-facing apps?" | **Limited.** No public URLs without Databricks login, no firewall, no ingress/egress controls. | Position for **internal apps** or apps behind customer's own auth layer. External-facing is on roadmap—document customer need. |
| "What about cost control?" | **Fixed 24x7 pricing only.** No pay-per-use. | Be transparent. Best fit is apps with **consistent usage patterns**. Highly variable workloads may see cost objections. |
| "Can we use GPUs?" | **No GPU/custom hardware config.** | Position for **CPU-based workloads**. GPU inference should use Model Serving, not Apps. |
| "Can we connect to external databases?" | **Lakebase only.** | Position for apps that **natively use Lakehouse data**. Hybrid OLTP apps are not a fit today. |
| "What about CVE protection?" | **Unclear.** | Escalate to security team for specific customer concerns. Document and feed to PM. |

**Key Message:** Apps is best for **internal, data-native, moderate-traffic applications**. Be honest about limitations; it builds trust and prevents failed deployments.

**When to Walk Away (For Now):**
- Customer needs external-facing apps with internet exposure
- Customer needs horizontal auto-scaling for burst traffic
- Customer is highly cost-sensitive with variable workloads
- Customer requires GPU inference in the app layer

**Document Every "Walk Away":** These are loss analysis signals. Feed to PM via Field Signal Log.

---

## ICP Definition (To Be Validated)

### Ideal Customer Profile for Apps

| Dimension | Criteria |
|-----------|----------|
| **Platform Maturity** | Already using Databricks for analytics/ML |
| **Use Case** | Building new data-intensive applications |
| **Buyer** | Data team with business unit sponsorship |
| **Tech Stack** | Open to Python/modern frameworks (not legacy Java/.NET) |
| **AI Interest** | Wants AI-powered applications |

### Disqualifiers (For Now)

| Signal | Reason |
|--------|--------|
| Legacy app migration priority | Platform not ready yet |
| Hyperscaler-first strategy | Harder to displace |
| No existing Databricks footprint | Cold start too hard |
| Pure IT buyer (no business sponsor) | Hard to show business value |

---

## Marketing Events Strategy

### Why Events Matter for Apps
- Executives need to see Apps in action to say "I want that!"
- Field needs demos to reference in customer conversations
- Marketing events drive awareness and create demand

### Event Calendar for Apps Visibility

| Event | Timing | Target Demo | Owner | Status |
|-------|--------|-------------|-------|--------|
| **NRF (National Retail Federation)** | Jan | Retail cockpit: Inventory visibility app | Marketing + Retail Lead | ⬜ TBD |
| **HIMSS (Healthcare)** | Mar | HLS cockpit: Clinical operations app | Marketing + HLS Lead | ⬜ TBD |
| **Data+AI Summit** | Jun | Flagship Apps demo (multi-archetype) | Marketing | ⬜ TBD |
| **Data+AI World Tours** | Ongoing | Regional Apps demos by vertical | Field Marketing | ⬜ TBD |
| **AWS re:Invent** | Nov | Apps vs hyperscaler positioning demo | Marketing | ⬜ TBD |
| **Google I/O** | May | AI-powered Apps demo | Marketing | ⬜ TBD |
| **Money 20/20** | Oct | FSI cockpit: Risk dashboard app | Marketing + FSI Lead | ⬜ TBD |

### Event Demo Requirements

| Requirement | Description |
|-------------|-------------|
| **"I Want That!" Moment** | Demo must create immediate executive desire |
| **Industry Relevance** | Vertical-specific use case, not generic |
| **Platform Story** | Show data+AI integration, not just app |
| **Leave-Behind** | QR code to demo environment or video |

### Event Strategy Actions

| Action | Owner | Timeline |
|--------|-------|----------|
| Propose Apps demo for Data+AI Summit 2026 | Marketing + AA | P1 (M1-3) |
| Align with industry leads on vertical event presence | AA + Industry Leads | P1 (M1-3) |
| Create demo video library for field use | Marketing + AA | P2 (M4-6) |

---

## EBC (Executive Briefing Center) Strategy

### Why EBCs Matter
- Strategic customers visit EBCs for executive-level engagement
- Executives make platform decisions in EBCs
- "I want that!" moments drive Apps adoption from the top

### EBC Apps Coverage Standard

| Element | Description | Owner |
|---------|-------------|-------|
| **Apps Positioning Slot** | 15-30 min segment on Apps in every EBC | EBC Team + AA |
| **Live Demo** | Interactive Apps demo tailored to customer vertical | Industry Lead |
| **Business Value Story** | ROI narrative, not just technical | AA |
| **Customer Proof Point** | Reference customer in same vertical | AA |

### EBC Demo by Vertical

| Vertical | Demo | Key Message |
|----------|------|-------------|
| **Retail** | Inventory visibility cockpit | "Real-time business visibility" |
| **FSI** | Risk dashboard with ML | "AI-powered decision making" |
| **HLS** | Clinical operations app | "Data-driven care coordination" |
| **MFG** | Supply chain cockpit | "End-to-end visibility" |
| **DN** | Platform productivity app | "Democratize data access" |

### EBC Success Metrics

| Metric | Definition | Target |
|--------|------------|--------|
| **% of EBCs with Apps Demo** | EBCs that include Apps positioning | 80% by Q3 |
| **Exec "I Want That!" Rate** | Post-EBC feedback indicating Apps interest | TBD |
| **Apps Opportunities from EBCs** | Pipeline sourced from EBC Apps demos | TBD |

### EBC Strategy Actions

| Action | Owner | Timeline |
|--------|-------|----------|
| Define EBC Apps coverage standard with EBC team | AA + EBC Team | P1 (M1-3) |
| Create EBC demo kit by vertical | AA + Industry Leads | P2 (M4-6) |
| Pilot EBC Apps coverage with 5 strategic customers | AA + EBC Team | P2 (M4-6) |
| Track EBC Apps pipeline influence | AA + Ops | P2 (M4-6) |

---

## GTM Motion Gaps to Address

- [ ] Define attach rate metrics with BU leaders
- [ ] Create field enablement for app design conversations
- [ ] Build reference architectures showing "what good looks like"
- [ ] Develop customer maturity assessment tool
- [ ] Create objection-handling playbook with proof points
- [ ] Identify and profile successful Apps customers for case studies
- [x] Add event strategy for Apps visibility
- [x] Add EBC strategy for executive exposure
- [ ] Align with industry leads on use cases by vertical

---

*Last Updated: January 2026*

