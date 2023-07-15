# Trip Type Classification

This project focuses on performing trip type classification based on customer shopping trips using a provided dataset. The goal is to categorize the shopping trips into different types based on the items that customers purchased.

## Dataset

The dataset consists of customer visits to a Walmart store, with each visit represented by various features such as TripType, VisitNumber, Weekday, UPC, ScanCount, DepartmentDescription, and FinelineNumber. The dataset provides the necessary information for understanding customer shopping behavior.

## Feature Engineering and Data Visualization

The project involves extensive feature engineering techniques to extract meaningful information from the dataset. Feature engineering methods such as one-hot encoding, label encoding, and feature aggregation were applied to transform the raw data into a format suitable for model training. Additionally, data visualization techniques were employed to gain insights into the relationships between features and the TripType.

## Model Training - Random Forest Classifier

The trip type classification model was trained using a Random Forest Classifier. Random Forest is an ensemble learning algorithm that combines multiple decision trees to make predictions. The model leverages the power of ensemble learning to improve accuracy and robustness.

## Evaluation

The performance of the Random Forest Classifier model was evaluated using the log loss metric. The achieved log loss of 1.85 indicates the model's ability to make accurate predictions. A random model, on the other hand, produced a worst-case log loss of around 3.94, highlighting the effectiveness of the Random Forest Classifier in trip type classification.

## Conclusion

The trip type classification project demonstrates the use of feature engineering, data visualization, and Random Forest Classifier for categorizing shopping trips based on customer purchase behavior. The achieved log loss of 1.85 signifies the model's ability to accurately predict the TripType.

The documentation and code in this repository provide detailed information on the feature engineering techniques, data visualization approaches, and the implementation of the Random Forest Classifier.
