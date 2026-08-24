# Student Drug Addiction Detection

An AI system for early risk detection and responsible decision support, built for the CSE412 Artificial Intelligence Lab course at Daffodil International University.

## Overview
This project uses supervised machine learning (Naive Bayes, Logistic Regression, Decision Tree, and related classifiers) to classify addiction risk from behavioral and situational survey features such as academic performance decline, social isolation, financial issues, and risk-taking behavior.

## Repository Structure
```
.
├── notebook/
│   └── student_drug_addiction_detection.ipynb   # Full analysis, training & evaluation
├── report/
│   └── Project_Report.pdf                       # Full lab project report
├── data/
│   └── student_addiction_dataset_train.csv      # Training dataset
├── images/
│   ├── fig_correlation_heatmap.png
│   ├── fig_confusion_matrix_best_model.png
│   ├── fig_classification_report_best_model.png
│   └── fig_feature_importance.png
├── requirements.txt                              # Python dependencies
├── LICENSE
└── README.md
```

## Getting Started
```bash
git clone https://github.com/<your-username>/student-drug-addiction-detection.git
cd student-drug-addiction-detection
pip install -r requirements.txt
jupyter notebook notebook/student_drug_addiction_detection.ipynb
```

## Results
| Feature Correlation | Confusion Matrix |
|---|---|
| ![correlation](images/fig_correlation_heatmap.png) | ![confusion matrix](images/fig_confusion_matrix_best_model.png) |

| Classification Report | Feature Importance |
|---|---|
| ![classification report](images/fig_classification_report_best_model.png) | ![feature importance](images/fig_feature_importance.png) |

## Report
See [`report/Project_Report.pdf`](report/Project_Report.pdf) for the full write-up (methodology, results, and discussion).


## Course Info
- **Course:** CSE412 – Artificial Intelligence Lab
- **Department:** Computer Science and Engineering, Daffodil International University
- **Supervisor:** Dipro Paul, Lecturer
