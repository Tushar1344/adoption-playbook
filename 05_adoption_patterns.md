# Adoption Patterns: Databricks Apps

## App Archetypes Seeing Traction

Three distinct patterns of apps are gaining adoption:

---

## Archetype 1: Business Cockpit Apps

### Definition
An application that gives business persons a clear understanding of their business across the analytics maturity spectrum.

### The Analytics Maturity Stack

```
┌─────────────────────────────────────────────────────────────────┐
│                   BUSINESS COCKPIT APP                          │
├─────────────────────────────────────────────────────────────────┤
│                                                                 │
│  ┌─────────────────────────────────────────────────────────┐    │
│  │ PRESCRIPTIVE    │ What should be done about it?        │    │
│  ├─────────────────────────────────────────────────────────┤    │
│  │ SIMULATIONS     │ How to plan for different scenarios? │    │
│  ├─────────────────────────────────────────────────────────┤    │
│  │ PREDICTIVE      │ Where is the business going?         │    │
│  ├─────────────────────────────────────────────────────────┤    │
│  │ CAUSAL          │ What is causing current state?       │    │
│  ├─────────────────────────────────────────────────────────┤    │
│  │ DESCRIPTIVE     │ Where is the business now?           │    │
│  └─────────────────────────────────────────────────────────┘    │
│                                                                 │
│  Business users get FULL VISIBILITY without SQL skills          │
│                                                                 │
└─────────────────────────────────────────────────────────────────┘
```

### Characteristics

| Dimension | Description |
|-----------|-------------|
| **Target User** | Business executives, analysts, operations managers |
| **Value Prop** | Full business visibility without technical skills |
| **AI Integration** | Predictions, scenarios, recommendations |
| **Data Needs** | Aggregated operational + analytical data |
| **Databricks Fit** | Perfect—leverages Lakehouse + ML + Lakebase |

### Example Use Cases
- Executive dashboard with scenario planning
- Operations command center with anomaly detection
- Sales forecasting with prescription recommendations
- Supply chain visibility with risk simulation

---

## Archetype 2: Deeply Vertical Apps

### Definition
Applications that address a deep pain point for a customer or completely disrupt a process/approach for specific industry tasks.

### Characteristics

| Dimension | Description |
|-----------|-------------|
| **Target User** | Domain specialists, industry practitioners |
| **Value Prop** | Solve unsolvable problems or 10x process improvement |
| **AI Integration** | Often leverages cutting-edge AI (diffusion models, etc.) |
| **Data Needs** | Specialized, often proprietary data |
| **Databricks Fit** | Good—leverages AI platform + data gravity |

### Example Use Cases

| Industry | Use Case | Disruption |
|----------|----------|------------|
| **Manufacturing** | AI-based product design | Replace months of R&D with generative design |
| **Healthcare** | Clinical trial optimization | Accelerate drug development timelines |
| **Financial Services** | Real-time fraud network analysis | Move from batch to streaming detection |
| **Retail** | Demand sensing with external signals | Replace spreadsheet forecasting |

### Key Success Factor
These apps require **deep domain expertise** to build. Often require:
- Industry-specific data models
- Specialized AI/ML capabilities
- Domain expert involvement in design

---

## Archetype 3: Horizontal Apps

### Definition
Applications that greatly improve productivity within the platform for existing users OR reduce the barrier of entry for new user segments.

### Characteristics

| Dimension | Description |
|-----------|-------------|
| **Target User** | Platform users, data stewards, analysts |
| **Value Prop** | Democratize capabilities, reduce skill requirements |
| **AI Integration** | Often AI-assisted to lower skill barrier |
| **Data Needs** | Works with existing platform data |
| **Databricks Fit** | Excellent—extends platform value |

### Example Use Cases

| App Type | Description | Value |
|----------|-------------|-------|
| **Data Quality Checks** | Business/data rules defined by non-SQL users | Data stewards don't need SQL |
| **Catalog Browser** | Visual data discovery for business users | Analysts don't need Unity Catalog expertise |
| **Query Builder** | Natural language to SQL | Business users can self-serve |
| **Notebook Publisher** | Turn notebooks into shareable apps | Data scientists become app builders |

### Key Success Factor
These apps **expand the addressable user base** for Databricks:
- Non-technical users can access platform capabilities
- Technical users can 10x their productivity
- Creates "land and expand" motion within accounts

---

## Adoption Pattern Summary

| Archetype | Primary Buyer | Expansion Path | Complexity |
|-----------|---------------|----------------|------------|
| **Business Cockpit** | Business exec + Data team | Drives DW, ML adoption | Medium |
| **Deeply Vertical** | Industry LoB + Data team | Drives specialized ML, ETL | High |
| **Horizontal** | Platform team | Drives platform-wide adoption | Low-Medium |

---

## Archetype Targeting Matrix

Archetypes are **not mutually exclusive**—a customer may fit multiple patterns. Use signals to identify which archetypes apply:

| Signal | Cockpit | Vertical | Horizontal |
|--------|:-------:|:--------:|:----------:|
| **Unity Catalog adopted** | ✅ | | |
| **AI/ML maturity (models in prod)** | | ✅ | |
| **Large business user base** | ✅ | | ✅ |
| **Deep domain pain point** | | ✅ | |
| **Platform productivity needs** | | | ✅ |
| **Strong data gravity** | ✅ | ✅ | |
| **Executive sponsorship** | ✅ | ✅ | |
| **Small technical team** | | | ✅ |

**How to Use:**
1. Assess customer against each signal
2. Check which archetypes light up
3. Multiple ✅ = pursue multiple playbooks in parallel
4. Prioritize based on customer's stated priorities

---

## Use Case Qualification Framework

### Fit Assessment Questions

1. **Is the use case net-new or migration?**
   - Net-new → Good fit
   - Legacy migration → Not ready yet

2. **Does it leverage Databricks data gravity?**
   - Data already in Lakehouse → Strong fit
   - Requires new data onboarding → Okay fit
   - Data in competitor platform → Weak fit

3. **Does it require AI/ML?**
   - Yes, AI-powered → Differentiator
   - No AI needed → Still fits, but weaker moat

4. **Who is the end user?**
   - Business users → Good (expands addressable market)
   - Technical users only → Okay (platform extension)

5. **What's the governance requirement?**
   - Strict governance needed → Strong fit (moat)
   - Loose governance → Less differentiated

---

## Adoption Signal Tracking

### Leading Indicators

| Signal | What It Indicates |
|--------|-------------------|
| Unity Catalog adoption | Governance readiness for Apps |
| ML model deployment | AI integration opportunity |
| Large data footprint | Data gravity for Apps |
| Business user access requests | Demand for self-serve Apps |

### Lagging Indicators

| Signal | What It Indicates |
|--------|-------------------|
| Apps SKU adoption | Direct revenue |
| Multi-app deployments | Platform stickiness |
| Cross-workload expansion | Influenced revenue |

---

## Gaps to Address

- [ ] Build reference architectures for each archetype
- [ ] Create qualification playbook for field teams
- [ ] Identify and profile 2-3 lighthouse customers per archetype
- [ ] Develop demo assets for each pattern
- [ ] Define adoption metrics per archetype

---

*Last Updated: January 2026*

