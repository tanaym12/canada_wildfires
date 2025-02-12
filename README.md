# Canada Wildfires Analysis - STAT 201 Project

### By Charles Benkard, Hung Dinh, Tanay Mahendru, Kenny Zhou

## 1. Introduction
Wildfires are prevalent in Canada during the summer and cause ecological and humanitarian problems. They destroy homes, displace communities, and pose significant health risks due to air pollution. Additionally, wildfires impact old-growth forests and wildlife habitats. Various factors influence wildfire magnitude, including climate and management strategies, which differ by region. This project aims to analyze differences in wildfire sizes between British Columbia (BC) and Ontario (ON) to help with future mitigation efforts.

## 2. Research Question
**Which province, British Columbia or Ontario, experiences larger wildfires on average?**

## 3. Data Source
The dataset used in this project is obtained from an online source:

- **URL**: [Wildfire Dataset](https://gist.githubusercontent.com/hd54/d45ccf80e72b9c87dbc636fb9d33af93/raw/ec514840169031c4eff262d5c42474a44c8d728f/gistfile1.txt)
- The data includes information on wildfires reported by various agencies across Canada, filtered for BC and ON.

## 4. Methodology
We use R for data manipulation, visualization, and statistical inference. The analysis follows these steps:

1. **Data Cleaning**: Renaming columns and filtering for BC and ON.
2. **Exploratory Data Analysis (EDA)**: Visualizing distributions of wildfire sizes.
3. **Statistical Testing**: Conducting hypothesis testing using bootstrapping to compare wildfire sizes.
4. **Conclusion**: Summarizing findings and drawing insights.

## 5. Dependencies
To run this notebook, you need the following R libraries:
```r
library(cowplot)
library(dplyr)
library(gridExtra)
library(tidyverse)
library(repr)
library(infer)
library(scales)
library(broom)
```

## 6. Usage
1. Install the required R libraries if not already installed.
2. Download the dataset from the provided URL.
3. Run the Jupyter Notebook or R script to execute the analysis.

## 7. Results
The analysis compares wildfire sizes in BC and ON. The results include:
- Summary statistics and visualization of wildfire sizes.
- Statistical inference on differences between provinces.
- Potential factors influencing wildfire size variations.

## 8. Conclusion
This project provides insights into the wildfire size differences between BC and ON. The findings may help inform mitigation strategies and future research in wildfire management.

## 9. Authors
- Charles Benkard
- Hung Dinh
- Tanay Mahendru
- Kenny Zhou

## 10. Acknowledgments
This project was conducted as part of **STAT 201** coursework. Special thanks to our instructors and peers for their feedback.