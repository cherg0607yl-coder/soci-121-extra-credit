# How the U.S. Population Changed by Age and Sex, 2020–2025

SOCI 121 extra credit. This project looks at how the U.S. age structure changed between July 1, 2020 and July 1, 2025.

## Files

| File | What it is |
|---|---|
| `nc-est2025-agesex.xlsx` | Census Bureau data: U.S. population by 5-year age group and sex, 2020–2025 |
| `visualization.ipynb` | Data cleanup, a short exploratory analysis, two charts, and findings |

## Visualizations

1. **Population pyramids (2020 vs 2025):** side-by-side pyramids on the same scale. The 2025 pyramid has a dashed outline of the 2020 shape for comparison.
2. **Diverging bar chart:** the percent change in each age group from 2020 to 2025. Blue bars show growth and orange bars show decline.

## Key finding

**America is getting older.** The population grew 3.1%, but people aged 65+ grew about 15%. They went from 16.9% to 18.9% of the population, and ages 75–79 grew the most (+29.6%). The number of children under 18 fell about 2%, and the median age rose from 38.7 to 39.4.

## How to run

Requires Python 3 with `pandas`, `matplotlib`, `openpyxl` and Jupyter.

```bash
pip install pandas matplotlib openpyxl jupyter
```

```bash
jupyter notebook visualization.ipynb
```

Keep the Excel file in the same folder as the notebook.

## Data source

U.S. Census Bureau, Population Division. (2026). *Annual estimates of the resident population for selected age groups by sex for the United States: April 1, 2020 to July 1, 2025* (NC-EST2025-AGESEX) [Data set]. U.S. Department of Commerce. https://www.census.gov/data/tables/time-series/demo/popest/2020s-national-detail.html
