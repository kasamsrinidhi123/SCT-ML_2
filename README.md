# SCT-ML_2
# Customer Segmentation using K-Means Clustering

## 📌 Project Overview
This project applies **K-Means Clustering** to segment customers based on their annual income, spending score, and age. It helps businesses identify distinct customer groups and tailor marketing strategies effectively.

## 📂 Dataset
- **File:** `Mall_Customers.csv`
- **Columns:**
  - `CustomerID` - Unique customer ID
  - `Gender` - Male/Female
  - `Age` - Age of the customer
  - `Annual Income (k$)` - Annual income in thousand dollars
  - `Spending Score (1-100)` - Score assigned based on spending behavior

## 🔑 Key Steps
1. **Load Dataset**  
   Read and explore the dataset using Pandas.

2. **Feature Selection**  
   - 2D Clustering: `Annual Income` vs `Spending Score`  
   - 3D Clustering: `Age`, `Annual Income`, and `Spending Score`

3. **Elbow Method**  
   Determine optimal number of clusters by plotting **WCSS (Within-Cluster Sum of Squares)**.

4. **Apply K-Means**  
   Cluster customers into groups (e.g., 5 clusters).

5. **Visualization**  
   - 2D Scatter Plot of clusters.  
   - 3D Scatter Plot for deeper insights.

6. **Save Clustered Data**  
   Final clustered dataset can be exported for further analysis.

## 🛠️ Technologies Used
- **Python**
- **Pandas** (Data handling)
- **NumPy** (Numerical operations)
- **Matplotlib** (2D & 3D visualization)
- **Scikit-learn** (K-Means clustering)

## 📊 Results
- Visualized clusters in both **2D** and **3D**.
- Segmentation can help in targeted marketing strategies.

## 🚀 How to Run
1. Clone or download the repository.
2. Place `Mall_Customers.csv` in the same directory as the script.
3. Install dependencies:
   ```bash
   pip install pandas numpy matplotlib scikit-learn
