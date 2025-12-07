
---

## 📝 **Project Description**

Clutsering on World global measurement is the process of dividing countries into groups with similar characteristics based on the features.  
This project uses **unsupervised learning** to identify clusters in a global data.

### The workflow includes:

- Loading and exploring the dataset  
- Handling missing values  
- Standardizing/normalizing features  
- Applying **K-Means Clustering**  
- Using **Elbow Method** to find the optimal number of clusters  
- Visualizing clusters  
- Interpreting groups as developed and developing countries based on cluslters  

---

## 🔧 **Technologies Used**

- **Python**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Seaborn**
- **Scikit-learn (KMeans, StandardScaler)**

---

## 📊 **Clustering Workflow**

1. Load the customer dataset (`Customer.csv`)
2. Select relevant features such as:
   - Age  
   - Income  
   - Spending Score  
   - Purchase Behavior  

3. Standardize the numerical features using:
   ```python
   from sklearn.preprocessing import StandardScaler
