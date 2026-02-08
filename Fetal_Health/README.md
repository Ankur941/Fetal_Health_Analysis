# Fetal Health Classification Analysis

Improved machine learning analysis for classifying fetal health status using cardiotocogram (CTG) data.

## 📊 Project Overview

This project classifies fetal health into three categories:
- **Normal** (Class 1)
- **Suspect** (Class 2)  
- **Pathological** (Class 3)

## 🎯 Key Improvements

- ✅ Comprehensive data exploration with visualizations
- ✅ QuantileTransformer for handling outliers and skewed distributions
- ✅ Feature selection using Random Forest importance
- ✅ GridSearchCV for hyperparameter optimization
- ✅ Clean pipelines (QuantileTransformer → SMOTE → Classifier)
- ✅ SMOTE for class imbalance handling
- ✅ VotingClassifier ensemble method
- ✅ Proper cross-validation throughout

## 📈 Results

**Best Model: Random Forest - 92.02% Accuracy**

See detailed [Performance Analysis](Performance_Analysis.md) for complete breakdown.

## 📁 Files

- `Bootcamp_refined.ipynb` - Main analysis notebook
- `Performance_Analysis.md` - Detailed model performance report

## 🚀 Usage

Open `Bootcamp_refined.ipynb` in Jupyter Notebook to see the complete analysis.
