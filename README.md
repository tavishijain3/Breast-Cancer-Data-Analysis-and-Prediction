# Breast Cancer Data Analysis and Prediction

This project focuses on performing Exploratory Data Analysis (EDA) on a Breast Cancer dataset to understand the underlying patterns, correlations, and insights. The dataset is used for prediction tasks, such as identifying benign or malignant tumors, and involves a structured approach to analyzing the features. The EDA is implemented following specific module-wise tasks and objectives, ensuring detailed statistical analysis and aesthetically appealing visualizations.

## Dataset Overview

The dataset used for this analysis is publicly available [here](https://raw.githubusercontent.com/salemprakash/EDA/main/Data/bcancer.csv). It contains various measurements of breast cancer cell nuclei from images and is typically used for diagnostic purposes (malignant or benign). The columns include features such as `radius_mean`, `texture_mean`, `smoothness_mean`, and many more, along with a `diagnosis` column indicating whether the tumor is malignant (1) or benign (0).

## Project Structure

The project is broken down into several modules:

### 1. Data Loading and Preprocessing
- Loaded the dataset from the specified URL.
- Checked the dataset structure, handled missing values, and dropped unnecessary columns (e.g., `Unnamed: 32`).
- Converted `diagnosis` into a binary categorical variable.

### 2. Exploratory Data Analysis (EDA)
- **Univariate Analysis**: Analyzed individual features, including measures of central tendency and dispersion. Plotted histograms, boxplots, and density plots for key features like `radius_mean`, `texture_mean`, etc.
- **Bivariate Analysis**: Examined relationships between pairs of variables using scatter plots, violin plots, and correlation heatmaps.
- **Multivariate Analysis**: Implemented scatter plots with multiple dimensions (size, hue, and shape), facet grids for better categorical analysis, and bubble plots.
  
### 3. Time Series Analysis (Adapted for Dataset)
- Although the dataset is not time-series, some tasks were adapted, including plotting and analyzing trends in the data.

### 4. 1D Statistical Data Analysis
- Applied measures of central tendency, dispersion, and visualizations like frequency distributions, cumulative frequency plots, and histograms.
- Analyzed categorical variables using pie plots and stacked bar charts.

### 5. Visualizations
- All visualizations use a custom dark purple and pink color palette to enhance readability and aesthetics.
- The project ensures that all plots are structured, neat, and easy to interpret with proper titles and axis labels.

### Tools & Libraries
- **Python** (Google Colab)
- **Libraries**: pandas, seaborn, matplotlib, numpy

### Features of EDA
- **Customized Visuals**: All graphs are carefully tailored for clarity, with a consistent color palette.
- **Statistical Insights**: Measures of central tendency, dispersion, and frequency distribution provide a comprehensive understanding of the dataset.
- **Advanced Plots**: Multivariate scatter plots, facet grids, and violin plots offer deeper insights into the relationships between features.

## Conclusion
This notebook demonstrates the application of various statistical and visualization techniques to analyze a breast cancer dataset. The insights drawn can be useful in building predictive models to classify breast cancer tumors more effectively.
