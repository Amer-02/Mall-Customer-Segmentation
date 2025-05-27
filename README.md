# 🛍️ Mall Customer Segmentation with K-Means Clustering

This project demonstrates how **K-Means Clustering**, an unsupervised machine learning algorithm, can be used to segment mall customers based on their demographics and spending behavior. By identifying distinct customer groups, businesses can design more effective marketing strategies and enhance customer experience.

---

## 📂 Files

`Mall_Customers.csv`  - Original dataset
`Customer_Segmentation_Mall.ipynb` - Python script

### Dataset Features:
- `CustomerID` – Unique customer identifier
- `Gender` – Male or Female
- `Age` – Customer's age
- `Annual Income (k$)` – Annual income in thousands of USD
- `Spending Score (1-100)` – A score assigned by the mall based on spending behavior and purchasing patterns

---

## 🚀 Key Highlights

✅ Clean and preprocess data for clustering  
✅ Visualize demographic and spending distributions  
✅ Determine optimal number of clusters using:
    - Elbow Method
    - Silhouette Score
✅ Perform K-Means clustering  
✅ Visualize clusters in 2D and 3D  
✅ Derive actionable insights from cluster characteristics

---

## 📊 Tools & Technologies Used

- Python
- Jupyter Notebook
- `pandas`, `numpy` – Data manipulation
- `matplotlib`, `seaborn`, `plotly` – Data visualization
- `scikit-learn` – Machine learning and clustering

---

## 🧠 Insights

The final clusters revealed interesting customer personas, such as:
- High income, low spending: Potential targets for promotional campaigns (Cluster 3)
- Low income, high spending: Impulsive shoppers (Cluster 0)
- Moderate income and spending: Budget-conscious customers (Cluster 1 and 4)

These insights can help in:
- Personalizing advertisements
- Designing loyalty programs
- Optimizing store layout and inventory
- Identifying high-value segments (Clusters 0 and 2)

---

## 🔮 Future Enhancements

- Add clustering comparison with DBSCAN and Agglomerative Clustering
- Automate cluster interpretation with NLP summaries
- Deploy as a Streamlit dashboard for interactive exploration

---
