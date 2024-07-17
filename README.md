Market Techniques using customer segmentation

The project focuses on customer segmentation using machine learning techniques, specifically clustering algorithms such as K-Means, K-Medoids, and Hierarchical clustering. The objective is to group customers based on their Age, Rating, and Positive Feedback Count and derive meaningful insights for targeted marketing strategies.

Data Exploration:

•	The dataset used is 'Womens.csv'.

•	Features selected for analysis: 'Age', 'Rating', and 'Positive Feedback Count'.

•	Data split into training and testing sets (80/20).


Data Preprocessing:

•	Numerical features scaled using StandardScaler.

•	K-Means clustering applied to training data.

•	Cluster labels assigned to both training and testing datasets.


Marketing Labels:

•	Defined marketing labels for each cluster to provide meaningful insights.

•	Labels include campaigns and strategies tailored to specific customer segments.

![image](https://github.com/evapatel1654/Marketing_Techniques_Using_Customer_Segmentation/assets/133888581/3fc277ca-5b5b-4fc2-9344-6b236df87e41)
 

Visualization:

•	Scatter plots for both training and testing datasets, highlighting clusters with specific colors.
 ![image](https://github.com/evapatel1654/Marketing_Techniques_Using_Customer_Segmentation/assets/133888581/c34cfe6e-4a24-480c-9bc0-9f6366ce7050)
![image](https://github.com/evapatel1654/Marketing_Techniques_Using_Customer_Segmentation/assets/133888581/310f3187-35df-493f-af22-e795b846e0c4)

 
•	Pie chart showcasing the distribution of data points in each cluster.
![image](https://github.com/evapatel1654/Marketing_Techniques_Using_Customer_Segmentation/assets/133888581/f230c4ab-c33f-47a7-9c73-e35a8051c12b)

 
Cluster Centers:

•	Cluster centers calculated and displayed, providing the central tendencies of each cluster.

![image](https://github.com/evapatel1654/Marketing_Techniques_Using_Customer_Segmentation/assets/133888581/7dc1aed8-19f0-4c98-a9ee-078e86f1ea2d)

 
Additional Feature Visualization:

•	Visualized clusters using PCA (Principal Component Analysis) and t-SNE (t-distributed Stochastic Neighbor Embedding).

•	Evaluated Silhouette Score for K-Means clustering.

•	Dendrogram representation of Hierarchical clustering.
![image](https://github.com/evapatel1654/Marketing_Techniques_Using_Customer_Segmentation/assets/133888581/201613a7-9157-41f1-9c69-29fcc8636044)


![image](https://github.com/evapatel1654/Marketing_Techniques_Using_Customer_Segmentation/assets/133888581/9ca616a7-e2f3-4840-b5ed-56940d64f6f3)

 ![image](https://github.com/evapatel1654/Marketing_Techniques_Using_Customer_Segmentation/assets/133888581/b37216cb-7ce4-4fb8-aaf9-9549b991c5e0)

![image](https://github.com/evapatel1654/Marketing_Techniques_Using_Customer_Segmentation/assets/133888581/fe5ee26f-86cb-4fbc-a053-df5b338ddc8f)

 
Cluster Profiling:

•	Cluster profiling done through feature visualizations, helping to understand the characteristics of each cluster.
 ![image](https://github.com/evapatel1654/Marketing_Techniques_Using_Customer_Segmentation/assets/133888581/77bf8288-d768-42a2-bfe7-465af15a4508)


Results:

•	K-Means clustering chosen for its higher accuracy compared to other methods.

•	Marketing labels assigned to each cluster for targeted campaigns.

•	Insights derived from visualizations aid in creating personalized marketing strategies.

Conclusion:

•	The project successfully utilizes machine learning clustering techniques for customer segmentation. The derived marketing labels provide actionable insights for businesses to tailor their strategies based on customer profiles. The visualizations enhance the interpretability of the clusters, making it easier for stakeholders to understand and implement targeted marketing campaigns.

Future Work:

•	Explore additional clustering algorithms for comparison.

•	Incorporate more features for a comprehensive customer segmentation.

•	Continuously update and refine marketing labels based on ongoing customer data.
