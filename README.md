# Principal-Component-Analysis-PCA-on-Handwritten-Digits-Dataset

Project Objective:

This project aims to identify which handwritten digits are most differentiated using Principal Component Analysis (PCA). The project simulates a real-world scenario in an image recognition service for a postal system. The key objective is to determine which digits are hardest to distinguish and guide efforts to collect more labeled examples for improved model training.

**Dataset:**

- Source: Pen-Based Recognition of Handwritten Digits dataset.
- Description: The dataset contains digit samples written by 44 writers using a pressure-sensitive tablet. Samples include $x$, $𝑦$ coordinates and pressure values collected at fixed intervals.
- Purpose: It enables training models to distinguish digits with high accuracy, simulating scenarios like postal code recognition.

**Methodology:**

- Data Preparation:
  
  - The dataset was loaded and pre-processed to isolate pixel feature values.
  - Exploratory Data Analysis (EDA) was performed to understand the distribution and variance within the dataset.

- Dimensionality Reduction:

  - PCA was applied to reduce the high-dimensional data while retaining maximum variance.
  - The principal components were analyzed to identify clusters and separability among digit labels.

- Visualization:

  - Scatter plots of the first few principal components were created to visualize digit clusters.
  - Pairwise distances between digits were examined to highlight digits that overlap in PCA space.

**Insights:**

- Easily Distinguishable Digits: Digits such as '4' and '2', '6' and '9' form well-separated clusters, indicating high recognizability.
- Hard-to-Distinguish Digits: Overlapping regions for digits like '8' and '3' suggest they are harder to classify, requiring more labeled data for these cases.
- Variance Analysis: The top principal components capture a significant portion of the dataset's variance, emphasizing PCA's effectiveness in reducing dimensionality.

**Tools Used:**
- Libraries: NumPy, Pandas, Matplotlib, Seaborn.
- Methods: PCA, pairwise comparison, data visualization.

**Conclusion:**
The project demonstrates the use of PCA for dimensionality reduction and insights into separability in a handwritten digits recognition problem. It highlights the value of focusing on harder-to-classify digits to improve model accuracy in real-world applications like postal systems.
