# Experiment 5:  Dimensionality Reduction and Model Evaluation (With and Without PCA)

## 🎯 Objective
To study the effect of dimensionality reduction using Principal Component Analysis (PCA) on the
performance of various machine learning classifiers. The task requires:
- Training and validating models without PCA (original feature space).
- Training and validating models with PCA (reduced feature space).
For both cases, students must perform hyperparameter tuning, apply 5-fold cross-validation, and
record performance.

---

## 🧰 Tools & Libraries Used
- **Python 3.10+** – Primary language for implementation
- **NumPy** – Efficient numerical operations and array handling
- **Pandas** – For managing datasets and storing model performance results
- **Scikit-learn** – For implementing classifiers, PCA, cross-validation, and evaluation metrics
- **Matplotlib** – For visualizing performance trends and comparison plots

---

## 📁 Folder Structure
```bash
ml-expt-6/
├── README.md                        # Overview, tools, file summary, run instructions
├── datasets/                     
│   └── spambase_csv.csv             # Dataset for training classification models
├── Experiment-6/
│   ├── expt-6.ipynb                 # Implementation notebook
├── screenshots/
│   ├── expt-6_9_1.png             
│   ├── expt-6_12_1.png
│   ├── expt-6_15_1.png
│   ├── ...
│   └── subplot.png
├── Assignment6_ML_Vidarshanaa.pdf  # Lab report
├── Assignment6_ML_Vidarshanaa.tex  # Latex report
└── requirements.txt                # Python packages and versions used
```

## 🚀 Instructions to Execute the Code

1. **Clone the Repository**
```bash
   git clone https://github.com/vidarshanaa15/ml-expt-6.git
   cd ml-expt-6
```

2. **Open the Notebooks**
- **Using Google Colab:**
  - Go to Google Colab
  - Click File > Upload Notebook and upload any .ipynb file from the Experiment-5 folder
  - *Or* paste the GitHub URL directly in Colab to open from repo
    
- **Running Locally with Jupyter Notebook:**
  - Install required packages:
  ```bash
  pip install -r requirements.txt
  ```
  - Then run
  ```bash
  pip install notebook
  jupyter notebook
  ```
  - Navigate to the Experiment-6 folder and open a notebook in your browser

## 📈 Model Performance (No-PCA vs With-PCA)

|--------------------|---------------------|------------------------|
| Model              | Performance (No-PCA)| Performance (With-PCA) |
|--------------------|---------------------|------------------------|
| SVM                | 0.9314              | 0.9245                 |
| Naive Bayes        | 0.7254              | 0.8329                 |
| KNN                | 0.9108              | 0.9085                 |
| Logistic Regression| 0.9130              | 0.9176                 |
| Decision Tree      | 0.8902              | 0.8741                 |
| Random Forest      | 0.9245              | 0.9085                 |
| AdaBoost           | 0.9153              | 0.9016                 |
| Gradient Boosting  | 0.9314              | 0.9085                 |
| XGBoost            | 0.9405              | 0.9108                 |
| Stacked Models     | 0.9199              | 0.9199                 |
|--------------------|---------------------|------------------------|

## 🙌 Credits

This experiment is part of the course **“ICS1512-Machine Learning Algorithms Laboratory”** at **SSN College of Engineering**.
