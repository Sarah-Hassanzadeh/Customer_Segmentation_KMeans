# 🛍️ Customer Segmentation Using K-Means Clustering

An Unsupervised Machine Learning project designed to segment mall customers into distinct groups based on their annual income and spending score, helping businesses identify target customer segments for marketing strategies.

---

## 📌 Project Overview
Understanding customer behavior is essential for retail and commercial businesses. In this project, the K-Means Clustering algorithm is applied to group customers with similar purchasing behaviors, and the Elbow Method is utilized to determine the optimal number of clusters.

---

## 🛠️ Tech Stack & Tools
- Language: Python 3.13
- Libraries: 
  - Data Processing: pandas, numpy
  - Visualization: matplotlib, seaborn
  - Machine Learning: scikit-learn (KMeans, StandardScaler)
- IDE: Visual Studio Code / Jupyter Notebook

---

## 📊 Dataset Features
The dataset (Mall_Customers.csv) includes:
- CustomerID: Unique ID assigned to the customer
- Genre: Gender of the customer
- Age: Age of the customer
- Annual Income (k$): Annual income of the customer
- Spending Score (1-100): Score assigned by the mall based on customer behavior and spending nature

---

## 🤖 Machine Learning Workflow
1. Data Exploration & Preprocessing: Loaded the dataset, inspected features, and normalized the data using StandardScaler.
2. Optimal Clusters (Elbow Method): Plotted the Within-Cluster Sum of Squares (WCSS) against the number of clusters to find the optimal $K$ value (Elbow point).
3. K-Means Modeling: Trained the KMeans model with the optimal clusters and assigned each customer to a specific segment.
4. Data Visualization: Created scatter plots showing distinct customer clusters along with cluster centroids.

---

## 📈 Key Visualizations

### 1. The Elbow Method Graph
Determining the optimal number of clusters ($K$):
![Elbow Method](elbow_method.png)

### 2. Customer Segmentation Output
Visualizing the clusters based on Annual Income and Spending Score:
![Customer Segmentation](mall_customers_segmentation.png)

---

## 🚀 How to Run
1. Clone the repository:
   `bash
   git clone [https://github.com/Sarah-Hassanzadeh/Customer-Segmentation-KMeans.git](https://github.com/Sarah-Hassanzadeh/Customer-Segmentation-KMeans.git)
