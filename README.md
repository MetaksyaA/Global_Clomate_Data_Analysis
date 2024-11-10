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
![Screenshot 2024-11-10 181617](https://github.com/user-attachments/assets/c00d0344-9757-441b-946a-7d2f29c92598)



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
![Screenshot 2024-11-10 185545](https://github.com/user-attachments/assets/9dd9fde1-16ba-4cc1-a0bb-4188d3265245)

![Screenshot 2024-11-10 185605](https://github.com/user-attachments/assets/4afbb935-c7c9-4253-8f24-d6523c4f7005)


![Screenshot 2024-11-10 185403](https://github.com/user-attachments/assets/6ed5fc31-3e04-43fa-8e38-f2db16ec3a1b)

![Screenshot 2024-11-10 185423](https://github.com/user-attachments/assets/73590ba5-618a-4293-9321-788ae845baf1)

![Screenshot 2024-11-10 185351](https://github.com/user-attachments/assets/f5f58fca-05c4-4c0f-8372-2a7b0092e025)


### 4. Data Visualization
- **Tool**: Power BI
- **Dashboard**: Interactive dashboard to visualize key insights from the dataset.

![Screenshot 2024-11-10 182014](https://github.com/user-attachments/assets/bb7d637c-33c4-4cbb-a52d-fe3b70963142)

![Screenshot 2024-11-10 182039](https://github.com/user-attachments/assets/3efd0a7f-bd30-46eb-8b1e-626532e38fdd)

![Screenshot 2024-11-10 182057](https://github.com/user-attachments/assets/1753b1a2-4277-4a1a-9146-4c7b37f74773)

![Screenshot 2024-11-10 182113](https://github.com/user-attachments/assets/abcc5573-84d2-444a-b079-441b047bd951)

![Screenshot 2024-11-10 182127](https://github.com/user-attachments/assets/d14354b4-6744-4a02-b0db-4cd5f2fa66d8)






## Technologies Used
- **Jupyter Notebook**: Data processing and analysis
- **PgAdmin**: Database queries
- **Power BI**: Visualization
- **MS Excel**: Data inspection and manual adjustments

## Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/MetaksyaA/Global_Clomate_Data_Analysis.git
