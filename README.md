![Python](https://img.shields.io/badge/Python-3.x-blue)
![EDA](https://img.shields.io/badge/Analysis-EDA-green)
![GIS](https://img.shields.io/badge/Focus-Spatial%20Analysis-orange)
![Tourism](https://img.shields.io/badge/Domain-Tourism-purple)

# Tourism Analysis: Data-Driven Accommodation Site Selection

> A data-driven project that identifies high-value accommodation locations by analyzing tourism demand and vacancy distribution.

This project analyzes national travel survey data to identify high-spending, overnight tourism regions, and proposes optimal accommodation infrastructure locations by integrating tourist hotspots and vacant housing data.

---

## Repository Structure

| Folder/File | Description |
|-------------|-------------|
| `notebooks/` | Full analysis pipeline (EDA → modeling → spatial analysis) |
| `docs/` | proposal & final presentation |
| `data/` | Dataset description only (data not included) |
| `docs/yeosu_map.html` | Interactive map visualization |

---

## Project Background

Traditional tourism analysis focuses on visitor counts.  
However, effective regional development requires understanding:

- Travel patterns  
- Spending behavior  
- Accommodation demand  

This project aims to provide data-driven insights for tourism policy and infrastructure planning.

---

## Data

- Source: National Travel Survey (국민여행조사)  
- Unit of Analysis: Regional tourism patterns  
- Key Variables:
  - Travel type (overnight / day trip)  
  - Tourism expenditure  
  - Visited locations  
  - Tourist attraction distribution  

---

## Methodology

1. Exploratory Data Analysis (EDA) of tourism patterns  
2. Identification of high-spending overnight tourism regions  
3. Integration with:
   - Tourist attraction data  
   - Vacant housing data  
4. Spatial analysis for location selection  
5. Evaluation of expected economic impact  

---

## Key Results

- Final selected region: Yeosu  
- Identified areas with:
  - High tourism demand  
  - High vacancy availability  
- Conducted spatial analysis combining:
  - Tourist hotspots  
  - Vacant housing clusters  
- Demonstrated potential for:
  → Regional economic revitalization  
  → Efficient accommodation infrastructure planning  

---

## Spatial Analysis: Vacancy vs Tourist Attractions

This map visualizes the relationship between:

- Vacant housing distribution (blue & purple)  
- Major tourist attractions (red)  

Highlighted regions (purple) represent top vacancy areas.
 <img width="737" height="818" alt="image" src="https://github.com/user-attachments/assets/c95a99c8-d518-4d0a-93d5-47dd62d1fa86" />


---

## Insights

- Certain regions show spatial mismatch between tourism demand and accommodation supply  
- High vacancy areas near tourist zones present opportunities for redevelopment  
- Data-driven planning can improve:
  - Resource allocation  
  - Regional tourism efficiency  

---

## Limitations & Future Work

- Web crawling for detailed location data was planned but not implemented  
- Analysis relies on aggregated regional data  
- Future improvements:
  - Incorporate real-time tourism data  
  - Use fine-grained spatial clustering  
  - Apply predictive modeling for demand forecasting  

---

## Data Availability

The dataset used in this project cannot be publicly shared.

---

## Tech Stack

- Python: pandas, numpy, scikit-learn, matplotlib, seaborn  
- Visualization: folium (interactive map)  
- Environment: Jupyter Notebook  

---

## Summary

This project demonstrates how combining:

- Tourism demand data  
- Spatial analysis  
- Vacancy information  

can lead to practical and actionable insights for urban and tourism development.

→ A step toward data-driven regional policy design.
