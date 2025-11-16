# Tokyo Travel Accommodation Insights

## One-liner
Interactive analysis to help travelers find the best-value neighbourhoods in Tokyo using accommodation prices, proximity to attractions, and transit access.

## Repo structure
- `data/` — raw / interim / clean data
- `notebooks/` — exploratory notebooks
- `sql/` — DDL and queries
- `scripts/etl/` — ETL scripts
- `dashboards/` — Tableau / PowerBI files
- `docs/` — data dictionary, sources, assumptions

## Getting started (Day 0)
1. Clone repo
2. Create conda env: `conda create -n tokyo_accom python=3.10 && conda activate tokyo_accom`
3. Install dependencies: see top of this README
4. Start DB (Day 1 will cover `docker compose up -d`)
