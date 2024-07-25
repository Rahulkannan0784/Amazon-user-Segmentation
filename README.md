# Amazon User Segmentation using K-Means Algorithm

## Project Overview

This project aims to segment Amazon users based on their behavior and preferences using the K-Means clustering algorithm.

## Dataset

* **Amazon.csv**: Contains user data with features such as:
	+ Demographics (age, gender, location)
	+ Purchase history (product categories, frequency, amount)
	+ Browsing behavior (product views, search queries)

## Methodology

### Data Preprocessing

* Handle missing values using imputation
* Scale/normalize features for clustering

### K-Means Clustering

* Apply K-Means algorithm to identify user segments
* Determine optimal number of clusters using Elbow method

### Segment Analysis

* Characterize each segment based on features and behavior
* Identify key differences and similarities between segments

## Results

* **User Segments**: Identified [X] distinct user segments based on clustering results
* **Segment Characteristics**: Described key features and behavior of each segment
* **Insights**: Provided recommendations for marketing strategies and customer experience enhancement based on segment analysis

## Code

* **amazon_user_segmentation.ipynb**: Jupyter Notebook containing data preprocessing, clustering, and analysis code
* **kmeans_clustering.py**: Python script for K-Means clustering implementation

## Dependencies

* **Python 3.x**
* **pandas**
* **numpy**
* **scikit-learn**
* **matplotlib**

## Usage

 Run `amazon_user_segmentation.ipynb` to perform data preprocessing, clustering, and analysis
