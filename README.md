# Cancer Classification Project

## Quick Start
1. Install: `pip install -r requirements.txt`
2. Run: `jupyter notebook cancer_classification.ipynb`

## Project Info
- Classifies 5 cancer types from genomic data
- Uses Random Forest and SVM
- TCGA dataset with 2000 samples, 1500 genes


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
