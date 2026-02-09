# HireSight — Hiring & Attrition as One Decision System

Hiring mistakes don’t show up immediately.
They surface months later as attrition, disengagement, and cultural misalignment.

HireSight explores how early hiring signals can be used to anticipate and reduce these failures.

## Problem
Startups often treat hiring and retention as separate problems.
In reality, poor hiring decisions are one of the strongest drivers of early attrition.

## What this project does
This project connects hiring and retention as one system by:
- Modeling attrition risk using early employee signals
- Identifying dominant drivers like work-life harmony and managerial clarity
- Translating predictions into interpretable decision insights
- Validates model insights using Power BI and Tableau dashboards to support decision-making

## Project Structure

The repository is organized to reflect the full decision pipeline — from data understanding to insights and validation.

hiresight-hiring-attrition-decision-system/
├── README.md
├── notebooks/
│   ├── 01_problem_and_data_understanding.ipynb
│   ├── 02_attrition_prediction_model.ipynb
│   └── 03_decision_logic_and_insights.ipynb
├── dashboards/
│   ├── powerbi_overview.png
│   └── tableau_attrition_analysis.png
├── slides/
│   └── README.md
├── assumptions.md
└── requirements.txt



**Folder intent**
- `notebooks/` → Core analysis and decision logic
- `dashboards/` → BI validation of model insights
- `slides/` → Business context and product architecture
- `assumptions.md` → Explicit modeling and data assumptions

## How to Navigate This Repository

If you’re short on time:
1. Start with `README.md` for problem context
2. Review `03_decision_logic_and_insights.ipynb` to understand product decisions
3. Check `dashboards/` for visual validation of trends
4. Refer to `slides/hiresight_case_study.pdf` for the full business case

## Design Philosophy

- Predictions are only useful if they inform decisions
- Hiring and retention are treated as one system
- Models are evaluated for interpretability, not just accuracy
- Dashboards exist to validate insights, not decorate results


## What’s inside
- Predictive attrition model (Random Forest)
- Decision-focused notebooks (not just model training)
- Power BI & Tableau dashboards for insight validation
- Case study deck explaining the product architecture

## What this is NOT
- A production-ready HR tool
- A claim of perfect prediction accuracy

## What this IS
- A product-thinking exercise focused on decisions, trade-offs, and impact

## Future improvements
- Human-in-the-loop decision validation
- Bias audits on managerial feedback
- Simulation of intervention impact on attrition

Built as part of a business case study at IIITDM Jabalpur.
