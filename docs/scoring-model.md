# AST Scoring Model

## Purpose

The scoring model converts simulated prior authorization workflow signals into operational readiness scores.

The scores are not clinical predictions. They are operational intelligence indicators used to identify workflow instability, trust breakdown, drift risk, reconciliation burden, and recovery pressure.

---

## Brand Standard

| Element | Standard |
|---|---|
| Accent | Tennessee Orange `#FF8200` |
| Background | White `#FFFFFF` |
| Text | Black `#111111` |
| Support | Warm Gray `#666666` |

---

## Core Scores

| Score | Meaning |
|---|---|
| Trust Risk Score | Measures likelihood that staff will stop trusting the workflow |
| Drift Risk Score | Measures likelihood that small workflow delays will compound |
| Reconciliation Density | Measures hidden manual labor and duplicate correction behavior |
| Recovery Status | Classifies whether the case is stable, monitored, drifting, or in recovery |

---

## Trust Risk Score Logic

Trust risk increases when:

- Routing confidence is low
- Eligibility confidence is low
- Manual verification is triggered
- Overrides are used
- Reconciliation events occur
- Escalation count rises

Example interpretation:

| Trust Risk Score | Meaning |
|---:|---|
| 0-25 | Stable trust condition |
| 26-50 | Monitor for trust degradation |
| 51-75 | Elevated trust instability |
| 76-100 | Critical trust breakdown risk |

---

## Drift Risk Score Logic

Drift risk increases when:

- Queue latency grows
- Escalation count rises
- Documentation is incomplete
- Routing confidence declines
- Manual work increases

Example interpretation:

| Drift Risk Score | Meaning |
|---:|---|
| 0-25 | Stable operational condition |
| 26-50 | Early drift monitoring |
| 51-75 | Active drift risk |
| 76-100 | Critical workflow instability |

---

## Recovery Status Categories

| Status | Meaning |
|---|---|
| Stable | Workflow is operating normally |
| Monitoring | Early instability is visible but contained |
| Drift Risk | Operational friction is compounding |
| Recovery Mode | Workflow requires active correction or escalation |

---

## Readiness Score Targets

| Category | Target |
|---|---:|
| Trust Stability | 8/10 |
| Drift Resistance | 8/10 |
| Human Dependency Risk | 8/10 |
| Escalation Containment | 8/10 |
| Workflow Integrity | 8/10 |
| Operational Recovery | 8/10 |
| Reconciliation Reduction | 8/10 |

---

## Executive Interpretation

A strong prior authorization workflow should not depend on staff manually catching every problem. The architecture should expose uncertainty, isolate variance, reduce reconciliation, and preserve trust through visible routing logic and measurable recovery paths.
