
---

## 🔍 Key Analysis Performed

### 1️⃣ Data Loading & Inspection
- Dataset shape and structure
- Column names and data types
- Initial data preview

### 2️⃣ Feature Categorization
- **Numerical Features**: RAM, Storage, Battery Capacity, Price, Rating  
- **Categorical Features**: Brand, Model Name, Processor, Operating System

(Some numerical features were initially in object format and converted after inspection.)

### 3️⃣ Missing Value Handling
- Checked total missing values per column
- Applied appropriate methods:
  - Dropping rows with very few missing values
  - Imputation using mean/mode where applicable

### 4️⃣ Outlier Analysis
- Boxplots used to detect outliers in:
  - RAM, Storage, Battery, Price, Rating
- Outliers were **not removed** as they represent:
  - Premium and flagship smartphone models
  - Real market variations

### 5️⃣ Univariate & Bivariate Analysis
- Distribution plots for numerical features
- Count plots for categorical features
- Relationship analysis between **Price** and other features

---

## 📈 Tools & Libraries Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 🎯 Conclusion
- Dataset is suitable for further modeling
- Outliers represent genuine high-end products
- Proper preprocessing decisions were made to preserve real-world trends

---

## 🚀 Next Steps
- Feature engineering
- Encoding categorical variables
- Model building and evaluation

---

## 👤 Author
**Kesavapavan Gadde**  

