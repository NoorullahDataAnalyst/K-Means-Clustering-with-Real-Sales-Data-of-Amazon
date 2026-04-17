## 🛒 Amazon Sales Profiler

K-Means Clustering on Real-World Order Data

## ⚡ The Objective
We took 50 Amazon orders and used Machine Learning to slice them into 3 distinct spending personas. No more guessing—just data-driven segmentation.
------------------------------
## 💎 The 3-Tier Breakdown

| Tier | Volume | Avg. Spend | Persona |
|---|---|---|---|
| 🥉 Low Budget | 20 Orders | $125 | Practical & Budget-Conscious |
| 🥈 Medium | 10 Orders |  $225 | The Balanced Middle |
| 🥇 VVIP / High | 20 Orders | $375 | Premium High-Value |

------------------------------
## 🛠️ The Toolkit

* Engine: K-Means Algorithm
* Data: 50 Real Sales Records
* Visuals: Seaborn & Matplotlib
* Logic: $K=3$ (Finding the "sweet spot" for each group)

------------------------------
## 🧠 How It Works

   1. Clustering: The algorithm identifies two major anchors at $125 and $375.
   2. K-Value: We set $K=3$ to isolate the extremes from the average shoppers.
   3. Visualization: We plot the coordinates to see the "gravity" of each cluster.

# Quick Look at the Core Logickmeans = KMeans(n_clusters=3, init='k-means++', random_state=42)y_kmeans = kmeans.fit_predict(X)

------------------------------
## 🎨 Visual Identity

* Cluster 1 (Low): 🟢 Green Points
* Cluster 2 (Medium): 🟡 Yellow Points
* Cluster 3 (VVIP): 🔴 Red Points (Centroid at $375)

------------------------------
Want to try it?
------------------------------
git clone https://github.com/NoorullahDataAnalyst/K-Means-Clustering-with-Real-Sales-Data-of-Amazon
------------------------------
After that lab will be ready for open. 
------------------------------

