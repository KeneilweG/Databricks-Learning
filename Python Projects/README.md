# BrightLearn Practice

# 📊 Viewership Analysis – Exploratory Data Analysis (EDA)

## 🔍 Project Overview
This project performs exploratory data analysis (EDA) on a viewership dataset containing over 100,000 records. The goal is to uncover platform-specific engagement patterns, content preferences, and behavioral trends across different play event types.

## 📁 Dataset Summary
- **Rows:** 108,661  
- **Columns:** 8  
- **Date Range:** 1970-01-01 (placeholder date)  
- **Unique Customers:** 929  
- **Key Fields:**  
  - `CustomerID`: Unique viewer identifier  
  - `TotalTimeWatched`: Duration spent per event (in seconds)  
  - `Platform`: Device used (Android, iOS, Web, Leanback)  
  - `PlayEventType`: Type of viewing (LiveTV, Catch Up, Downloads, Other)  
  - `VideoTitle`: Title of the content  
  - `date`, `Month`, `Day`: Temporal dimensions

## 🧪 EDA Objectives
- Quantify unique customer engagement by:
  - Platform  
  - Video title  
  - Play event type  
  - Month and day of week  
- Identify top-performing content and platforms  
- Detect potential data quality issues (e.g., placeholder dates, duplicates)

## 📊 Key Insights
- **Platform Engagement:**  
  - Leanback leads with 580 unique customers  
  - Android follows with 440  
- **Play Event Distribution:**  
  - LiveTV dominates with 900 unique viewers  
  - Catch Up and Downloads show niche engagement
- **Content Diversity:**  
  - Over 8,900 unique video titles  
  - Popular titles include *Skeem Saam*, *Uzalo*, *Peppa Pig*, and *Today*

## 📈 Visualizations
- Bar charts for:
  - Unique customers by platform  
  - Unique customers by video title  
  - Unique customers by play event type  
  - Temporal trends by month and day  
- Pie chart for platform distribution

## 🛠️ Tools & Libraries
- **Python**  
- **Pandas** for data manipulation  
- **Seaborn & Matplotlib** for visualization  
- **Databricks** for notebook execution and dashboarding

## ⚠️ Notes
- The dataset uses a placeholder date (`1970-01-01`)—likely due to missing or default timestamp values.  
- Consider filtering or imputing realistic date ranges for time-based analysis.  
- `TotalTimeWatched` may require normalization or binning for clearer insights.

## 📌 Next Steps
- Feature engineering: derive session-level metrics or viewer retention  
- Content clustering: group similar titles by genre or engagement  
- Dashboard integration: automate reporting via Power BI or Python-pptx



