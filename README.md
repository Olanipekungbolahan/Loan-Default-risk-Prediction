# Loan-Default-risk-Prediction
On this project, Random Forest Algorithm was used to build a machine learning model to predict the likelihood of loan default.

Data was scutinised for outliers using IQR method, the dataset was imbalanced, this was regularised by upsampling method to ensure the target features are enough for model training, data was Normalised using MinMax Scaler.

The Classifier was able to attain excellent accuracy which was analysed using confusion matrix with negligible Type I and II error, hence confirming reliability of the model.

Hyperparameter optimisation of the model was attempted using GridSearch and Randomised GridSearch.

The model was saved as a pkl file was was callaable for prediction.

The pkl file can be deployed into production environment for use in a live environment.
