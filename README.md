# Authorization Stability Tracker

## Detecting operational instability before prior authorization workflows fail.

**Created by Kori Pickle**  
BSHA Student | Healthcare Operations & Workflow Intelligence | Revenue Cycle Operations

---

## Brand Identity

This project uses a clean healthcare operations portfolio identity built around:

| Element | Standard |
|---|---|
| Primary Background | White `#FFFFFF` |
| Accent Color | Tennessee Orange `#FF8200` |
| Primary Text | Black `#111111` |
| Supporting Text | Warm Gray `#666666` |
| Style | Premium editorial, structured, high-whitespace, executive-facing |

The visual direction is intentionally clean, direct, and operational. The goal is to make healthcare workflow instability easy to understand at an executive level.

---

## Project Overview

The **Authorization Stability Tracker (AST)** is a healthcare operations intelligence project designed to detect operational drift, trust instability, escalation risk, and reconciliation burden inside prior authorization workflows.

Prior authorization problems rarely appear as one isolated failure. They usually build through small workflow breakdowns such as payer delays, incomplete documentation, routing uncertainty, staffing pressure, manual verification, and hidden rework. AST turns those breakdowns into measurable operational signals.

This project uses simulated, non-PHI healthcare workflow data to model how prior authorization instability affects:

- Patient access
- Revenue cycle operations
- Staff workload
- Escalation pressure
- Documentation reliability
- Denial risk
- Operational recovery

---

## Why This Project Matters

Most prior authorization tracking focuses on basic status updates:

- Approved
- Denied
- Pending
- More information needed

AST focuses on something deeper:

> Is the authorization workflow still stable, trusted, and recoverable?

That distinction matters because healthcare teams often compensate for weak systems through invisible labor. Staff create side spreadsheets, manually recheck information, bypass official routing, rely on tribal knowledge, or escalate through informal channels. Those behaviors are not staff problems. They are system signals.

AST is designed to surface those signals before the workflow becomes reconciliation-heavy and unstable.

---

## Core System Modules

| Module | Purpose |
|---|---|
| Trust Engine | Detects manual verification, override behavior, and workflow confidence breakdowns |
| Drift Engine | Measures latency growth, queue expansion, and compounding workflow variance |
| Reconciliation Engine | Tracks hidden labor, duplicate work, manual correction, and shadow workflow behavior |
| Escalation Engine | Monitors escalation frequency, unresolved cases, and operational pressure |
| Recovery Engine | Measures how quickly the workflow stabilizes after disruption |
| Executive Scorecard | Summarizes readiness across trust, drift, integrity, recovery, and reconciliation reduction |

---

## Repository Structure

```text
authorization-stability-tracker/
|
|-- data/
|   |-- authorization_cases.csv
|   |-- trust_engine.csv
|   |-- drift_engine.csv
|
|-- docs/
|   |-- system-architecture.md
|   |-- scoring-model.md
|
|-- stress-tests/
|   |-- trust-collapse-test.md
|   |-- operational-drift-test.md
|   |-- human-dependency-test.md
|
|-- reports/
|   |-- executive-audit-report.md
|
|-- dashboards/
|   |-- dashboard-layout.md
|
|-- workflow-maps/
|   |-- workflow-map.md
|
|-- README.md
|-- LICENSE
```

---

## Stress Tests

AST is built around three operational integrity tests.

### 1. Trust Collapse Test

Evaluates whether staff continue trusting the workflow when payer eligibility, documentation timing, routing, or demographic data becomes unreliable.

Key signals:

- Manual verification spikes
- Duplicate work
- Side spreadsheet behavior
- Workflow bypassing
- Escalation growth
- Turnaround-time drift

### 2. Operational Drift Test

Evaluates whether small workflow inconsistencies compound into backlog, rework, delayed reimbursement, and operational drag over time.

Key signals:

- Queue buildup
- Documentation lag
- Escalation clustering
- Rework acceleration
- Delayed downstream claims
- Staff frustration indicators

### 3. Human Dependency Test

Evaluates whether the workflow can function without specific experienced staff carrying undocumented process knowledge.

Key signals:

- Routing confusion
- Tribal knowledge exposure
- Authorization delays
- Manual dependency spikes
- Undocumented workaround reliance

---

## Target Readiness Categories

| Category | Target Score |
|---|---:|
| Trust Stability | 8/10 |
| Drift Resistance | 8/10 |
| Human Dependency Risk | 8/10 |
| Escalation Containment | 8/10 |
| Workflow Integrity | 8/10 |
| Operational Recovery | 8/10 |
| Reconciliation Reduction | 8/10 |

---

## Portfolio Positioning

This project demonstrates practical healthcare administration and operations skills, including:

- Prior authorization workflow analysis
- Revenue cycle operations thinking
- Operational risk detection
- Quality improvement logic
- Stress-test design
- Executive reporting
- Dashboard planning
- Simulated healthcare data modeling

It is designed as a no-cost, portfolio-ready project using simulated healthcare operations data. No patient information, protected health information, or live organizational data is used.

---

## Signature Insight

> Prior authorization workflows do not fail only when a denial happens. They begin failing when staff stop trusting the workflow and start manually stabilizing the system themselves.

---

## Created By

**Kori Pickle**  
Healthcare Operations & Workflow Intelligence  
University of Phoenix BSHA Student
