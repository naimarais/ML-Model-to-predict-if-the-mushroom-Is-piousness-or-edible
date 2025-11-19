# ML-Model-to-predict-if-the-mushroom-is-poisonous-or-edible
The goal of this notebook is to create a machine leaning model to predict whether a mushroom is poisonous or edible based on its features. The dataset contains 8124 instances and 23 attributes.
Project Summary
Mushroom Edibility Prediction using Neural Networks and PCA
Objective: Developed and evaluated machine learning models to accurately predict whether a mushroom is poisonous or edible based on its features.

Key Technologies: Python, Pandas, Scikit-learn (LabelEncoder, OneHotEncoder, PCA), Keras/TensorFlow (Sequential API, Dense layers).

Methodology & Achievements:

Data Preprocessing: Performed data loading, initial inspection, and handled categorical features by applying LabelEncoder for the target variable and OneHotEncoder for the features. Transformed 22 initial features into 116 one-hot encoded features.
Neural Network Development: Constructed a deep learning model using Keras, featuring two dense hidden layers (128 and 32 neurons with ReLU activation) and a sigmoid output layer for binary classification.
Dimensionality Reduction (PCA): Implemented Principal Component Analysis (PCA) to reduce the feature space by retaining 95% of the variance, successfully reducing 116 features to 40.
Performance Optimization: Trained a second neural network using the PCA-transformed data, demonstrating a significant reduction in training time (from 10.4 seconds to 7.01 seconds) without compromising prediction accuracy.
Model Evaluation: Achieved 100% accuracy on both the original and PCA-optimized neural network models, verified by confusion matrices, indicating robust classification performance.
Impact: Successfully built a highly accurate predictive model for mushroom edibility, showcasing proficiency in data preprocessing, deep learning, and dimensionality reduction techniques for performance enhancement.
