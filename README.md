# Business-Analytics-and-Visual-Storytelling  

This repository showcases a portfolio of **business analytics and storytelling projects** that combine data integration, statistical modeling, and visualization to extract actionable insights and communicate them effectively for decision-making.  

Each project applies advanced data wrangling, exploratory analysis, and econometric/statistical techniques to diverse domains — from **hospitality markets (Airbnb)** to **global innovation (Nobel Prize)** to **financial services (Bank Loans)**.  

---

## Project Portfolio  

### 1. Airbnb-NZ-Performance-Analysis-2024-2025  
- **Dataset:** 575,000+ Airbnb listings & 33M guest reviews (July 2024 – June 2025)  
- **Focus:** Pricing dynamics, host behavior, guest sentiment, and property segmentation.  
- **Techniques:**  
  - Exploratory Data Analysis (distributions, seasonal demand, regional trends)  
  - K-Prototypes clustering & silhouette validation (host/property types)  
  - Panel data regression (fixed vs. random effects, Hausman test)  
  - Lexicon-based sentiment analysis (AFINN, Bing, NRC)  
- **Key Insights:**  
  - Queenstown median nightly price ≈ NZD 210 vs. Auckland ≈ NZD 160  
  - Identified 5 host/property clusters (silhouette score 0.46)  
  - Superhosts maintain >97% response rates, charge ~15% more  
  - Sentiment score +0.62 on average, with praise for cleanliness/location  

---

### 2. Nobel_Excellence_Index  
- **Dataset:** Integrated World Bank Indicators, HDI, QS University Rankings, and Nobel Laureates API  
- **Focus:** Drivers of Nobel Prize productivity at the **country and university level**.  
- **Techniques:**  
  - Multi-source data wrangling (CSV, Excel, JSON, API integration)  
  - Correlation analysis & exploratory statistics  
  - Visualization of global Nobel trends, innovation indicators, and education metrics  
- **Key Insights:**  
  - Wealthier countries with higher GDP per capita & R&D spending dominate Nobel counts  
  - Strong link between QS-ranked universities and laureate productivity  
  - Balanced investment in **education, R&D, and innovation** = long-term Nobel success  
  - Patent filings and journal publications strongly correlate with Nobel outcomes  

---

### 3. Bank Loan Analysis  
- **Dataset:** 418 loan applications from multiple sources (CSV, XML, JSON)  
- **Focus:** Customer profiling, loan application trends, and risk factors.  
- **Techniques:**  
  - Data integration & cleaning across heterogeneous sources  
  - Feature engineering (e.g., `TotalBalance` = savings + checking)  
  - Pivot tables, descriptive analysis, and demographic profiling  
- **Key Insights:**  
  - Identified narrow low-balance customer segment (top 15 applicants spread = $104)  
  - Seasonal loan purposes: car, appliances most frequent  
  - Residence stability (≥3 years) correlated with censored loan categories  
  - Education/job type linked to age & financial stability patterns  

---

## Tools & Technologies  
- **Languages:** Python (pandas, NumPy, matplotlib, seaborn), R  
- **Libraries:** plm, tidyverse, cluster, factoextra, nltk, textdata  
- **Techniques:** Clustering (K-Prototypes), Panel Data Regression, Sentiment Analysis, Correlation & ANOVA  
- **Environments:** Jupyter Notebooks, RStudio, SPSS  
- **Visualization & Storytelling:** Power BI, ggplot2, matplotlib  

---

## Repository Structure  
```
Business-Analytics-and-Visual-Storytelling/
│
├── Airbnb-NZ-Performance-Analysis-2024-25/ # Hospitality market analysis
├── Nobel-Excellence-Index/ # Global innovation & Nobel analysis
├── bank-loan-analysis/ # Loan profiling & risk assessment
│
├── LICENSE
└── README.md
```

---

## Key Takeaways  
- Business analytics projects require **end-to-end pipelines**: wrangling → modeling → storytelling.  
- Across domains, segmentation and regression techniques help uncover **hidden patterns**.  
- Storytelling with data (reports, presentations, dashboards) ensures **insights are actionable** for stakeholders.  

---

## License  
This repository is licensed under the **MIT License**.  
