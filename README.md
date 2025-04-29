# Project Title
Clustering Techniques Analysis: K-Means, K-Medoids, K-Median, and Hierarchical Clustering

## Overview
This report analyzes and compares the performance of four clustering techniques—K-Means, K-Medoids, K-Median, and Hierarchical Clustering—on a dataset with four numerical attributes. The goal is to evaluate the effectiveness of each algorithm in terms of cluster shape, robustness to outliers, and computational efficiency.

---

## Contents

### 1. K-Means Clustering
- **Description**: Centroid-based algorithm minimizing squared Euclidean distance.
- **Pros**: Fast and efficient for spherical, well-separated clusters.
- **Cons**: Sensitive to outliers and assumes equal-sized clusters.
- ![image](https://github.com/user-attachments/assets/0919689b-6fac-4cd3-b6fc-63ea0c3bb200)


### 2. K-Medoids Clustering
- **Description**: Uses actual data points (medoids) instead of means.
- **Pros**: Robust to outliers; handles non-spherical clusters.
- **Cons**: More computationally intensive than K-Means.
- ![image](https://github.com/user-attachments/assets/c6e2445f-a44a-4520-828b-3fffb4fec776)


### 3. K-Median Clustering
- **Description**: Minimizes sum of absolute deviations (Manhattan distance).
- **Pros**: Very robust to outliers; ideal for skewed data.
- **Cons**: Computationally slower.
- ![image](https://github.com/user-attachments/assets/3cc0a8c4-c320-4159-a53b-84f57751a4cd)


---

## Comparative Summary

| Algorithm  | Strengths                                      | Weaknesses                       |
|------------|------------------------------------------------|----------------------------------|
| K-Means    | Fast, efficient, good for spherical clusters   | Sensitive to outliers            |
| K-Medoids  | Robust to outliers, handles irregular shapes   | Slower than K-Means              |
| K-Median   | Best for skewed data, most stable clusters     | Computationally demanding        |

![image](https://github.com/user-attachments/assets/95fd2f11-cd83-4c4a-a16c-bc3ff8ca1412)

---

## 4. Hierarchical Clustering
- **Methods Used**: Single, Complete, and Average Linkage
- **Distance Metric**: Euclidean
- **Visualizations**: Dendrogram and Venn-style diagram
- **Comparison**:
  - **Single Linkage**: Chain-like clusters; not always ideal.
    ![image](https://github.com/user-attachments/assets/a35e1747-152e-40a8-9dd3-ffa45de78eab)

  - **Complete Linkage**: Compact clusters; sensitive to outliers.
  - ![image](https://github.com/user-attachments/assets/c44ff4a4-efb5-4555-9394-7bb1a42983f0)

  - **Average Linkage**: Balanced clustering.
    ![image](https://github.com/user-attachments/assets/6c531740-1067-4330-b4c7-5aa2686dad6b)


---

## Conclusion
- **Best for Outlier-Rich or Irregular Data**: K-Medoids or K-Median
- **Best for Clean, Uniform Data**: K-Means
- **Hierarchical Clustering**: Offers detailed insight into cluster structure; useful for visualization.

---

## Notes
- Ideal for use in exploratory data analysis (EDA) and preprocessing steps for unsupervised learning tasks.
- Visualization tools (dendrograms, Venn diagrams) greatly enhance interpretability.

