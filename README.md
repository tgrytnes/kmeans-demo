# 🧠 K-Means Clustering on Real-World Data

This is a simple demo of K-Means clustering using real restaurant data to identify customer tipping behavior based on the total bill amount.

## 📊 Dataset

- [Seaborn tips dataset](https://github.com/mwaskom/seaborn-data)
- Features used:
  - `total_bill` (how much the customer spent)
  - `tip` (how much they tipped)

## 🔍 What the script does

- Loads the dataset from a public URL
- Applies K-Means clustering with 3 groups
- Visualizes the clusters in a scatter plot
- Saves the result to `img/tips_clusters.png`

## 🚀 How to run

```bash
pip install -r requirements.txt
python kmeans.py