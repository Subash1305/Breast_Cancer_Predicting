# Breast Cancer Prediction

## Dependencies
The following dependencies are required to run the application:

- pandas
- numpy
- seaborn
- matplotlib.pyplot
- warnings
- sklearn.model_selection
- sklearn.ensemble
- sklearn.svm
- sklearn.preprocessing
- sklearn.metrics

You can install the dependencies by running the following command:

```
pip install pandas numpy seaborn matplotlib scikit-learn
```

## Usage
To run the application, execute the following command:

```
python breast_cancer_prediction.py
```

The application will run and display the results in the console or generate output files, depending on the implementation.

## Functionality
The application provides the following functionality:

1. Data Loading: Load the breast cancer dataset and preprocess it for analysis.
2. Exploratory Data Analysis: Conduct exploratory data analysis to gain insights into the dataset and understand the relationships between variables.
3. Data Preprocessing: Preprocess the data by handling missing values, scaling features, and encoding categorical variables.
4. Model Training: Train different classification models, such as Gradient Boosting Classifier (GBC), Random Forest Classifier (RFC), and Support Vector Classifier (SVC), to predict breast cancer.
5. Model Evaluation: Evaluate the trained models using performance metrics, including accuracy, precision, recall, specificity, and ROC-AUC score.
6. Result Analysis: Analyze the results and select the best-performing model based on the evaluation metrics.
7. Prediction: Use the selected model to make predictions on new, unseen data.

## Conclusion
The Breast Cancer Prediction application aims to analyze and predict whether a patient has breast cancer based on cell nuclei features. By utilizing ensemble techniques and machine learning algorithms, the application provides accurate predictions and insights into the dataset. The performance metrics help evaluate the effectiveness of different models and select the best one for breast cancer prediction. The application can be further enhanced by incorporating additional features, optimizing the models, and integrating it into a user-friendly interface for easy accessibility.
