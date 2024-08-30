# Customer Segmentation with K-Means Clustering

This project demonstrates how to use the K-Means Clustering algorithm to segment customers based on their purchasing behavior. The approach involves preprocessing the data, selecting relevant features, and applying K-Means to group customers into distinct segments.

## Table of Contents

1. [Project Overview](#project-overview)
2. [Dataset](#dataset)
3. [Installation](#installation)
4. [Results](#results)

## Project Overview

The aim of this project is to build a customer segmentation model using the K-Means Clustering algorithm. By analyzing customer data, we group customers into different segments based on their purchasing patterns, which can be used for targeted marketing and personalized customer service.

### Key Features

- Data preprocessing and cleaning
- Feature selection for clustering
- Applying the K-Means Clustering algorithm
- Visualization of customer segments

## Dataset

- The dataset used in this project is `customers.csv`, which contains customer purchasing data.
- **Columns:**
  - `CustomerID`: Unique identifier for each customer.
  - `Gender`: Gender of the customer.
  - `Age`: Age of the customer.
  - `Annual Income`: Annual income of the customer.
  - `Spending Score`: A score assigned based on customer spending behavior.

> **Note:** Make sure your dataset is placed in the root directory of the project with the name `customers.csv`.

## Installation

To run this project, you will need to have Python installed along with the following Python packages:

- Pandas
- NumPy
- Matplotlib
- Seaborn
- scikit-learn

> Ensure you are using a Python environment to avoid conflicts with other projects.

## Results

- The results of the K-Means Clustering algorithm are visualized to show the different customer segments.
- The centroids of the clusters are highlighted to indicate the center of each segment.
