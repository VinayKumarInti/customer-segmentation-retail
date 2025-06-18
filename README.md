# Customer Segmentation for a Retail Chain

## 📌 Project Summary
This project performs customer segmentation using K-Means clustering on a mall customer dataset. The main objective is to group customers based on their Annual Income and Spending Score so that the business can tailor marketing strategies to specific customer segments.

---

## 🔍 Steps Taken

1. **Data Loading and Exploration**  
   - Loaded the dataset (`Mall_Customers.csv`) into a Pandas DataFrame  
   - Explored the data to understand the structure, types, and distribution

2. **Data Cleaning**  
   - Verified that the dataset had no missing/null values  
   - No duplicate or incorrect values were found

3. **Feature Selection**  
   - Selected `Annual Income (k$)` and `Spending Score (1-100)` for clustering  
   - These features best represent spending behavior and financial capacity

4. **K-Means Clustering**  
   - Applied K-Means clustering algorithm using `sklearn`  
   - Used the **Elbow Method** to determine the optimal number of clusters (k=5)

5. **Visualization**  
   - Visualized clusters using scatter plots  
   - Clearly labeled different customer segments

---

## 📈 Business Insights

- **Cluster 1**: Low income, low spending → Price-sensitive customers  
- **Cluster 2**: High income, high spending → Premium customers (ideal target for promotions)  
- **Cluster 3**: High income, low spending → Potential for upselling  
- **Cluster 4**: Average income and spending → Stable segment  
- **Cluster 5**: Low income, high spending → Impulsive buyers, may require budgeting offers  

---

## 📂 Deliverables

- ✔️ Jupyter Notebook with code, markdown explanations, and visuals  
- ✔️ This README file with project summary, steps taken, and insights  

---

## 🛠️ Technologies Used

- Python  
- Pandas, NumPy, Matplotlib, Seaborn  
- Scikit-learn (KMeans clustering)  
- Jupyter Notebook
