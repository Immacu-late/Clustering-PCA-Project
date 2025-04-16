# Customer Segmentation & PCA Analysis

This project explores customer transaction data to segment users and optimize revenue strategies using unsupervised learning. It compares performance before and after applying dimensionality reduction via PCA.

---

## 🔍 Business Questions
- How can we group customers based on their transaction behaviors (e.g. region, revenue)?
- Which customer segments or regions contribute most to revenue?
- What patterns exist between transaction costs and revenue efficiency?

---

## 📊 Techniques Used
- Data Wrangling & Preprocessing
- Feature Scaling
- K-Means Clustering (optional extension)
- Dimensionality Reduction (PCA)
- Random Forest Regressor for comparison

---

## 📁 Project Structure
- `clustering_pca_analysis.ipynb`: Main analysis notebook
- `data/fct_transactions.csv`: Dataset (not included publicly)
- `requirements.txt`: Python libraries used
- `images/`: Boxplots, explained variance plots, etc.

---

## 📈 Model Results

- **Original Dataset:**  
  MSE = 0.0783  
  MAE = 0.0117

- **PCA-Reduced Dataset:**  
  MSE = 0.0664  
  MAE = 0.0242

➡️ PCA reduced the dataset to **6 components**, explaining **85%** of the variance.

---

## 🚀 How to Run

```bash
pip install -r requirements.txt
