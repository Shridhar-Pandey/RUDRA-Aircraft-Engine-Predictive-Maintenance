
# **Remaining Useful Life (RUL) Prediction (Regression)**

This folder contains models designed for estimating the Remaining Useful Life (RUL) of aircraft engines using regression techniques. These models are crucial for predicting when maintenance should be performed to prevent failures.

## **Files Overview:**

1. **Exponential_Degradation_Model_for_RUL_Prediction.ipynb**
   - Implements an Exponential Degradation Model to predict the Remaining Useful Life (RUL) of aircraft engines.
   - The model uses degradation signals over time to estimate how much useful life remains before the engine requires maintenance.

2. **LSTM_Based_RUL_Estimation.ipynb**
   - Utilizes a Long Short-Term Memory (LSTM) network to predict the RUL based on time-series data.
   - The model is designed to capture the temporal dependencies in the data, providing a more accurate estimation of when the engine will likely fail.

3. **Similarity_Metrics_for_RUL_Prediction.ipynb**
   - Applies similarity-based approaches to estimate the RUL by comparing the current engine's performance to historical data from other engines.
   - The model identifies patterns and trends that closely match those of previously failed engines to predict the RUL.

## **Usage Instructions:**

- Each notebook is self-contained and can be run independently.
- Ensure that the necessary datasets and dependencies are in place before executing the models.
- The outputs include RUL predictions and visualizations that illustrate the model performance.

## **Dependencies:**

- Python 3.x
- TensorFlow/Keras
- Scikit-learn
- Pandas
- NumPy
- Matplotlib
