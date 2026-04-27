# ACC102 Mini Assignment: U.S. Financial Industry ROE Analysis (2020–2025)

---

## 1. Problem & Users
This project addresses the need to understand long-term profitability and leverage trends in the U.S. financial sector, using publicly available financial data. The primary audience includes students and researchers seeking to explore the relationship between corporate financial structure and performance over a full business cycle.

---

## 2. Data
- **Source**: WRDS Compustat North America Fundamentals Database
- **Date Range**: January 2020 to December 2025
- **Key Fields**: 
  - `datadate`: Financial statement date
  - `conm`: Company name
  - `ni`: Net income
  - `ceq`: Common equity
  - `lt`: Total liabilities
  - `gvkey`: Company identifier

---

## 3. Methodology (Python Steps)
1. Load and filter the dataset to retain only records from January 2020 to December 2025.
2. Calculate core financial ratios: Return on Equity (ROE) and debt-to-equity ratio.
3. Clean the data by removing missing values and extreme outliers.
4. Conduct descriptive analysis, including annual average ROE trends and top-performing company rankings.
5. Generate visualizations: an ROE trend chart and a scatter plot of leverage vs. ROE.
6. Save all outputs to the standardized `figures/` folder.

---

## 4. Core Findings
1. The average ROE of the U.S. financial industry shows a steady recovery trend from 2022 onward, reflecting post-pandemic economic stabilization.
2. Companies with moderate debt-to-equity ratios generally exhibit more stable and sustainable ROE performance.
3. There is significant variation in profitability among financial institutions, with the top 10 firms maintaining consistently higher ROE throughout the period.
4. Extreme outliers in ROE, both positive and negative, are mostly associated with temporary shocks or accounting adjustments rather than long-term operational performance.
5. The full 2020–2025 cycle reveals that industry profitability is closely tied to macroeconomic conditions and interest rate environments.

---

## 5. How to Run
1. Clone or download the full repository to your local machine.
2. Ensure Python 3 is installed, along with the required libraries: `pandas` and `matplotlib`.
3. Open `ACC102_Analysis.ipynb` in Jupyter Notebook or Jupyter Lab.
4. Run the code cells sequentially. All file paths are pre-configured, so no modification is needed.
5. The generated charts will be automatically saved to the `figures/` folder.

---

## 6. Product Links / Demo
- **GitHub Repository**: https://github.com/Yangyanfu888/ACC102-Track2-Financial-Analysis
- **Video Demonstration**: 1–3 minute screencast showing code execution, results, and visualization (AI-narrated).

---

## 7. Limitations & Future Work
- **Limitations**: The analysis is based on annual financial statements and does not incorporate high-frequency market data, which may capture shorter-term volatility. The study focuses only on the financial sector, limiting cross-industry comparisons.
- **Future Plans**: Extend the analysis to include quarterly data for more granular trend tracking, incorporate additional macroeconomic variables such as interest rates, and compare performance across different financial sub-industries (e.g., banks vs. insurance companies).
