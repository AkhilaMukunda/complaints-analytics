# Customer Complaints Analytics & Classification

**Tools:** Python, SQL, Pandas, Scikit-learn, Matplotlib, Seaborn

## Overview
End-to-end analysis of 50,000 consumer financial complaints from the CFPB dataset (2015–2024), covering trend analysis, SQL-based querying, statistical hypothesis testing, and NLP-based complaint classification.

## Key Findings
- Credit Reporting accounts for ~60% of all complaints, dominated by Equifax, TransUnion, and Experian
- Complaint volume grew at ~1,008 complaints/year (R²=0.78), with a 69% spike in 2022
- Credit Reporting response rates are statistically significantly different from other categories (p≈0, T=21.3)
- Random Forest classifier achieves 86% accuracy in categorising complaints from narrative text

## Project Structure
- `complaints_analysis.ipynb` - full analysis notebook
- `complaints_dashboard.png` - summary dashboard
- `confusion_matrix.png` - ML classification results

## Dataset
[CFPB Consumer Complaint Dataset](https://www.kaggle.com/datasets/namigabbasov/consumer-complaint-dataset) - 2M+ real complaints (2011–2024)
