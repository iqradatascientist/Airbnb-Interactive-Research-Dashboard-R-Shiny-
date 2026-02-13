# Airbnb Interactive Research Dashboard (R Shiny)

A fully interactive Shiny dashboard analyzing Airbnb listings across major cities to uncover pricing trends, demand patterns, and market insights.

This project demonstrates end-to-end data analytics workflow — from data cleaning and exploration to interactive visualization and deployment.

🔗 Live App: https://iqradatascientist.shinyapps.io/custom_research_dashboard/

---

## Project Objectives

- Understand pricing distribution across neighborhoods  
- Identify high-demand areas based on listings and reviews  
- Compare room types and their market behavior  
- Provide actionable insights for hosts and investors  

---

## Features

✔ Interactive filters (neighborhood, price range)  
✔ KPI metrics (average price, total listings, reviews)  
✔ Dynamic plots with Plotly  
✔ Executive Summary with business insights  
✔ Clean, deployment-ready Shiny app  

---

## Dashboard Screenshots

### Overview Tab
![Overview](<img width="1363" height="508" alt="image" src="https://github.com/user-attachments/assets/6a1879e5-d5fe-4c10-96c2-421e0d3bcf94" />)

### Analysis Tab
![Analysis](screenshots/analysis.png)

### Trends Tab
![Trends](screenshots/trends.png)

---

## Key Insights (Sample)

- Average listing prices vary significantly across neighborhoods  
- Certain areas dominate market supply  
- Entire homes/apartments attract higher pricing compared to private rooms  
- Listings with higher reviews tend to stabilize at competitive prices  

These insights can help optimize pricing strategies and investment decisions.

---

## Dataset

Airbnb public listings dataset including:

- Price  
- Neighborhood group  
- Room type  
- Number of reviews  
- Listing metadata  

(Sample version included for reproducibility)

---

## Tech Stack

- R  
- Shiny  
- ggplot2  
- dplyr  
- plotly  
- ShinyApps.io deployment  

---

## Run Locally

```r
install.packages(c("shiny","shinydashboard","ggplot2","dplyr","plotly"))
shiny::runApp()
