🌦️ Weather Temperature Prediction Using Machine Learning

📌 Project Overview

Weather Temperature Prediction is a machine learning project that predicts temperature using various meteorological parameters, including humidity, wind speed, wind direction, visibility, atmospheric pressure, rainfall, and weather descriptions.

The project applies data preprocessing, exploratory data analysis, data visualization, and machine learning regression algorithms to understand the relationship between weather conditions and temperature.

🎯 Objectives

* Predict temperature using weather-related parameters.
* Perform data preprocessing and exploratory data analysis.
* Implement and compare different machine learning regression algorithms.
* Evaluate model performance using standard regression metrics.
* Visualize relationships between weather parameters and temperature.

📊 Dataset

The project uses a weather dataset containing approximately 10,000 records and 8 original attributes.

The dataset includes the following parameters:

* Humidity
* Wind Speed
* Wind Direction
* Visibility
* Atmospheric Pressure
* Rainfall
* Weather Description
* Temperature

Target Variable: Temperature_c

The dataset is preprocessed before training the machine learning models.

🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Seaborn
* Google Colab / Jupyter Notebook

⚙️ Project Workflow

1. Import the weather dataset.
2. Explore the dataset and examine its structure.
3. Check missing values, data types, and duplicate records.
4. Encode categorical weather descriptions.
5. Handle invalid atmospheric pressure values.
6. Separate input features and the target variable.
7. Split the dataset into training and testing sets.
8. Apply feature scaling.
9. Train and compare machine learning regression models.
10. Evaluate model performance using regression metrics.
11. Visualize relationships between weather parameters and temperature.

🤖 Machine Learning Algorithms

1. Linear Regression

A regression algorithm used to model the relationship between weather parameters and temperature.

2. K-Nearest Neighbors (KNN) Regression

Predicts temperature using the values of nearby observations in the feature space.

3. Support Vector Regression (SVR)

Uses support vector techniques to model relationships between input weather parameters and temperature.

📈 Model Evaluation

The models are evaluated using the following metrics:

* R² Score: Measures how well the model explains variations in temperature.
* Mean Absolute Error (MAE): Measures the average absolute prediction error.
* Mean Squared Error (MSE): Measures the average squared prediction error.
* Root Mean Squared Error (RMSE): Measures prediction error while retaining the target variable’s units.

Reported Model Results

Algorithm	R² Score
Linear Regression	86.40%
K-Nearest Neighbors (KNN)	86.30%
Support Vector Regression (SVR)	87.77%

Based on the reported results, Support Vector Regression achieved the highest R² score of approximately 87.77%.

These results are based on the existing project code and reported evaluation results.

📉 Data Visualization

The project uses regression plots to explore relationships between temperature and:

* Rainfall
* Humidity
* Wind Speed
* Wind Direction
* Visibility
* Atmospheric Pressure

🚀 How to Run the Project

Prerequisites

* Python 3.10 or later
* pip
* Jupyter Notebook or Google Colab

Installation

1. Clone this repository:

git clone https://github.com/YOUR_USERNAME/YOUR_REPOSITORY.git

2. Open the project directory.
3. Install the required libraries:

pip install -r requirements.txt

4. Place the weather dataset in the appropriate location.
5. Open the notebook in Google Colab or Jupyter Notebook.
6. Update the dataset path in the code to match your environment.
7. Run the notebook cells in order to preprocess the data, train the models, and evaluate their performance.

🔮 Future Improvements

* Improve data preprocessing and feature scaling.
* Perform hyperparameter tuning.
* Compare additional machine learning algorithms.
* Use larger and more diverse weather datasets.
* Develop a user-friendly interface for temperature prediction.
* Explore real-time weather data integration.

📝 Conclusion

This project demonstrates how machine learning can be applied to weather data for temperature prediction.

By implementing Linear Regression, KNN Regression, and Support Vector Regression, the project compares different approaches to predicting temperature.

The reported results indicate that Support Vector Regression performed best among the three evaluated models.

👨‍💻 Project Information

Project Name: Weather Temperature Prediction Using Machine Learning
Domain: Machine Learning and Data Science
Programming Language: Python
Problem Type: Regression
Target Variable: Temperature

⸻

Developed as a machine learning project to explore weather data analysis and temperature prediction.
