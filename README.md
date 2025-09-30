# ML-Regression-Project
# Energy Consumption Prediction Project

## Project Description

This repository contains a data analysis and machine learning project focused on predicting **Energy Consumption** based on various environmental and occupancy factors. The analysis and model development are performed within a **Jupyter Notebook** (`EnergyConsumptionProject.ipynb`) using Python's scientific computing stack.

The goal of this project is to build a reliable predictive model (likely **Linear Regression**, based on the notebook's imports) that can estimate energy usage based on parameters like temperature, humidity, and building occupancy.


## Files in this Repository

| File Name | Description |
| :--- | :--- |
| **EnergyConsumptionProject.ipynb** | The main Jupyter Notebook containing the data loading, cleaning, exploratory data analysis (EDA), model training, and evaluation steps. |
| **Energy\_Consumption dataset.xlsx - Sheet1.csv** | The primary dataset used for this analysis. It contains features such as `Month`, `Hour`, `Temperature`, `Humidity`, `Occupancy`, `HVACUsage`, `LightingUsage`, and the target variable, `EnergyConsumption`. |
| **README.md** | This file, providing an overview and instructions for the project. |


## Project Methodology (As seen in the Notebook)

The `EnergyConsumptionProject.ipynb` notebook generally follows these steps:

1.  **Data Loading:** The **CSV file** is loaded into a pandas DataFrame.
2.  **Data Preprocessing:** Steps may include handling categorical variables (e.g., `DayOfWeek`, `Holiday`, `HVACUsage`) using encoding, checking for missing values, and scaling numerical features using **StandardScaler**.
3.  **Exploratory Data Analysis (EDA):** Visualizations and statistics to understand the relationship between input features and energy consumption.
4.  **Model Training:** The data is split into training and testing sets, and a **Linear Regression** model from `sklearn` is trained.
5.  **Model Evaluation:** The model's performance is assessed using metrics like **Mean Squared Error (MSE)** and the **R-squared score** to determine its predictive accuracy.


## Prerequisites

To run the notebook locally or in a cloud environment like Google Colab, you need a Python environment with the following libraries:

* **pandas**
* **numpy**
* **matplotlib**
* **scikit-learn** (`sklearn`)
* **openpyxl** (Often needed to read the original Excel file, though the CSV is provided)

### Installation

You can install the required libraries using `pip`:

```bash
pip install pandas numpy matplotlib scikit-learn openpyxl
