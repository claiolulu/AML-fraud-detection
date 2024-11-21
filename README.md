
# AML Fraud Detection Project README

## Overview

This project focuses on fraud detection on user transaction data utilizing machine learning and data engineering approaches. Specifically, it aims to enhance anti-money laundering (AML) efforts by leveraging feature engineering and supervised machine learning models, such as Random Forest and XGBoost, applied to synthetic financial transaction data. The study primarily works with the AMLSim synthetic dataset to simulate realistic transaction behaviors and identify suspicious patterns. Feature engineering is a key component, helping improve model accuracy and interpretability by creating new insights from raw data. The project also explores different sampling techniques to address data imbalances and evaluates the impact of engineered features on model performance.

This repository contains a Jupyter Notebook titled `Data.ipynb`, which performs data analysis using Python. The notebook provides insights by exploring, transforming, and visualizing data to help users better understand the dataset. The project is intended for anyone interested in exploring data with Python, particularly using common data science libraries.


## Requirements

To run this notebook, you need to have the following software and libraries installed:

- **Python 3.6+**
- **Jupyter Notebook** or **JupyterLab**
- **Pandas** for data manipulation
- **NumPy** for numerical operations
- **Matplotlib** or **Seaborn** for data visualization

You can install the required packages using pip:

```sh
pip install pandas numpy matplotlib seaborn jupyter
```

## Usage

To run the notebook, follow these steps:

1. **Clone the Repository**: First, clone this repository to your local machine.
   ```sh
   git clone <repository-url>
   ```

2. **Navigate to the Directory**: Change into the directory containing the notebook.
   ```sh
   cd <repository-directory>
   ```

3. **Launch Jupyter Notebook**: Start Jupyter Notebook to open and interact with `Data.ipynb`.
   ```sh
   jupyter notebook
   ```

4. **Open the Notebook**: In the browser window that opens, click on `Data.ipynb` to view and execute the cells.

## Contents

- **Data Loading**: The notebook starts by importing the dataset using Pandas.
- **Data Cleaning**: It includes data preprocessing steps such as handling missing values and transforming data types.
- **Exploratory Data Analysis (EDA)**: Various visualizations and descriptive statistics are used to analyze the dataset.
- **Feature Engineering**: Feature engineering plays a critical role in improving the performance of machine learning models by transforming raw data into informative features.
- **Modeling**: Machine learning models such as Random Forest and XGBoost are used to predict fraudulent transactions. These models are trained and evaluated on engineered features and synthetic transaction data.
- **Evaluation**: The notebook uses metrics like precision, recall, F1-score, and confusion matrices to evaluate model performance, with particular attention to the impact of feature engineering.

## Customization

You can modify the notebook to work with your own dataset by changing the file path and adjusting the data cleaning and visualization steps accordingly.

## Contributing

Feel free to contribute to this project by forking the repository and submitting pull requests. Any suggestions to improve the analysis or expand on existing content are welcome.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

## Contact

If you have any questions or feedback, feel free to contact the repository owner via email or open an issue on the GitHub page.
