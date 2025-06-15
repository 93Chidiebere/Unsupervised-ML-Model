# Customer Segmentation Using Unsupervised Machine Learning

This project explores unsupervised machine learning techniques to segment customers based on their purchasing behavior. Using clustering algorithms, particularly **K-Means**, the project helps businesses understand customer groupings and tailor marketing strategies effectively.

## 🧠 Problem Statement

In today's data-driven world, companies need to understand their customers better. However, when customer data lacks predefined labels or categories, **unsupervised learning** can be a powerful tool to discover hidden patterns and group customers with similar behaviors or profiles.

The goal of this project is to:
- Group customers into meaningful clusters based on selected features.
- Analyze the characteristics of each cluster.
- Provide actionable insights for targeted marketing.

## 📁 Dataset

The dataset used in this project includes the following features:

- **Customer ID**
- **Gender**
- **Age**
- **Annual Income (k$)**
- **Spending Score (1–100)**

> 📌 *Note: The dataset is a synthetic sample often used for clustering demonstrations (e.g., Mall Customers dataset).*

## 🔧 Tools & Technologies

- Python 🐍
- Jupyter Notebook 📒
- Libraries:
  - `pandas` for data manipulation
  - `matplotlib` and `seaborn` for data visualization
  - `scikit-learn` for clustering (KMeans)
  - `warnings` for cleaner outputs

## 📊 Methodology

1. **Data Preprocessing**
   - Data loaded and cleaned (e.g., dropped missing values)
   - Gender encoded numerically
   - Selected features: `Age`, `Annual Income`, `Spending Score`

2. **Exploratory Data Analysis (EDA)**
   - Distribution plots of income, age, and spending score
   - Correlation matrix for feature relationship insights

3. **Optimal Cluster Determination**
   - Elbow Method used to identify the ideal number of clusters (k)

4. **Model Building**
   - KMeans algorithm applied with optimal `k`
   - Cluster labels assigned to each customer

5. **Cluster Visualization**
   - 2D plots for different feature combinations with cluster colors

6. **Interpretation**
   - Characteristics of each cluster analyzed for business decision-making

## 📈 Results

The clustering identified **5 unique customer segments**, each with distinct behaviors and spending patterns. This segmentation can support:

- Personalized marketing
- Customer retention strategies
- Targeted promotions

## 📌 Key Takeaways

- K-Means is effective for customer segmentation when features are properly selected and scaled.
- Visualizing clusters helps stakeholders understand abstract ML results.
- Proper preprocessing, including encoding and normalization, is crucial in unsupervised models.

## 🚀 Future Work

- Apply dimensionality reduction (e.g., PCA) for higher-dimensional clustering
- Explore hierarchical clustering or DBSCAN
- Incorporate more features such as purchase frequency or product categories

## 📚 How to Run This Project

1. Clone the repo:

```bash
git clone https://github.com/93Chidiebere/unsupervised-ml-customer-clustering.git
cd unsupervised-ml-customer-clustering
