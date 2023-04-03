# House Prices - Advanced Regression Techniques

This repository contains my solution to the [House Prices - Advanced Regression Techniques](https://www.kaggle.com/c/house-prices-advanced-regression-techniques) competition on Kaggle. The goal of this competition is to predict the sale prices of homes in Ames, Iowa, using a dataset of 79 features.

My solution achieved a score of approximately 0.15 on the competition leaderboard.

## Data

The data for this competition can be downloaded from the [competition website](https://www.kaggle.com/c/house-prices-advanced-regression-techniques/data). In addition to the training and test datasets, I have also included a `data_description.txt` file that describes the meaning and possible values of each feature.

## Approach

My approach to this problem involved several steps:

1. Exploratory data analysis to understand the structure and distribution of the data.
2. Data preprocessing to handle missing values, convert categorical features to numerical features, and scale the data.
3. Feature engineering to create new features that capture important information in the data.
4. Model selection and hyperparameter tuning using cross-validation.
5. Ensemble learning to combine multiple models for improved performance.

I have documented each step in detail in the Jupyter Notebook.

## Results

My final submission achieved a score of approximately 0.15 on the competition leaderboard. This places me in the top 10% of participants at the time of writing.

## Dependencies

To run the Jupyter Notebook, you will need the following Python libraries:

- pandas
- numpy
- scikit-learn
You can install these libraries using `pip` or another package manager.

## Usage

To run the Jupyter Notebook, first install the required libraries using the command:

```sh
pip install -r requirements.txt
