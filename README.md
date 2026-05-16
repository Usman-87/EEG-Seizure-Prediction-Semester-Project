# EEG-Based Epileptic Seizure Prediction Using Machine Learning

## Project Overview

This project presents a comparative machine learning study for EEG-based epileptic seizure prediction using Logistic Regression under different preprocessing and regularization strategies.

The study evaluates the impact of:

- Feature Standardization
- SMOTE-based Class Balancing
- L1 Regularization
- L2 Regularization
- Elastic Net Regularization

The project also analyzes the challenges of class imbalance in EEG seizure classification and evaluates model performance using multiple visualization and evaluation techniques.

---

## Datasets Used

### 1. Federated EEG Dataset
Used for:
- Multi-class EEG seizure classification
- Imbalance analysis
- Model evaluation

### 2. Epileptic Seizure Recognition Dataset
Used for:
- Cross-dataset validation
- Seizure prediction evaluation

---

## Technologies and Libraries

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Imbalanced-learn (SMOTE)

---

## Machine Learning Techniques

- Logistic Regression
- L1 Regularization
- L2 Regularization
- Elastic Net
- SMOTE Oversampling

---

## Evaluation Methods

- Confusion Matrix
- ROC Curve
- Precision-Recall Curve
- Class Distribution Analysis

---

## Project Structure

```text
EEG-Seizure-Prediction-Semester-Project/
│
├── notebooks/
│   └── eeg_seizure_prediction.ipynb
│
├── graphs/
│   ├── class_distribution.png
│   ├── confusion_matrix.png
│   ├── roc_curve.png
│   └── precision_recall.png
│
├── report/
│   ├── report.tex
│   └── report.pdf
│
├── README.md
├── LICENSE
└── .gitignore
```

---

## Visual Results

### Class Distribution

![Class Distribution](graphs/class_distribution.png)

---

### Confusion Matrix

![Confusion Matrix](graphs/confusion_matrix.png)

---

### ROC Curve

![ROC Curve](graphs/roc_curve.png)

---

### Precision-Recall Curve

![Precision Recall](graphs/precision_recall.png)

---

## Key Findings

- Severe class imbalance significantly affected seizure prediction performance.
- Baseline Logistic Regression showed majority-class bias.
- SMOTE improved minority seizure prediction and balanced learning.
- Regularization techniques helped stabilize model behavior.

---

## Future Improvements

- Deep Learning-based EEG classification
- CNN and LSTM architectures
- Advanced feature extraction
- Real-time seizure detection systems

---

## Author

**Usman Ahmad**  
Institute of Management Sciences

---

## License

This project is licensed under the MIT License.
