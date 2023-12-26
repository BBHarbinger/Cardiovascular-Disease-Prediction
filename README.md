# Cardiovascular Disease Risk Prediction

## Project Overview
This project focuses on developing machine learning models to predict the risk of cardiovascular diseases using the 2021 Behavioral Risk Factor Surveillance System (BRFSS) dataset. Our aim is to identify key lifestyle factors that significantly influence cardiovascular health and provide a data-driven approach to risk assessment. 

## Dataset
We utilized the 2021 Behavioral Risk Factor Surveillance System (BRFSS) dataset, provided by the Centers for Disease Control and Prevention (CDC), with the aim of identifying crucial patterns and risk factors pertinent to cardiovascular health.
The BRFSS is a leading health-related telephone survey in the United States, collecting comprehensive data on residents' health behaviors, chronic conditions, and preventive service usage.
Our selected dataset comprises 19 carefully chosen variables, focusing on lifestyle factors that could potentially influence the risk of CVDs. These variables encompass a range of aspects from dietary habits to medical history, offering a broad perspective on factors affecting cardiovascular health.
(Dataset Source: https://www.kaggle.com/datasets/alphiree/cardiovascular-diseases-risk-prediction-dataset)

## Features of the Project
- Data Preprocessing and Exploration
- Feature Engineering
- Machine Learning Models: Logistic Regression, Random Forest, Neural Networks
- Model Evaluation and Comparison

## Technologies Used
- Python
- Pandas, NumPy
- Scikit-Learn, TensorFlow/Keras
- Matplotlib, Seaborn for visualization

## How to Run the Project
1. Clone the repository:
2. Install the required packages:
3. Run the Jupyter notebooks or Python scripts:

## Results and Discussion
Our models demonstrated the ability to accurately predict cardiovascular disease risk, with the Neural Network showing the most promising results. The project provides valuable insights into the impact of lifestyle factors on cardiovascular health.

## Protential Future Work:
- Expanding Data Sources: To mitigate the limitations of self-reported data, future studies could integrate medical records or biometric data, where available, to validate and enrich the dataset.

- Advanced Hyperparameter Optimization Techniques: With more computational power, advanced techniques like Bayesian optimization, genetic algorithms, or automated machine learning (AutoML) frameworks could be employed to explore a broader hyperparameter space more efficiently.

- Model Ensemble Techniques: Combining predictions from various models could improve accuracy and robustness. Future work could explore ensemble methods, such as stacking or blending, especially integrating the output of the Feedforward Neural Network with models like Random Forest and Logistic Regression.

- Deep Learning Exploration: Given the success of the Feedforward Neural Network, further exploration into deep learning architectures such as Convolutional Neural Networks (CNNs) for structured data, or Long Short-Term Memory (LSTM) networks for sequential data, could be considered if the dataset characteristics support their application.

- Model Interpretability: With the increasing complexity of models, ensuring that they remain interpretable is vital, particularly in healthcare. Techniques such as SHAP (SHapley Additive exPlanations) or LIME (Local Interpretable Model-agnostic Explanations) could be incorporated to provide insights into model decisions.

## Contributors
Project developed by Felix Yuzhou Sun, Ganlin Ouyang, Qi Yu


