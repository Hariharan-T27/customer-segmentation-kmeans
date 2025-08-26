 
# Customer Segmentation Using K-Means

This project performs customer segmentation using the K-Means clustering algorithm. By analyzing customer annual income and spending scores, we identify distinct customer groups that help businesses understand consumer behavior and make data-driven decisions for targeted marketing strategies.

## 1️⃣ Clone the Repository
``` bash 
git clone https://github.com/Hariharan-T27/customer-segmentation-kmeans.git
cd Customer_Segmentation_Using_K-Means
```

## 2️⃣ Install Dependencies
It’s recommended to create a virtual environment:
```bash
pip install -r requirements.txt
```
requirements.txt
```bash
numpy
pandas
matplotlib
seaborn
scikit-learn
```

## 📊 Data Overview

- Dataset: customer_data.csv

- Features Used:

    - Annual Income (k$)

    - Spending Score (1–100)

## 📌 Methodology

#### Data Collection & Cleaning

- Load customer data from CSV

- Check shape, info, and missing values

#### Feature Selection

- Selected features: Annual Income and Spending Score

#### Finding Optimal Number of Clusters

- Used Elbow Method with Within-Cluster Sum of Squares (WCSS)


#### Model Training

- Trained KMeans clustering with n_clusters = 4

#### Visualization

- Scatter plot showing customer groups and centroids

## 📈 Results

- #### Optimal Number of Clusters: 4

- #### Customer Segments Identified:
    - High Income, High Spending

    - High Income, Low Spending

    - Moderate Income, Moderate Spending

    - Low Income, Low Spending

This segmentation enables targeted marketing and better customer relationship management.

## 🔑 Key Insights

- Customers are not uniformly distributed across income and spending score.

- Two major profitable groups are high spenders.

- Businesses can tailor offers, discounts, and engagement strategies based on these clusters.

## 📌 Future Enhancements

- Include additional features like Age, Gender, and Occupation for richer insights.

- Apply other clustering algorithms (e.g., Hierarchical, DBSCAN) for comparison.

- Deploy an interactive dashboard using Streamlit or Plotly Dash.

## 👨‍💻 Author
- Hariharan Thirunagari

  Data Science & Analytics Enthusiast
