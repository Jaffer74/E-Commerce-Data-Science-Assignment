# eCommerce Data Science Assignment  

This repository contains my solution for the **eCommerce Transactions Data Science Assignment**, involving tasks such as Exploratory Data Analysis (EDA), building a Lookalike Model, and performing Customer Segmentation using clustering techniques.  

## Tasks  

### 1. Exploratory Data Analysis (EDA)  
- Performed EDA on Customers, Products, and Transactions datasets.  
- Key visualizations and statistics to understand customer behavior, product performance, and sales trends.  
- Generated **5 business insights** to aid decision-making.  

#### Deliverables  
- `FirstName_LastName_EDA.pdf`: A PDF report containing insights.  
- `FirstName_LastName_EDA.ipynb`: Jupyter Notebook for EDA.  

---

### 2. Lookalike Model  
- Developed a **Lookalike Recommendation System** that identifies top 3 similar customers based on profile and transaction history.  
- Used both customer and product information to compute similarity scores.  

#### Deliverables  
- `FirstName_LastName_Lookalike.csv`: Contains a mapping of Customer IDs to their lookalike recommendations and similarity scores.  
- `FirstName_LastName_Lookalike.ipynb`: Jupyter Notebook for model implementation.  

---

### 3. Customer Segmentation (Clustering)  
- Performed **customer segmentation** using clustering techniques (e.g., K-Means, DBSCAN).  
- Used profile and transaction data to identify distinct customer groups.  
- Evaluated the clusters using **DB Index** and visualized the results.  


## Project Structure  

ecommerce-ds-assignment/  
├── data/  
│   ├── Customers.csv  
│   ├── Products.csv  
│   └── Transactions.csv  
├── notebooks/  
│   ├── FirstName_LastName_EDA.ipynb  
│   ├── FirstName_LastName_Lookalike.ipynb  
│   └── FirstName_LastName_Clustering.ipynb  
├── reports/  
│   ├── FirstName_LastName_EDA.pdf  
│   ├── FirstName_LastName_Lookalike.csv  
│   └── FirstName_LastName_Clustering.pdf  
├── requirements.txt  
└── README.md  


- **Customers.csv**: Contains customer profile data (e.g., CustomerID, Region, SignupDate).  
- **Products.csv**: Contains product details (e.g., ProductID, Category, Price).  
- **Transactions.csv**: Records transactions (e.g., TransactionDate, Quantity, TotalValue).  
- **Notebooks**: Python scripts for EDA, Lookalike Model, and Clustering.  
- **Reports**: PDFs summarizing insights and results for each task.  

---

## Getting Started  

### Prerequisites  

Ensure the following are installed on your system:  
- [Python 3.8+](https://www.python.org/)  
- [Jupyter Notebook](https://jupyter.org/)  
- Required Python libraries:  
  - `pandas`  
  - `numpy`  
  - `matplotlib`  
  - `seaborn`  
  - `scikit-learn`  

---

## Project Deliverables  

1. **Exploratory Data Analysis (EDA)**  
   - Conducted EDA to understand customer behavior, product performance, and sales trends.  
   - **Deliverables**:  
     - `FirstName_LastName_EDA.ipynb`: Jupyter Notebook with EDA code and visualizations.  
     - `FirstName_LastName_EDA.pdf`: A concise PDF report summarizing key business insights.  

2. **Lookalike Model**  
   - Built a Lookalike Recommendation System to identify the top 3 similar customers based on profile and transaction data.  
   - **Deliverables**:  
     - `FirstName_LastName_Lookalike.ipynb`: Jupyter Notebook containing the model code.  
     - `FirstName_LastName_Lookalike.csv`: CSV file mapping Customer IDs to their lookalikes with similarity scores.  

3. **Customer Segmentation (Clustering)**  
   - Performed customer segmentation using clustering algorithms such as K-Means.  
   - Evaluated clusters with the **DB Index** and visualized them.  
   - **Deliverables**:  
     - `FirstName_LastName_Clustering.ipynb`: Jupyter Notebook containing the clustering implementation.  
     - `FirstName_LastName_Clustering.pdf`: PDF report summarizing clustering results, metrics, and plots.  

---

## Key Metrics  

- **EDA**: Focused on generating actionable insights from the datasets.  
- **Lookalike Model**: Evaluated based on the accuracy and relevance of recommendations.  
- **Customer Segmentation**:  
  - **DB Index**: Used to evaluate the quality of clustering.  
  - Visualizations: Plots to represent clusters effectively and validate segmentation results.  


-----
## THANK YOU !
