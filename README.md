# Customer Segmentation using Unsupervised Learning
### DecodeLabs Data Science Internship — Project 3 (Week 3)

## 📌 Overview
This project applies **Unsupervised Machine Learning** to segment mall customers
into distinct groups based on their **Age, Annual Income, and Spending Score**.

## 🎯 Objectives
- Apply **PCA (Principal Component Analysis)** for dimensionality reduction
- Use **K-Means Clustering** to group customers
- Validate the optimal number of clusters using:
  - **Elbow Method**
  - **Silhouette Score**
- Translate clusters into actionable **business personas**

## 🛠️ Tech Stack
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn (StandardScaler, PCA, KMeans, Silhouette Score)

## 📂 Files
| File | Description |
|------|-------------|
| `Customer_Segmentation_Project3.ipynb` | Main Jupyter Notebook with full pipeline |
| `Mall_Customers.csv` | Dataset used for clustering |
| `README.md` | Project documentation |

## 🔄 Pipeline (IPO Architecture)
1. **Scale** – Standardize features using `StandardScaler`
2. **Compress** – Reduce dimensions using `PCA`
3. **Cluster** – Apply `K-Means` clustering
4. **Translate** – Convert clusters into human-readable business personas

## 📊 Results
The model identifies distinct customer segments such as:
- High-Value Trendsetters
- Affluent Conservatives
- Budget-Conscious Explorers
- Conservative Minimizers
- Balanced Majority

Each segment comes with a recommended **marketing action**.

## 🚀 How to Run
```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
jupyter notebook Customer_Segmentation_Project3.ipynb
```

## 📈 Future Improvements
- Test on a real dataset with 20+ features
- 3D visualization of PCA components
- Compare with DBSCAN / Hierarchical Clustering

---
*Part of the DecodeLabs Industrial Training Kit — Batch 2026*
