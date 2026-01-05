# Product Context: Databricks Apps

## Product Overview

**Databricks Apps** is a new product line enabling customers to build and deploy applications natively on the Databricks platform.

---

## Current State

| Metric | Value |
|--------|-------|
| **Revenue Growth** | $5M → $70M in one year (organic, 14x growth) |
| **GTM Maturity** | Scaled organically without clear product strategy |
| **SKU Model** | Standalone SKU available |

### What's Working
- Strong organic adoption signal
- Executive preference for building on Databricks
- Natural synergy with existing data/AI investments

### What's Not Ready Yet
- App hosting platform capabilities still being built
- Fine-grained cost control not available
- Infinite scalability not yet competitive with hyperscalers
- Not positioned to compete head-to-head with established app platforms

---

## Product Limitations (Current)

### High-Level Limitations

| Limitation | Impact | Expected Resolution |
|------------|--------|---------------------|
| **Legacy App Support** | Cannot migrate Java/.NET enterprise apps | FY27 (next year) |
| **Cost Control** | No fine-grained cost management | In development |
| **Scalability** | Not yet "infinite" like hyperscalers | In development |

### Detailed Gap Inventory (Field Signal: Jan 2026)

| Category | Gap | Impact | Use Case Blocked | Source |
|----------|-----|--------|------------------|--------|
| **Scaling** | Vertical scaling only | Can't handle burst workloads | High-traffic apps | Field SA |
| **Scaling** | No horizontal scaling | Limits distributed app patterns | Multi-instance apps | Field SA |
| **Customization** | No GPU/custom hardware config | Can't run GPU-intensive workloads | AI inference apps | Field SA |
| **Customization** | Needs configuration guides | Developers unsure how to optimize | All | Field SA |
| **Model Serving** | Complex standard model deployment | Friction for ML-powered apps | AI apps | Field SA |
| **Database** | Lakebase only, no external DB | Can't connect to existing OLTP | Hybrid apps | Field SA |
| **Domains** | No custom domains/vanity URLs | Can't brand customer-facing apps | External apps | Field SA |
| **Security** | No public URLs without Databricks login | Blocks external-facing apps | Customer portals | Field SA |
| **Security** | No firewall for external apps | Can't safely expose to internet | Public apps | Field SA |
| **Security** | No ingress/egress controls | Compliance blocker (regulated industries) | FSI, HLS apps | Field SA |
| **Security** | CVE protection unclear | Security team concerns | Enterprise apps | Field SA |
| **Security** | File system security gaps | App server hardening concerns | All | Field SA |
| **Cost** | Fixed 24x7 pricing only | No pay-per-use, cost unpredictable | Cost-sensitive apps | Field SA |
| **Observability** | No user session tracking | Can't analyze user behavior | All | Field SA |
| **Observability** | No access pattern analytics | Can't optimize app performance | All | Field SA |

### Gap Priority for PM Feedback

| Priority | Gap Cluster | Deal Impact | Action |
|----------|-------------|-------------|--------|
| **1** | Security (public apps, firewall, ingress/egress) | Blocks regulated industries | Escalate to PM immediately |
| **2** | Cost (fixed pricing) | Objection in every deal | Include in PM feedback cycle |
| **3** | Scaling (horizontal) | Limits architecture patterns | Track loss analysis |
| **4** | Observability | Post-deployment friction | Lower priority |

### Current Sweet Spot
- **Net-new applications** built natively on Databricks
- Customers already invested in Databricks data/AI ecosystem
- Use cases leveraging Lakebase, Governance, and AI integration

---

## Product Roadmap

### Near-Term (FY26)

| Initiative | Description |
|------------|-------------|
| **App Spaces** | Related apps that can be spun up/down easily |
| **Cost Efficiency** | Improved resource management for app clusters |

### Mid-Term (FY27)

| Initiative | Description |
|------------|-------------|
| **Legacy Framework Support** | Java/.NET app migration capability |
| **Fully Featured Apps** | More complete app development experience |

### Long-Term Vision

| Initiative | Description |
|------------|-------------|
| **Vertical SaaS on Apps** | CDP, Cybersecurity Analytics built on Apps platform |
| **Platform Maturity** | Compete with hyperscaler app platforms |

---

## Product Strategy Assessment

### Strengths
- 14x organic growth validates market demand
- Strong integration with Databricks ecosystem
- Executive buy-in for platform consolidation

### Gaps / Risks
- No clear product strategy documented
- ICP (Ideal Customer Profile) may not be aligned between Product and GTM
- Feature gaps limit competitive positioning vs. established platforms

### Critical Questions
- [ ] Is there alignment between Product and GTM on ICP?
- [ ] What's the biggest product gap killing deals today?
- [ ] How do we message limitations while the platform matures?

---

## Implications for Adoption Architect Role

1. **Position for net-new apps** - Don't fight the legacy migration battle yet
2. **Lead with ecosystem value** - Apps + Lakebase + Governance + AI = differentiation
3. **Manage expectations** - Set realistic timelines for feature parity
4. **Capture signal** - Use adoption friction to influence PM roadmap prioritization

---

*Last Updated: January 2026*

