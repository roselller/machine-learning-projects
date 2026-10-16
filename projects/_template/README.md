# <Project name>

**Domain:** <label from CONVENTIONS.md> · **Status:** <Planned / In progress / Done> · **End-to-End:** <✔ or blank>

## Problem
**Explain what question is being answered and why anyone should care:**

_Example:_
_This project investigates [specific question] using [relevant data]. The goal is to understand [what you want to learn], which matters because [practical or analytical significance]._

_Tip: Start with one answerable question. You can expand the scope later if the data supports it._

## Data
**The data should include:**
- Source: [Name of source and URL]
- Coverage: [Population and time period]
- Key variables: [Variables used in the analysis]
- Preparation: [Cleaning, filtering, and transformations]
- Limitations: [Known data quality or coverage constraints]

## Approach
**Describe how the question is answered:**
1. Load and validate the data.
2. Explore it: missing values, distributions, class balance.
3. Build a simple baseline model.
4. Try one or two stronger models and compare them.
5. Evaluate with the chosen metric and visualise the results.

## Results
**Summarize what the project actually found:**
- Key findings: The most important numerical or qualitative results.
- Interpretation: What those results mean in relation to your research question.
- Evidence: The metrics, tables, charts, or statistical tests supporting your conclusions.
- Caveats: What you cannot conclude from the available evidence.

## How to run
**Give enough information to reproduce the analysis:**

### Requirements
- Python `[version]`
- Dependencies listed in `requirements.txt`

### Setup
1. Clone the repository.
2. Install the dependencies.
3. Obtain the source data, following data/README.md

### Execute
```bash
pip install -r requirements.txt
```
Open notebook.ipynb, select the project's .venv kernel, and run all cells.

## Next steps
**List the most valuable improvements or unanswered questions.**

_Example:_
_- Investigate whether the observed patterns differ across relevant subgroups._
_- Test whether the findings hold under alternative assumptions._
_- Obtain additional data to address current limitations._