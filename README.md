# Global Economic and Climate Impact Analysis

This data analysis project explores the relationship between global economic trends and climate change. It leverages data from sources like Meta, NOAA (National Oceanic and Atmospheric Administration), and the World Happiness Report to provide insights into how economic factors correlate with climate impact across various regions.

## 📊 Project Overview

### Data Sources:
- **Meta**: Social media data for analyzing global trends.
- **NOAA**: Climate data, including temperature, precipitation, and other climate metrics.
- **World Happiness Report**: Economic and social indicators linked to the quality of life and well-being.

### Analysis Focus:
- Investigating the correlation between economic indicators (such as GDP, employment rates) and climate metrics (like temperature changes, carbon emissions).
- Analyzing how these relationships vary by region and over time.
  
### Deliverables:
- Cleaned and modeled data sets.
- Visualizations that depict global economic and climate patterns.
- Insights into the interconnections between economic and climate trends.

## 💻 Technologies Used

### Language:
- **R**: The main language used for data analysis, visualization, and modeling.

### Libraries:
- **tidyverse**: A collection of R packages for data manipulation and visualization, including `ggplot2`, `dplyr`, and `tidyr`.
- **tidymodels**: A framework for building and evaluating machine learning models in R.
- **arrow**: For reading and writing Arrow-based data formats, enabling efficient data handling.
- **readxl**: For reading Excel files into R.
- **writexl**: For writing data frames to Excel files.
- **openxlsx**: Provides advanced Excel file manipulation capabilities.
- **repurrrsive**: Includes the `purrr` package for enhancing functional programming in R.
- **jsonlite**: For parsing and working with JSON data.
- **scales**: Used for scaling continuous variables and formatting labels for plots.
- **patchwork**: Allows combining multiple `ggplot2` plots into one cohesive visual.
- **ggrepel**: Adds labels to `ggplot2` plots, avoiding overlap and improving readability.
- **ggthemes**: Provides additional themes and scale functions for `ggplot2` plots.
- **ggridges**: For creating ridge plots that visualize distributions of continuous variables.
- **RColorBrewer**: A tool for selecting and applying color palettes to plots.
- **ggplot2**: A fundamental library for data visualization in R, used to create static, interactive, and animated plots.
- **sf**: For handling and analyzing spatial data, allowing you to work with geographic coordinates and features.

### Tools:
- **Excel**: Used for initial data handling, formatting, and basic analysis.

## 📂 Getting Started

### Prerequisites:
1. Install **R** and **RStudio** if you haven't already. You can download R from [here](https://cran.r-project.org) and RStudio from [here](https://rstudio.com/products/rstudio/download/).
2. Install the necessary R libraries. You can do this by running the following commands in RStudio:

```r
install.packages("tidyverse")
install.packages("tidymodels")
install.packages("arrow")
install.packages("readxl")
install.packages("writexl")
install.packages("openxlsx")
install.packages("repurrrsive")
install.packages("jsonlite")
install.packages("scales")
install.packages("patchwork")
install.packages("ggrepel")
install.packages("ggthemes")
install.packages("ggridges")
install.packages("RColorBrewer")
install.packages("ggplot2")
install.packages("sf")

