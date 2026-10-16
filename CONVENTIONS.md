# Conventions

## Folder naming
Projects live in `projects/` and are named `XX-name-of-project` so folders sort in order and have no spaces in URLs.

## Domain labels
Each project gets exactly one of these labels:
- Classification
- Regression
- Clustering
- Time Series
- NLP
- Computer Vision
- Recommendation
- Data Analytics
- Dashboard

## Status
- **Planned**: The project identifies with a problem statement, a dataset, and a chosen success measure.
- **In progress**: The project contains committed work, but is missing elements that would be considered finished.
- **Done**: The project has to meet the criteria:
  - The README states the problem, data source, approach, results with my metric, and how to run it.
  - It reproduces from a fresh clone with `requirements.txt`.
  - It includes key visuals and a short conclusion.
  - No large datasets or secrets are committed.

## End-to-End
A project is End-to-End (✔) when it covers the whole path from raw data to something a person can actually use, not just a notebook with a model score (e.g., a script that takes new data and returns predictions).