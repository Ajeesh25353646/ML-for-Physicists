# Arrest Prediction Based on Crime Data (Los Angeles 2010-2017)
link to used dataset: https://www.kaggle.com/datasets/cityofLA/crime-in-los-angeles


### Project Overview
This project leverages machine learning to predict the likelihood of an arrest in response to criminal incidents across Los Angeles from 2010 to 2017. Using a dataset from the Los Angeles Police Department (LAPD), we analyzed factors contributing to arrests, such as crime type, location, and reporting delays, providing insights into patterns that can enhance law enforcement strategies.

### Key Features
- **Data Processing & Feature Engineering**: Processed 1.6 million crime records, optimized relevant features, and implemented one-hot encoding to handle categorical data.
- **Extensive Model Comparison**: Explored various supervised machine learning algorithms—including Logistic Regression, Decision Trees, SVM, and k-Nearest Neighbors—to identify the best-performing model. The neural network model consistently outperformed other algorithms in accuracy and robustness.
- **Modeling with Neural Networks & Random Forests**: Built a dense neural network and tested a Random Forest model, achieving an AUC score of 0.81 on both.
- **Hyperparameter Optimization**: Used Keras Tuner for optimizing model parameters, refining performance without overfitting.
- **Evaluation**: Assessed model effectiveness using ROC-AUC and precision metrics, demonstrating robust discrimination between arrest and non-arrest cases.

### Results
The neural network model provided slightly superior classification accuracy over the Random Forest model, especially in cases with complex feature interactions. However, Random Forest with three key features (crime type, area, and premise) nearly matched the performance, indicating the simplicity of underlying patterns. Further, statistics was used to make some interesting plots. 
