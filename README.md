## Recipe Rating Prediction with Machine Learning

This project explores and prepares a dataset containing recipe ratings for machine learning model training.  The goal is to build a model that can predict the rating a user will give to a recipe based on various features.

### Table of Contents

* Project Overview: #project-overview
* Data Exploration and Cleaning: #data-exploration-and-cleaning
* Feature Engineering: #feature-engineering
* Text Processing for Reviews: #text-processing-for-reviews
* Getting Started: #getting-started
* Usage: #usage
* Contributing: #contributing
* License: #license

### Project Overview

This project provides a framework for preparing a recipe rating dataset for machine learning. It performs the following tasks:

* **Data Loading:** Reads training and test data from CSV files.
* **Data Exploration:** Analyzes numerical data using descriptive statistics and visualizations.
* **Data Cleaning:** Identifies and removes outliers using IQR method.
* **Feature Scaling:** Standardizes numerical features for improved model performance.
* **Text Processing:** Converts review text into numerical features using TF-IDF vectorization.

This prepared data can be used to train various machine learning models to predict recipe ratings.


### Data Exploration and Cleaning

The code explores the data to understand its distribution and identify any potential issues. It then utilizes the Interquartile Range (IQR) method to detect and remove outliers that might negatively impact model training.

### Feature Engineering

This section currently focuses on feature scaling, where numerical features are transformed to have a standard normal distribution (mean 0 and standard deviation 1). This helps machine learning algorithms treat all features equally.


### Text Processing for Reviews

The reviews are preprocessed by combining them from training and test data. TF-IDF vectorization is used to convert the textual reviews into numerical features, capturing the importance of words within the dataset. These transformed features are then added back to the original data for model training.


### Getting Started

1. **Clone the repository:**

```bash
git clone https://https://github.com/arch-adi21/User-Rating-ML.git
```

2. **Install dependencies:**

   - Make sure you have Python 3 and `pip` installed.
   - Run the following command in the project directory:

   ```bash
   pip install -r requirements.txt
   ```


### Usage

This script focuses on data preparation. You can modify the script to train your desired machine learning model using libraries like scikit-learn or TensorFlow. 


### Contributing

We welcome contributions to this project! Feel free to fork the repository and submit pull requests with improvements or additional functionalities.


### License

This project is licensed under the MIT License.  See the LICENSE file for details.
