# 🌍 Global Development Indicators Dashboard

![Dashboard Preview](https://github.com/VishalJha01/Global-development-indicators-Dashboard/blob/main/Screenshot%202025-07-26%20135838.png)

A **Power BI dashboard** visualizing **1,000+ socio-economic, demographic, and environmental indicators** tracked across **200+ countries**, powered by **World Bank – World Development Indicators (WDI)** data.

---

## 📌 Overview

Are we truly developing as a world?

This interactive dashboard provides a clear and data-driven perspective on global development trends — from **GDP growth and life expectancy** to **unemployment, population, and energy access**.  
It allows users to **compare nations, regions, and income groups over time** while highlighting leaders, laggards, and gaps in development.

Built as part of my **BCA portfolio**, the project demonstrates how **credible datasets** can be transformed into **actionable, insightful, and visually compelling** stories using **Power BI**.

---

## ✨ Features

- ✅ **Global KPIs**: GDP, population, death rate, life expectancy, and unemployment — dynamically calculated.
- ✅ **Top Performers**: DAX-driven **Top 10 countries** for any indicator in the latest year.
- ✅ **Historical Trends**: Line charts tracking the **Top 5 countries** over decades.
- ✅ **Geographic Insights**: World map showing indicator distribution across **countries, regions, and income groups**.
- ✅ **Income Group Analysis**: Donut chart visualizing population share by income classification.
- ✅ **Interactive Slicers**: Drill down by **year, region, country, income group, or indicator**.

---

## ⚙️ Tools & Techniques Used

- **Power BI Desktop** – End-to-end dashboard design & visualization.
- **Data Modeling & Transformation** – Building optimized relationships for smooth report performance.
- **Power Query** – Robust data cleaning, transformation, and unification of multiple datasets.
- **Advanced DAX Measures** – Context-aware KPIs, dynamic rankings, and custom logic:
  - `CALCULATE()` – Dynamic context adjustments.
  - `TOPN()` – Ranking countries by indicator.
  - `SELECTEDVALUE()` – Context-sensitive titles and measures.
  - `SWITCH(TRUE())` – Flexible indicator selection.

---

## 📊 Dataset

- **Source:** [World Bank – World Development Indicators (WDI)](https://datacatalog.worldbank.org/search/dataset/0037712/World-Development-Indicators)
- **Coverage:** 1,000+ indicators, 200+ countries, spanning decades of **socio-economic, demographic, and environmental** data.
- **Credibility:** Data from a **globally trusted institution** ensuring real-world relevance.

---

## 🎯 Primary Goals

- **Identify global leaders and laggards** in GDP, life expectancy, education, and other indicators.
- **Spot development gaps** where unemployment, death rates, and energy access remain challenges.
- **Enable data-driven comparisons** by **income group, region, and country** across multiple years.
- **Showcase data storytelling skills** through advanced **Power BI techniques** and real-world data.

---

## 🚀 Getting Started

1. Clone this repository:
   ```bash
   git clone https://github.com/VishalJha01/Global-development-indicators-Dashboard.git
