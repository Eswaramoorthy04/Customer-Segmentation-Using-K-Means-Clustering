# Customer Segmentation Using K-Means Clustering

## 📌 Overview
This project focuses on **customer segmentation** using the **K-Means clustering algorithm**.  
Supermarket sales data is analyzed to group customers based on their purchasing patterns such as total spending, unit price, and quantity purchased.

Customer segmentation helps businesses understand customer behavior and improve marketing strategies.

---

## 🧠 Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib

---

## 📊 Dataset
- Dataset: **Supermarket Sales**
- File: `supermarket_sales - Sheet1.csv`

### Selected Features for Clustering:
- Total
- Unit Price
- Quantity

---

## ⚙️ Methodology
1. Loaded and explored the dataset using Pandas  
2. Selected relevant numerical features  
3. Standardized the features using **StandardScaler**  
4. Applied the **Elbow Method** to determine the optimal number of clusters  
5. Performed **K-Means clustering** on the scaled data  
6. Assigned cluster labels to each customer  
7. Visualized the customer clusters using scatter plots  

---

## 📉 Elbow Method
The Elbow Method was used to identify the optimal number of clusters by analyzing the **Within-Cluster Sum of Squares (WCSS)**.  
Based on the elbow point, **4 clusters** were selected.

---

## 📈 Cluster Visualization
Clusters were visualized to understand customer spending behavior and purchasing patterns.  
Each color in the plot represents a different customer segment.

---

## ✅ Results
The model successfully grouped customers into distinct clusters, helping identify:
- High-spending customers  
- Moderate buyers  
- Low-spending or occasional customers  

This segmentation can support targeted marketing and sales strategies.

---

## 🚀 Future Improvements
- Add more customer features (rating, customer type, payment method)
- Try other clustering algorithms (DBSCAN, Hierarchical Clustering)
- Perform detailed cluster profiling
- Create interactive visualizations

---
