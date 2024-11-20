# Social-Media-Advertising-

DS605: Fundamentals of Machine Learning

A
Project on
Social Media Advertising

Submitted by

Meenakshi Iyer
202418031
Kshiti Mulani
202418034
Sreelakshmi Nair
202418037
Shaili Parikh
202418049

Submitted to

Prof. Arpit Rana

And

Teaching Assistants:

Himanshu Beniwal
Bhavan Bhatt













		
Project Overview:

The project focuses on leveraging social media data from platforms like Instagram, Facebook, Twitter, and Pinterest to enhance advertising strategies using clustering and unsupervised learning. It identifies patterns in user behavior and preferences, aiming to segment audiences effectively and optimize ad targeting for better campaign performance.

Data Analysis & Pre-processing:
We collected a comprehensive dataset containing social media advertising metrics such as Campaign ID, Campaign Goal, ROI, Engagement Score, and Customer Segments. The dataset was preprocessed to handle missing values, outliers, and inconsistencies in features such as Clicks, Impressions, and Acquisition Cost. Feature engineering techniques were applied to create new derived metrics or transform existing ones to enhance clustering performance and insights

Machine Learning Models:

We employed K-Means, Gaussian Mixture Model (GMM), and DBSCAN. K-Means is efficient and simple, ideal for large datasets with well-defined clusters. GMM offers a probabilistic approach, allowing for soft clustering and better modeling of complex relationships. DBSCAN is effective in identifying clusters of varying shapes and densities, while also detecting noise. These models were chosen to provide diverse perspectives on clustering and extract meaningful insights from the data.


Model Application and Evaluation:

We employed K-Means, Gaussian Mixture Model (GMM), and DBSCAN to identify patterns in the data. To evaluate the quality of the clusters, we used the Silhouette Score, which measures how similar data points are to their own cluster compared to other clusters. We also visualized the clusters using various charts, providing clear insights into the distribution and performance of the different clustering models. This approach allowed us to identify the most effective clustering method for understanding advertisement campaign data.



Conclusions:
GMM produced the best results in terms of cluster quality, offering more nuanced groupings and better capture of data complexity. On the other hand, K-Means proved to be a simpler and more efficient option, particularly for faster computations, making it suitable for larger datasets or real-time applications.


Insights:
 
The clustering analysis provided valuable insights into customer segmentation, allowing for more targeted marketing strategies. By identifying distinct audience groups, we can optimize ad spend and focus on high-converting segments.

