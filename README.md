# 365 Data Science Challenge

> A completed challenge submission exploring student engagement on a data-science learning platform.

![Status: Completed](https://img.shields.io/badge/status-completed-2ea44f)

## Overview

This repository contains an analysis prepared for the 365 Data Science Challenge. Its documented scope covers cleaning the supplied learning-platform data, exploring and visualising engagement, engineering features and building predictive models in a single Jupyter notebook.

## Project status

| Item | Details |
|---|---|
| Status | ✅ Completed |
| Repository visibility | Public |
| Last verified | Not recently executed; README checked against the current `main` branch |

## Key features

- Keeps the challenge data in a dedicated `data_files/` directory.
- Presents the analytical workflow in one Jupyter notebook.
- Covers data cleaning, exploration and visualisation.
- Documents feature engineering and machine-learning work as part of the challenge scope.

## Results

The current repository README does not state the final business insight, target variable, selected model or evaluation score.

<!-- REVIEW: Add the final model, validation method, metric and one decision-relevant engagement insight from `notebook.ipynb`. -->

## Tech stack

| Technology | Purpose |
|---|---|
| Python | Analysis and modelling language documented by the repository |
| Jupyter Notebook | Execution format for `notebook.ipynb` |

<!-- REVIEW: Add only the libraries actually imported by the current notebook after a reproducibility pass. -->

## How it works

1. Source files are read from `data_files/`.
2. `notebook.ipynb` cleans and explores the supplied data.
3. Engagement patterns are visualised.
4. Features are prepared for predictive modelling.
5. Model results and conclusions are produced inside the notebook.

## Repository structure

Only directly verified current paths are listed:

```text
.
├── data_files/
├── notebook.ipynb
└── README.md
```

## Getting started

The existing repository README instructs users to install `requirements.txt`, but that file is not present on the current `main` branch. Until a dependency manifest is added, setup cannot be reproduced from the repository alone.

```bash
git clone https://github.com/DominikDawiec/365-Data-Science-Challenge.git
cd 365-Data-Science-Challenge

python -m venv .venv
source .venv/bin/activate  # Windows: .venv\Scripts\activate
python -m pip install jupyter
jupyter notebook notebook.ipynb
```

Install the notebook's verified dependencies before running all cells; they should be captured in a new manifest rather than guessed here.

## Usage

Open `notebook.ipynb` and run the cells in their documented order with `data_files/` kept at the repository root. Review the challenge's data terms before copying or redistributing any input files.

## Data and methodology

The current README identifies the subject as student engagement on a data-science course platform and lists cleaning, exploration, visualisation, feature engineering and machine learning as the methods used. Individual source filenames, the data-collection period, target definition and validation protocol are not documented in the repository README and are therefore not inferred here.

## Contact

Created by [Dominik Dawiec](https://www.linkedin.com/in/dominikdawiec/).
