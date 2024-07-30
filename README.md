# REs-climate-change-analysis-Morocco

# Modeling and Simulating the Harvesting Potential of Renewable Energy Sources in Morocco

## Overview

This repository contains four Google Colab notebooks focused on modeling and simulating the harvesting potential of renewable energy sources in Morocco. The project aims to evaluate the potential of various Solar PV potential; Wind potential Onshore and Offshore, correct biases in climate data, and project future energy harvesting potential following 2 climate change scenarios.

## Project Description

### Objective

The primary objective of this project is to model and simulate the harvesting potential of renewable energy sources in Morocco. By analyzing historical data, correcting biases, and projecting future scenarios.


## Notebooks

### 1. Historical Distribution
**Filename:** `Historical_distribution.ipynb`

**Description:**
This notebook analyzes the historical distribution of climate variables and renewable energy data in Morocco. It includes the following sections:
- **Data Loading :** Importing ag historical climate data.
- **Potential calculation :** Analyzing the historical trends of climate variables.
- **Visualization:** Creating historical potential distribution.

### 2. Bias Correction
**Filename:** `climate_data_bias_correction.ipynb`

**Description:**
This notebook addresses biases in climate model data through correction techniques. It includes:
- **Loading Raw Data:** Importing raw climate model data.
- **Correction Methods:** Applying linear scaling bias correction method to the data.

### 3. Bias Corrected Data Visualization
**Filename:** `bias_corrected_data_visualisation.ipynb`

**Description:**
This notebook visualizes the bias-corrected climate data to ensure the effectiveness of the corrections. It includes:
- **Loading Corrected Data:** Importing bias-corrected climate data.
- **Comparative Analysis:** Comparing raw and corrected data.
- **Visualization:** Creating visual representations of corrected data distributions.


### 4. Future Projections
**Filename:** `Future_projections.ipynb`

**Description:**
This notebook projects future climate variables and renewable energy potential under different scenarios. It includes:
- **Loading Scenario Data:** Importing future scenario climate data.

- **Analysis:** Analyzing projected changes in climate variables.
- **Visualization:** Visualizing future impacts on renewable energy harvesting.

## How to Use

1. **Open Google Colab:**
   - Ensure you have a Google account.
   - Open each notebook in Google Colab by uploading them or opening them from Google Drive.

2. **Install Required Libraries:**
   - Each notebook contains the necessary library installation commands. Run these cells to install any missing packages.

3. **Follow the Notebooks Sequentially:**
   - Start with `historical_distribution.ipynb` to understand the historical context.
   - Proceed to `bias_correction.ipynb` to apply bias correction on climate variables.
   - Use `bias_corrected_data_visualisation.ipynb` to visualize the impact of corrections.
   - Finish with `future_projections.ipynb` to explore future climate scenarios and their impacts on potential.

## Requirements

- Python 3.x
- Google Colab or Jupyter Notebook
- Libraries: Pandas, NumPy, Matplotlib and others as specified in each notebook

## Contact

For any questions or further information, please contact [Salma EL HESSAK] at [salma.elhessak@gmail.com].
