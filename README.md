# Supply Chain Analysis 

## A. Introduction

This project focuses on analyzing a **supply chain dataset** to extract actionable insights that improve **operational performance, cost efficiency, and customer satisfaction**.  
Using **Python** and data science techniques, the analysis covers various aspects such as **demand forecasting, supplier performance, logistics optimization, transportation costs, defect rates, and profitability evaluation**.  

The overall goal is to:  
- Identify **patterns and risks** in the supply chain  
- Provide **predictive and prescriptive analytics** for planning  
- Optimize **inventory, transportation, and supplier relationships**  
- Enable stakeholders to make **data-driven decisions**  

---

## B. Overall Analysis Completed

The following analysis was performed in **Python** using various libraries/packages wherever required:

- **EDA (Exploratory Data Analysis)**
- **Demand Forecasting**
- **Location Rankings** (based on product selling)
- **Average Sales** of each product type per location
- **Defect Rate Analysis** (by product type)
- **Transportation Cost Evaluation**
- **Lead Times** of each product type per supplier
- **Product & Customer Analysis**
- **Predictive Analytics for Future Planning**
- **Supply Chain Performance Evaluation**
- **Supplier Assessment** (Lead Times, Defect Rates, Inspection Outcomes)
- **Logistics Optimization Study**
- **Predictive Analytics**: Demand Forecasting & Inventory Optimization
- **Prescriptive Analytics**: Supply Chain & Shipping Cost Optimization, Production Scheduling & Route Optimization
- **Defect Prediction & Supplier Performance Evaluation**

---

## C. Supply Chain Dataset Overview

### Dataset Composition
- **100 observations**, **24 features** covering multiple supply chain aspects
- **Product Categories**: Skincare, Haircare, Cosmetics
- **SKU Price Range**: 1.69 – 99.17
- **Null Values**: None
- **Gender Data**: Missing in 31% of observations

---

### Product Demand & Sales Insights
- **High-Demand Products**
  - Kolkata: Major market with highest sales
  - Bangalore: Lowest sales among major cities
  - Delhi: Leads in average sales across all categories
  - Delhi & Chennai: High defect rates **do not reduce sales** significantly
- **Defect Rates**
  - Haircare shows **higher defect rates** than Skincare and Cosmetics
- **Revenue Generation**
  - Skincare = **highest revenue contributor** (premium, high-priced items dominate)

---

### Transportation & Shipping Insights
- **Cost Efficiency by Mode**
  - Sea = Most cost-efficient
  - Air = Fastest, most expensive
  - Rail = Balanced between cost & time
- **Time Efficiency**
  - Supplier 3 = Highest delays for Cosmetics
- **Lead Time vs Sales**
  - 1–2 days = Higher sales (fast cycles)
  - 5 days = Surprisingly highest sales (661.67 units)
  - 4 & 6 days = Lowest sales

---

### Defect Rates & Inspection Patterns
- **Regional Trends**: Delhi & Chennai → consistently high defect rates
- **Inspection Backlog**: Rail & Air shipments face most delays
- **By Transportation Mode**:
  - Rail & Air = Highest defect rates
  - Sea = Moderate defects (long exposure in transit)

---

### Supplier-Specific Observations
- **Performance**
  - Avg. Lead Times = 14–17 days
  - Merchant 1 = Longest manufacturing vs supply gap (5 days)
  - Merchant 4 = Lowest pass rate (0%)
  - Merchant 1 = Highest pass rate (50%)
- **Quality Inspection Rates**
  - Overall defect inspection rate = 2.7%
  - Merchant 1 = Lowest defect rate (1.75%)

---

### Correlation Analysis
- **Lead Time vs Stock Levels** → Weak positive correlation (0.0679)
- **Stock Levels vs Sales** → Negligible positive correlation (0.0222)
- **Sales vs Lead Times** → 1–2 day lead times boost sales; 5-day lead times unexpectedly highest

---

### Route & Logistics Insights
- **Defect Rates by Route**
  - Sea Route B & Rail Route C = Highest defect rates
- **Efficiency Scores**
  - Calculated as shipments ÷ average costs → higher = more cost-efficient
- **Mode-Specific**
  - Rail & Air = Higher failure rates

---

### Inventory & Demand Planning
- **Stock Levels vs Sales** → Weak link → need for better demand forecasting
- **Seasonal/Product Trends** → Likely drive demand more than stock levels

---

### Merchant-Specific Expense Analysis
- **Merchant 4**
  - Lower transportation cost for Cosmetics
  - Higher cost for Skincare
- **Profitability by Product**
  - Cosmetics = Most profitable (lower transport costs + steady demand)
  - Skincare = Higher costs eat into profit
- **Supplier Profit Margins**
  - Supplier 3 = Highest profitability

---

### Key Risk Areas
- High defect rates in **Delhi & Chennai**
- **Rail & Air inspection delays**
- Wide **supplier pass rate variability**
- Lead time inefficiencies (esp. Merchant 1)

---

## D. Recommendations

1. **Address High Defect Rates (Delhi & Chennai)**
   - Implement quality audits
   - Train logistics teams (esp. Haircare handling)
   - Optimize packaging

2. **Optimize Transportation Costs & Modes**
   - Use predictive analytics for **mode selection**
   - Prioritize **Sea/Rail** for non-perishables
   - Negotiate contracts for high-demand routes

3. **Streamline Inspection & Reduce Backlogs**
   - Invest in **automated inspection tools**
   - Create **regional hubs** for faster checks

4. **Reduce Lead Time Discrepancies**
   - Develop **vendor performance management system**
   - Improve collaboration between production & logistics

5. **Improve Inventory & Demand Forecasting**
   - Deploy **forecasting models** for seasonal/regional demand
   - Real-time stock monitoring to avoid over/under-stocking
   - Integrate **sales data + supply chain operations**

---

✅ This analysis provides a **360° view of supply chain performance**, covering **demand forecasting, transportation, supplier assessment, logistics optimization, and profitability analysis**.
