# IBM Applied Data Science Capstone - SpaceX

## Project Overview

This repository contains my final project for the IBM Applied Data Science
Capstone course in the IBM Data Science Professional Certificate on Coursera.

The objective is to analyze SpaceX Falcon 9 launch data and predict whether
the first stage will land successfully.

## Business Problem

SpaceX reduces launch costs by recovering and reusing Falcon 9 first stages.
Predicting first-stage landing success can support launch-cost estimation and
competitive bidding decisions.

## Project Workflow

1. SpaceX data collection using a REST API
2. Falcon 9 launch-data collection using web scraping
3. Data cleaning and wrangling
4. Exploratory data analysis using SQL
5. Exploratory data visualization
6. Interactive mapping using Folium
7. Interactive dashboard development using Plotly Dash
8. Classification-model development and evaluation
9. Technical reporting through PowerPoint and PDF

## Machine-Learning Models

The following classifiers were tuned using GridSearchCV:

- Logistic Regression
- Support Vector Machine
- Decision Tree
- K-Nearest Neighbors

## Repository Contents

### Notebooks

- `01_Data_Collection_Web_Scraping.ipynb`
- `02_Data_Wrangling.ipynb`
- `03_EDA_SQL.ipynb`
- `04_EDA_Data_Visualization.ipynb`
- `05_Machine_Learning_Prediction.ipynb`

### Application

- `spacex_dash_app.py`

### Presentation

- `Akash_S_IBM_Data_Science_Capstone.pptx`
- `Akash_S_IBM_Data_Science_Capstone.pdf`

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- SQL and SQLite
- BeautifulSoup
- Folium
- Plotly Dash
- Jupyter Notebook

## Key Findings

Replace this section with the exact results from the completed notebooks:

- Overall first-stage landing success rate: `ADD RESULT`
- Highest-performing launch site: `ADD RESULT`
- Important orbit findings: `ADD RESULT`
- First successful ground-pad landing: December 22, 2015
- Best-performing classification model(s): `ADD RESULT`
- Highest test accuracy: `ADD RESULT`

## Running the Project

Install the dependencies:

```bash
pip install -r requirements.txt
