Project Overview
This project performs an in-depth analysis of an eCommerce transaction dataset to gain actionable business insights, build predictive models, and segment customers into clusters based on their purchasing behavior. It demonstrates the application of data analysis, machine learning techniques, and visualization for data-driven decision-making.

Key Features:

Exploratory Data Analysis (EDA):
Identified top customers by revenue, best-selling products, and revenue trends over time.
Derived region-wise revenue distribution for market expansion opportunities.
Delivered five actionable business insights to improve operations and marketing strategies.

Lookalike Model:
Built a model using cosine similarity to identify the top 3 similar customers for each user based on their purchasing behavior.
Provided personalized customer recommendations for targeted marketing.

Customer Segmentation:
Implemented KMeans clustering to group customers into 4 distinct clusters based on total spend, quantity purchased, and region of activity.
Evaluated the clustering model using metrics like Davies-Bouldin Index and Silhouette Score.
Visualized the clusters using PCA to understand customer groups better.

Project Deliverables

EDA Insights Report:
Summarized key findings and actionable insights.
Highlighted the top-performing customers, products, and regions.

Lookalike.csv File:
Contains the top 3 lookalike customers and similarity scores for each user.

Clustering Results Report:
Number of clusters formed: 4.
Evaluation metrics:
Davies-Bouldin Index: Indicates compactness and separation of clusters.
Silhouette Score: Reflects the quality of clustering.
PCA-based visualization of clusters.

Python Code:
Jupyter Notebooks/Python scripts for all tasks:
Data loading and preprocessing.
EDA and visualization.
Lookalike model development.
Customer segmentation using clustering.

Technologies Used
Programming Language: Python
Libraries:
Pandas, NumPy (Data manipulation)
Matplotlib, Seaborn (Visualization)
Scikit-learn (Machine learning models and metrics)
PCA (Dimensionality reduction for visualization)
