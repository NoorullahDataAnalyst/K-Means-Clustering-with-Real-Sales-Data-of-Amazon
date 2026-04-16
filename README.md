# K-Means-Clustering-with-Real-Sales-Data-of-Amazon Customer Segmentation
## Amazon Customer Segmentation: K-Means Clustering
This project applies K-Means Clustering to a real-world dataset of 50 Amazon customers to identify distinct shopping behaviors. By grouping customers based on their purchasing patterns, businesses can create more targeted marketing strategies and personalized recommendations.
## 🚀 Project Overview
In this analysis, we process sales data to uncover hidden patterns among 50 unique customers. The goal is to segment these shoppers into clusters that represent "High Spenders," "Frequent Shoppers," or "Budget-Conscious" groups.
## 📊 Dataset Features
The model analyzes the following key attributes for 50 customers:

* Customer ID: Unique identifier for each shopper.
* Annual Income: Total yearly earnings.
* Spending Score: A metric (1–100) assigned by Amazon based on customer behavior and purchasing history.
* Purchase Frequency: How often the customer shops.

## 🛠️ Tech Stack

* Python 3.x
* Pandas: For data manipulation and cleaning.
* Scikit-learn: For implementing the K-Means algorithm.
* Matplotlib / Seaborn: For data visualization.

## 📈 Visualizations
The project includes several key visual insights:

   1. Elbow Method: A plot used to determine the optimal number of clusters ($k$) by measuring the Within-Cluster Sum of Squares (WCSS).
   2. Cluster Scatter Plot: A 2D visualization (Income vs. Spending Score) where each color represents a different customer segment.
   3. Centroids: Clearly marked "center points" for each group to show the average profile of each cluster.

## 🔍 Key Findings
After clustering the 50 customers, we identified:

* Cluster 1: High income, high spending (Target for luxury goods).
* Cluster 2: Average income, average spending (Stable core customers).
* Cluster 3: High income, low spending (Target for discount alerts).

## 💻 How to Run

   1. Clone this repository.
   2. Install dependencies: pip install pandas matplotlib seaborn scikit-learn
   3. Run the Jupyter Notebook or Python script to generate the clusters and plots.

------------------------------

