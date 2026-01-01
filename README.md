# 🏠 House Price Prediction using Machine Learning  
### Hyperparameter Tuning with GridSearchCV

## 📌 Project Overview  
This project focuses on building a **robust house price prediction system** using advanced machine learning regression techniques.  
The objective is to **accurately predict house prices** through proper **data preprocessing, feature encoding, feature scaling**, and **hyperparameter tuning** using **GridSearchCV**.

The project leverages powerful ensemble-based models:
- **Random Forest Regressor**
- **LightGBM Regressor**

---

## 📂 Dataset Description  
- The dataset contains housing-related features such as location, size, and property attributes  
- Target variable: **price**  
- Irrelevant columns like `date`, `country`, and `street` were removed during preprocessing  

---

## ⚙️ Technologies & Tools Used  
- Python  
- NumPy  
- Pandas  
- Matplotlib  
- Scikit-learn  
- LightGBM  
- GridSearchCV  

---

## 🛠️ Project Workflow  

### 1️⃣ Data Loading  
- Loaded the dataset using **Pandas**
- Initial exploration using `.head()`, `.info()`, and `.describe()`

### 2️⃣ Data Preprocessing  
- Removed non-informative and redundant columns  
- Checked and handled:
  - Missing values  
  - Duplicate records  
- Applied **Label Encoding** to categorical features such as `city` and `statezip`

### 3️⃣ Feature Scaling & Data Splitting  
- Separated features (`X`) and target (`y`)
- Split the data into **training (80%)** and **testing (20%)**
- Applied **StandardScaler** to normalize numerical features

---

## 🤖 Model Building & Hyperparameter Tuning  

### 🔹 Random Forest Regressor  
- Used **GridSearchCV** to tune:
  - `n_estimators`
  - `max_depth`
  - `min_samples_split`
  - `min_samples_leaf`
- Performed **5-fold cross-validation**
- Evaluated using **R² Score**

### 🔹 LightGBM Regressor  
- Implemented **GridSearchCV** for optimal hyperparameter selection  
- Efficient gradient boosting technique for faster and more accurate predictions  
- Final evaluation carried out using **R² Score**

---

## 📊 Model Evaluation  
- Model performance measured using **R² Score**
- Best-performing model selected based on cross-validation and test accuracy

---

## 🚀 Results & Insights  
- Hyperparameter tuning significantly improved model performance  
- LightGBM demonstrated strong predictive capability  
- The project effectively handles a real-world regression problem

---

## 📁 Project Structure  
House-Price-Prediction/    
│   
├── Data/   
│ └── House_price_dataset.csv   
├── README.md   
├── houserent_gridsearch.ipynb   

---

## 👩‍💻 Author  

**Inderpreet Kaur**  
📧 Email: inderpreetkaur0649@gmail.com       
🔗 LinkedIn: https://www.linkedin.com/in/inderpreet-kaur-613b1437b/     

---

## ⭐ Conclusion  
This project highlights the importance of **data preprocessing, feature scaling, ensemble learning**, and **hyperparameter tuning** in building accurate and reliable machine learning models.  
It is a **portfolio-ready end-to-end regression project** suitable for real-world applications.
