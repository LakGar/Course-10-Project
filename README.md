# :rocket: Applied Data Science Capstone

This Capstone project represents the culmination of the [IBM Data Science Professional Certificate](https://www.coursera.org/professional-certificates/ibm-data-science) specialization, serving as the final course. It integrates and applies all the knowledge and skills acquired throughout the specialization into a comprehensive project.

## :page_facing_up: Project Overview

SpaceX has revolutionized the commercial space industry, making space travel more affordable. The Falcon 9 rocket, which SpaceX promotes on its website, costs approximately $62 million per launch, significantly lower than other providers, which can cost upwards of $165 million. This cost reduction is largely due to SpaceX’s ability to reuse the first stage of the rocket. Therefore, predicting whether the first stage will successfully land is crucial in estimating the overall cost of a launch. In this project, we utilize public data and machine learning models to predict the likelihood of SpaceX reusing the first stage.

## :page_facing_up: Research Questions

- How do factors like payload mass, launch site, number of flights, and orbit type influence the success of the first stage landing?
- Has the success rate of landings improved over time?
- Which binary classification algorithm is most effective for this prediction task?

## :page_facing_up: Methodology

### 1. Data Collection

- Obtained data using the SpaceX REST API.
- Supplemented data with web scraping from Wikipedia.

### 2. Data Preparation

- Filtered and cleaned the data.
- Addressed missing values.
- Applied One-Hot Encoding to prepare data for binary classification.

### 3. Exploratory Data Analysis (EDA)

- Conducted EDA using both visualization techniques and SQL queries.

### 4. Interactive Visual Analytics

- Created interactive visualizations using Folium and Plotly Dash.

### 5. Predictive Analysis

- Built, tuned, and evaluated various classification models to identify the best-performing algorithm.
