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

## 📈 Phase 2: Data Transformation & Feature Engineering (In Progress)
To prepare the dataset for deeper Pivot Table analysis and visualization, I am currently working on:
* **Dynamic Age Segmentation:** Implementing a nested `IF` logical formula to group individual customer ages into business-focused demographic buckets (`Young Adult`, `Middle age adult`, etc.).

## 🛠️ Tech Stack
* **Tool:** Microsoft Excel (AutoFilter Auditing, Logical Formulas, Text Standardization, Data Deduplication)
