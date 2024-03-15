# DataScience_Tools-CS3DS19

## Customer Segmentation using Clustering

This repository contains code and workflows for a project aimed at segmenting customers of an automobile company using clustering techniques. The project involves data understanding, preprocessing, clustering, and cluster validity assessment using KNIME workflows.

## Project Overview

The automobile company plans to expand into new markets and wants to implement targeted marketing strategies similar to those used in their existing market. The sales team has classified customers into different segments based on their behavior (Segments A, B, C, D) and performed segmented outreach successfully. The goal of this project is to build and test classification models to predict the customer segmentation in new markets.

### Tasks:

1. **Data Understanding and Preprocessing**
   - Understand the characteristics and quality of the dataset.
   - Perform data preprocessing steps such as handling missing values, encoding categorical variables, and standardizing numerical variables.
   - Visualize the data before clustering, with colors representing the class labels.

2. **Clustering**
   - Build clustering models using various algorithms (e.g., K-means, DBSCAN).
   - Experiment with different numbers of clusters and evaluate the models using internal metrics.

3. **Cluster Validity**
   - Evaluate the clustering results using appropriate cluster validity measures.
   - Select the best-performing clustering model based on the evaluation metrics and domain knowledge.

## Repository Structure

- `data/`: Contains the dataset `customer.csv` and the `customer_clean_data.csv`.
- `task1/ and task2+3/`: Includes KNIME workflows for data preprocessing, clustering, and cluster validity assessment.
- `README.md`: This file explaining the project and repository contents.
- `customer_description.txt` description of the data.

## Usage

1. Clone the repository:

2. Install KNIME Analytics Platform from [here](https://www.knime.com/downloads).

3. Open KNIME and import the workflows.

4. Follow the steps in the workflows to understand the data, preprocess it, perform clustering, and evaluate cluster validity.

## Requirements

- KNIME Analytics Platform
- Python 3 (if additional data preprocessing or analysis is required)

## Acknowledgements

- The dataset used in this project was acquired from the Analytics Vidhya hackathon.

