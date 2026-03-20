# 🎓 Student Placement Prediction

A machine learning project that predicts whether a student will be placed based on their CGPA and IQ score using Logistic Regression.

\---

## 📌 Overview

This end-to-end ML project covers the full pipeline — from data loading and exploratory data analysis (EDA) to model training, evaluation, and visualization. The model classifies students as **Placed (1)** or **Not Placed (0)**.

\---

## 📁 Dataset

* **File:** `placement.csv`
* **Features used:**

  * `cgpa` — Cumulative Grade Point Average
  * `iq` — IQ Score
* **Target:**

  * `placement` — 1 (Placed) / 0 (Not Placed)

\---

## 🔄 Project Pipeline

```
1. Data Loading \& Exploration
2. Exploratory Data Analysis (EDA)
3. Feature Selection
4. Train-Test Split
5. Feature Scaling
6. Model Training (Logistic Regression)
7. Model Evaluation
8. Decision Boundary Visualization
```

\---

## 🛠️ Tech Stack

|Tool|Purpose|
|-|-|
|Python|Core language|
|Pandas|Data loading \& manipulation|
|NumPy|Numerical operations|
|Matplotlib|Data visualization|
|Scikit-learn|ML model, scaling, evaluation|
|MLxtend|Decision region plotting|

\---

## 🚀 Getting Started

### 1\. Clone the repository

```bash
git clone https://github.com/your-username/placement-prediction.git
cd placement-prediction
```

### 2\. Install dependencies

```bash
pip install numpy pandas matplotlib scikit-learn mlxtend
```

### 3\. Run the notebook

```bash
jupyter notebook Placement\_Prediction.ipynb
```

Make sure `placement.csv` is available in the working directory (or update the path inside the notebook).

\---

## 📊 Model Details

* **Algorithm:** Logistic Regression
* **Train/Test Split:** 90% / 10%
* **Scaling:** StandardScaler (fit on train, transform on test)
* **Evaluation Metric:** Accuracy Score
* **Visualization:** Decision boundary plotted on training data using `mlxtend`

\---

## 📈 Results

The model outputs a classification accuracy on the test set and plots the decision regions to visually separate placed vs. non-placed students based on CGPA and IQ.

\---

## 📂 Repository Structure

```
placement-prediction/
│
├── End\_to\_End.ipynb      # Main Jupyter notebook
├── placement.csv         # Dataset
└── README.md             # Project documentation
```

\---

## 🤝 Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss what you'd like to change.

\---

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).

