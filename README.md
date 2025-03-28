Customer Segmentation - Clustering
This portfolio project demonstrates my ability to apply unsupervised machine learning techniques to a real-world marketing dataset, showcasing my end-to-end data science process—from data cleaning and exploratory analysis to feature engineering, modeling, and insights generation.

🎯 Project Objective
The objective of this project is to perform customer segmentation for a company’s marketing campaign data using clustering algorithms, primarily K-Means. By grouping customers with similar characteristics and behaviors, the business can design targeted marketing strategies, improve customer retention, and enhance product recommendations.

📁 Dataset Overview
Source: Kaggle - https://www.kaggle.com/code/karnikakapoor/customer-segmentation-clustering/input

Observations: ~2,240 rows

Features:

Demographics: Age (derived from Year_Birth), Marital Status, Income, Education

Customer behavior: Spending on various product categories (Wine, Fruits, Meats, etc.)

Campaign responses: Number of accepted offers

Tenure: Date of becoming a customer

Family size and living situation

🔍 Methodology
1. Data Cleaning and Preprocessing
Converted Dt_Customer into a datetime format and calculated customer tenure.

Derived Age from the year of birth and created features like total spending.

Handled missing income values.

Encoded categorical variables using Label Encoding.

Standardized numerical features using StandardScaler to prepare for clustering.

2. Exploratory Data Analysis (EDA)
Conducted visual analysis using Seaborn and Matplotlib to uncover relationships between age, income, spending habits, and campaign responsiveness.

Identified key customer trends such as:

High wine and meat spending in middle-aged groups

Distinct spending patterns across marital status and education levels

Income distribution skewness and its influence on spending

3. Feature Engineering
Created composite metrics like:

Total_Spend: Sum of spending across all product categories

Family_Size: Combination of number of children and presence of partner

Customer_Tenure: Days since first purchase

4. Clustering with K-Means
Applied K-Means clustering to group customers into segments.

Used Elbow Method with Yellowbrick’s KElbowVisualizer to identify the optimal number of clusters.

Reduced dimensionality and visualized customer clusters with 2D scatter plots.

5. Segment Profiling
Interpreted each customer segment based on demographic and behavioral characteristics.

Example insights:

Cluster 0: High-income, high-spending customers, responsive to campaigns—ideal for premium product marketing.

Cluster 2: Low-income, low-spending, unresponsive—cost-sensitive group that may need loyalty offers.

Cluster 4: Young customers with moderate income but high campaign responsiveness—good target for future growth.

📈 Key Takeaways
Successfully segmented the customer base into 5 distinct clusters.

Provided actionable marketing insights that could help increase ROI by targeting customers based on behavioral profiles.

Demonstrated strong grasp of the end-to-end machine learning pipeline for unsupervised learning problems.

🛠️ Tools & Technologies Used
Programming: Python

Libraries: Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn, Yellowbrick

Techniques: Data wrangling, feature engineering, KMeans clustering, Elbow Method, Standardization, Label Encoding
