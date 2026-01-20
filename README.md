# Sampling Techniques

This repository demonstrates multiple data sampling techniques used to select **70% of a training dataset** for analysis and model development.

## Implemented Sampling Methods

### 1. Simple Random Sampling
Randomly selects 70% of the training data without considering class distribution.

### 2. Stratified Sampling
Selects 70% of samples from each class while preserving the original class proportions.

### 3. Systematic Sampling
Selects every second record from the training dataset in a fixed, sequential manner.

### 4. Cluster Sampling
Groups data into 10 clusters using KMeans, randomly selects 5 clusters, and includes all samples from those clusters.

### 5. Bootstrap Sampling
Randomly samples data with replacement to create a dataset equal to 70% of the original training size.

## Objective
To compare different sampling strategies and understand their impact on data representation.

## Notes
- All sampling methods are applied to the same training dataset.
- Sampling percentage is kept consistent across methods for fair comparison.

