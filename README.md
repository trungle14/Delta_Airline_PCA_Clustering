# Delta-Fleet-Analysis
Delta Airlines' website have data on all of their aircraft in a certain site section.We will try to investigate the different aircraft in Delta’s fleet, including their similarity and difference in this project.

## Introduction
This GitHub repository hosts a comprehensive analysis project focusing on Principal Component Analysis (PCA) and clustering techniques. The project includes detailed Jupyter notebooks that demonstrate the application of PCA to reduce dimensionality of datasets, followed by the use of clustering algorithms to identify distinct groups within the data. Through insightful visualizations and code, the project aims to provide a deep understanding of these powerful data analysis methods.

## Dependencies
Python, Numpy, Pandas, Matplotlib, Seaborn, Sklearn

![delta-plane-exterior-KNOWDELTA0621-39eb72ab62704acf9167adb2c08e62e9](https://github.com/trungle14/Delta_Airline_PCA_Clustering/assets/143222481/0e801f2f-f054-4bf1-818a-216c58c10374)




### Delta Airlines' website have data on all of their aircraft in a certain site section. In hands-on project, we will investigate the different aircraft in Delta’s fleet. Which planes are similar? Which are dissimilar?


So, now that we’ve simplified the complex data set into a lower dimensional space we can visualize and work with, we will use clustering to find patterns in the data, in our case, the aircraft which are most similar?

![image](https://github.com/trungle14/Delta_Airline_PCA_Clustering/assets/143222481/d8fbfdf1-005e-4bc3-8cdf-9b30d5d31618)



<img width="389" alt="Screenshot 2024-02-24 at 23 55 44" src="https://github.com/trungle14/Delta_Airline_PCA_Clustering/assets/143222481/215cfe59-c42a-4c12-b4b9-a745d8895449">



So, now that we’ve simplified the complex data set into a lower dimensional space we can visualize and work with, we will use clustering to find patterns in the data, in our case, the aircraft which are most similar?

<img width="454" alt="Screenshot 2024-02-24 at 23 35 41" src="https://github.com/trungle14/Delta_Airline_PCA_Clustering/assets/143222481/60bf5bf9-4cf8-4761-9e05-5546b3a3f793">

Upper Left Cluster (Red Dot): This cluster contains a single data point far away from all others. This could be an outlier or a point that significantly differs from the rest of the data in the higher-dimensional space. It is colored red and is positioned at a high value along Principal Component 2 and a low value along Principal Component 1.

Bottom Center Cluster (Cyan Dots): This cluster is tightly grouped around the center of the plot, indicating that these data points are similar to each other based on the values of the two principal components. The data points are colored cyan, and they spread slightly along the Principal Component 1 axis while being clustered closely around a low value of Principal Component 2.

Right Center Cluster (Yellow Dots): This cluster is made up of points that are more spread out than the bottom center cluster and are located in the middle to the right side of the plot. The points are colored yellow, and they appear to have moderate values along both Principal Component 1 and Principal Component 2.

Top Right Cluster (Purple Dots): This cluster is sparse and has points that are higher along the Principal Component 2 axis and spread across a range of values along the Principal Component 1 axis. The points are colored purple, and they are less densely packed compared to the bottom center cluster, indicating more variation within this cluster.
