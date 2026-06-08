# Bike Buyers Analysis

An end-to-end data analytics project using Microsoft Excel to analyze consumer demographic profiles. This repository serves as a live, evolving log of my progress as I transform raw transactional data into structured business insights.

## 📁 Repository Files
* `Raw Data.xlsx`: The original, unformatted dataset containing abbreviations and duplicate records.
* `Cleaned Data.xlsx`: The finalized, deduplicated, and formatted dataset ready for analysis.

---

## 🛠️ Phase 1: Data Cleaning & Quality Assurance
Before moving into analytical modeling, I executed a strict data cleaning workflow to ensure data integrity:

1. **Table Structuring & Alignment:** Standardized the visual layout and text alignment across the entire dataset for readability.
2. **Deduplication:** Identified and removed duplicate rows to eliminate redundant customer records.
3. **Data Auditing via AutoFilter (`Ctrl + Shift + L`):** Utilized Excel's filter tools to review all unique categorical values, checking for anomalies, missing entries, or formatting discrepancies.
4. **Data Standardization (Text Expansion):**
   * Converted single-letter marital abbreviations (`M` / `S`) to fully qualified terms (`Married` / `Single`).
   * Expanded gender tags (`M` / `F`) into professional categories (`Male` / `Female`).

---

## 📈 Phase 2: Data Transformation & Feature Engineering
To prepare the dataset for deeper Pivot Table analysis and visualization, I completed:
* **Dynamic Age Segmentation:** Implemented a nested `IF` logical formula to group individual customer ages into business-focused demographic buckets (`Young Adult`, `Middle age adult`, etc.).

## 🛠️ Tech Stack
* **Tool:** Microsoft Excel (AutoFilter Auditing, Logical Formulas, Text Standardization, Data Deduplication, Pivot Charts)

---

## 📊 Phase 3: Data Visualizations & Key Insights
To uncover purchasing trends, I built targeted Pivot Charts to segment our buyers. 

### 🎯 Insight 1: Age Demographics vs. Bike Ownership
By implementing dynamic age segmentation, the data reveals that the primary customer base is concentrated heavily in core working-age demographics:
* **Middle-aged Adults** represent the highest conversion group at **52%**.
* **Young Adults** follow closely behind at **44%**.
* **Senior Citizens** make up the smallest consumer segment at just **4%**.

![Age Group Demographic Chart](image/age_demographics_chart.png)

*Business Recommendation: Marketing campaigns should heavily target young and middle-aged working professionals.*

### 🎯 Insight 2: Household Size & Children Demographics
Segmenting bike buyers by the number of children in their households reveals a strong concentration among smaller family structures:
* **30%** of buyers have **0 children**.
* **40%** of buyers have a small family unit with **1 to 2 children** (split equally at 20% each).
* Large families represent a clear minority, with households of 5 children contributing just **4%** of total purchases.

![Number of Children Demographic Chart](image/children_demographics_chart.png)

*Business Recommendation: Company should focus more on families with 2 or less than 2 children*
