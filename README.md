Cat vs. Dog Image Classification:

This project classifies images of cats and dogs using Principal Component Analysis (PCA) and Support Vector Machines (SVM). The dataset is split into training and test sets, and the model is tuned using grid search with cross-validation to find the best hyperparameters.

Project Overview:

The goal of this project is to classify images of cats and dogs. We use PCA for dimensionality reduction and SVM for classification. The pipeline is optimized using GridSearchCV to identify the best combination of PCA components and SVM kernels.

Dataset
The dataset consists of images of cats and dogs organized into training and test folders. Each image is resized to 50x50 pixels, normalized, and flattened before being fed into the model.

Modeling Process
Image Preprocessing:
Images are resized to 50x50 pixels.
Pixels are normalized by dividing by 255.0.
Images are flattened into 1D arrays.
Feature Extraction:
PCA is applied to reduce dimensionality.
Modeling:
SVM is used for classification.
A pipeline combining PCA and SVM is created.
Hyperparameter Tuning:
GridSearchCV is used to find the best number of PCA components and the best SVM kernel.
Evaluation:
The model is evaluated on the test set, and performance metrics are generated.
