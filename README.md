# 🌸 Iris Flower Classification Project

## 📌 Overview
This project is a beginner-friendly Machine Learning application that classifies Iris flowers into three species (**Setosa**, **Versicolor**, and **Virginica**) based on their physical measurements.

The goal was to build a complete ML pipeline from raw data to a fully working model using Python and Scikit-Learn.

## 🛠️ Technologies Used
* **Language:** Python 🐍
* **Libraries:**
    * `pandas` (for data manipulation)
    * `scikit-learn` (for machine learning algorithms)
    * `matplotlib` / `seaborn` (for data visualization)

## ⚙️ How It Works
The project follows a standard Machine Learning workflow:

1.  **Data Loading:** Fetched the famous Iris dataset from `sklearn.datasets`.
2.  **Exploratory Data Analysis (EDA):** Analyzed the data structure and statistics.
3.  **Preprocessing:**
    * Split the data into **Training (80%)** and **Testing (20%)** sets.
    * Applied **Normalization** (`MinMaxScaler`) to scale features between 0 and 1.
4.  **Model Training:** Used the **k-Nearest Neighbors (k-NN)** classifier (with `n_neighbors=3`).
5.  **Evaluation:** Tested the model on unseen data.

## 📊 Results
The model achieved an accuracy score of **100%** on the test dataset.

**Confusion Matrix:**
[[10 0 0] 
 [ 0 9 0]
 [ 0 0 11]]

## 🚀 How to Run
1.  Open the notebook in **Google Colab**.
2.  Run the cells sequentially to load data, train the model, and view results.
3.  (Optional) Input your own "Mystery Flower" measurements to see a prediction.

## 🔮 Future Improvements
* [ ] **Real-world Testing:** Implement a generic function to accept new measurements and predict the species.
* [ ] **Algorithm Comparison:** Benchmark k-NN against Decision Trees and Logistic Regression.
* [ ] **Scalability:** Test the workflow on a larger, more complex dataset (e.g., Titanic or Housing Prices).
 
