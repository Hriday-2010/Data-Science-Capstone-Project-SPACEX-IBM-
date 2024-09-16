# IBM Data Science Capstone Project - SpaceX

This project is the final capstone for the IBM Data Science Professional Certificate. It focuses on analyzing and predicting the outcomes of SpaceX Falcon 9 rocket launches, with the goal of determining factors that contribute to successful landings and cost efficiency.

## Project Overview

SpaceX’s reusable rocket technology has significantly reduced space travel costs. However, ensuring the success of rocket landings is critical to their mission. This project uses real-world data to analyze launch outcomes and build predictive models.

## Objectives

- **Data Collection & Cleaning**: Gathered launch data from various sources, including APIs and web scraping.
- **Exploratory Data Analysis (EDA)**: Investigated patterns and trends in the data related to rocket success.
- **Feature Engineering**: Created meaningful features to improve model performance.
- **Model Development**: Developed machine learning models such as Logistic Regression, Decision Trees, Random Forest, and XGBoost.
- **Outcome Prediction**: Used models to predict whether future SpaceX launches will have successful landings.

## Key Steps

1. **Data Collection**: Used API calls and web scraping to gather the Falcon 9 launch dataset.
2. **Data Preprocessing**: Handled missing values, feature scaling, and data cleaning.
3. **EDA & Feature Engineering**: Conducted in-depth analysis to generate insights and select key features.
4. **Modeling**: Implemented and fine-tuned models, including:
   - Logistic Regression
   - Decision Trees
   - Random Forest
   - XGBoost
5. **Model Evaluation**: Evaluated the performance of the models using metrics such as accuracy, precision, recall, and F1-score.
6. **Optimization**: Fine-tuned hyperparameters for better accuracy and prediction.

## Results

- **Best Model**: The Random Forest and XGBoost models achieved the highest accuracy in predicting the success of rocket landings.
- **Key Factors**: Launch site, payload mass, and booster version were identified as significant predictors of successful landings.

## Tools & Technologies

- **Python**: Used for data analysis and model building.
- **Pandas, NumPy**: Data manipulation and analysis.
- **Matplotlib, Seaborn**: Data visualization.
- **Scikit-learn, XGBoost**: Machine learning algorithms.
- **Jupyter Notebook**: Development environment.
- **APIs & Web Scraping**: For data collection.

## Conclusion

This project provided valuable insights into the success factors of SpaceX's rocket launches, and the predictive models built could be used to further improve their mission success rates. The successful application of data science techniques to real-world data highlights the power of analytics in advancing space technology.

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/Hriday-2010/Data-Science-Capstone-Project-SPACEX-IBM-.git
