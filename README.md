# Data Science (eCommerce-Transactions Dataset)

Overview
This project involves:

1.Performing Exploratory Data Analysis (EDA).
2.Building a Lookalike Model to recommend similar customers.
3.Conducting Customer Segmentation using clustering techniques.

Tasks
Task 1: Exploratory Data Analysis (EDA)
Visualized transaction patterns, revenue, customer spending, and product performance.
Identified key business insights using matplotlib and seaborn.

Task 2: Lookalike Model
Built a model to recommend 3 similar customers based on their purchase behavior.
Used cosine similarity and saved recommendations in Lookalike.csv.

Task 3: Customer Segmentation
Applied KMeans clustering to group customers.
Evaluated clusters using Davies-Bouldin Index and Silhouette Score.
Visualized customer clusters.

Technologies Used
Python
Libraries: pandas, matplotlib, seaborn, scikit-learn

How to Run
1.Ensure the datasets (Customers.csv, Products.csv, Transactions.csv) are in the specified directory.
2.Run the Python scripts for each task:
    Task 1: eda_analysis.py
    Task 2: lookalike_model.py
    Task 3: customer_segmentation.py
3.Outputs:
    EDA: Visualizations and insights in plots.
    Lookalike: Recommendations saved in Lookalike.csv.
    Segmentation: Cluster visualizations.
    
Output Files
Lookalike.csv: Contains customer recommendations with similarity scores.
