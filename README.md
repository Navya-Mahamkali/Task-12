# Task-12
# Mall Customer Segmentation using K-Means Clustering

## 📌 Project Overview
This project performs customer segmentation using the K-Means clustering algorithm. The goal is to group customers based on their annual income and spending score to identify distinct customer types for targeted marketing strategies.

---

## 📊 Dataset
- Dataset Name: Mall Customers Dataset
- Total Records: 200 (approx.)
- Features Used:
  - Annual Income (k$)
  - Spending Score (1–100)

- Removed Feature:
  - CustomerID (not useful for clustering)

---

## 🛠 Tools & Technologies
- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

---

## ⚙️ Steps Performed

1. Loaded dataset and explored structure
2. Selected relevant features (Income & Spending Score)
3. Dropped CustomerID column
4. Applied StandardScaler for normalization
5. Used Elbow Method to find optimal K
6. Trained K-Means model
7. Assigned cluster labels to dataset
8. Visualized clusters using scatter plot
9. Interpreted clusters into customer segments
10. Exported segmented dataset to CSV

---

## 📈 Results

- Optimal number of clusters: **K = 5**
- Customers grouped into 5 distinct segments

---

## 🔍 Customer Segments

| Cluster | Customer Type |
|--------|--------------|
| 0 | Low Income – Low Spending |
| 1 | High Income – High Spending |
| 2 | Low Income – High Spending |
| 3 | High Income – Low Spending |
| 4 | Average Customers |

---

## 📊 Outputs
- Elbow Curve (K vs Inertia)
- Cluster Visualization Plot
- Segmented Dataset (CSV file)

---

## 🚀 How to Run

1. Install dependencies:
   pip install pandas numpy matplotlib scikit-learn

2. Place dataset file:
   Mall_Customers.csv

3. Run Jupyter Notebook:
   jupyter notebook

---

## 📌 Business Insights
- Helps identify high-value customers
- Enables targeted marketing campaigns
- Improves customer retention strategies

---

## 📌 Future Improvements
- Add more features (Age, Gender)
- Use advanced clustering (DBSCAN, Hierarchical)
- Deploy dashboard using Streamlit

---

## 👨‍💻 Author
Navya Mahamkali
   
