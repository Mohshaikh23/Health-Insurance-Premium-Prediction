# Health Insurance Premium Prediction and Analysis

This repository contains code and analysis for predicting health insurance premiums using a machine learning model. The project includes data preprocessing, exploration, feature mapping, visualization, and training a Random Forest Regressor model for premium prediction.

## Table of Contents

- [Introduction](#introduction)
- [Prerequisites](#prerequisites)
- [Data Exploration](#data-exploration)
- [Feature Engineering](#feature-engineering)
- [Machine Learning Model](#machine-learning-model)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Introduction

The goal of this project is to predict health insurance premiums using features such as age, sex, BMI, and smoking status. The machine learning model predicts insurance premiums based on these features, providing valuable insights for both insurers and insured individuals.

## Prerequisites

### Clone the repository

```bash
git clone https://github.com/Mohshaikh23/Health-Insurance-Premium-Prediction.git
```

Before running the code, ensure you have the required libraries installed:

- numpy
- pandas
- plotly
- scikit-learn

You can install them using the following command:

```bash
pip install numpy pandas plotly scikit-learn
```

## Data Exploration

The code begins by exploring the dataset using `pandas` methods like `head()`, `shape`, `info()`, and `describe()`. It checks for missing values and displays the distribution of smoker status and regions.

## Feature Engineering

The 'sex' and 'smoker' columns are mapped from string values to numerical values for model compatibility. The distribution of regions where people are living is visualized using a pie chart.

## Machine Learning Model

The data is split into training and test sets. After exploring different algorithms, a Random Forest Regressor is selected and trained using the training data. The model learns to predict health insurance premiums based on age, sex, BMI, and smoking status.

## Results

The trained model's predicted premium amounts are shown for the test dataset. This showcases how the model's predictions align with the actual premium values.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, feel free to open an issue or create a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
