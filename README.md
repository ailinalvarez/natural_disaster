# 🌍 Natural Disaster Intelligence Project  

## 📌 Overview

This project presents an exploratory data analysis (EDA) of global natural disaster events recorded between 2023 and 2025. The analysis focuses on identifying temporal, geographic, and categorical patterns, as well as evaluating the social and economic impact of these events.

The goal is to transform raw event data into structured insights that help better understand how natural disasters are distributed and how their consequences vary across regions and disaster types.

## 🎯 Objectives

This analysis aims to explore:

The temporal distribution of natural disasters and potential seasonal patterns
The geographic concentration of events across countries
Differences in frequency across disaster types
The social impact of disasters (affected population)
The economic impact of disasters (estimated financial losses)
The relationship between frequency, severity, and impact

## 📊 Dataset

The dataset includes information about global natural disaster events, with the following key variables:

- date — date of the event
- location — country where the event occurred
- disaster_type — category of disaster (e.g., earthquake, flood)
- affected_population — number of people affected
- population — total population of the country
- severity_level — severity classification
- is_major_disaster — indicator of major events
- estimated_economic_loss_usd — estimated financial loss
- km2 — country surface area

An additional dataset was used to enrich the analysis with population and geographic information.

## 🔍 Methodology

The project follows a structured exploratory data analysis approach:

- Data preprocessing
    - Date transformation and feature engineering (year, month, week)
    - Data cleaning and validation
- Exploratory analysis
    - Temporal analysis (seasonality and distribution over time)
    - Geographic analysis (event concentration by country)
    - Disaster type analysis (frequency comparison)
- Impact analysis
    - Social impact
        - Absolute (affected population)
        - Relative (proportion of population affected)
    - Economic impact
        - Total losses
        - Average loss per event
        - Impact by severity

## 📈 Key Insights

- Natural disasters are not evenly distributed over time, showing patterns that suggest seasonal dynamics.
- Events tend to concentrate geographically, with certain regions experiencing higher exposure.
- Disaster types vary significantly in frequency, with some occurring more regularly than others.
- Social impact differs when measured in absolute vs relative terms, highlighting differences between large and small populations.
- Economic losses are not solely driven by the number of events; less frequent disasters can generate disproportionately high financial damage.
- Severity plays a key role, as major disasters account for a significant share of total economic impact.

## 🧠 Conclusions

Natural disasters are multidimensional phenomena whose impact cannot be understood through a single metric. Their occurrence and consequences vary across time, geography, and type, while social and economic impacts do not always align.

A comprehensive analysis requires considering both frequency and severity, as well as combining absolute and relative measures to better assess vulnerability and exposure.

## ⚠️ Limitations
- The dataset contains estimated values for economic losses
- Differences in reporting across countries may affect comparability
- No external socio-economic indicators (e.g., GDP) are included
- The analysis is exploratory and does not infer causal relationships


## 🛠️ Tools & Technologies
 Python
Pandas
Matplotlib / Seaborn
Jupyter Notebook

## 📎 Project Structure
disaster_event.ipynb → main analysis notebook
synthetic_disaster_events_2025.csv → primary dataset
pais_km2_pop.csv → supplementary dataset