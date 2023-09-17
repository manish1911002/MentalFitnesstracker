# Mental Health Fitness Tracker
The Mental Health Fitness Tracker project focuses on analyzing and predicting mental fitness levels of individuals from various countries with different mental disorders. It utilizes regression techniques to provide insights into mental health and make predictions based on the available data. The project also provides a platform for users to track their mental health and fitness levels. The project is built using Python.

## Table of Contents
Installation
Usage
Data Cleaning and Preprocessing
Exploratory Analysis
Data Preprocessing
Model Building and Evaluation
Usage
Contributing
License
References
## Installation
To use the code and run the examples, follow these steps:

Ensure that you have Python 3.x installed on your system.
Install the required libraries by running the following command:
Copy code
pip install pandas numpy seaborn matplotlib plotly scikit-learn
Download the project files and navigate to the project directory.
Data
## Usage
Make sure you have the necessary datasets: mental-and-substance-use-as-share-of-disease.csv and prevalence-by-mental-and-substance-use-disorder.csv. These datasets are available from Kaggle or any reliable source related to mental health data.

## Data Cleaning and Preprocessing
The project performs data cleaning and preprocessing to prepare the data for analysis and model building. The steps include:

Merging the two datasets using common columns: 'Entity', 'Code', and 'Year'.
Dropping the 'Entity' column as it is not needed for analysis.
Renaming columns for better readability.
Converting non-numeric values to NaN using the pd.to_numeric() function.
Dropping the 'Code' column as it is not needed for analysis.
Imputing missing values with the mean using SimpleImputer from scikit-learn.
## Exploratory Analysis
The project performs exploratory analysis to gain insights into the data. Some of the visualizations include:

Correlation heatmap using Seaborn's sns.heatmap() to understand the relationships between different features.
Scatter plots and regression plots using Seaborn's sns.jointplot() to visualize the relationship between mental fitness and other variables.
Pairplots using Seaborn's sns.pairplot() to visualize the distribution and relationships of all features.
## Data Preprocessing
Data preprocessing includes encoding categorical variables using LabelEncoder from scikit-learn. This step is necessary before building the machine learning models.

## Model Building and Evaluation
The project builds three regression models to predict mental fitness levels:

Linear Regression: Uses scikit-learn's LinearRegression to build a linear regression model.
Random Forest Regressor: Uses scikit-learn's RandomForestRegressor to build a random forest regression model.
The models are evaluated using Mean Squared Error (MSE), Root Mean Squared Error (RMSE), and R-squared (R2) scores on both the training and testing datasets.


## Usage
Ensure you have the required datasets and Python libraries installed as mentioned in the installation section.
Modify the code in the script mental_health_fitness_tracker.py to provide the correct file paths for the datasets.
Run the script mental_health_fitness_tracker.py to execute the program.
Follow the prompts in the console to select the country, mental disorder, and year range for analysis.
The program will display the results of the analysis, including visualizations of the data.
You can also track your own mental fitness level by providing your data through the console prompts.
The program will provide insights and predictions based on the input data.
## Contributing
Contributions are welcome! If you find any issues or have suggestions to improve the project, feel free to open an issue or submit a pull request.

## License
This project is licensed under the MIT License.

## References
Datasets used in this project were taken from Kaggle.
This project was made during my internship period for Edunet Foundation in association with IBM SkillsBuild and AICTE.
Feel free to customize the code snippets and explanations to provide more specific details and highlights about your Mental Health Fitness Tracker project.
