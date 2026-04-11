![Python](https://img.shields.io/badge/Python-3.x-blue)
![Tourism](https://img.shields.io/badge/Topic-Tourism-green)
![EDA](https://img.shields.io/badge/Analysis-EDA-orange)
![Policy](https://img.shields.io/badge/Focus-Policy%20Analysis-purple)

# Tourism Analysis Project: Travel Patterns and Accommodation Strategy

A data analysis project based on the National Travel Survey, aimed at identifying high-spending, overnight tourism regions.
This study integrates travel patterns, expenditure data, and regional characteristics to support data-driven accommodation infrastructure and policy recommendations.
---

## Repository Structure

| File | Description |
|------|------|
| `제3회 BDA 채용 공모전_P-Valley.ipynb` | Full analysis pipeline (EDA → analysis → results) |
| `제3회 BDA 채용 공모전.pdf` | Initial submission report |
| `제3회 BDA 채용 공모전(2차 심사 파일)_P-Valley.pdf` | Final presentation for competition |
---

## Analysis Overview

### Initial Analysis (analysis.ipynb)

| Section | Description |
|------|------|
| Data Loading & Preprocessing | Cleaning data and preparing analysis-ready variables |
| Travel Pattern Analysis | Regional comparison of travel types (overnight vs day trips) |
| Expenditure Analysis | Distribution and comparison of tourism spending by region |
| Candidate Region Selection | Identification of high-spending overnight tourism regions |
| Spatial Insights | Exploration of regional tourism characteristics |

### Advanced Analysis (analysis_advanced.ipynb)

| Section | Description |
|------|------|
| Data Integration | Combining tourism data with attraction distribution and vacant housing data |
| Location Analysis | Identifying optimal regions for accommodation infrastructure |
| Case Study (Yeosu) | In-depth regional analysis with tourist attractions and housing data |
| Impact Evaluation | Estimating potential regional economic effects |

---

## Data Preparation

Use the National Travel Survey dataset and preprocess it within the notebook.

Additional datasets may include:
- Tourist attraction distribution data  
- Vacant housing data  

---

## Key Findings

- **Yeosu** was identified as the most suitable high-spending overnight tourism region
- Spatial analysis combining tourist attractions and vacant housing enabled practical location insights
- Results suggest strong potential for regional economic growth through accommodation infrastructure development
- Tourism patterns and expenditure structures vary significantly across regions
  → Effective policy decisions require integrating multiple regional characteristics

---

## Limitations & Future Work

- The analysis focuses on observed patterns and does not establish causal relationships
- External factors such as seasonality and policy constraints are not fully considered
- Web scraping was considered to collect additional spatial and infrastructure data for optimal location selection, but was not implemented due to data accessibility constraints
- Future work may extend to predictive modeling and optimization-based location analysis, incorporating automated data collection (e.g., web scraping)

---

## Environment

- **Language**: Python 3.x
- **Libraries**: pandas, numpy, scikit-learn, matplotlib, seaborn
- **Tools**: Jupyter Notebook
