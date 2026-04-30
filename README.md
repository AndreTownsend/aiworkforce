# AI vs. The Workforce — 10-Year Forecast (2026–2035)

## Executive Summary
This project analyzes the impact of artificial intelligence (AI) on the global workforce using historical data (2015–2025) and predictive modeling through 2035. The analysis highlights a growing gap between jobs automated and new AI-related job creation, while also identifying sectors that will experience net job gains or losses. Despite rising automation, productivity increases significantly, suggesting economic growth alongside workforce disruption.

---

## Business Problem
As AI adoption accelerates globally, organizations, governments, and workers face uncertainty regarding job displacement, job creation, and long-term employment trends. 

**Key Questions:**
- Will AI create more jobs than it replaces?
- Which industries are most at risk?
- How will AI impact unemployment and productivity?

---

## Methodology
- **Data Creation:** Simulated dataset representing global AI investment, job automation, job creation, unemployment, and productivity (2015–2025)
- **Forecasting Model:** Polynomial Regression (Degree 2) using `scikit-learn`
- **Time Horizon:** Forecast from 2026 to 2035
- **Data Processing:** `pandas`, `numpy`
- **Visualization:** `matplotlib`, `seaborn`
- **Output:** CSV files for Power BI dashboard integration

---

## Key Visualizations

![AI Workforce Analysis](project1_ai_workforce.png)

**Charts Included:**
- Job Displacement vs Job Creation
- Global AI Investment Growth
- Net Job Change by Industry
- Automation Risk by Sector
- AI Productivity Growth
- Global Unemployment Trends

---

## Findings

### 1. Job Displacement Outpaces Job Creation
- By 2035, **jobs automated significantly exceed new AI jobs created**
- Indicates a widening workforce gap

### 2. Sector-Level Impact is Uneven
- **High-risk sectors:** Manufacturing, Retail, Transportation  
- **Growth sectors:** Software Development, Healthcare, Education  

### 3. AI Investment is Rapidly Increasing
- AI investment shows **exponential growth**, driving automation trends

### 4. Productivity Gains are Significant
- AI productivity index nearly **quadruples from 2015 to 2035**

### 5. Unemployment Remains Stable (with fluctuations)
- Despite disruption, unemployment does not spike dramatically due to:
  - New job creation
  - Economic adaptation

---

## Skills Demonstrated

- **Data Analysis:** Pandas, NumPy  
- **Machine Learning:** Polynomial Regression (Scikit-learn)  
- **Data Visualization:** Matplotlib, Seaborn  
- **Forecasting & Predictive Modeling**  
- **Business Insight Generation**  
- **Data Storytelling for Decision Making**  
- **Power BI Data Preparation (CSV export)**  

---

## Tools & Technologies
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-learn  
- Power BI  

---

## Next Steps

- Integrate **real-world datasets** (World Bank, OECD, IMF)
- Enhance model accuracy using:
  - Time series models (ARIMA, Prophet)
  - Machine learning ensembles
- Build an **interactive Power BI dashboard**
- Segment analysis by:
  - Country
  - Skill level
  - Education level
- Develop policy recommendations for workforce adaptation

---

## Author
**Andre Townsend, MBA**  
Data Analytics Portfolio  

---

## Project Insight
AI is not just replacing jobs — it is reshaping the entire structure of the global workforce. The challenge is not technology, but adaptation.
