# Algorithm-for-Massive-Data
# Project 1: Finding similar items

## Author
Togzhan Seitzhagyparova  
Master in Data Science for Economics  
Università degli Studi di Milano  

## Files Included
- **Project_1_clean.ipynb** – Jupyter Notebook containing the full code pipeline:
  - Data download via Kaggle API
  - Preprocessing (cleaning, language filtering, tokenization)
  - Duplicate detection with TF–IDF + Cosine Similarity and MinHash + LSH
  - Graph construction and cluster analysis
  - Evaluation with Precision, Recall, and F1-score
  - Visualizations and qualitative examples
- **Report on project 1.pdf** – Final report (≈7 pages) including:
  - Introduction and motivation
  - Dataset and preprocessing description
  - Methodology
  - Experimental results
  - Graphs and discussion
  - Conclusion and declaration of originality
- **README.md** – This file, providing instructions and project overview.

## How to Run the Notebook
1. Open **Project_1_clean.ipynb** in **Google Colab** (recommended).  
2. In the first code cell, add your **Kaggle API credentials**:  
   ```python
   !mkdir -p ~/.kaggle
   !echo '{"username":"YOUR_USERNAME","key":"YOUR_KEY"}' > ~/.kaggle/kaggle.json
   !chmod 600 ~/.kaggle/kaggle.json
