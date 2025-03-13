# oibsip_task1

# 🌸 Iris Flower Classification

## 📌 Project Overview

This project implements a **Machine Learning model** to classify **Iris flower species** based on their features. The dataset consists of three species:

- **Setosa**

- **Versicolor**

- **Virginica**

Using **Scikit-Learn**, the model is trained to predict the species based on four features:

- Sepal Length

- Sepal Width

- Petal Length

- Petal Width

## 🛠 Tech Stack

- **Programming Language**: Python

- **Libraries Used**:

  - `numpy` (Numerical computations)

  - `pandas` (Data manipulation)

  - `matplotlib` & `seaborn` (Data visualization)

  - `scikit-learn` (Machine Learning models)

  - `joblib` (Model saving/loading)

## 📂 Dataset
The dataset is taken from **Scikit-learn's built-in Iris dataset**. It can also be downloaded separately.

## 🚀 Installation & Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/iris-flower-classification.git
   cd iris-flower-classification
   ```
2. Install dependencies:
   ```bash
   pip install numpy pandas matplotlib seaborn scikit-learn joblib
   ```
3. Run the Jupyter Notebook or Python script:
   ```bash
   jupyter notebook iris_classification.ipynb
   ```

## 📊 Exploratory Data Analysis (EDA)

- Visualized dataset distributions using **pairplots**

- Checked for missing values

- Performed statistical analysis

## 🔍 Model Training

1. Split the dataset into **training (80%)** and **testing (20%)**.

2. Trained using **Logistic Regression**.

3. Evaluated using accuracy score & classification report.

## 🎯 Model Evaluation

- Used **Confusion Matrix** & **Classification Report**.

- Achieved an accuracy of **~97%**.

## 🛠 Model Deployment (Optional)
To deploy the model using **Streamlit**, run:

streamlit run app.py

## 📌 Future Improvements

- Try different classification models (Decision Trees, Random Forest, SVM)

- Deploy as a **web app** using Flask or FastAPI

- Optimize hyperparameters for better accuracy

---

