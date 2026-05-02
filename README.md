# Simple Models Win Too: A Classification Benchmark

> A Final Year Data Science Undergraduate's comparative study of 
> Logistic Regression, Random Forest & XGBoost on the Titanic dataset.

## 📊 Results

| Model               | Accuracy | F1 Score | ROC-AUC |
|---------------------|----------|----------|---------|
| Logistic Regression | 0.8045   | 0.7482   | 0.8828  |
| Random Forest       | **0.8156**   | **0.7724**   | **0.8921**  |
| XGBoost             | 0.7765   | 0.7297   | 0.8730  |

## 🔍 Key Finding
Random Forest outperformed XGBoost across all three metrics. 
Logistic Regression came in a close second — beating XGBoost entirely.
Complexity ≠ performance on small, structured datasets.

## 🛠️ Tech Stack
- Python 3.x
- scikit-learn
- XGBoost
- pandas, numpy
- matplotlib, seaborn

## 📁 Structure
├── ml_benchmark.ipynb   # Full experiment notebook
├── requirements.txt     # Dependencies
└── README.md            # Project overview

## 🚀 Run It Yourself
pip install -r requirements.txt
jupyter notebook ml_benchmark.ipynb

## 📝 Article
Read the full LinkedIn article here: [Link]
