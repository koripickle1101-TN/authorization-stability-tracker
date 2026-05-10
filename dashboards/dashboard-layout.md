# AST Dashboard Layout

## Dashboard Name

Authorization Stability Tracker Executive Dashboard

---

## Brand Identity

| Element | Standard |
|---|---|
| Background | White `#FFFFFF` |
| Accent | Tennessee Orange `#FF8200` |
| Primary Text | Black `#111111` |
| Supporting Text | Warm Gray `#666666` |
| Visual Style | Premium editorial, clean healthcare operations, executive-facing |

---

## Dashboard Purpose

This dashboard is designed to show whether the prior authorization workflow is stable, drifting, or entering recovery mode.

It should help answer:

- Are authorization queues becoming unstable?
- Are staff manually verifying too many cases?
- Are escalation counts increasing?
- Are documentation problems causing drift?
- Are reconciliation events increasing?
- Is workflow trust weakening?

---

## Section 1: Executive Scorecards

Recommended top-row cards:

| Card | Measure |
|---|---|
| Average Trust Risk Score | Average trust risk across all cases |
| Average Drift Risk Score | Average drift risk across all cases |
| Total Escalations | Sum of escalation count |
| Manual Verification Rate | Percent of cases with manual verification |
| Reconciliation Event Rate | Percent of cases with reconciliation events |
| Recovery Mode Cases | Count of cases in recovery mode |

---

## Section 2: Operational Stability Trends

Recommended charts:

| Chart | Purpose |
|---|---|
| Queue Latency by Case | Shows authorization delay pressure |
| Drift Risk by Service Line | Identifies workflow zones with instability |
| Escalation Count by Payer Type | Shows payer-related operational pressure |
| Recovery Status Distribution | Shows workflow stability categories |

---

## Section 3: Trust and Reconciliation

Recommended charts:

| Chart | Purpose |
|---|---|
| Trust Risk Score by Case | Finds cases with trust instability |
| Manual Verification by Payer Type | Shows where staff rechecking increases |
| Override Usage | Tracks bypass behavior |
| Reconciliation Events | Identifies hidden correction labor |

---

## Section 4: Executive Interpretation

Recommended insight box:

```text
Key Insight:
Workflow instability is strongest when queue latency, manual verification, and escalation count rise together. These signals suggest that staff may be compensating for workflow uncertainty before the system fully detects instability.
```

---

## Suggested Build Tool

Use Google Sheets first. Then connect the CSV or Sheet to Looker Studio when ready.

Start simple. A basic dashboard with 4 scorecards and 4 charts is enough for version 1.
