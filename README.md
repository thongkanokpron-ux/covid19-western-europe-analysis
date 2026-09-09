# COVID-19 Trends & Vaccination Analysis in Western Europe

This repository contains data processing, analysis, and visualization of COVID-19 infection trends and vaccination coverage across Western European nations.

---

## Project Structure

```text
covid19-western-europe-analysis/
├── data/
│   ├── raw/          # Raw datasets before processing
│   └── processed/    # Cleaned and standardized datasets
├── notebooks/        # Jupyter Notebooks used for EDA and analysis
├── images/           # Exported charts and visualization plots
└── README.md         # Overview and project documentation
```

---

## Datasets Overview
```text
The analysis leverages the following key datasets:
- Global COVID-19 Dataset: Tracks total confirmed cases, deaths, and recoveries by country.
- Testing Records: Contains testing statistics and positivity rates over time.
- Variants Found: Tracks identified SARS-CoV-2 variants across recorded intervals.
- Vaccinations Data: Provides total doses administered and breakdown by vaccine manufacturers.
```
---

## Tech Stack & Libraries
```text
- Language: Python 3.x
- Data Processing: pandas, numpy
- Data Visualization: matplotlib, seaborn
- Environment: Jupyter Notebook / Visual Studio Code
```
---

## Data Cleaning & Preprocessing Highlights
```text
- Standardized core schema across datasets (country, Cases, Deaths, Recovered).
- Filtered out non-country regional aggregates (e.g., European Union).
- Handled missing and inconsistent entries to maintain data integrity.
- Exported clean data directly into the data/processed/ directory.
```
---

## Author
```text
Name: Thongkanok Pornchai
GitHub: `@thongkanokpron-ux`
```
