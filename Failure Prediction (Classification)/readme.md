# **Failure Prediction (Classification)**

This folder contains various machine learning models developed for predicting failures in aircraft engines. The models focus on binary and multiclass classification tasks.

## **Files Overview:**

1. **CNN_Multiclass_and_Binary_Classifier.ipynb**
   - Implements a 1D Convolutional Neural Network (CNN) for both binary and multiclass classification.
   - The model processes sequential time-series data from aircraft engines to predict potential failures.

2. **CNN_SVM_Classifier_for_Binary_Classification.ipynb**
   - Combines a Convolutional Neural Network (CNN) for feature extraction with a Support Vector Machine (SVM) for binary classification.
   - Aimed at enhancing the accuracy of failure prediction by leveraging the strengths of both CNN and SVM.

3. **LSTM_Model_for_Binary_Classification.ipynb**
   - Utilizes a Long Short-Term Memory (LSTM) network tailored for binary classification tasks.
   - Designed to capture temporal dependencies in time-series data for predicting imminent engine failures.

4. **RNN_Model_for_Multiclass_and_Binary_Classification.ipynb**
   - Applies a Recurrent Neural Network (RNN) model for both binary and multiclass classification.
   - Focuses on modeling the sequential nature of the data to classify different failure types.

## **Usage Instructions:**

- Each notebook can be executed independently.
- Ensure that the required datasets and dependencies are correctly set up before running the models.
- Results include classification reports, confusion matrices, and visualizations for model performance evaluation.

## **Dependencies:**

- Python 3.x
- TensorFlow/Keras
- Scikit-learn
- Pandas
- NumPy
- Matplotlib


