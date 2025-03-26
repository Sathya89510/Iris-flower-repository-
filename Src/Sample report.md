### 4. Sample Report (reports/report.md)
```markdown
# Iris Flower Classification Report

## 1. Introduction
Classification of Iris flowers into three species using morphological measurements.

## 2. Dataset Overview
- 150 samples (50 per species)
- 4 features:
  - Sepal length
  - Sepal width
  - Petal length
  - Petal width
- Target: Species (3 classes)

## 3. Exploratory Data Analysis
- Setosa flowers are clearly separable
- Versicolor and virginica have some overlap
- Petal measurements more discriminative than sepal

## 4. Methodology
### Data Preprocessing
- No missing values
- Standardized features (mean=0, std=1)

### Models Tested
1. Logistic Regression
2. K-Nearest Neighbors (KNN)
3. Support Vector Machine (SVM)
4. Random Forest
5. Neural Network

### Evaluation Metrics
- Accuracy
- Precision
- Recall
- F1-score
- Confusion matrix

## 5. Results
| Model                | Accuracy | Precision | Recall | F1-score |
|----------------------|----------|-----------|--------|----------|
| Logistic Regression  | 0.97     | 0.97      | 0.97   | 0.97     |
| KNN (k=3)            | 0.98     | 0.98      | 0.98   | 0.98     |
| SVM                  | 0.98     | 0.98      | 0.98   | 0.98     |
| Random Forest        | 0.96     | 0.96      | 0.96   | 0.96     |
| Neural Network       | 0.97     | 0.97      | 0.97   | 0.97     |

## 6. Key Findings
- All models performed exceptionally well (>95% accuracy)
- KNN and SVM achieved highest accuracy (98%)
- Petal measurements were most important features

## 7. Conclusion
The KNN model with k=3 demonstrated the best performance with 98% accuracy, making it suitable for this classification task.
