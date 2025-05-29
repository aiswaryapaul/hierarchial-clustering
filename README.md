# Mall Customer Segmentation using Hierarchical Clustering

This project performs customer segmentation using **hierarchical clustering** on the widely-used **Mall Customers dataset**. The goal is to group customers based on features like **Annual Income** and **Spending Score**, enabling targeted marketing strategies.

## 📊 Dataset



- `CustomerID` – Unique customer ID
- `Gender` – Male or Female
- `Age` – Age of the customer
- `Annual Income (k$)` – Annual income in thousands
- `Spending Score (1-100)` – Score assigned based on customer behavior and spending nature

## 🧠 Objective

To segment customers into clusters using **agglomerative hierarchical clustering**, which helps in:

- Understanding customer groups
- Targeting specific segments with marketing strategies
- Improving customer satisfaction and retention

## 🛠️ Techniques Used

- Data preprocessing
- Dendrogram plotting using `scipy.cluster.hierarchy`
- Agglomerative clustering using `sklearn.cluster.AgglomerativeClustering`
- Cluster visualization with matplotlib

## 📈 Visualizations

- Dendrogram to determine the optimal number of clusters
- Scatter plot to visualize cluster formation

## 📂 Project Structure

