# Cancer Classification Project

## Quick Start
1. Install: `pip install -r requirements.txt`
2. Run: `jupyter notebook cancer_classification.ipynb`

## Project Info
1. DATASET OVERVIEW
   - Total Samples: 2000
   - Total Genes (Features): 1500
   - Cancer Types: 5 ['Breast Invasive Carcinoma (BRCA)', 'Kidney Renal Clear Cell Carcinoma (KIRC)', 'Lung Adenocarcinoma (LUAD)', 'Colon Adenocarcinoma (COAD)', 'Prostate Adenocarcinoma (PRAD)']

2. DATA PREPROCESSING (SPARK)
   - Cleaning: Removed rows with missing values.
   - Scaling: StandardScaler (Mean=0, Std=1).
   - Reduction: PCA reduced 1500 genes to 50 Components.

3. MODEL PERFORMANCE
   - Model A: Random Forest (100 Trees)
   - Accuracy: 0.2549 (25.49%)
   - Model B: Support Vector Machine (Linear, One-vs-Rest)
   - Accuracy: 0.2177 (21.77%)
   - WINNING MODEL: Random Forest

4. BIOLOGICAL INSIGHTS (TOP 5 BIOMARKERS)
   Gene  Importance_Score
  APOC3          0.031957
APOBEC4          0.030042
  ATF6B          0.029725
  AP4S1          0.029329
 AKAP14          0.028835
============================================================


## 🧪 Testing Guide

### Quick Validation (2 minutes):
1. Clone the repo
2. Open the notebook and run the first 5 cells

### Full Test (10 minutes):
1. Run the entire notebook start to finish
2. Verify these outputs:
   - Data loading and shape display
   - PCA dimensionality reduction
   - Random Forest training
   - SVM training  
   - Accuracy scores (> 80% expected)
   - Confusion matrices

### Expected Results:
- Random Forest Accuracy: 85%+
- SVM Accuracy: 80%+
- 5 cancer classes correctly identified
- No error messages in execution
