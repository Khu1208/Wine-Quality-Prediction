# Wine-Quality-Prediction
Wine Quality Prediction Classification

## Overview
This project focuses on predicting the quality of red wine using machine learning algorithms. The dataset used contains various chemical properties of wines along with their quality ratings. By analyzing these properties, we aim to build models that can accurately predict the quality of wine based on its characteristics.

## Dataset
The dataset, `winequality-red.csv`, comprises 1599 entries and 12 columns. Each row represents a sample of red wine with attributes such as fixed acidity, volatile acidity, citric acid, residual sugar, chlorides, free sulfur dioxide, total sulfur dioxide, density, pH, sulphates, alcohol content, and quality rating. The quality ratings range from 3 to 8, with higher values indicating better quality.

## Installation
To run this project locally, follow these steps:
1. Clone the repository:
   git clone https://github.com/yourusername/wine-quality-prediction.git
2. Navigate to the project directory:
   cd wine-quality-prediction/
3. Install the required Python packages:
   pip install numpy pandas matplotlib seaborn scikit-learn


## Usage
1. **Exploratory Data Analysis (EDA):**
- Load and explore the dataset using Python and Pandas.
- Visualize data distributions, correlations, and relationships using Matplotlib and Seaborn.

2. **Model Building:**
- Implement machine learning algorithms such as Logistic Regression, K-Nearest Neighbors (KNN), Support Vector Machine (SVM), and Random Forest Classifier.
- Train the models using the dataset and evaluate their performance.

3. **Model Evaluation:**
- Evaluate the models based on accuracy scores to determine their predictive capabilities.
- Compare the performance of different algorithms and identify the most suitable model for wine quality prediction.

4. **Contributing**
- Contributions to improve the codebase, add new features, or fix issues are welcome.
- Fork the repository, make changes, and submit pull requests for review.

## Results
After training and evaluating the models, we achieved the following accuracy scores:
- Logistic Regression: 86.87%
- K-Nearest Neighbors (KNN): 87.29%
- Support Vector Machine (SVM): [Insert Accuracy Score]
- Random Forest Classifier: 89.38%

## Future Work
- Explore advanced machine learning techniques like ensemble methods or neural networks for improved accuracy.
- Fine-tune hyperparameters and optimize model performance.
- Incorporate additional features or external datasets to enhance prediction capabilities.




