Project Overview

This project focuses on segmenting mall customers based on their Annual Income and Spending Score. Customer segmentation is a crucial marketing strategy that helps businesses tailor their offerings and marketing efforts to different customer groups effectively. By understanding the characteristics and behaviors of different segments, the mall can enhance customer satisfaction and boost sales.

Motivation

The motivation behind this project is to provide actionable insights to the mall's management and marketing teams. By dividing customers into meaningful segments, the mall can:
Customize marketing campaigns to target specific customer groups.
Optimize store layouts and product placements to improve customer experience.
Develop personalized promotions and loyalty programs.
Identify high-value customer segments for focused attention.

Data

The dataset is acquired from Kaggle and the link is given below :
 /kaggle/input/customer-segmentation-tutorial-in-python/Mall_Customers.csv
The dataset used in this project contains customer information, including:
CustomerID: A unique identifier for each customer.
Gender: The gender of the customer.
Age: Age of the customer.
Annual Income (k$): Annual income of the customer.
Spending Score (1-100): Spending score assigned to the customer.

Data Preprocessing
The data was cleaned and preprocessed to handle missing values and ensure consistency. This included:
Handling missing data (if any).
Encoding categorical variables.
Scaling numerical features.

Exploratory Data Analysis (EDA)

The EDA phase involved exploring the data's characteristics, distribution, and relationships. Key findings from the EDA include:
Distribution of customer age.
Annual income distribution.
Spending score distribution.
Pair plots and heatmaps to visualize correlations between variables.

Customer Segmentation

In this project, we employed K-Means clustering, a popular unsupervised machine learning technique, to segment customers based on their Annual Income and Spending Score.

K-Means Clustering

We used the K-Means clustering algorithm to identify distinct customer segments.
The optimal number of clusters was determined using the "elbow method."

Results

Visualizations and analysis of the customer segments.
Insights and recommendations for the mall's management and marketing teams.# Mall-Customers-Segmentation-internsavy-
