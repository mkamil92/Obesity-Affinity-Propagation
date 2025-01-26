# Obesity-Affinity-Propagation

This repository contains code that applies the Affinity Propagation algorithm to a dataset on obesity. The aim of this task is to cluster individuals based on various factors related to obesity, such as age, BMI, and other features.

## Dataset
The dataset used for this analysis contains information related to obesity and its different factors. The features include  age, gender, BMI, and physical activity. You can explore the dataset in `ObesityDataset.csv`.

## Algorithms Used
The main algorithm used in this analysis is **Affinity Propagation**, which is a clustering algorithm that does not require the number of clusters to be specified in advance. The algorithm identifies "exemplars," which are the representative points for each cluster.

## Steps Involved:
1. **Data Preprocessing**:
   - Data cleaning, including handling missing values.
   - Normalization of features for better clustering performance.
   
2. **Applying Affinity Propagation**:
   - Affinity Propagation was applied to identify clusters based on similarities between individuals.
   
3. **Results**:
   - The clustering results are presented, showing how individuals are grouped based on their obesity-related features.
