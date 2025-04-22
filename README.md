# ML-project

🌍 Industrial Emission Forecasting Using NPRI Data (Canada)

Harjoban Singh (Machine Learning Analyst)

📌 Project Overview

This project focuses on analyzing and forecasting pollutant release data sourced from Canada's National Pollutant Release Inventory (NPRI). The study aims to support proactive environmental decision-making by modeling emissions from critical industrial sectors, including oil sands, manufacturing, mining, and electric power generation. The project is executed in two main phases: data preprocessing and exploratory analysis, followed by time-series regression modeling for future predictions.

🎯 Project Objectives

Clean and prepare NPRI emissions data collected over multiple years.

Perform exploratory data analysis (EDA) to detect key emission trends, contributors, and anomalies.

Build time-series regression models to forecast pollutant emissions five years into the future.

Support Environment and Climate Change Canada (ECCC) in identifying high-impact sectors and planning mitigation strategies.

📊 Data Overview

The dataset used in this study includes annual pollutant release records across various Canadian provinces and territories. Key features include pollutant type, release quantity, facility name, geolocation, industrial sector, and reporting year. The data is structured and aggregated for statistical modeling after initial cleaning and integration steps.

Challenges addressed during preprocessing include handling missing values, standardizing facility names, extracting temporal features, and encoding categorical variables for machine learning workflows.

🧪 Phase 1: Exploratory Data Analysis

Using Pandas, Matplotlib, Seaborn, and GeoPandas, the EDA process investigated the spatial and temporal distribution of emissions across Canada. Visualizations included:

Line plots for annual emissions trends

Sector-wise pollutant release comparisons

Geographic heatmaps showing concentration of high-emission facilities

Correlation matrices to identify multivariate dependencies

This phase revealed that oil sands and electric power sectors are among the highest contributors to reported emissions.

📈 Phase 2: Time-Series Regression Modeling

The forecasting models were developed using Linear Regression and trained on annual pollutant trends for each sector.

Models were built using train-test splits with standardized features.

R² score and Mean Squared Error (MSE) were used as evaluation metrics.

Sector-level predictions were visualized to highlight expected release patterns over the next five years.

The models provided reasonably accurate forecasts, particularly in sectors with strong historical emission consistency.

🧰 Tech Stack

Python

Pandas, NumPy, Matplotlib, Seaborn, GeoPandas

Scikit-learn for regression modeling

Google Colab as the development environment

OpenPyXL for reading Excel data

💡 Key Insights

Oil sands and electricity generation sectors are projected to maintain high levels of emissions without intervention.

Geospatial analysis shows regional clustering of high-output facilities, especially in Alberta and Ontario.

Predictive modeling supports long-term planning for targeted emission reduction initiatives.

🔮 Future Enhancements

Integrate external weather and policy datasets to improve forecast accuracy.

Develop sector-specific models using advanced techniques such as Random Forest Regression or LSTM networks.

Deploy predictions into an interactive Streamlit dashboard for stakeholder use.

Collaborate with regulatory bodies to test model effectiveness in real-world planning scenarios.

📞 Contact

Harjoban Singh 

📧 hjawanda@norquest.ca

📞 +1 (780-224-0890
