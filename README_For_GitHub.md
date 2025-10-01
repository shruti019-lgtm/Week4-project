# COVID-19 Global Tracker — Project Package (Ready-to-Upload)

This repository contains a complete, **ready-to-use** project package for a COVID-19 Global Tracker.
All files are provided as **final outputs** (no code required from you). The visuals are included as high-quality images,
and a detailed PDF report explains every chart, interpretation, and how each visualization maps to Power BI and Tableau.

## Included files
- `COVID19_Project_With_Charts.pdf` — Polished visual report (illustrative charts embedded).
- `COVID19_Global_Tracker_Full_Project.pdf` — Full project documentation (ETL, M-code, DAX, Tableau calc fields) with explanations.
- `COVID19_Global_Tracker_Project.pdf` — Additional documentation file.
- `visuals/` — PNG images for each chart:
  - `global_daily_new.png`
  - `top10_countries.png`
  - `small_multiples.png`
  - `india_drilldown.png`
  - `india_forecast.png`

## Notes
- The charts in these PDFs are **illustrative** and created to show the exact visuals you will see when using live data.
- If you want the charts to use **real live data**, upload the raw CSV files from Johns Hopkins CSSE and OWID in this chat (or provide permission to fetch them), and I will regenerate the visuals and replace the images with real-data charts.

## How to upload to GitHub
1. Create a new repository on GitHub (https://github.com/new).
2. Name the repo (e.g., `covid19-global-tracker`).
3. On your computer, clone the repo or upload files directly using the GitHub web UI:
   - Using web UI: click "Add file" → "Upload files" and drag the files from this package.
   - Using git:
     ```bash
     git clone https://github.com/YOUR_USERNAME/covid19-global-tracker.git
     cd covid19-global-tracker
     # copy the files into this folder, then:
     git add .
     git commit -m "Add project package (PDFs + visuals)"
     git push origin main
     ```
4. After upload, your files will be available at `https://github.com/YOUR_USERNAME/covid19-global-tracker`.

## If you want real-data charts
Provide any of these CSVs in this chat (upload):
- `time_series_covid19_confirmed_global.csv`
- `time_series_covid19_deaths_global.csv`
- `time_series_covid19_recovered_global.csv` (optional)
- `vaccinations.csv` or `owid-covid-data.csv` (optional)

I will immediately regenerate the PDF with real-data visuals and provide an updated ZIP.

---

Thank you — Shruti. If you prefer the README in Hindi, tell me and I'll add a Hindi version.