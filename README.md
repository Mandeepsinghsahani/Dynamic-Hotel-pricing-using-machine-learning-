# Dynamic Pricing for Hotels using Machine Learning

## Project Overview
This project explores the application of machine learning models, specifically Random Forest and XGBoost, to develop an optimized pricing strategy for predicting the Average Daily Rate (ADR) in hotels. Using a sample of over 119,000 hotel reservation records, the study investigates the interrelationship between various booking and hotel characteristics (e.g., lead time, stay duration, market segment, and deposit type) and ADR. The goal is to enhance revenue optimization, increase occupancy levels, and implement competitive pricing mechanisms.

## Table of Contents
- [Project Overview](#project-overview)
- [Project Structure](#project-structure)
- [Getting Started](#getting-started)
- [Data Preprocessing](#data-preprocessing)
- [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
- [Feature Engineering](#feature-engineering)
- [Model Training](#model-training)
- [Model Evaluation](#model-evaluation)
- [Results](#results)
- [Conclusion](#conclusion)

## Getting Started

### Prerequisites
1. Python 3.8 or higher
2. Jupyter Notebook
3. Required libraries listed in `requirements.txt`

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/Mandeepsinghsahani/Dynamic-Hotel-pricing-using-machine-learning-.git
   cd hotel_dynamic_pricing
   ```

2. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

### Running the Project
1. **Data Preprocessing**: Run the `1_data_preprocessing.ipynb` notebook to preprocess the data.
2. **Exploratory Data Analysis**: Run the `2_exploratory_data_analysis.ipynb` notebook to perform EDA.
3. **Feature Engineering**: Run the `3_feature_engineering.ipynb` notebook to create new features.
4. **Model Training**: Run the `4_model_training.ipynb` notebook to train the models.
5. **Model Evaluation**: Run the `5_model_evaluation.ipynb` notebook to evaluate the models.

## Data Preprocessing
In this step, the dataset is loaded, missing values are handled, and initial preprocessing is performed. The processed data is saved for further analysis.

## Exploratory Data Analysis (EDA)
EDA involves visualizing the data to understand trends and relationships. This step helps in identifying important features and preparing the data for modeling.

## Feature Engineering
New features are created to enhance model performance. One-hot encoding is applied to categorical variables, and other relevant features are engineered.

## Model Training
Random Forest and XGBoost models are trained to predict ADR. The training process includes splitting the data into training and testing sets and optimizing the models.

## Model Evaluation
The models are evaluated using RMSE and R² metrics. Visualizations are created to compare true vs. predicted ADR values.

## Results
The results indicate that machine learning algorithms, particularly XGBoost, significantly improve pricing accuracy. The evaluation metrics for both models are provided in the `model_performance.html` report.

## Conclusion
The project demonstrates the effectiveness of machine learning models in dynamic pricing for hotels. By leveraging data-driven approaches, hotels can optimize revenue, increase occupancy levels, and maintain competitive pricing strategies.
