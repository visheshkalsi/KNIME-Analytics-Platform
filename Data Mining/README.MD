# Predictive Modelling and Classification Project #
This project involves building and evaluating classifiers to predict the "QUALIFIED" attribute in a real-world dataset. The task required preprocessing, feature engineering, and testing multiple classification models to identify the best-performing classifier. Key highlights:

### Datasets used: ###
1. Training data for model building
2. Unknown data for predictions
3. Submission format for Kaggle.

Dataset included 38 attributes with detailed descriptions for understanding the feature space.

### Preprocessing: ###
- Removed outliers using interquartile range.
- Normalised features with Min-Max and Z-Score techniques.
- Converted numerical features to categorical where needed and addressed missing values.
- Split data into training (70%) and testing (30%) sets for evaluation.

### Classification Models: ###
- Implemented five classifiers: Decision Tree, K-Nearest Neighbour (KNN), Random Forest, Support Vector Machine (SVM), and Multi-Layer Perceptron (MLP).
- Tuned hyperparameters for each model and validated performance using accuracy and ROC-AUC metrics.
- Random Forest outperformed others with 90.861% accuracy and an AUC of 0.9567.

### Insights: ###
- Emphasised the importance of feature engineering and tailored preprocessing for improving model accuracy.
- Identified Random Forest as the optimal classifier due to its superior performance on the training and validation sets.
- This project demonstrates advanced skills in data preprocessing, model evaluation, and classifier selection, leveraging tools like KNIME and Python for effective predictive modelling.
