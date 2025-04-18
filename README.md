
# 🍷 Wine Clustering Assignment

## 📌 Question:
Comparitive performance study of different clustering algorithms using different pre-processing techniques with different numbers of clusters on different evaluation parameters
Select any small dataset from UCI library
Create Colab notebook and perform cluster alaysis
Upload on github and describe in brief with results, tables, graphs and conclusion and upload on github.


## ⚙️ Algorithms Compared
-KMeans Clustering
-Agglomerative (Hierarchical) Clustering
-Mean Shift Clustering

## 🧹 Preprocessing Techniques Applied
-No Processing (Raw data)
-Normalization (MinMaxScaler)
-Standardization (StandardScaler)
-PCA (Principal Component Analysis with 2 components)
-Standardization + Normalization (T+N)
-Standardization + Normalization + PCA (T+N+PCA)

## 📊 Evaluation Metrics
- **Silhouette Score**
- **Calinski-Harabasz Index**
- **Davies-Bouldin Score**
- **Adjusted Rand Index (only for evaluation, not training)**

## 📈 Visualizations
- Scatter plots of clusters (2D PCA space)
- Dendrograms for hierarchical clustering
- Elbow method and Silhouette analysis plots to determine optimal clusters
- Heatmaps and pairplots for feature relationships

## 📦 Dataset
**UCI Wine Dataset**  
Loaded using:  
```python
from sklearn.datasets import load_wine
```
- 178 samples
- 13 features
- 3 target classes (used only for evaluation)

## 📁 Project Structure
```
Wine-Clustering/
│
├── Clustering.ipynb            # Main Jupyter notebook
├── README.md                   # This file
├── data/                       # (Optional) Folder for exporting dataset if needed
├── plots/                      # Saved visualizations
└── requirements.txt            # Required Python packages
```

## 🚀 How to Run
1. Clone this repo:
   ```bash
   git clone <repo-url>
   cd Wine-Clustering
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Open the notebook:
   ```bash
   jupyter notebook Clustering.ipynb
   ```

## 📋 Requirements
List of required Python packages (included in `requirements.txt`):
- numpy
- pandas
- matplotlib
- seaborn
- scikit-learn
- scipy

To install:
```bash
pip install -r requirements.txt
```
