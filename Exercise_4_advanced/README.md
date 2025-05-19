# Assignment 4 (Advanced) – Clustering Countries for Humanitarian Aid Allocation

This notebook addresses a real-world problem faced by HELP International, an NGO aiming to distribute $10 million in aid. The goal is to use unsupervised learning techniques to **cluster countries** based on socio-economic and health indicators, enabling data-driven decisions about where aid is most needed.

## 📊 Dataset Description

Each row represents a country, with the following features:

- `country`: Country name  
- `child_mort`: Child mortality (deaths under 5 per 1000 live births)  
- `exports`: Exports as a percentage of GDP  
- `health`: Health expenditure as a percentage of GDP  
- `imports`: Imports as a percentage of GDP  
- `income`: Net income per person  
- `inflation`: Annual GDP growth rate  
- `life_expec`: Life expectancy at birth  
- `total_fer`: Total fertility rate  
- `gdpp`: GDP per capita

## 📌 Contents

- Exploratory Data Analysis (EDA):
  - Summary statistics and distribution plots
  - Skewness analysis of variables
- Data preprocessing:
  - Feature scaling
  - Outlier detection and removal
- Clustering:
  - KMeans algorithm
  - Elbow method and silhouette score analysis
  - Cluster interpretation and visualization
- Key insights:
  - Identification of countries in the most critical condition
  - Recommendations for resource allocation

## 🧠 Techniques Used

- StandardScaler
- KMeans clustering
- Elbow method to determine optimal number of clusters
- Silhouette analysis for validation
- Visualizations using pairplots, scatter plots, and heatmaps

## 🛠️ Tools & Libraries

- Python
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/Mateoo18/Data_Science.git
   cd Data_Science/Exercise_4_advanced
