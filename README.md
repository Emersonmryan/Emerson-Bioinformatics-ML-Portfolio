# Emerson's Bioinformatics & Machine Learning Portfolio
### Year 10 Student | Melbourne Top Private School | Monash University Internship Applicant

## 👤 About Me
I am a Year 10 student at a top private school in Melbourne, passionate about **STEM, computational biology, and machine learning for biomedicine**. I have built two end-to-end ML projects focused on protein function classification and pediatric brain cancer genomic subtype prediction.

This portfolio showcases my skills in Python, data preprocessing, model building, and scientific analysis as a young STEM learner.

---

## 🧬 Project 1: Hybrid Protein Classification
**Integrating Sequence + Structural/Experimental Features for Enhanced Protein Function Prediction**

### Key Details
- **Goal**: Improve protein function prediction by combining sequence data with structural/experimental features (beyond standard sequence-only models)
- **Dataset**: [Kaggle - Protein Sequence & Structural Data](https://www.kaggle.com/code/navabhi256/protein-classification/input?select=pdb_data_seq.csv)
- **Data Scope**: 140k+ raw protein entries → cleaned to 60k+ high-quality samples (X-ray crystallography data from PDB)
- **Features**: Amino acid sequences + residue count, molecular weight, pH, resolution, density metrics
- **Models**: Character embeddings → CNN → LSTM (compared 5 iterative architectures)
- **Key Innovation**: Merged sequence + numerical features into a streamlined single-input model that outperformed complex multi-input designs
- **Tools**: Python, Pandas, TensorFlow/Keras, Matplotlib, Seaborn, Jupyter

**Key Outcomes**
- Cleaned ~57% of raw data via rigorous preprocessing (handling missing values, outliers)
- Addressed extreme class imbalance with weighted loss & macro evaluation
- Proved structural/experimental features boost prediction accuracy by 12%
- Demonstrated "simplicity over complexity" in bioinformatics ML

---

## 🧠 Project 2: Pediatric Brain Cancer Genomic Classification
**Supervised Learning for Brain Cancer Subtype Prediction from Gene Expression Data**

### Key Details
- **Goal**: Classify 5 pediatric brain cancer subtypes + normal tissue using high-dimensional gene expression profiles
- **Dataset**: [Kaggle - Brain Cancer Gene Expression (CuMiDa)](https://www.kaggle.com/datasets/brunogrisci/brain-cancer-gene-expression-cumida)
- **Data Scope**: 130 samples, 54,676 gene features (curated microarray dataset)
- **Classes**: Normal, Ependymoma, Glioblastoma, Pilocytic Astrocytoma, Medulloblastoma
- **Pipeline**: Standardization → PCA dimensionality reduction → model tuning & comparison
- **Models Compared**: Logistic Regression, Decision Tree, Random Forest, XGBoost
- **Best Model**: Logistic Regression (Accuracy = 0.879, Weighted F1 = 0.880, Mean AUC = 0.982)
- **Tools**: Python, Scikit-learn, XGBoost, Pandas, Plotly, PCA, t-SNE

**Key Outcomes**
- Reduced 54k gene features to 50 PCA components (retaining 88% variance)
- Built a clinically usable cancer subtype classifier for pediatric patients
- Conducted robust model evaluation (confusion matrix, ROC-AUC) for imbalanced clinical data

---

## 🧰 Core Skills (Year 10 STEM/Coding)
- **Programming**: Python (Pandas, NumPy, Scikit-learn, TensorFlow/Keras)
- **Data Science**: EDA, preprocessing, dimensionality reduction, model evaluation
- **Bioinformatics**: Protein/DNA sequence analysis, genomic data processing
- **ML/AI**: Supervised learning, deep learning (CNN/LSTM), class imbalance handling
- **Scientific Thinking**: Hypothesis testing, result interpretation, reproducible research

---

## 📩 Contact
- Location: Melbourne, Australia
- Email: 644146personal@gmai.com
- Education: Year 10, Top Private School
