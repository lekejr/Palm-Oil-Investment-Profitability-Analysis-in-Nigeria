
Project Title: Palm Oil Profitability Analysis (Nigeria)

OVERVIEW:
This project evaluates the profitability potential of palm oil plantation investments across major producing states in Nigeria. 
The objective is to estimate profit per hectare, break-even plantation size for ₦1 billion annual profit, ROI, and payback period. 
It integrates publicly available data, cost benchmarks from Okomu and Presco PLC, and proxy assumptions where data gaps exist.

FILES INCLUDED IN THIS FOLDER:

1. Palm_Oil_Raw_Datasets.xlsx
   - Contains all raw data collected from FAOSTAT, Okomu Oil PLC, Presco PLC, NIFOR, NIMET, PropertyPro, Jiji, USDA PSD, and PIND Foundation.
   - Each dataset is organized into its own sheet with the same name as the source.
   - Includes proxy notes where data was unavailable or estimated (e.g., Edo yield used as proxy for Ondo).

2. FINAL_PALM_OIL_MODEL.xlsx
   - Cleaned and merged dataset with all computed profitability metrics.
   - Sheets include: State_Profit_Model, Yield_Benchmarks, Cost_Table, and Price_Data.
   - Key outputs: Profit_per_ha, Hectares_for_1B, ROI, and Payback_Years.

3. analysis_notebook.ipynb
   - Full Python analysis notebook.
   - Contains all data loading, cleaning, calculations.

4. Reoprt Palm Oil Investment Profitability Analysis in NigeriaPDF
   - 8 page investor-focused analytical report.
   - Covers objectives, methodology, data sources, results, and recommendations.
   - Includes dashboard snapshot and link.

5. Executive_Summary_Palm pdf
   - One-page investor summary of findings, key insights, and recommended top states.

6. sources_list.xlsx
   - Comprehensive list of all data sources with URLs, access dates, and usage notes.

7. Dashboard_Link.txt
   - Contains the Power BI dashboard link for interactive exploration.
   
8. README.txt
   - This documentation file describing folder contents and structure.

ASSUMPTIONS AND PROXIES:
- CPO Extraction Rate: 22% (based on Okomu & Presco PLC reports)
- Base Price (2025): ₦2,500,000 per MT (USDA PSD & local market average)
- Base Operating Cost: ₦3,647,220 per hectare (derived from Cost_Table sheet)
- Ondo yield proxied from Edo due to similar rainfall pattern (NIMET data)
- ROI and Payback calculated per hectare before financing or tax considerations.

NOTES:
- All monetary values are in Nigerian Naira (₦).
- All area measurements are in hectares (ha).
- All raw data and proxies are fully documented in the sources_list.xlsx file.
- The interactive dashboard link is accessible to anyone with the link.


Prepared by:
Leke John Oluwagbemiga
Data Analyst | HNG13 Internship (Stage 4)
