# Customer Segmentation using K-Means Clustering

This project implements **K-Means clustering** to segment customers of a retail store based on their **purchase behavior**.  
Additionally, the clustering quality is evaluated using the **Silhouette Score** to ensure well-defined clusters.

---

##  Dataset
**Customer Segmentation Tutorial in Python** (Kaggle)

🔗 https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python

### Dataset Features
- CustomerID
- Gender
- Age
- Annual Income (k$)
- Spending Score (1–100)

---

##  Objective
To group customers into meaningful segments using **unsupervised learning** and validate the clustering performance using:
- Elbow Method
- Silhouette Score

---

##  Methodology
1. Load and explore the dataset  
2. Select relevant features  
3. Determine optimal number of clusters using **Elbow Method**  
4. Apply **K-Means Clustering**  
5. Evaluate clustering using **Silhouette Score**  
6. Visualize customer segments  
7. Interpret clusters for business insights  

---

##  Technologies Used
- Python
- NumPy
- Pandas
- Matplotlib
- Scikit-learn

---

##  Algorithms & Techniques
### 🔹 K-Means Clustering
- Distance Metric: Euclidean Distance  
- Initialization: k-means++  

### 🔹 Elbow Method
- Used to determine optimal number of clusters by analyzing **WCSS**

### 🔹 Silhouette Score
- Measures how well each data point fits within its cluster
- Score range: **-1 to +1**
  - +1 → Well-clustered
  - 0 → Overlapping clusters
  - -1 → Incorrect clustering

---

##  Results
- Optimal number of clusters selected: **5**
- Silhouette Score confirms good cluster separation
- Customers grouped into segments such as:
  - High income – high spending
  - High income – low spending
  - Low income – high spending
  - Low income – low spending
  - Average income – average spending

These insights help in:
- Targeted marketing
- Personalized offers
- Improved customer retention

---


