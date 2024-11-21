# Advanced Big Data Analytics Framework for Predicting Renewable Energy Production  

This project demonstrates an analytics framework for predicting renewable energy production from solar and wind sources.  

## Overview  
- **Dataset**: Collected from [this repository](https://github.com/Bob05757/Renewable-energy-generation-input-feature-variables-analysis).  
- **Data Processing**: Combined CSV files for solar and wind data into single datasets, adding a "Nominal capacity (MW)" column based on site differences.  
- **Tools Used**: Python (Pandas, Matplotlib, Seaborn, Scikit-learn), Power BI.  
- **Objective**: Predict power generation based on environmental factors using Linear Regression models.  

## Repository Contents  
- `data/`: Contains combined solar and wind CSV files.  
- `graphs/`: Additional plots and graphs visualizing feature analysis.
- `model.ipynb`: Jupyter notebook containing the machine learning models and analysis used to predict renewable energy production. This notebook explores data preprocessing, feature engineering, and the prediction models.
- `Project_Report.pdf`: Comprehensive report detailing the methodology, data analysis, findings, and results of the project.
- `powerbi_windfarm_report.jpg`: Screenshot of the Power BI report visualizing key insights from the wind farm dataset.


## Key Features  
- Analysis of power generation with environmental parameters.  
- Correlation heatmaps for feature analysis.  
- Linear Regression model evaluation.  
- Seasonal and hourly insights into power generation.  

## Power BI Report  
The Power BI report includes interactive dashboards highlighting:  
- Monthly trends in wind power generation.  
- Seasonal trends in wind power generation.  
- Monthly wind speed variation.

## How to Run  
1. Clone this repository:  
   ```bash  
   git clone https://github.com/your_username/Advanced-Big-Data-Analytics-Framework.git