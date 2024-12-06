# Driving-Growth
Driving Growth Through Customer Insights and Segmentation
Table of Contents
Executive Summary
Driving Growth Through Customer Insights and Segment
n
Business Problem
Identify customer segments.
Drive targeted marketing strategies. the - Assess strengths and weaknesses of s2gments.
Data Preprocessing
Data cleaning and transformation.
Variable3selection.
Exploratory Data Analysis (EDA)
Key insights into customer behaviours.
Correlation heatmaps and feature 4istributions.
Clustering Analysis
Applying K-Means clustering.
Identifying c5stomer segments.
Cluster Evaluation
Applyingthe  Elbow Method, Silhouette Score, and Davies-Bouldin Index.
Optima6 cluster selection.
Application and Recommendations
What type of company/organization could this data pertain to?
Patterns in customer behavior through clustering
Actionable insights and recommendations
Executive Summary:
"This Executive summary addresses one of the significant business challenges: to achieve visibility into customer behaviours across all disparate product divisions for fact-based decision-making in marketing as well as operations. The hypothetic multinational retail or CPG company sells a huge category of products, including personal electronics, houseware, automotive, gardening, and jewelry. Thus, customers were clustered or segmented using clustering techniques concerning their purchasing behaviours, developing a valuable insight into definite and quite sharply segmented customer groups and their predispositions. "The analysis identified four key customer segments.

Cluster 0 consists of customers who are primarily interested in Personal Electronics, with a medium interest in Garden and Novelty Gifts but minimal engagement in Housewares and Automotive.

Cluster 1 has a strong preference for Housewares and Jewelry, with some interest in Personal Electronics but weaker activity in Automotive and Garden.

Cluster 2 consists of customers whose buying involvement is minimal for most of the divisions; the interest in Jewelry was at a medium level and relatively low activities in both Automotive and Garden. Lastly,

Cluster 3 consists of customers having heterogeneous preference profiles, evinced from strong purchase activities on the Garden, Jewelry, and Novelty Gifts and notable revenue from Personal Electronics and Automotive sectors.

"Marketing effort for Cluster 0 shall be focused on Personal Electronics while offering an extension to Garden and Novelty Gifts. Cluster 1 shows an opportunity to invest in Housewares while leveraging the secondary interest in Jewelry. For Cluster 2, targeted campaigns with special offers or bundled discounts can be used to stoke interest in lagging categories of Personal Electronics and Housewares. Cluster 3 will allow the company to cross-sell products across different categories, employ bundled promotions, and offer multi-category discounts. The company can use these to align product offerings and marketing with customer preferences, optimize inventory planning, and drive campaigns for engagement and revenue across the diverse product divisions. egies.

1.0 - Business Problem
"In our group project, we focused on addressing a business problem faced by a large retail or consumer goods company operating across diverse product divisions such as Personal Electronics, Housewares, Automotive, Garden, and Jewelry. Our objective was to analyze customer data to gain insights into purchasing behaviours and leverage those insights to enhance business outcomes. "The key goals of our project were to:

Identify Customer Segments: Use clustering techniques to uncover distinct customer segments based on their purchase behaviours across the various product divisions.\n",

Drive Targeted Marketing Strategies: Develop tailored marketing strategies, refine product offerings, and design targeted promotions to better serve each customer segment.

Assess Segment Strengths and Weaknesses: Understand the strengths (dominant purchase areas) and weaknesses (low or no purchases) of each segment to optimize inventory, sales strategies, and customer engagement initiatives."
#import necessary libraries
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
