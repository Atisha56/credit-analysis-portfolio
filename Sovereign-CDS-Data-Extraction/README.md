# Sovereign CDS Data Extraction & Macro Dataset Construction

- **Date:** Jan 2025
- **Status:** Data extraction complete (assigned scope — analysis out of scope for this project)
- **Tools:** Python, Bloomberg Terminal, FRED API

## Overview
Extracted and cleaned daily CDS spreads for 19 sovereign nations via Bloomberg Terminal,
and cross-country short-term interest rate series via the FRED API, building structured
datasets to support sovereign credit risk research.

## What Was Done
- Extracted 20+ years of daily CDS spreads (2005–2026) for 19 sovereign nations: Austria,
  Belgium, Denmark, Finland, France, Germany, Greece, Ireland, Italy, Japan, Korea,
  Netherlands, Portugal, Spain, Sweden, UK, Australia, Mexico, and Norway
- Pulled and processed 3-month short-term interest rate series for 8 countries (US, Canada,
  UK, France, Germany, Italy, Japan, Spain) via the FRED API
- Cleaned and structured both datasets into a usable panel format

## Files
- `Country_Specific_CDS_Data.xlsx` — daily CDS spreads, 19 countries
- `Treasury_data_pull.ipynb` — FRED short-term interest rate extraction script

[← Back to Credit Analysis Portfolio](../)
