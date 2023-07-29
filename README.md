

# Logistic Regression Project: Predicting Ad Clicks

## Overview

In this project, I worked with an advertising dataset to predict whether a particular internet user would click on an advertisement based on various user features. The main goal was to create a logistic regression model that could accurately predict ad clicks based on user characteristics.

## Dataset

The dataset used for this project contains the following features:

- 'Daily Time Spent on Site': consumer time on the site in minutes
- 'Age': customer age in years
- 'Area Income': average income of the geographical area of the consumer
- 'Daily Internet Usage': average minutes a day consumer is on the internet
- 'Ad Topic Line': headline of the advertisement
- 'City': city of the consumer
- 'Male': whether or not the consumer was male (binary: 0 or 1)
- 'Country': country of the consumer
- 'Timestamp': time at which the consumer clicked on the ad or closed the window
- 'Clicked on Ad': target variable, 0 or 1 indicating clicking on the ad

## Project Steps

1. Data Exploration: I began by exploring the dataset to gain insights into the data distribution, identify any missing values, and understand the relationship between different features.

2. Data Preprocessing: After analyzing the dataset, I performed data preprocessing steps such as handling missing values, encoding categorical variables, and splitting the data into training and testing sets.

3. Gradient Descent Algorithm: Instead of relying solely on pre-built libraries, I implemented my own logistic regression algorithm using gradient descent from scratch. This allowed me to have a better understanding of the optimization process and fine-tune the model accordingly.

4. Model Training: I trained the logistic regression model on the training data using the custom gradient descent algorithm and tuned the hyperparameters to achieve optimal performance.

5. Model Evaluation: Next, I evaluated the model's performance on the test dataset, calculating accuracy and other relevant metrics. I compared the results with the accuracy obtained using scikit-learn's logistic regression implementation to validate the correctness of my custom algorithm.

6. Results: The logistic regression model achieved an impressive accuracy of 97%, which was in line with the accuracy obtained using scikit-learn's logistic regression.

## How to Use

To run this project on your machine, follow these steps:

1. Clone the repository to your local machine using the following command:

```
git clone https://github.com/Rohith-pamidimarri/logistic-regression-ad-clicks.git
```

2. Navigate to the project directory:

```
cd logistic-regression-ad-clicks
```

3. Ensure you have the required dependencies installed. You can install them using the following command (if not already installed):

```
pip install -r requirements.txt
```

4. Open and run the Jupyter notebook `Logistic_Regression_Ad_Clicks.ipynb`. This notebook contains the entire project code, from data preprocessing to model evaluation.

5. You can modify and experiment with the code to explore different aspects of the project or try different algorithms for comparison.

## Contributing

I welcome contributions and feedback! If you find any issues or have suggestions for improvement, please feel free to open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

Let's stay connected and keep learning together! 🚀 #MachineLearning #DataScience #LogisticRegression #AI #DataAnalysis

---
