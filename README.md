# 📊 Task 1 – Customer Personality Analysis (Data Preparation)

## 📝 Objective  
The goal of this task was to prepare the **Customer Personality Analysis dataset** for further exploration and analysis by ensuring it is clean, consistent, and structured.  

---

## 🔧 Steps Performed  

1. **Data Cleaning**  
   - Identified missing values in the dataset.  
   - Handled missing entries in the **Income** column by replacing them with the median value.  
   - Checked for duplicate records and dataset integrity.  

2. **Format Adjustments**  
   - Converted the **Dt_Customer** column from text to proper `datetime` format for accurate time-based analysis.  
   - Standardized categorical columns (e.g., *Education*, *Marital_Status*) into **UPPERCASE** to maintain consistency.  

3. **Feature Engineering**  
   - Created **Age** column from `Year_Birth`.  
   - Calculated **Customer Tenure (Customer_For_Days)** from enrollment date.  
   - Derived **Children** column from `Kidhome + Teenhome`.  
   - Computed **Total_Spending** (sum of Wines, Fruits, Meat, Fish, Sweets, and Gold products).  
   - Computed **Total_Purchases** (sum of deals, web, catalog, and store purchases).  

4. **Reorganization of Dataset**  
   - Grouped columns into logical categories: Demographics, Customer Info, Spending, Purchases, Campaigns, and Other.  
   - Exported the cleaned dataset as `customer_personality_organized.csv` for future analysis.  

---

## 📌 Short Summary  
- The dataset now has **2,240 rows and 34 structured columns**.  
- Missing values were treated, dates standardized, and categorical fields normalized.  
- Additional features (Age, Children, Spending, Purchases, Tenure) were added to enrich analysis potential.  
- The dataset is ready for further **exploratory data analysis (EDA), segmentation, and visualization** tasks.  
