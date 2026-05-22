# 🧠 AI & Machine Learning Portfolio

Welcome to my Artificial Intelligence and Machine Learning repository! This workspace contains a collection of projects I developed, focusing on both classical Machine Learning algorithms and modern Deep Learning architectures.

The goal of this repository is to demonstrate practical, data-driven solutions ranging from structured tabular data analysis to complex time-series forecasting.

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/Scikit_Learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-D00000?style=for-the-badge&logo=keras&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)

---

## 📂 Repository Structure & Projects

### 1. 🏡 Machine Learning - Real Estate Price Prediction & Clustering
* **Folder:** `Machine_Learning/`
* **Description:** An end-to-end machine learning project utilizing a Kaggle competition dataset for real estate. The objective is to accurately predict house prices and identify underlying patterns in the housing market.
* **Key Concepts & Algorithms:** * **Regression:** Decision Trees and Random Forest Regressors for robust price prediction.
  * **Clustering:** K-Means algorithm to group properties based on features.
  * **Data Processing:** Handling missing values, feature engineering, and data scaling.

### 2. 📈 Deep Learning - LSTM Stock Price Forecasting
* **Folder:** `Deep_Learning/`
* **Description:** A highly optimized Recurrent Neural Network (RNN) designed to predict the future stock price of Tesla (TSLA) based on the past 60 days of market data.
* **Key Concepts:** Time-series forecasting, sequential memory, and data normalization (`MinMaxScaler`).
* **Pro Features:** Implemented `EarlyStopping` to prevent overfitting and `ReduceLROnPlateau` to dynamically adjust the learning rate during training. Real-time data is fetched dynamically using the `yfinance` API.

---

## 🛠️ How to Use

All projects are provided as Jupyter/Colab Notebooks (`.ipynb`) for maximum readability and interactivity. You can view the code, markdown explanations, and output graphs directly on GitHub.

To run the models locally:
1. Clone the repository:
   ```bash
   git clone https://github.com/TunaStark/ITO-ML-DL-Examples.git
   
2. Install dependencies: Ensure you have the required libraries installed (tensorflow, pandas, scikit-learn, yfinance).
3. Run the notebooks: For the Machine Learning project, make sure the train and test .csv files are located in the same directory as the notebook.

Developed by TunaG
