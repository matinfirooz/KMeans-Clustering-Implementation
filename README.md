# Hardware Accelerators Course - Homework 1: KMeans Clustering Implementation

This project is the first assignment for the "Hardware Accelerators" course at Shahid Beheshti University, Faculty of Engineering and Computer Science, for the Spring semester of 1402-1403. The primary goal is to implement the KMeans clustering algorithm from scratch and apply it to two different datasets.

**Important Note:** The implementation of the KMeans algorithm must be done using only a chosen programming language and its basic functions. The use of any pre-existing libraries for KMeans is prohibited.

***

## Project Overview

The project is divided into two main parts:
1.  Clustering a 3D dataset.
2.  Performing customer segmentation on a marketing dataset.

The final submission should be a `.zip` file named `HW1_StudentNumber_Fullname.zip` containing separate sub-folders for each part of the assignment.

***

## Understanding the KMeans Algorithm

KMeans is an unsupervised learning algorithm that partitions data into a specified number of clusters. It aims to maximize the similarity of data within a cluster and minimize the similarity between different clusters, often using a distance metric like the Euclidean distance.

The algorithm follows these steps:
1.  **Initialization**: Randomly select 'k' data points as the initial cluster centers.
2.  **Assignment**: Assign each data point to the nearest cluster center, thereby labeling it.
3.  **Update**: Recalculate the cluster centers by computing the mean of all data points assigned to each cluster.
4.  **Iteration**: Repeat the assignment and update steps until the cluster centers no longer change, or a specified number of iterations has been completed.

***

## Part 1: 3D Data Clustering

### Objective
Apply the custom-built KMeans algorithm to a set of 3D data points.

* **Dataset**: `means_3D_data.csv`.
* **Parameters**:
    * Number of clusters (k): 3.
    * Stopping criteria: A maximum of 10 iterations or until the cluster centers do not change.

### Required Outputs for Part 1
1.  **CSV Output**: A CSV file, similar in format to the input, containing the original data along with the assigned cluster number and the final coordinates of the cluster center for each point.
2.  **PDF Report**: A detailed PDF report explaining the code written for the KMeans implementation.

***

## Part 2: Customer Segmentation

### Objective
Analyze customer data from a store using the KMeans algorithm to provide actionable insights for the marketing department, potentially leading to increased sales.

* **Dataset**: `Customers.csv`. This file includes five columns: `CustomerID`, `Gender`, `Age`, `Annual Income`, and `Spending Score`.

### Tasks for Part 2
1.  **Feature Selection**: As a crucial pre-processing step in machine learning, you must first decide which two columns from the dataset are the most appropriate features to use for the KMeans algorithm.
2.  **Clustering**: Using the two features selected, apply the KMeans algorithm to the data.
    * **Parameters**:
        * Number of clusters (k): 5.

### Required Outputs for Part 2
1.  **CSV Output**: A CSV file, similar to the input format, which includes the original data along with the assigned cluster number and the final coordinates of the cluster center for each customer record.

***

## Project Structure

The final submission should be a single `.zip` file organized as follows:

Markdown

# Hardware Accelerators Course - Homework 1: KMeans Clustering Implementation

This project is the first assignment for the "Hardware Accelerators" course at Shahid Beheshti University, Faculty of Engineering and Computer Science, for the Spring semester of 1402-1403. The primary goal is to implement the KMeans clustering algorithm from scratch and apply it to two different datasets.

**Important Note:** The implementation of the KMeans algorithm must be done using only a chosen programming language and its basic functions. The use of any pre-existing libraries for KMeans is prohibited.

***

## Project Overview

The project is divided into two main parts:
1.  Clustering a 3D dataset.
2.  Performing customer segmentation on a marketing dataset.

The final submission should be a `.zip` file named `HW1_StudentNumber_Fullname.zip` containing separate sub-folders for each part of the assignment.

***

## Understanding the KMeans Algorithm

KMeans is an unsupervised learning algorithm that partitions data into a specified number of clusters. It aims to maximize the similarity of data within a cluster and minimize the similarity between different clusters, often using a distance metric like the Euclidean distance.

The algorithm follows these steps:
1.  **Initialization**: Randomly select 'k' data points as the initial cluster centers.
2.  **Assignment**: Assign each data point to the nearest cluster center, thereby labeling it.
3.  **Update**: Recalculate the cluster centers by computing the mean of all data points assigned to each cluster.
4.  **Iteration**: Repeat the assignment and update steps until the cluster centers no longer change, or a specified number of iterations has been completed.

***

## Part 1: 3D Data Clustering

### Objective
Apply the custom-built KMeans algorithm to a set of 3D data points.

* **Dataset**: `means_3D_data.csv`.
* **Parameters**:
    * Number of clusters (k): 3.
    * Stopping criteria: A maximum of 10 iterations or until the cluster centers do not change.

### Required Outputs for Part 1
1.  **CSV Output**: A CSV file, similar in format to the input, containing the original data along with the assigned cluster number and the final coordinates of the cluster center for each point.
2.  **PDF Report**: A detailed PDF report explaining the code written for the KMeans implementation.

***

## Part 2: Customer Segmentation

### Objective
Analyze customer data from a store using the KMeans algorithm to provide actionable insights for the marketing department, potentially leading to increased sales.

* **Dataset**: `Customers.csv`. This file includes five columns: `CustomerID`, `Gender`, `Age`, `Annual Income`, and `Spending Score`.

### Tasks for Part 2
1.  **Feature Selection**: As a crucial pre-processing step in machine learning, you must first decide which two columns from the dataset are the most appropriate features to use for the KMeans algorithm.
2.  **Clustering**: Using the two features selected, apply the KMeans algorithm to the data.
    * **Parameters**:
        * Number of clusters (k): 5.

### Required Outputs for Part 2
1.  **CSV Output**: A CSV file, similar to the input format, which includes the original data along with the assigned cluster number and the final coordinates of the cluster center for each customer record.

***

## **Project Structure**

The final submission should be a single `.zip` file organized as follows:

HW1_StudentNumber_Fullname.zip

```
├── Part1_3D_Clustering/            
│   ├── means_3D_data.csv     
│   ├── output_3d_clusters.csv    
├── Part2_Customer_Segmentation/        
│   ├── Customers.csv 
│   ├── output_customer_segments.csv
├── README.md           
```
