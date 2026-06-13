# Togather Data Take-Home Task

Analysis of event requests and supplier quotes to surface growth opportunities and commercial
recommendations for 2025.

## Structure

```
├── data/
│   ├── raw/          # original Excel files (not committed)
│   └── processed/    # cleaned outputs written by notebooks
├── notebooks/
│   └── 01_eda.ipynb  # exploratory data analysis (requests, quotes, combined)
├── outputs/
│   ├── figures/      # exported charts for the presentation
│   └── presentation/ # final slide deck
└── requirements.txt
```

## Setup

```bash
pip install -r requirements.txt
```

Place the raw data files in `data/raw/`:
- `food_requests.xlsx`
- `food_quotes.xlsx`

## Running the analysis

```bash
jupyter notebook notebooks/01_eda.ipynb
```

Run all cells top-to-bottom. Figures are saved to `outputs/figures/` automatically.
