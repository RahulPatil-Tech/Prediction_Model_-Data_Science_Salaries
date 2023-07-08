# Prediction_Model_-Data_Science_Salaries
This repository contains a prediction model for data science salaries from 2020 to 2030. The model uses historical salary data and applies a machine learning algorithm to forecast future salary trends in the field of data science.

# Dataset
The dataset used for training and evaluating the prediction model is not included in this repository due to privacy and licensing concerns. However, a sample dataset with anonymized salary information can be obtained from Kaggle.

The dataset contains the following columns:
1. <b>Year</b>: The year of the salary record.</br>
2. <b>Experience</b>: The number of years of experience of the data scientist.</br>
3. <b>Education</b>: The highest level of education completed by the data scientist.</br>
4. <b>Skills</b>: A comma-separated list of skills possessed by the data scientist.</br>
5. <b>Salary</b>: The annual salary of the data scientist.</br>

# Dependencies
The following dependencies are required to run the prediction model:

Python 3.7 or above
NumPy
Pandas
Scikit-learn

# Usage
To use the prediction model, follow these steps:
1. Clone the repository:
```shell
git clone https://github.com/yourusername/prediction-model.git
cd prediction-model
```
2. Install the required dependencies:

```shell
pip install -r requirements.txt
```
3. Obtain the dataset and place it in the repository's root directory.
```shell
python predict_salary.py
```
The script will load the dataset, preprocess the data, train the prediction model, and generate salary predictions for the years 2020 to 2030.

# Model Evaluation
The prediction model is evaluated using various metrics such as mean squared error (MSE), mean absolute error (MAE), and R-squared (R^2) score. The evaluation results are displayed in the notebook, along with visualizations of the predicted salary trends.

# Future Work
While this prediction model provides valuable insights into data science salary trends, there are several avenues for future improvement and exploration. Some potential areas of future work include:
1. Incorporating additional features such as job titles, specific industry sectors, and company size to enhance the model's predictive capabilities.</br>
2. Collecting and incorporating more recent salary data to improve the accuracy and relevance of the predictions.</br>
3. Exploring advanced machine learning techniques and algorithms, such as neural networks, to potentially achieve better predictive performance.</br>

# Contributing
Contributions to this prediction model are welcome. If you have any suggestions, improvements, or bug fixes, please submit a pull request. For major changes, please open an issue to discuss the proposed modifications.

# License
This prediction model is released under the <b>MIT License</b>.[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

# Disclaimer
The predictions made by this model are based on historical data and machine learning algorithms. They should be used as general guidelines and not as definitive salary forecasts. The model's accuracy may vary based on various factors, and it is advised to consider other factors, such as economic conditions and market trends, when making decisions regarding salaries.
