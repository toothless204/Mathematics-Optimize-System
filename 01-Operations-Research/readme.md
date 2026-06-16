# 01 — Operations Research Portfolio

> A progressive Operations Research portfolio built to demonstrate how mathematical models can turn operational complexity into better decisions.

This repository is not a random collection of assignments. It is designed as a structured decision-science portfolio: each project represents a different class of real-world decision problem, a different level of managerial decision-making, and a higher level of mathematical modeling complexity.

The portfolio moves from **logistics cost optimization** to **production planning**, **facility network design**, **inventory uncertainty**, and **workforce scheduling**.

---

## Why This Portfolio Exists

Operations Research is not just about solving equations.

It is about answering questions that matter in the real world:

- Where should goods be shipped?
- What should a factory produce?
- Where should facilities be located?
- How much inventory should be held under uncertainty?
- How should people and shifts be scheduled fairly and efficiently?

This repository is built to show the full workflow:

```text
Business Problem
      ↓
Mathematical Model
      ↓
Optimization / Simulation
      ↓
Result Interpretation
      ↓
Managerial Decision
```

---

## Portfolio Architecture

| Project | Decision Question | Decision Level | Core Method |
|---|---|---|---|
| OR-1 | How can transportation cost be minimized? | Operational | Linear Programming |
| OR-2 | What should be produced, when, and with which resources? | Tactical | LP / MILP |
| OR-3 | Which facilities should be opened to serve demand efficiently? | Strategic | MILP / Binary Optimization |
| OR-4 | How should inventory be managed when demand is uncertain? | Tactical | Stochastic Optimization + Monte Carlo |
| OR-5 | How can workforce schedules satisfy demand, fairness, and constraints? | Operational | Integer Programming |

---

## Project Roadmap

| No. | Project | Topic | Domain | Method | Status |
|---|---|---|---|---|---|
| 1 | [OR-1-Optimasi-Biaya](./OR-1-Optimasi-Biaya/) | Transportation Cost Optimization | Logistics | LP — Transportation Model | Finished |
| 2 | [OR-2-Production-Mix](./OR-2-Production-Mix/) | Multi-Period Production Mix Optimization | Manufacturing | LP / MILP | Planned |
| 3 | [OR-3-Facility-Location](./OR-3-Facility-Location/) | Facility and Warehouse Network Design | Distribution Network | MILP — Binary Location Model | Planned |
| 4 | [OR-4-Inventory-Optimization](./OR-4-Inventory-Optimization/) | Inventory Policy Under Demand Uncertainty | Retail / Pharmaceutical Supply Chain | Stochastic Model + Simulation | Planned |
| 5 | [OR-5-Workforce-Scheduling](./OR-5-Workforce-Scheduling/) | Multi-Skill Workforce Scheduling | Healthcare / Service Operations | Integer Programming | Planned |

---

## Technical Progression

This portfolio is arranged to show increasing modeling maturity.

```text
OR-1  Transportation Model
      Continuous LP, cost minimization, supply-demand constraints
        ↓
OR-2  Production Mix
      Multi-period planning, resource allocation, inventory carry-over
        ↓
OR-3  Facility Location
      Binary decisions, network design, capacity allocation
        ↓
OR-4  Inventory Optimization
      Uncertainty, probability distributions, Monte Carlo validation
        ↓
OR-5  Workforce Scheduling
      Integer programming, combinatorial decisions, fairness constraints
```

---

## Project Design Standard

Each project is expected to contain:

| Component | Purpose |
|---|---|
| Problem Statement | Defines the real-world decision problem |
| Mathematical Formulation | Converts the problem into variables, objective function, and constraints |
| Dataset | Contains input parameters and assumptions |
| Solver Implementation | Solves the model using Python, Excel Solver, or optimization libraries |
| Outputs | Shows optimal solution, tables, charts, maps, or dashboards |
| Business Interpretation | Explains what the result means for decision-makers |
| Sensitivity Analysis | Tests how the solution changes under different assumptions |

---

## Repository Structure

```text
01-Operations-Research/
│
├── README.md
│
├── OR-1-Optimasi-Biaya/
│   ├── README.md
│   ├── data/
│   ├── src/
│   ├── outputs/
│   └── docs/
│
├── OR-2-Production-Mix/
│   ├── README.md
│   ├── data/
│   ├── src/
│   ├── outputs/
│   └── docs/
│
├── OR-3-Facility-Location/
│   ├── README.md
│   ├── data/
│   ├── src/
│   ├── outputs/
│   └── docs/
│
├── OR-4-Inventory-Optimization/
│   ├── README.md
│   ├── data/
│   ├── src/
│   ├── outputs/
│   └── docs/
│
└── OR-5-Workforce-Scheduling/
    ├── README.md
    ├── data/
    ├── src/
    ├── outputs/
    └── docs/
```

---

## Folder Convention

| Folder | Description |
|---|---|
| `data/` | Input data, parameters, assumptions, and data dictionary |
| `src/` | Python scripts, notebooks, solver models, and computational workflow |
| `outputs/` | Optimization results, charts, tables, maps, and executive summaries |
| `docs/` | Mathematical formulation, methodology notes, reports, and references |
| `README.md` | Project overview, model explanation, key results, and insights |

---

## Methods Covered

This portfolio covers several important Operations Research methods:

- Linear Programming
- Transportation Model
- Mixed Integer Linear Programming
- Facility Location Model
- Production Planning
- Inventory Optimization
- Stochastic Modeling
- Monte Carlo Simulation
- Integer Programming
- Workforce Scheduling
- Sensitivity Analysis
- Scenario Analysis

---

## Tools

The tools used across the projects may include:

- Python
- pandas
- NumPy
- SciPy
- PuLP
- Google OR-Tools
- matplotlib
- folium
- Excel Solver
- Jupyter Notebook

---

## What This Portfolio Demonstrates

This repository is built to demonstrate the ability to:

- Translate real-world problems into mathematical models
- Define decision variables, objective functions, and constraints
- Solve optimization problems using computational tools
- Interpret quantitative results in business language
- Connect operations, economics, technology, and managerial decision-making
- Build decision-support models that are understandable, repeatable, and useful

---

## Project-Level Intent

### OR-1 — Transportation Cost Optimization

The foundation project.  
Focuses on minimizing distribution cost while satisfying supply and demand constraints.

**Main capability shown:** logistics optimization using linear programming.

---

### OR-2 — Production Mix Optimization

A tactical planning project.  
Focuses on deciding production quantities across products, periods, and limited resources.

**Main capability shown:** production planning, resource allocation, and margin optimization.

---

### OR-3 — Facility Location Optimization

A strategic network design project.  
Focuses on deciding which facilities or warehouses should be opened and how demand should be allocated.

**Main capability shown:** binary decision-making, location strategy, and network optimization.

---

### OR-4 — Inventory Optimization Under Uncertainty

A stochastic decision project.  
Focuses on determining reorder points, safety stock, and order quantities under uncertain demand and lead time.

**Main capability shown:** uncertainty modeling, service-level trade-offs, and simulation validation.

---

### OR-5 — Workforce Scheduling Optimization

A combinatorial service-operations project.  
Focuses on assigning workers to shifts while satisfying staffing needs, skill requirements, fairness, and cost constraints.

**Main capability shown:** integer programming, scheduling, and operational workforce planning.

---


## References

- Hillier, F. S., & Lieberman, G. J. *Introduction to Operations Research*.
- Taha, H. A. *Operations Research: An Introduction*.
- Winston, W. L. *Operations Research: Applications and Algorithms*.
- Bertsimas, D., & Tsitsiklis, J. N. *Introduction to Linear Optimization*.
- Silver, E. A., Pyke, D. F., & Peterson, R. *Inventory Management and Production Planning and Scheduling*.

---

## Status

This portfolio is under active development.  
Each project will be expanded with data, mathematical models, solver implementation, output analysis, and managerial interpretation.
