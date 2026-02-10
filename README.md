# Data Platform Agent Skills

A curated skill library for coding agents focused on data engineering, data science, and interactive data applications.

## Install with `npx skills`

List all available skills:

```bash
npx skills add legout/data-platform-agent-skills --list
```

Install specific skills:

```bash
npx skills add legout/data-platform-agent-skills \
  --skill data-engineering-core \
  --skill data-science-eda \
  --skill data-science-notebooks
```

Install all skills:

```bash
npx skills add legout/data-platform-agent-skills --skill '*'
```

## Repository layout

- `skills/` — installable skill directories (for `npx skills` discovery)
- `data-engineering/` — data engineering source content
- `data-science/` — data science, notebooks, and interactive apps
- `flowerpower-skill/` — FlowerPower skill package
- `tools/` — utility scripts

## Skill categories

### Data Engineering (23 skills)
- Core: Polars, DuckDB, PyArrow, PostgreSQL
- Storage: Lakehouse (Delta, Iceberg, Hudi), cloud access, auth
- Orchestration: Prefect, Dagster, dbt
- Quality, Observability, Streaming

### Data Science (5 skills)
- **EDA** — Exploratory Data Analysis
- **Feature Engineering** — ML feature preparation
- **Model Evaluation** — Validation and tuning
- **Notebooks** — Jupyter, marimo
- **Interactive Apps** — Streamlit, Panel, Gradio

### Pipeline Framework (1 skill)
- FlowerPower — Hamilton DAG-based pipelines

## Notes

This repository intentionally excludes internal development planning documents.
