🛍️ Customer Segmentation using K-Means Clustering
This project focuses on customer segmentation using unsupervised machine learning techniques. It utilizes K-Means clustering to group mall customers based on attributes like age, annual income, and spending score. Such segmentation helps businesses tailor marketing strategies to target specific customer groups more effectively.
📁 Project Overview
The dataset includes features such as:
CustomerID
Gender
Age
Annual Income (k$)
Spending Score (1-100)
The goal is to identify distinct customer clusters based on their purchasing behavior and demographics.
🧠 Approach
Performed data cleaning and handled missing/duplicate values.
Conducted Exploratory Data Analysis (EDA) with visual insights.
Applied K-Means Clustering on selected features.
Used the Elbow Method and Silhouette Score to determine the optimal number of clusters (K=5).
Visualized the clusters in 2D and 3D plots for better understanding of customer groups.
🛠️ Technologies Used
Python
Pandas, NumPy
Matplotlib, Seaborn
Scikit-learn (KMeans, silhouette_score)
3D Visualization (matplotlib mplot3d)
📊 Key Highlights
Analyzed 200+ customer records from a mall dataset.
Achieved interpretable segmentation into 5 unique clusters.
Created multiple cluster visualizations: Income vs Spending Score, Age vs Spending Score, and 3D clustering plots.
📈 Visual Insights
Gender distribution and age-income-spending patterns
Elbow plot and silhouette analysis for optimal K
Cluster visualization in both 2D and 3D
✅ Future Work
Integrate clustering results into a customer recommendation engine.
Deploy interactive dashboards for business users using Streamlit or Dash.
Try other clustering techniques like DBSCAN or Hierarchical Clustering.
