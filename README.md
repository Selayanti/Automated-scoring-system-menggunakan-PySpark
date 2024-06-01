# Automated-scoring-system-menggunakan-PySpark
This project aims to develop an automated scoring system for essay questions using PySpark and the Alternating Least Squares (ALS) algorithm from Apache Spark ML. The system is designed to efficiently score essay answers on a large scale, providing an accurate and efficient grading process.

# Overview
The Automated Essay Scoring System is built using Python and PySpark, a powerful distributed computing framework for big data processing. The system employs the ALS algorithm, a collaborative filtering technique, to predict scores for essay answers based on the content of the essay and the given question.

# Features
- Data Preprocessing: Handles text data preprocessing, missing value treatment, and data type conversion.
- Big Data Processing: Processes large-scale data using PySpark and splits the data into training and testing sets.
- Machine Learning Modeling: Utilizes the Alternating Least Squares (ALS) algorithm for predictive modeling.
- Model Evaluation: Evaluates the regression model's performance using the Root Mean Squared Error (RMSE) metric.
- Natural Language Processing: Converts text data into numerical representations using hashing techniques.

# Acknowledgments
- Apache Spark
- PySpark
- Alternating Least Squares (ALS) algorithm
