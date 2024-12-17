# Customer Segmentation Using K-Means Clustering  

## **Objective**  
This project uses the K-Means clustering algorithm to group customers of a retail store based on their purchase history. The aim is to identify distinct customer segments, which can help businesses create targeted marketing strategies and improve customer satisfaction.

---

## **Dataset**  
- **Source**: [Kaggle - Customer Segmentation Tutorial](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python)  
- **Features Used**:  
  - **Annual Income**: Customers' yearly earnings.  
  - **Spending Score**: A score assigned based on purchasing behavior.  
- Download the dataset and save the CSV file as `Mall_Customers.csv` in the project directory.

---

## **Workflow**  
1. **Data Preprocessing**:  
   - Load the dataset and clean the data (if needed).  
   - Select relevant features (`Annual Income`, `Spending Score`).  

2. **Clustering**:  
   - Apply K-Means clustering to group customers.  
   - Use the Elbow Method to determine the optimal number of clusters.  

3. **Visualization**:  
   - Visualize the clusters using a scatter plot for better understanding of customer groups.  

## Results
- Customers are grouped into distinct segments based on their income and spending behavior.
- Visualizations provide a clear understanding of the formed clusters, which can be used for targeted marketing.

## Technologies Used
- Language: Python
- Libraries:
  - pandas
  - numpy
  - matplotlib
  - seaborn
  - scikit-learn
