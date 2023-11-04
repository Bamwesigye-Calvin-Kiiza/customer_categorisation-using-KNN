# Telecommunications Customer Segmentation using K-Nearest Neighbors (KNN)

## Overview

This repository contains code and a dataset for building a classification model to predict customer segmentation based on demographic data. The goal is to categorize customers into one of four groups (Basic Service, E-Service, Plus Service, Total Service) using K-Nearest Neighbors (KNN) algorithm.

## Dataset
### Downloading the Dataset

The dataset is hosted online. You can download it using the following link:

[teleCust1000t.csv](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-ML0101EN-SkillsNetwork/labs/Module%203/data/teleCust1000t.csv)


The dataset contains demographic information including features like region, age, and marital status. The target variable, `custcat`, has four possible values representing the customer groups.

## Dependencies

- Python 3.8>
- Libraries: pandas, scikit-learn,numpy,matplotlib,seaborn

## Files

- `customer_categorisation _using_KNN.ipynb`: Jupyter notebook containing the code for data preprocessing, model training, and evaluation.

## Usage

1. Clone the repository

2. Navigate to the project directory

3. Install the required libraries
5. Follow the instructions in the notebook/script to preprocess the data, train the KNN classifier, and evaluate the model.

## Results

The trained KNN model can be used to predict the customer segmentation of new or unknown cases based on their demographic data.

## Notes

- The dataset used in this project is synthetic and for demonstration purposes only.
- Feel free to replace it with your own dataset for real-world applications.

## Acknowledgments

- This project is inspired by the need for personalized customer offerings in the telecommunications industry.

