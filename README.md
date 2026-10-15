# Heart Disease Prediction Using Machine Learning

## 📌 Project Overview

This project focuses on predicting the presence of heart disease using machine learning techniques. The dataset contains medical and clinical attributes of patients, which are used to train and evaluate different classification models.

Multiple machine learning algorithms are implemented and compared based on their performance.

## 🎯 Objective

The main objective of this project is to build a machine learning model that can predict whether a patient is likely to have heart disease based on the given medical features.

## 📊 Dataset

The dataset contains **918 patient records** and **12 columns**, including patient-related medical and clinical attributes.

The target variable is:

* `HeartDisease` — indicates whether heart disease is present.

The dataset is provided in the repository as:

```text
heart.csv
```

## 🛠️ Technologies & Libraries Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

## 🔍 Project Workflow

The project follows these major steps:

1. Loading the dataset
2. Understanding the dataset structure
3. Checking for missing values and duplicates
4. Data cleaning and preprocessing
5. Exploratory Data Analysis (EDA)
6. Encoding categorical variables
7. Feature scaling
8. Splitting the dataset into training and testing sets
9. Training multiple machine learning models
10. Comparing model performance
11. Evaluating accuracy and F1-score

## 🤖 Machine Learning Models

The following classification algorithms were implemented:

* Logistic Regression
* K-Nearest Neighbors (KNN)
* Naive Bayes
* Support Vector Machine (SVM)
* Decision Tree

## 📈 Results

The models were compared using Accuracy and F1-score.

| Model                  |   Accuracy |   F1 Score |
| ---------------------- | ---------: | ---------: |
| Logistic Regression    | **86.96%** | **88.57%** |
| K-Nearest Neighbors    |     86.41% |     88.15% |
| Naive Bayes            |     85.33% |     86.83% |
| Support Vector Machine |     84.78% |     86.79% |
| Decision Tree          |     76.63% |     79.23% |

### 🏆 Best Performing Model

**Logistic Regression** achieved the highest accuracy of approximately **86.96%** among the models evaluated in this project.

## 📁 Project Structure

```text
Heart-Disease-Prediction/
│
├── heart.ipynb
├── heart.csv
├── requirements.txt
└── README.md
```

### File Description

| File               | Description                                                                             |
| ------------------ | --------------------------------------------------------------------------------------- |
| `heart.ipynb`      | Jupyter Notebook containing data analysis, preprocessing, model training and evaluation |
| `heart.csv`        | Heart disease dataset used for the project                                              |
| `requirements.txt` | Python libraries required to run the project                                            |
| `README.md`        | Project documentation                                                                   |

## 🚀 How to Run the Project

### 1. Clone the repository

```bash
git clone <your-github-repository-url>
```

### 2. Navigate to the project folder

```bash
cd Heart-Disease-Prediction
```

### 3. Install the required libraries

```bash
pip install -r requirements.txt
```

### 4. Open the Jupyter Notebook

```bash
jupyter notebook heart.ipynb
```

Run the notebook cells sequentially to reproduce the analysis and model results.

## 📌 Conclusion

This project demonstrates the application of machine learning classification algorithms for heart disease prediction. Among the tested models, Logistic Regression achieved the best performance with an accuracy of approximately **86.96%**.

The comparison of multiple models provides an understanding of how different machine learning algorithms perform on the given dataset.

## 👨‍💻 Author

**Akshat Kumar**

B.Tech Computer Science Engineering
Manipal University Jaipur

## 📄 License

This project was created for academic/educational purposes.
