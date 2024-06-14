


# Wine Quality Prediction
![](https://github.com/Devesh061102/09-Wine-Quality-MlFlow/blob/main/Screenshots/Screenshot_14-6-2024_163449_127.0.0.1.jpeg?raw=true)

![](https://github.com/Devesh061102/09-Wine-Quality-MlFlow/blob/main/Screenshots/Screenshot_14-6-2024_163514_127.0.0.1.jpeg?raw=true)

## Objective
The main objective of this project is to analyze various factors influencing wine quality and develop a predictive model to forecast wine quality based on these factors.

## Data Collection
The project starts with collecting a dataset of wine quality.

## Dataset
The dataset used is sourced from [Kaggle](https://www.kaggle.com/datasets/yasserh/wine-quality-dataset/data). It includes physicochemical properties of wine and their quality scores. The dataset contains the following columns:

- **Input variables (based on physicochemical tests):**
  1. Fixed Acidity
  2. Volatile Acidity
  3. Citric Acid
  4. Residual Sugar
  5. Chlorides
  6. Free Sulfur Dioxide
  7. Total Sulfur Dioxide
  8. Density
  9. pH
  10. Sulphates
  11. Alcohol
- **Output variable (based on sensory data):**

  12. Quality (score between 0 and 10)

## Preprocessing
- Inspecting data for missing values and duplicates
- Cleaning data and converting data types as necessary
- Descriptive statistics and initial visualizations

## Exploratory Data Analysis (EDA)
- Distribution analysis of wine quality scores
- Analyzing relationships between different physicochemical properties and quality scores
- Correlation heatmap to identify significant correlations

## Model Training
- **Data Preparation:** Splitting the dataset into features (X) and target variables (y), encoding categorical variables (if any), and standardizing numerical variables
- **Model Selection:** Training and evaluating an Elastic Net regression model to predict wine quality
- **Model Evaluation:** Using metrics like R² score, Mean Absolute Error (MAE), and Mean Squared Error (MSE) to evaluate model performance

## Evaluation
The Elastic Net model is evaluated based on its predictive performance, and the best-performing model is selected for deployment.

## Model Deployment
The best-performing model is deployed using Flask, a lightweight web server gateway interface (WSGI) web application framework. This allows the model to be accessed via a simple web interface, enabling real-time predictions.

## Lessons Learned
This project provided a valuable opportunity to apply data science concepts to a practical problem. Key lessons learned include:
- The importance of data cleaning and preprocessing in ensuring accurate analysis
- How to use regression models, particularly Elastic Net, and evaluate their performance
- The critical role of feature engineering in improving model accuracy
- Insights into the factors that influence wine quality

I’m excited about the potential applications of this project and look forward to exploring more ways to leverage data science in the field of wine production and quality control. 🍷

## Authors
- [Devesh](https://github.com/Devesh061102)

