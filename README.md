# hw5_geospatial

This is a toy repository created for **HWRS 564 Homework 5** to practice setting up a GitHub repository, working with version control, and managing a Python project environment.

## What this repo is

This repo explores basic **geospatial analysis** in Python using watershed and streamgage data for the American Southwest. It is used as a sandbox to demonstrate:

- Creating and initializing a GitHub repository
- Cloning a repo to a local machine
- Adding files and committing changes
- Pushing updates back to GitHub

It is **not** intended as a production project — it is a learning exercise in Git and Python workflows.

## Contents

- `homework5.ipynb` — Jupyter notebook with geospatial analysis (the required "additional file" for HW5)
- `HW5_Building_Blocks_5_withBlanks.ipynb` — Course building blocks notebook
- `Data/` — Shapefiles and spatial data used in the analysis
- `pyproject.toml` / `uv.lock` — Python environment configuration

## How to run

This project uses [uv](https://github.com/astral-sh/uv) for environment management.

```bash
uv sync
uv run jupyter notebook
```
