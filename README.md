# HDI Clustering Shiny App

## Overview
This Shiny app visualizes clusters of countries based on Human Development Index (HDI) indicators using 3D scatterplots. 

## Features
- Interactive 3D scatterplot using **plotly**
- Visualizes clusters of countries based on scaled HDI indicators
- Customizable layout with detailed axis titles

## Data
The dataset used is `shiny.csv`, containing scaled variables:
- `life_exp_scaled`: Scaled life expectancy at birth (years)
- `gni_scaled`: Scaled Gross National Income (GNI) per capita
- `yrs_sch_scaled`: Scaled expected years of schooling
- `cluster`: Clustering group identifier

### Data Source
[World Bank Open Data](https://data.worldbank.org)

## Installation
1. Clone this repository and ensure you have **R** and **RStudio** installed
2. Install required R packages:
   ```R
   install.packages(c("shiny", "tidyverse", "plotly", "dplyr"))
   ```
3. Place `shiny.csv` in the root directory

## Running the App
1. Open the project file in **RStudio**.
2. Run the app:
   ```R
   shiny::runApp()
   ```

## Usage
- Explore clusters of countries through an interactive 3D plot
- Analyze the relationships between life expectancy, GNI, and years of schooling
- Visualize HDI clustering results in a clean and engaging format

## Collaborators

This project was a collaborative effort by the following individuals:

- Ephrata Getachew
- Aika Shorayeva
- Ebony Wamwitha
  
