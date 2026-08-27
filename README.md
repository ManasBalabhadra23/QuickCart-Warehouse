# QuickCart Stockout Risk Prediction

This project uses machine learning to predict stockout risk for QuickCart products across different stores.

The products are classified into three categories:
- Safe
- At-Risk
- Imminent

## What I Did
- Cleaned and explored the data
- Combined inventory, store, SKU, supplier, and event data
- Created useful features related to stock, demand, reorder points, and suppliers
- Built Logistic Regression and Random Forest models
- Compared model performance
- Analyzed important features
- Generated stockout risk predictions

## Tools Used
Python, Pandas, NumPy, Scikit-learn, Matplotlib, Google Colab

## Best Result
Random Forest achieved approximately **93.79% accuracy** and **87.77% balanced accuracy**.

## Results

| Model | Accuracy | Balanced Accuracy | Imminent Recall |
|---|---:|---:|---:|
| Majority Baseline | 62.28% | 33.33% | 0.00% |
| Logistic Regression | 85.16% | 77.90% | 99.48% |
| Random Forest | 93.79% | 87.77% | 70.58% |

Random Forest achieved the best overall performance with **93.79% accuracy** and **87.77% balanced accuracy**.

Logistic Regression achieved the highest **Imminent Recall of 99.48%**, making it particularly useful when detecting imminent stockouts is the main priority.
