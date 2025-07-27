# Road Accident Severity Prediction in India

Road accidents are a cause of serious concern in India, resulting in several deaths and injuries annually. Accident data analysis and forecasting accident severity can help in taking effective preventive measures. This research applies machine learning methods, specifically the Decision Tree Classifier, to classify accident severity on the basis of several factors affecting road accidents, including road conditions, vehicle type, driver behaviour, and environmental conditions.

The dataset, which was collected from accident and vehicle reports, was pre-processed with missing value handling, encoding the categorical variables, and class imbalance handling using SMOTE. The training and testing of the model used default performance metrics like accuracy, precision, recall, and F1-score. The model based on Decision Tree had an accuracy of 86%, indicating its performance in predicting accident severity. These results can assist policymakers and traffic authorities in developing evidence-based road safety measures to reduce risks of accidents and improve emergency response systems.

## Project Files
- `Accident_Information.csv`: Raw accident data
- `Vehicle_Information.csv`: Vehicle-related data
- `road_accident_prediction_decision_tree_vs_neural_network.ipynb`: Model comparison notebook
- `road_accident_prediction_india.ipynb`: Main analysis and prediction notebook

## How to Use
1. Clone this repository
2. Open the notebooks in Jupyter or VS Code
3. Follow the steps in the notebooks to explore the data and run the models

## Requirements
- Python 3.x
- pandas, numpy, scikit-learn, imbalanced-learn, matplotlib, seaborn, jupyter

## License
This project is for educational and research purposes only.
