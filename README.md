## Water-Potability-Prediction-with-ML-Classification
This project explores the application of Machine Learning (ML) to predict water potability, leveraging two popular algorithms: K-Nearest Neighbors (KNN) and Random Forest Classification. By analyzing various physical and chemical properties of water.

## Table of Contents

- [Introduction](#introduction)
- [Objectives](#objectives)
- [Dataset](#dataset)
- [Dataset Description](#dataset-description)
- [Project Structure](#project-structure)
- [Methodology](#methodology)
- [Results](#results)
- [Conclusion](#conclusion)
- [License](#license)
- [How to Use](#how-to-use)
- [Contributing](#contributing)

## Introduction

Water quality is a critical factor in maintaining human health and ensuring the sustainability of environmental resources. This project employs machine learning algorithms, specifically K-Nearest Neighbors (KNN) and Random Forest Classification, to predict the potability of water. By analyzing various physical and chemical properties of water, the project aims to provide a scalable and efficient solution for assessing water quality, especially in areas lacking access to standard testing facilities.

## Objectives

- Train machine learning models on water quality data to predict potability.
- Compare the performance of KNN and Random Forest algorithms in predicting water potability.
- Identify the most effective model for future deployment in water quality assessments.

## Dataset

The project utilizes the Water Potability Dataset made available by MainakRepositor, comprising various parameters related to water quality to evaluate its suitability for human consumption.

**Data Source:** [Water Potability Dataset](https://github.com/MainakRepositor/Datasets/blob/master/water_potability.csv) by MainakRepositor. 

### Dataset Description

Each entry in the dataset represents a water sample analyzed based on the following parameters:

- **pH**: Measures the acidity or alkalinity of the water on a scale from 0 to 14.
- **Hardness**: The concentration of calcium and magnesium in water, measured in mg/L.
- **Solids**: Total dissolved solids (TDS) in water, measured in ppm (parts per million).
- **Chloramines**: The amount of chloramines (chlorine and ammonia) in water, measured in mg/L.
- **Sulfate**: Concentration of sulfate ions in water, measured in mg/L.
- **Conductivity**: The electrical conductivity of water, indicating the ion concentration, measured in μS/cm.
- **OrganicCarbon**: Total organic carbon (TOC) in water, measured in mg/L.
- **Trihalomethanes**: Chemical byproducts formed by the reaction of chlorine with natural organic matter in water, measured in μg/L.
- **Turbidity**: The clarity of water, measured in NTU (Nephelometric Turbidity Units).
- **Potability**: A binary indicator where 1 denotes potable (safe for drinking) and 0 denotes not potable.


## Project Structure

1. **Library Importation**: Setup of the Python environment with necessary libraries.
2. **Dataset Importation**: Loading the water potability data from a CSV file.
3. **Data Analysis**: Employing descriptive statistics and data visualization for an in-depth understanding of the dataset.
4. **Data Pre-processing**: Cleaning and preparing the data for analysis.
5. **Model Training**: Applying machine learning algorithms to the training data.
6. **Model Evaluation**: Assessing model performance using precision, recall, and confusion matrices.

## Methodology

The methodology includes data pre-processing, exploration, outlier handling, and machine learning model training and evaluation, specifically focusing on KNN and Random Forest algorithms.

## Results

The project's findings indicate that the Random Forest Classifier outperforms the KNN model across all evaluation metrics, demonstrating higher efficiency in classifying water's potability.

## Conclusion

The Random Forest model, with its superior performance, is recommended for future deployment in water quality classification tasks. Its effectiveness in accurately identifying potable and non-potable water samples underscores its reliability for practical applications.

## License

This project is open source and available under the [MIT License](LICENSE), promoting free use, modification, and distribution of the software, ensuring that contributions are welcomed and recognized.

## How to Use

1. Clone this repository.
2. Install required libraries
3. Execute the Jupyter notebooks to interact with the datasets and models.
4. Modify and experiment with the models as per your dataset and requirements.

## Contributing

Feel free to contribute by submitting pull requests, suggesting improvements, or reporting issues. Your contributions will help improve the project and benefit the community.

