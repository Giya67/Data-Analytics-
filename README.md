# Data-Analytics-# 

**Overcoming Critical Challenges in Sustainable Energy Access and Utilization in Ethiopia**

This project leverages **World Bank energy indicators** and **machine learning** to analyze and forecast trends in **sustainable energy access** and **renewable energy utilization** in Ethiopia. The study provides data-driven insights to guide **policy development**, **resource allocation**, and **infrastructure planning** for improved access to electricity and clean energy technologies.

---

## **Project Overview**

Access to sustainable energy is a key enabler of socio-economic development. Ethiopia, with abundant renewable energy resources (e.g., hydropower, solar, wind), faces critical challenges such as:

- Low rural electricity access rates.
- Overreliance on hydropower, making the energy supply vulnerable to climate variability.
- High energy intensity, indicating inefficiencies in energy usage.
  
This project applies predictive models to **forecast energy trends** and **support policy planning** to overcome these challenges. The **Random Forest Regression model** achieved superior performance with an R² score of **0.988**, providing reliable predictions for future energy scenarios.

---

## **Key Features**

- **Exploratory Data Analysis (EDA):** Identify disparities in energy access and trends in renewable energy consumption.
- **Machine Learning Models:** Use **Linear Regression**, **Decision Tree Regression**, and **Random Forest Regression** to forecast energy trends.
- **Data Visualization:** Interactive dashboard built with **Dash** and **Plotly** for visualizing key indicators.
- **Comparative Analysis:** Benchmark Ethiopia's energy metrics against neighboring countries (e.g., Kenya, Somalia, Sudan).

---

## **Project Objectives**

### **General Objective**
Develop a data-driven approach to forecast trends in sustainable energy access and utilization in Ethiopia using World Bank indicators.

### **Specific Objectives**
1. Analyze the current state of electricity access and energy consumption in Ethiopia.
2. Evaluate the impact of renewable energy production on the share of renewable electricity.
3. Forecast future trends in electricity access and renewable energy output.
4. Recommend strategies for improving energy sustainability in Ethiopia.

---

## **Dataset**

The dataset was sourced from the **World Bank's Sustainable Energy for All** initiative and includes the following key features:
- **Access to electricity** (rural, urban, and total population percentages)
- **Energy intensity** (MJ per 2011 USD PPP)
- **Renewable electricity output** (GWh)
- **Renewable energy consumption** (TJ)
- **Total final energy consumption** (TFEC)

---

## **Technologies Used**

- **Programming Language:** Python  
- **Data Analysis Libraries:** `pandas`, `numpy`  
- **Machine Learning Libraries:** `scikit-learn`  
- **Visualization:** `matplotlib`, `plotly`, `dash`  
- **Dashboard Development:** Plotly Dash  

---

## **Machine Learning Models**

| Model                    | Mean Squared Error (MSE) | R² Score |
|--------------------------|---------------------------|-----------|
| Linear Regression         | 341.10                    | 0.797     |
| Decision Tree Regression  | 34.04                     | 0.980     |
| Random Forest Regression  | 19.44                     | 0.988     |

The **Random Forest Regression** model was the most effective in capturing complex relationships between energy indicators, making it suitable for trend prediction.

---

## **Dashboard Features**

### **Dynamic Visualization**
- **Interactive Plots:** Users can select features to visualize trends and distributions dynamically.
- **Plot Types:** Scatter plots, line plots, bar charts, and box plots.
- **Year Filter:** Allows users to filter data by year range for time-series analysis.

### **Static Plots**
- **Histogram:** Distribution of the selected feature.
- **Box Plot:** Distribution and spread of renewable electricity share across different regions or categories.

---

## **Key Findings**

1. **Rural-Urban Disparities:** Only **30%** of Ethiopia's rural population has electricity access, compared to **98%** in urban areas.
2. **Dependency on Hydropower:** Over **95%** of electricity comes from hydropower, posing risks from seasonal climate variations.
3. **Energy Intensity:** Ethiopia consumes more energy per unit of economic output than many of its peers, indicating room for efficiency improvements.
4. **Future Projections:** Without intervention, rural access is projected to reach only **45%** by 2030, below development targets.

---

## **Recommendations**

1. **Expand Decentralized Energy Solutions:** Increase investment in rural solar microgrids to boost access to **60%** by 2030.
2. **Promote Clean Fuel Technologies:** Aim for **50%** adoption of clean cooking technologies through subsidies and incentives.
3. **Diversify Energy Sources:** Reduce reliance on hydropower by developing solar and wind projects, targeting **25%** of total output by 2030.
4. **Improve Energy Efficiency:** Implement programs to reduce energy intensity from **12 MJ per USD** to **8 MJ per USD** by 2030.
5. **Data-Driven Policymaking:** Establish analytics units to optimize energy planning and scenario forecasting.

---

## **Installation Instructions**

1. Clone the repository:
   ```bash https://github.com/Giya67/Data-Analytics-.git
   ```
2. Navigate to the project directory:
   ```bash https://github.com/Giya67/Data-Analytics-
   ```
3. Install required dependencies:
   ```bash import pandas as pd
import seaborn as sns
import matplotlib.pyplot as plt

   ```
4. Run the dashboard:
   ```bash

!pip install dash
!pip install dash-bootstrap-components
!pip install plotly
   ```

---

## **How to Use the dashbord **

- Access the dashboard at `http://localhost:8050` after running the app.
- Use the dropdowns to select features for analysis.
- Adjust the year range slider to filter time-series data.
- Explore static plots for additional insights.

---

## **License**

This project is licensed under the [MIT License](LICENSE).

---

## **Contact**

For questions or collaboration opportunities, please reach out to **Habtamu Hailu** at **giyando@gmail.com**.

---

This README file provides all necessary information to understand, install, and use the project effectively. Customize it further for your GitHub page.
