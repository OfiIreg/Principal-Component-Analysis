# Anderson Cancer Center: PCA & Logistic Regression Model

This analysis demonstrates how to identify essential variables for donor funding prioritization using **Principal Component Analysis (PCA)** on a cancer dataset, followed by **Logistic Regression** for prediction.

## Analysis Steps
1. Load the Breast Cancer dataset from `sklearn.datasets`.
2. Standardize the dataset to prepare it for PCA.
3. Apply PCA to reduce the number of features to **2 principal components**.
4. Train a **Logistic Regression** model on the PCA-transformed dataset.
5. Evaluate model performance.

## Requirements
Ensure the following Python libraries are installed:

```
pip install pandas numpy scikit-learn matplotlib
```

## How to Use This Notebook
1. Open the notebook file:
   ```
   PCA Implementation on Cancer Dataset.ipynb
   ```
2. Run the cells in order (top to bottom).
3. Review:
   - PCA visualizations
   - Model accuracy
   - Confusion matrix
   - PCA loadings (important for donor funding justification)

## Key Insights
- PCA reduces dimensional complexity while retaining the most important variance in the data.
- Logistic Regression performs well even with only 2 PCA components.
- PCA loadings reveal which clinical factors contribute most to cancer diagnosis, useful for presenting findings to donors.

## Output Files
| File | Description |
|------|-------------|
| `PCA Implementation on Cancer Dataset.ipynb` | Jupyter Notebook with full analysis |
| `README.md` | Instructions and analysis explanation |

## Next Steps (Optional Enhancements)
- Expand PCA to more components and compare performance.
- Visualize PCA loadings as a heatmap.
- Deploy the model as a simple web or dashboard app.

---

## Academic Information

**Assignment:** Principal Component Analysis
**Course:** Programming in R & Python  
**Institution:** Nexford University 
**Student:** Ofure Iregbeyen  
**Date:** 07-11-2025 

---

**End of README** 

