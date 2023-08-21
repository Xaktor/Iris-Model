# Iris Flower Classification Model
This repository contains a machine learning model for classifying iris flowers based on sepal and petal measurements. The model is trained and evaluated using the classic iris dataset.

Model Overview
The model implements and compares two machine learning algorithms:

Neural network model using Keras/TensorFlow
Support vector machine (SVM) with a linear kernel
The neural network consists of a LSTM layer followed by a dense output layer with sigmoid activation. The model is trained for 200 epochs with categorical cross-entropy loss.

The SVM uses Scikit-Learn's SGDClassifier to fit a linear SVM model on the dataset.

Both models are evaluated on a test set split from the original data. Accuracy scores are compared.

Getting Started
The model is implemented in Python 3 using common data science libraries like Pandas, NumPy, Matplotlib, etc.

To use this model yourself, first ensure you have the required libraries installed, including:

TensorFlow
Keras
Scikit-Learn
Pandas
NumPy
Matplotlib
You can install requirements using:

pip install -r requirements.txt
The main model code is contained in iris_model.py. You can run this file directly to train and evaluate the model.

Data
The classic Iris flower dataset is used containing 50 samples from each of 3 species of Iris. Four features are provided for each sample - sepal length, sepal width, petal length and petal width. The model uses the first two features to classify the 3 species.

Results
The SVM model achieved higher accuracy on the test set compared to the neural network, likely owing to the small number of features. The neural network can likely achieve better performance with more features.

Contributing
Contributions to improve the model are welcome! Please open issues or pull requests on GitHub.

License
The code in this repository is available under the MIT License. The Iris dataset itself is in the public domain.
