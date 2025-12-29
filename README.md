# fraud-detection-ml
Machine Learning project for credit card fraud detection with imbalanced data handling
# 🔍 Credit Card Fraud Detection

Machine Learning project for detecting fraudulent credit card transactions using imbalanced data handling techniques.

## 📊 Project Overview

This project implements a complete ML pipeline to detect credit card fraud, addressing the challenge of highly imbalanced datasets (0.172% fraud rate). The solution applies various techniques including SMOTE, undersampling, and threshold optimization to achieve optimal precision-recall trade-offs.

## 🎯 Objectives

- Build robust fraud detection models handling severe class imbalance
- Compare multiple ML algorithms (Logistic Regression, Random Forest, XGBoost, etc.)
- Optimize for business metrics (cost of false positives vs false negatives)
- Provide interpretable results for stakeholders

## 📁 Project Structure
```
fraud-detection-ml/
├── data/                  # Dataset files
├── notebooks/             # Jupyter notebooks (EDA, modeling, evaluation)
├── reports/              # Generated analysis and figures
├── presentation/         # Project presentation slides
└── requirements.txt      # Python dependencies
```

## 🛠️ Technologies Used

- **Python 3.8+**
- **Libraries:** pandas, numpy, scikit-learn, imbalanced-learn, seaborn, matplotlib
- **ML Models:** Logistic Regression, Random Forest, XGBoost, Neural Networks
- **Techniques:** SMOTE, Random Undersampling, Threshold Tuning, Cross-Validation

## 📈 Dataset

- **Source:** [Kaggle Credit Card Fraud Detection](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)
- **Size:** 284,807 transactions
- **Features:** 30 (anonymized via PCA)
- **Target:** Binary classification (Fraud/Legitimate)
- **Imbalance Ratio:** 492 frauds (0.172%)

## 🚀 Getting Started

### Prerequisites
```bash
python 3.8+
pip
jupyter notebook
```

### Installation

1. Clone the repository
```bash
git clone https://github.com/Chris05-Gen/fraud-detection-ml.git
cd fraud-detection-ml
```

2. Create virtual environment
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. Install dependencies
```bash
pip install -r requirements.txt
```

4. Download dataset from Kaggle and place in `data/raw/`

5. Launch Jupyter
```bash
jupyter notebook
```

## 📊 Results

*(To be updated after analysis)*

- **Best Model:** TBD
- **Precision:** TBD
- **Recall:** TBD
- **F1-Score:** TBD
- **AUC-ROC:** TBD

## 🔑 Key Insights

*(To be updated after analysis)*

## 📝 Report & Presentation

- [Project Report](reports/project_report.pdf)
- [Presentation Slides](presentation/slides.pptx)

## 👨‍💻 Author

**[Your Name]**
- GitHub: [@Chris05-Gen](https://github.com/Chris05-Gen)
- LinkedIn: [Your Profile](https://linkedin.com/in/your-profile)

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- Course: Machine Learning (Prof. Giuseppe Polese, Prof.ssa Loredana Caruccio)
- Dataset: [Credit Card Fraud Detection Dataset](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)
```
