# Global Climate Data Analysis

## Overview

This project provides an in-depth analysis of global climate, agricultural, and environmental data. The dataset includes information on geospatial coordinates, climate variables, air quality measures, natural disasters, sun and moon phases, and agricultural categories. Tools used for data processing, analysis, and visualization include Jupyter Notebook, PgAdmin, Power BI, and MS Excel.

## Dataset

- **Rows**: 28,731
- **Columns**: 51
- **Categories**:
  - Geospatial Information
  - Climate Variables
  - Air Quality Measures
  - Natural Disasters
  - Sun and Moon Phases
  - Agricultural Categories

## Project Steps

### 1. Data Preprocessing and EDA
- **Tools Used**: Jupyter Notebook, PgAdmin, MS Excel
- **Tasks**:
  - Reverse geocoding to populate country information
  - Adding calculated columns
  - Generating a correlation matrix



### 2. Key Data Queries
Using PostgreSQL, we explored relationships and patterns, including:
- **Temperature vs. Air Quality**
- **Sunrise and Sunset Extremes**
- **Average Monthly Temperature by Country**
- **Natural Disaster Counts by Type**
- **Weather Condition Frequency by Location**



### 3. Principal Component Analysis (PCA) and Clustering
- **PCA**: Conducted on July and September data to reduce dimensions while preserving variability.
- **Clustering**: Used the Elbow Method with K-means to determine the optimal number of clusters.



### 4. Data Visualization
- **Tool**: Power BI
- **Dashboard**: Interactive dashboard to visualize key insights from the dataset.

![Screenshot 2024-11-10 182014](https://github.com/user-attachments/assets/bb7d637c-33c4-4cbb-a52d-fe3b70963142)


## Technologies Used
- **Jupyter Notebook**: Data processing and analysis
- **PgAdmin**: Database queries
- **Power BI**: Visualization
- **MS Excel**: Data inspection and manual adjustments

## Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/MetaksyaA/Global_Clomate_Data_Analysis.git
