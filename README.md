#  Palm Oil Investment Profitability Analysis – Nigeria

A data-driven financial and agronomic evaluation of palm oil investment potential across major producing states in Nigeria.  
This report provides **profitability modelling**, **state-by-state comparison**, **ROI & payback analysis**, and **scenario simulations** to guide investors targeting ₦1 billion annual profit.

---

##  Table of Contents
1. [Introduction](#1-introduction)  
2. [Objective and Scope](#2-objective-and-scope)  
3. [Data Sources](#3-data-sources)  
4. [Methodology](#4-methodology)  
   - [4.1 Data Processing](#41-data-processing)  
   - [4.2 Modeling Formulas](#42-modeling-formulas)  
   - [4.3 Scenario Design](#43-scenario-design)  
5. [Results and Dashboard](#5-results-and-dashboard)  
   - [5.1 Key Insights](#51-key-insights)  
6. [Sensitivity Analysis](#6-sensitivity-analysis)  
7. [Investment & Financial Implications](#7-investment--financial-implications)  
8. [Recommendations](#8-recommendations)  
9. [Limitations](#9-limitations)  
10. [Conclusion](#10-conclusion)  
11. [Appendices](#11-appendices)  
12. [References](#12-references)  

---

## 1. Introduction
Nigeria’s palm oil sector is re-emerging as one of the most promising agribusiness investments.  
Domestic supply remains below national demand while global consumption continues to grow (FAO, 2024).  
This report builds a **profitability model** comparing Nigerian states across yield, cost, and revenue potential.

---

## 2. Objective and Scope

**Core Investor Question:**  
 *At what scale and in which states can a palm oil plantation generate ₦1 billion annual profit?*

**Scope includes:**  
- Estimating profit per hectare per state  
- Determining minimum hectares for ₦1B profit  
- ROI and payback modelling  
- 3-scenario simulations (Conservative, Base, Optimistic)  
- State recommendations & risk management steps  

---

## 3. Data Sources

| Source | Link | Use |
|-------|------|-----|
| Okomu Oil PLC Annual Report | https://okomugroup.com/ | Yield & cost benchmarks |
| Presco PLC Annual Report | https://presco-plc.com/ | Yield & capex validation |
| FAOSTAT | https://www.fao.org/faostat/en/#data/QCL | National production checks |
| NIFOR | https://nifor.gov.ng/ | Pricing & agronomy practices |
| FAO OpenKnowledge | https://openknowledge.fao.org/ | Cost & margin structure |
| NIMET | https://nimet.gov.ng/ | Rainfall & climate data |
| PropertyPro | https://www.propertypro.ng/ | Land price proxies |
| Jiji | https://jiji.ng/ | Equipment & machinery costs |
| PIND Foundation | https://pindfoundation.org/ | Regional clusters |
| USDA PSD | https://apps.fas.usda.gov/psdonline/ | International price context |

Datasets processed:  
- **State_Profit_Model**  
- **Yield_Benchmarks**  
- **Cost_Table**  
- **Price_Data**  

---

## 4. Methodology

### 4.1 Data Processing
- Cleaned in Python (duplicates removed, units standardized to ₦ and ha)  
- Numeric parsing for cost extraction  
- Missing yields proxied using similar agro-climatic states (e.g., Edo → Ondo)

---

### 4.2 Modeling Formulas
CPO_Yield_per_ha = FFB_Yield_tons_per_ha × 0.22
Profit_per_ha = (CPO_Yield_per_ha × Price_per_MT) – Cost_per_ha
Hectares_for_1B = 1,000,000,000 ÷ Profit_per_ha
ROI = Profit_per_ha ÷ Cost_per_ha
Payback_Years = Cost_per_ha ÷ Profit_per_ha


### 4.3 Scenario Design
| Scenario | Yield | Price | Cost |
|----------|--------|--------|-------|
| Conservative | –15% | –15% | +5% |
| Base | Actual | ₦2.5M/MT | None |
| Optimistic | +15% | +15% | –5% |

---

## 5. Results and Dashboard

### **State Profitability Summary**

| State | Profit/ha (₦) | Hectares for ₦1B | ROI | Payback (yrs) | Suitable Land (ha) |
|-------|---------------|-------------------|------|----------------|---------------------|
| Edo | 4,602,780 | 217 | 1.26 | 0.79 | 200,000 |
| Cross River | 4,052,780 | 247 | 1.11 | 0.90 | 180,000 |
| Akwa Ibom | 3,502,780 | 285 | 0.96 | 1.04 | 110,000 |
| Delta | 2,952,780 | 339 | 0.81 | 1.23 | 120,000 |
| Rivers | 3,022,780 | 331 | 0.83 | 1.21 | 150,000 |
| Bayelsa | 2,522,780 | 396 | 0.69 | 1.45 | 90,000 |
| Ondo | 1,852,780 | 540 | 0.51 | 1.97 | 80,000 |

### Dashboard (Interactive)
<img width="1490" height="1632" alt="merged-image-1763634387082" src="https://github.com/user-attachments/assets/e6adfbdc-41fb-4951-aa91-d20c5755b365" />

**State-wise Palm Oil Profitability Model** includes:
- Profit per ha  
- Hectares for ₦1B profit  
- ROI vs Payback comparison  

---

## 5.1 Key Insights
- **Edo leads** with highest profit/ha and fastest payback (0.79 yrs).  
- Cross River & Akwa Ibom offer strong yields and mill access.  
- Ondo underperforms due to high costs & scattered mills.  
- Average break-even scale: **~326 hectares** for ₦1B annual profit.

---

## 6. Sensitivity Analysis

| Scenario | Avg Profit/ha (₦) | Hectares for ₦1B | ROI | Payback (yrs) |
|----------|--------------------|-------------------|------|----------------|
| Conservative | 2,883,000 | 425 | 0.79 | 1.27 |
| Base | 3,392,780 | 326 | 0.93 | 1.07 |
| Optimistic | 3,908,000 | 274 | 1.07 | 0.92 |

Yield fluctuations have the **largest impact** on profit.

---

## 7. Investment & Financial Implications

| State | Investment (₦M) | ROI | Payback (yrs) |
|--------|------------------|------|----------------|
| Edo | 792 | 1.26 | 0.79 |
| Cross River | 900 | 1.11 | 0.90 |
| Akwa Ibom | 1,040 | 0.96 | 1.04 |

- **Pilot Capital (200 ha):** ₦730M–₦750M  
- **Break-even:** < 2 years after maturity  
- **Scale Path:** Use blended finance for expansion  

---

## 8. Recommendations

### 1. Pilot Phase (200–500 ha, Edo)
- Leverage existing mill clusters to reduce logistics costs.

### 2. Operational Strategy
- Offtake agreements with processors  
- Apply NIFOR best practices to maintain 14+ tons FFB/ha  

### 3. Scale-Up Plan
- Expand in 1,000 ha increments after 2 harvest cycles  
- Reinvest early profits into mini-processing units  

### 4. Risk Management
- Secure land titles  
- Hedge price volatility  
- Ensure environmental compliance for ESG funding  

---

## 9. Limitations
- Uniform cost & yield assumptions per state  
- No 5-year cashflow (future version should add OPEX/CAPEX depreciation)  
- Land price proxies from online platforms  
- Mill extraction rates estimated  

---

## 10. Conclusion
Edo, Cross River, and Akwa Ibom are the **most profitable** and scalable states for palm oil investment.  
A **200–500 ha pilot in Edo** provides the strongest early returns and fastest path toward achieving **₦1B annual net profit**.

---

## 11. Appendices

### **Appendix A: Interactive Dashboard**
[*Link to Dashboard*](https://app.powerbi.com/view?r=eyJrIjoiNmY3ODk3MmItZTBhYS00MWI5LWI3MzItNjdlYWViOGM3NTQ0IiwidCI6IjRkYWRkNTgyLTM1YTQtNGEzMy1hNDM4LTI1OTYwMDM3MjZkMCJ9)

### **Appendix B: Model Output Summary**
| State | Profit/ha (₦) | Hectares for ₦1B | ROI | Payback |
|-------|---------------|-------------------|------|----------|
| Edo | 4,602,780 | 217 | 1.26 | 0.79 |
| Cross River | 4,052,780 | 247 | 1.11 | 0.90 |
| Akwa Ibom | 3,502,780 | 285 | 0.96 | 1.04 |

### **Appendix C: Python/Notebook Code**
<img width="927" height="738" alt="Screenshot (749)" src="https://github.com/user-attachments/assets/f90b86bb-04f8-4103-9c8a-fde17a3ac3bc" />
<img width="979" height="671" alt="Screenshot (750)" src="https://github.com/user-attachments/assets/f8808c77-d4c6-4253-92dd-7ac4ce34940f" />


---

## 12. References
- FAO (2024). FAO Statistical Database.  
- FAO OpenKnowledge (2024). Palm Oil Cost & Margin Structures.  
- NIFOR (2024). Agronomy Best Practices.  
- Okomu Oil PLC (2024). Annual Report.  
- Presco PLC (2024). Annual Report.  
- PropertyPro (2024). Land Price Proxies.  
- Jiji (2024). Machinery Costs.  
- PIND Foundation (2024). Regional Clusters.  
- USDA PSD (2024). International Palm Oil Prices.  
- NIMET (2024). Rainfall & Temperature Data.  


