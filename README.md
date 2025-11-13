# 🚢 Titanic Data Cleaning and Preprocessing

This project demonstrates complete **data cleaning and preprocessing** on the Titanic dataset.  
It was created as part of the **Elevate Labs Data Cleaning and Preprocessing Task**.

---

## 🧠 Objective

To clean, preprocess, and prepare the Titanic dataset for further data analysis or machine learning by performing:
1. Importing and exploring the dataset  
2. Handling missing values using mean/median/imputation  
3. Converting categorical features into numerical form  
4. Normalizing and standardizing numerical data  
5. Visualizing and removing outliers  

---

## 🪜 Steps Performed

### **1️⃣ Import and Explore**
- Loaded the dataset using `pandas`
- Displayed basic information, data types, and missing values
- Checked numerical and categorical distributions

### **2️⃣ Handle Missing Values**
- Filled `Age` with median  
- Filled `Embarked` with mode  
- Dropped columns with excessive missing values (`Cabin`, `Name`, `Ticket`, `PassengerId`)

### **3️⃣ Encode Categorical Features**
- Used `LabelEncoder` to convert `Sex` and `Embarked` into numeric codes  
- Ensured the dataset is suitable for ML algorithms

### **4️⃣ Normalize/Standardize Numerical Features**
- Applied `StandardScaler` to scale continuous variables  
- Excluded target variable `Survived` from scaling

### **5️⃣ Visualize and Remove Outliers**
- Used boxplots to visualize outliers  
- Applied the **IQR (Interquartile Range)** method to remove them  
- Replotted boxplots after cleaning to confirm results

---

## 🧰 Tools and Libraries Used
- **Python**
- **Pandas**
- **NumPy**
- **Seaborn**
- **Matplotlib**
- **Scikit-learn (LabelEncoder, StandardScaler)**

---

## 📂 Repository Contents
| File | Description |
|------|--------------|
| `titanic_cleaning.py` | Main Python script for data cleaning and preprocessing |
| `titanic_cleaned.csv` | Cleaned dataset output |
| `README.md` | Project documentation |

---

## 💾 Output
After cleaning, the dataset is saved as:
**titanic_cleaned.csv**

