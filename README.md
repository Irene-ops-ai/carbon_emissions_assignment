# Carbon Emissions Prediction (SDG 13: Climate Action)
## Project Overview
This project focuses on UN Sustainable Development Goal 13 – Climate Action, addressing the urgent global challenge of climate change caused by rising carbon emissions.
The goal is to predict future CO₂ emission trends using a machine learning model to help policymakers, researchers, and environmental organizations make informed decisions for a sustainable future.

## Objectives
Analyze and clean real-world carbon emission data.

Train a Supervised Learning model to predict CO₂ growth percentage.

Evaluate model performance and visualize emission patterns.

Reflect on ethical implications of AI in environmental sustainability.

## Machine Learning Approach
Model Used: Linear Regression

Learning Type: Supervised Learning

Features: year, gdp, population

Target Variable: co2_growth_prct

Accuracy: ~0.56

## Tools & Libraries
Tool	                 Purpose
Python (Google Colab) -	Model development and testing
Pandas & NumPy	      - Data cleaning and manipulation
Matplotlib	          - Data visualization
Scikit-learn	        - Machine learning modeling
Streamlit (optional)	- Interactive web app deployment

## Dataset
The dataset was sourced from the UN SDG Database and contains information on:

Yearly carbon emissions

GDP per country

Population growth

CO₂ growth percentage

Each feature contributes to understanding how economic and population factors influence global emissions.

## Model Workflow
Data Loading: Import CSV data into Pandas.

Data Cleaning: Handle missing values and normalize data.

Feature Selection: Select year, GDP, and population as predictors.

Model Training: Train a Linear Regression model using Scikit-learn.

Evaluation: Test accuracy (0.56) and visualize predictions.

Deployment (optional): Build a Streamlit app for user input and prediction.

## Ethical & Sustainability Considerations
Ensuring data fairness to avoid regional bias.

Using AI responsibly to support sustainable development.

Promoting transparency in climate data modeling and interpretation.

## Demo & Visuals
Below are some screenshots from the notebook:

Data visualization (CO₂ trends)

Model prediction outputs

Evaluation metrics

### Demo Screenshots
#### Data Preview
![Data Preview](Demo/library imports, data loading, data cleaning.png)

#### Model training
![Model Training](Demo/model training & evaluation.png)

#### Results
![Results](Demo/results 1.png)

![Results](Demo/results 2.png)


