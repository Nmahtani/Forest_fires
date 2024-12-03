# Forest Fires ETL Project 

This project showcases a complete ETL (Extract, Transform, Load) pipeline using Python to analyze forest fire patterns and their relationship with climatic factors such as temperature, humidity, wind, and rainfall. 

## Table of Contents
- [Overview](#overview)
- [Dataset](#dataset)
- [Project Workflow](#project-workflow)
- [Technologies Used](#technologies-used)
- [Visualizations](#visualizations)
- [Acknowledgments](#acknowledgments)

---

## Overview
Forest fires have devastating effects on the environment, ecosystems, and communities. This project aims to:
- Analyze climatic factors contributing to forest fires.
- Visualize relationships between variables to identify patterns.
- Build a foundation for predictive modeling of fire risk in future extensions.

---

## Dataset
The dataset used in this project is **"Forest Fires Data"** from Kaggle, uploaded by [Elikplim](https://www.kaggle.com/datasets/elikplim/forest-fires-data). It contains information about forest fires, including:
- **Climatic factors**: temperature, humidity, wind, and rainfall.
- **Burned area**: the total area affected by the fire.

You can download the dataset [here](https://www.kaggle.com/datasets/elikplim/forest-fires-data) (requires a Kaggle account).

---

## Project Workflow
1. **Extract**:
   - Load the dataset using `pandas`.
2. **Transform**:
   - Clean and preprocess the data by:
     - Removing irrelevant columns (`day`, `month`).
     - Renaming columns for better clarity.
     - Categorizing fires by size and creating new metrics.
   - Handle missing values for a robust analysis.
3. **Load**:
   - Use `seaborn` and `matplotlib` for insightful visualizations:
     - Scatter plot to observe relationships.
     - Bar chart for distribution of fire categories.
     - Box plot to compare climate indices.

---

## Technologies Used
- **Programming Language**: Python
- **Libraries**:
  - `pandas`: Data manipulation and preprocessing.
  - `seaborn` and `matplotlib`: Data visualization.
  - `numpy`: Numerical computations.
- **Tools**:
  - Jupyter Notebook for running the project interactively.

---

## Visualizations
Here are some key visualizations generated in the project:

1. **Scatter Plot**: Relationship between temperature and burned area, categorized by fire size.
2. **Bar Chart**: Distribution of fire sizes across the dataset.
3. **Box Plot**: Weather index variability across fire categories.

---

## Acknowledgments
- Dataset sourced from [Kaggle](https://www.kaggle.com/).
- Special thanks to the Kaggle community for providing accessible datasets.

---

Feel free to fork, star ⭐, and contribute to this project. Happy coding! 😊
