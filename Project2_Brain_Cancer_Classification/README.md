# Pediatric Brain Cancer Genomic Classification
## Supervised Learning for Cancer Subtype Prediction from Gene Expression Data

### Overview
This project builds and compares supervised ML models to classify pediatric brain cancer subtypes using high-dimensional gene expression data—aimed at supporting early cancer diagnosis.

### Dataset
- **Source**: [Kaggle - Brain Cancer Gene Expression (CuMiDa)](https://www.kaggle.com/datasets/brunogrisci/brain-cancer-gene-expression-cumida)
- **Scope**: 130 samples, 54,676 gene expression features
- **Classes**: 5 pediatric brain cancer subtypes + normal tissue

### Pipeline
1. Data loading & label encoding (stratified to preserve class balance)
2. Train-test split (80/20)
3. Standard scaling (normalizing gene expression values)
4. PCA dimensionality reduction (54k → 50 components, 88% variance retained)
5. Model training & hyperparameter tuning (GridSearchCV)
6. Evaluation (Accuracy, Precision, Recall, F1, Confusion Matrix, ROC-AUC)

### Model Performance
| Model               | Test Accuracy | Weighted F1 | Mean AUC |
|---------------------|---------------|-------------|----------|
| Logistic Regression | 0.879         | 0.880       | 0.982    |
| Random Forest       | 0.842         | 0.838       | 0.971    |
| XGBoost             | 0.815         | 0.810       | 0.965    |
| Decision Tree       | 0.789         | 0.785       | 0.950    |

### Key Outcomes
- PCA effectively reduced dimensionality without losing predictive power
- Logistic Regression (simple, interpretable) outperformed complex tree-based models
- Model is clinically relevant for pediatric brain cancer subtype prediction

### Tools
Python, Pandas, Scikit-learn, XGBoost, Plotly, Matplotlib, Seaborn, PCA, UMAP
