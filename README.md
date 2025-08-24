
# NYC Restaurants — MongoDB + Jupyter (Ready-to-Run)

## Quick start
```bash
docker compose up -d --pull always --build
# then open Jupyter: http://localhost:8888/?token=rayen
# open: notebooks/mongo_queries.ipynb
```
Replace `data/restaurants.sample.json` with your full dataset if needed.

## Services
- MongoDB 7 on localhost:27017
- Jupyter (scipy-notebook) on localhost:8888 (token: rayen)
