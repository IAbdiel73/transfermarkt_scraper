# Scraper Transfermarket

Web scraper for player/club data from Transfermarkt, with data analysis and visualizations.

## Setup

This project uses [uv](https://docs.astral.sh/uv/) for dependency management.

```bash
uv sync
```

## Usage

Open [01_scraper.ipynb](01_scraper.ipynb) and select the project's `.venv` as the Jupyter kernel:

```bash
uv run jupyter notebook
```

## Requirements

- Python >= 3.10
- Google Chrome (used by Selenium via `webdriver-manager`)
