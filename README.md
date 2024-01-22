# SteamGames
## Video Game Peak Concurrent User Prediction


=======
# Overview

This project is centered around the development of a machine learning pipeline aimed at predicting the Peak Concurrent User Count (Peak CCU) for video games. It encompasses a comprehensive approach, handling various aspects of machine learning including data acquisition, preprocessing, exploratory data analysis, and modeling. It focuses on the Steam gaming platform, a cornerstone in the digital gaming world operated by Valve Corporation. Since its inception in 2003, Steam has been a pivotal force in PC gaming, offering a rich and diverse library of games ranging from indie gems to blockbuster titles.
This project showcases the power of machine learning in providing meaningful insights in the gaming industry, particularly in understanding and predicting user engagement metrics like Peak CCU.

# Data
The dataset used for this project is a comprehensive collection of metadata for all games available on Steam. This includes crucial information like game titles, release dates, developers, publishers, user reviews, ratings, and system requirements, along with more nuanced data such as estimated owners, DLC count, and supported languages.

- Link to the dataset: https://www.kaggle.com/datasets/mexwell/steamgames/data

# Video Game Peak Concurrent User Prediction

## Key Features

- **Data Handling**: The initial stage involves gathering and cleaning data, ensuring a robust dataset for analysis.
- **Exploratory Data Analysis (EDA)**: Through histograms, box plots, and other visualization tools, the dataset is thoroughly analyzed to understand the underlying distributions and detect outliers.
- **Preprocessing and Feature Engineering**: Techniques such as imputation for handling missing values, categorical data processing, and outlier detection are integral parts of the project.
- **Modeling with CatBoostRegressor**: The project leverages CatBoostRegressor, an advanced machine learning algorithm, for building the predictive model.
- **Dimensionality Reduction with PCA**: Principal Component Analysis (PCA) is used to reduce the number of features while retaining essential information.
- **Optimization and Validation**: Various preprocessing strategies are experimented with to enhance the model's performance. The project uses cross-validation for model robustness and Optuna for hyperparameter tuning.
- **Model Evaluation**: The final model's performance is gauged on a test set, focusing on minimizing the Mean Absolute Error (MAE).
- **Deployment**: The trained model is saved and equipped for future predictions, demonstrating its practical applicability.

