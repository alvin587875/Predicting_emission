# NPRI Emissions Prediction

This project predicts future emissions for various industries using data from the National Pollutant Release Inventory (NPRI). The work involves data exploration, visualization, preprocessing, and training machine learning models to provide accurate forecasts.

## Table of Contents

1. [Project Overview](#project-overview)
2. [Team Members](#team-members)
3. [Technologies Used](#technologies-used)
4. [Project Structure](#project-structure)
5. [Key Features](#key-features)
6. [How to Run Locally](#how-to-run-locally)

## Project Overview

Using NPRI data, this project aims to provide insights into industry emissions trends and predict future levels. Models such as Linear Regression and Random Forest Regressor were employed for this purpose, and the best-performing models were evaluated and saved for deployment.

## Team Members

- **Lovepreet Kanur LNU**
- **Getachew TELIA**
- **Alvin Mathew**

## Technologies Used

- **Python**
- **Pandas** and **NumPy** for data manipulation
- **Matplotlib** and **Seaborn** for visualization
- **Scikit-learn** for machine learning models and preprocessing
- **Jupyter Notebooks** for interactive development

## Project Structure

```plaintext
├── data/                  # Raw and processed datasets
├── notebooks/             # Jupyter notebooks for EDA and modeling
├── models/               # Saved machine learning models
├── README.md             # Project documentation
├── requirements.txt      # Project dependencies
```

## Key Features

- **Data Exploration**: Visualizations and summaries of emissions trends and patterns.
- **Data Preprocessing**: Handling missing values, encoding categorical variables, and scaling numerical features.
- **Model Training**: Linear Regression and Random Forest Regressor were implemented and evaluated.
- **Evaluation Metrics**: Models were assessed using RMSE and other performance metrics.

## How to Run Locally

### Prerequisites

- Python 3.8 or above
- Required libraries listed in `requirements.txt`

### Steps

1. Clone this repository:

   ```bash
   git clone <repository_url>
   cd <repository_folder>
   ```

2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Open Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

4. Run the EDA and Modeling notebooks sequentially.

---

For any issues or suggestions, please open an issue in this repository. Thank you!

