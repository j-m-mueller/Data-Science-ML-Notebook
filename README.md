# Data Science: A Machine Learning Notebook
A Jupyter Notebook with an exemplary workflow on data preparation and model creation in *scikit-learn* and *TensorFlow / Keras*. For demonstration, the model is based on the Boston Housing Dataset, which is imported via the *scikit-learn* dataset repository.

The notebook contains the following steps:
- data exploration (show data distribution, correlations, and issues with invalid values)
- model creation and fitting for two different models (K-nearest Neighbors Regressor and Random Forest Regressor, both from *scikit-learn*), along with one Deep Neural Network (*TensorFlow*)
- rating of Feature Importances based on the Random Forest Regressor model and using the result for an optimized model
- a small template to use the model for actual predictions

*Note:* Due to reasons of simplicity, the notebook does not contain advanced methods like K-fold cross-validation, feature interactions, grid search, etc. Its main purpose is to demonstrate some basic tools and procedures.

*Designed for TensorFlow version 1.8.0rc and Keras version 2.2.4.*
