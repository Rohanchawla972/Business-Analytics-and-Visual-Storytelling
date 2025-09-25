# Nobel_Excellence_Index

## Repository Structure
- **README.md** — Project overview, methodology, and documentation  
- **Nobel_Price_Analysis.ipynb** — Python notebook with full wrangling, integration, and analysis  
- **Nobel_Price_Analysis.pdf** — Final detailed report with findings and recommendations  
- **Datasets/Raw/** — Original datasets (World Bank Indicators, HDI, QS Rankings, Nobel JSON)  
- **Datasets/Filtered/** — Cleaned and structured datasets (Nobel_Laureates_Filtered.xlsx, Nobel_Laureates_Flat.xlsx)  
- **Datasets/Merged/** — Final integrated dataset (MERGED.csv)  
- **LICENSE** — License information (MIT)
## Problem Statement  

Despite their prestige, global university rankings (such as QS) often emphasize reputation and input metrics rather than true innovation outcomes. This project asks:  

**What factors enable countries and universities to consistently produce Nobel laureates?**  

The objective is to integrate **Nobel laureate data**, **national innovation indicators**, **QS university rankings**, and **HDI metrics** to:  
- Identify the strongest country-level drivers of Nobel productivity (e.g., R&D investment, GDP per capita, doctoral education).  
- Evaluate whether top-ranked universities are also the most efficient at producing laureates.  
- Provide insights into how nations and institutions can align research investment with measurable innovation outcomes.  

##  Data Sources and Wrangling  
This project involved **advanced multi-source data integration and wrangling** to study global patterns in Nobel Prize awards.  

- **Raw Data (Unstructured / Multiple Sources):**  
  - World Bank indicators: GDP, GDP per capita, R&D expenditure, patents, journal articles, tertiary education enrollment/completion.  
  - UNDP Human Development Index (HDI).  
  - QS World University Rankings.  
  - Nobel Laureates dataset (JSON via Nobel Prize API).  

- **Filtered Data (Standardized & Reshaped):**  
  - Nobel laureates cleaned into structured Excel sheets (`Filtered` and `Flat` versions).  
  - Missing values handled, categorical values standardized, and formats aligned for merging.  

- **Merged Data (Final Integration):**  
  - A unified dataset (`MERGED.csv`) combining Nobel, HDI, QS, and World Bank indicators.  
  - Enabled **cross-sectional and time-series analysis** by aligning across years and countries.  

This pipeline highlights **end-to-end wrangling** — from raw JSON, Excel, and CSV inputs to a structured, research-ready dataset.  

---

## Tools and Techniques  

- **Programming**: Python (pandas, numpy, matplotlib, seaborn)  
- **Data Wrangling**: Cleaning, reshaping, filtering, and merging heterogeneous sources  
- **Statistical Analysis**: Correlation studies, descriptive statistics, and exploratory data analysis (EDA)  
- **Visualization**: Trend analysis, country comparisons, impact of R&D and education on Nobel outcomes  
- **Presentation**: Results consolidated in PowerPoint for a non-technical audience  

---

##  Analysis and Insights  

Key findings from the analysis:  

- **Historical Trends**  
  Nobel Prizes show clear shifts over time, with scientific categories (Physics, Medicine, Chemistry) dominating in the 20th century, and growing representation in Economics and Peace in the late 20th/21st century.  

- **Country-Level Insights**  
  Wealthier nations with higher GDP per capita and sustained investments in R&D are strongly overrepresented among Nobel laureates.  

- **Education & Research Impact**  
  Strong correlation between tertiary education enrollment, QS university rankings, and Nobel Prize counts. Countries with globally ranked universities produce more laureates.  

- **Innovation Linkages**  
  Patent filings and journal publications align with Nobel recognition, highlighting the role of scientific output as a predictor.  

- **Integrated Findings**  
  Countries with balanced progress in **education, research funding, innovation, and human development** show the highest long-term Nobel success.  

---

##  Purpose  

This project demonstrates:  
- **Advanced data wrangling** across heterogeneous sources (raw → filtered → merged).  
- **Analytical storytelling** by combining global development indicators with Nobel history.  
- **Actionable insights** useful for policymakers, universities, and research organizations.  

