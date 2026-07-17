# Clustering & Dimensionality Reduction for Workforce Analytics

**PKCERT AI & Software Development Internship – Task 12**  
**Government Sector AI & Software Development Program**

---

## Project Overview

This project demonstrates practical application of unsupervised machine learning techniques for employee segmentation and workforce insights. Using the IBM HR Employee Attrition dataset as a proxy, the analysis applies **K-Means**, **Hierarchical Clustering**, **PCA**, and **t-SNE** with strong contextual framing for Pakistan's public sector human resource management.

The work showcases data preprocessing, algorithm selection, visualization, and critical analysis — skills essential for AI-driven governance and policy support.

## Objectives Achieved
- Comprehensive dataset preparation and EDA
- Implementation of K-Means (with Elbow & Silhouette methods)
- Hierarchical Clustering with dendrogram visualization
- Dimensionality reduction using PCA and t-SNE
- Comparative analysis and actionable recommendations for public sector HR

## Repository Structure
├── notebooks/
│   └── Task12_Clustering_Dimensionality_Reduction.ipynb
├── data/
│   └── HR_Employee_Attrition.csv
├── reports/                        
├── requirements.txt
├── README.md
└── .gitignore


## Key Findings & Recommendations

- Optimal number of employee segments: **3**
- t-SNE provided superior visualization of complex employee groups
- K-Means recommended for scalable deployment in government HR systems
- Strong potential for reducing attrition and improving talent management in federal/provincial services

## Technologies Used
- **Python** 3.9+
- **scikit-learn** – Clustering & Dimensionality Reduction
- **pandas**, **numpy** – Data manipulation
- **matplotlib**, **seaborn** – Visualization

## How to Run

```bash
pip install -r requirements.txt
jupyter notebook