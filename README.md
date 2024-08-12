# **RUDRA: Aircraft Engine Predictive Maintenance**
"RUDRA" symbolizes protection and strength, reflecting the project's aim to ensure aircraft engine reliability through predictive maintenance and RUL estimation. The name emphasizes the project's focus on preventing failures and enhancing safety, drawing inspiration from the powerful deity Rudra in Indian mythology.

## **Project Overview**

Predictive Maintenance (PdM) techniques are employed to monitor the condition of equipment, enabling maintenance and repairs to be scheduled ahead of time. This proactive approach significantly reduces downtime costs and enhances the overall efficiency of operations.

### **Objective**

The primary goal of this project is to implement various Predictive Maintenance methodologies and evaluate their performance. These methods are categorized into two broad types:

- **Classification:** Predicting whether a machine will fail within the upcoming *n* days.
- **Regression:** Estimating the Remaining Useful Life (RUL) of a machine.

### **Data Description**

The dataset comprises multiple multivariate time series, each representing data from different engines within a fleet of the same type. The engines operate normally at the start of each time series, gradually developing faults that eventually lead to system failure. The training set consists of 100 engines with varied run lengths (ranging from 128 to 356 cycles), while the test set contains data from a different set of 100 engines, stopping just before a failure occurs.

### **Exploratory Data Analysis (EDA)**

Comprehensive EDA was performed to gain insights into the data patterns and underlying trends, which are crucial for model development.

### **Models for Predictive Maintenance**

The following models have been implemented to address the predictive maintenance tasks:

1. **Exponential Degradation Model** for RUL Prediction
2. **Similarity-Based Model** for RUL Prediction
3. **LSTM Model** for RUL Prediction
4. **LSTM Model** for Binary and Multiclass Classification
5. **RNN Model** for Binary and Multiclass Classification
6. **1D CNN** for Binary and Multiclass Classification
7. **1D CNN-SVM** for Binary Classification

### **Experimental Setup**

To further refine the predictive capabilities, the following advanced techniques are planned:

- **AutoKeras** for Failure Prediction
- **TSFresh** for Feature Extraction
- **Dynamic Time Warping (DTW)** and Time Series Clustering
- **Genetic Algorithms** for Model Optimization
- **Hidden Markov Models** for Sequential Data Analysis
- **Survival Analysis** for Time-to-Event Prediction
- **Autoencoders** for Anomaly Detection

## **Technologies Used**

- **Programming Languages:** Python
- **Libraries:** TensorFlow, Keras, Scikit-learn, TSFresh
- **Tools:** Jupyter Notebook, Google Colab
- **Data Handling:** Pandas, NumPy, Matplotlib, Seaborn
- **Models:** LSTM, RNN, CNN, SVM, AutoKeras, Hidden Markov Models

## **Getting Started**

To clone and run this project locally, follow these steps:

```bash
git clone https://github.com/Shridhar-Pandey/RUDRA-Aircraft-Engine-Predictive-Maintenance.git
cd RUDRA-Aircraft-Engine-Predictive-Maintenance
pip install -r requirements.txt
