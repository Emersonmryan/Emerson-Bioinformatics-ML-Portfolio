# Hybrid Protein Classification
## Integrating Sequence and Structural Features for Enhanced Predictive Accuracy

### Overview
This project develops a hybrid multi-modal deep learning model for protein function classification—combining amino acid sequence data with structural/experimental features to outperform sequence-only models.

### Dataset
- **Source**: [Kaggle - Protein Sequence & Structural Data (pdb_data_seq.csv)](https://www.kaggle.com/code/navabhi256/protein-classification/input?select=pdb_data_seq.csv)
- **Raw Data**: 140,911 protein entries (X-ray crystallography data from PDB)
- **Cleaned Data**: 60,757 high-quality samples (57% retention after preprocessing)

### Research Gap Addressed
Standard protein classification models rely only on sequence data, which limits performance when sequence similarity is low. This project adds structural/experimental features (pH, resolution, molecular weight) to improve accuracy.

### Model Architecture
Final Design: Single-Input CNN + LSTM
1. Feature merging (sequence embeddings + numerical structural features)
2. CNN layer for local motif detection
3. LSTM layer for long-range sequence dependencies
4. Softmax classification layer

### Key Findings
1. Structural features add unique predictive signal (12% accuracy boost)
2. Simple merged architectures outperform complex multi-input designs
3. Rigorous data cleaning is critical for bioinformatics ML (removed 43% noisy data)

### Tools
Python, Pandas, NumPy, TensorFlow/Keras, Matplotlib, Seaborn, Jupyter Notebook
