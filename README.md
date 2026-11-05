# ✈️ Financial Health Assessment: Wizz Air Holdings Plc

**Submitted by:** Bibinandh Ananthakrishnan (Reg No: 202388718)

## 📌 Executive Summary
This project evaluates the financial stability and operational efficiency of **Wizz Air Holdings Plc**, a FTSE-listed "Super Affordable Airline" based in Hungary. Using the 2022 audited financial statements, the analysis focuses on the airline's ability to meet short-term obligations and manage its working capital amidst a competitive aviation landscape.

The assessment reveals a company with **strong liquidity** (Current Ratio: 1.14) but an aggressive creditor strategy, taking ~95 days to pay suppliers.

---

## 📊 Key Ratio Analysis

### 1. Liquidity Ratios (Solvency)
These metrics assess Wizz Air's ability to cover its short-term debts.
* **Current Ratio:** **1.14**
  *Insight:* With €1.57B in Current Assets vs €1.37B in Liabilities, Wizz Air is in a healthy position to cover immediate debts.
* **Quick Ratio (Acid Test):** **1.09**
    *Insight:* Even after removing Inventory (fuel/spare parts) from the equation, the company remains liquid, with $1.09 of liquid assets for every $1 of debt.

### 2. Efficiency Ratios (Activity)
These metrics measure how effectively the airline manages its cash and inventory.
* **Stock Turnover:** **12.2 Days**
    *Insight:* Extremely efficient inventory management. The airline turns over its stock (fuel/supplies) roughly every 12 days, preventing capital from being tied up.
* **Debtor Payment Period (DSO):** **41.1 Days**
    *Insight:* It takes ~41 days to collect revenue from partners/agencies.
* **Creditor Payment Period (CPP):** **95.5 Days**
   *Insight:* Wizz Air delays payments to suppliers for over 3 months. While this preserves cash flow, it risks straining supplier relationships.

---
## 🚀 Strategic Recommendations

Based on the ratio analysis, the following financial strategies are proposed:

1.  **Optimize Collections:** The **41-day** collection period (DSO) is relatively high for an airline. Implementing automated invoicing could shorten this cycle to improve cash inflows.
2.  **Supplier Relationship Management:** While a **95-day** payment period (CPP) boosts cash on hand, it is unsustainable long-term. Exploring early-payment discounts with fuel suppliers could reduce operating costs.
3.  **Inventory Control:** Maintain the current **12-day** stock turnover rate to prevent excess capital from being locked in unused spare parts or fuel hedges.
 ------

## 🛠 Methodology & Technical Logic

### A. Financial Data Extraction
* **Source:** Consolidated Statement of Financial Position (2022) & Comprehensive Income Statement.
* **Key Inputs:**
    * Current Assets: €1,572.5m
    * Current Liabilities: €1,373.7m
    * Inventory: €70.9m 
    * Cost of Sales (Operating Expenses): €2,128.7m 

### B. Analytical Formulas (Excel/Python Logic)
To automate this analysis, the following logic was applied to the financial dataset:

**1. Liquidity Assessment**
```excel
= (Current_Assets - Inventory) / Current_Liabilities
// Result: 1.093 (Quick Ratio) indicates strong short-term solvency

= (Trade_Payables / Total_Operating_Expenses) * 365
// Result: 95.49 Days. Indicates aggressive cash retention strategy.

