#  Heart Disease Diagnostic Assistant (84.74% Accuracy)

Is project mein humne machine learning ka istemal karte hue heart disease ko predict karne ka ek system banaya hai. Humne EDA (Exploratory Data Analysis) se lekar Model Optimization tak ke saare steps follow kiye hain.



##  **Project Highlights**
* **Best Model:** Optimized K-Nearest Neighbors (KNN).
* **Final Accuracy:** **84.74%** (Tuned via GridSearchCV).
* **Key Findings:** `exang` (Exercise Induced Angina) aur `thalch` (Max Heart Rate) heart disease ke sab se bade indicators sabit hue.



##  **Machine Learning Pipeline**

### **1. EDA (Exploratory Data Analysis)**
* Missing values aur outliers ko handle kiya (IQR Method).
* Correlation matrix ke zariye important features identify kiye.
* Seaborn aur Matplotlib ke zariye visualization banayi.

### **2. Preprocessing**
* **Feature Scaling:** `StandardScaler` ka istemal kiya taake KNN model distance sahi se calculate kar sake.
* **Train-Test Split:** 80% data training ke liye aur 20% evaluation ke liye rakha.
* **Data Leakage Prevention:** Scaler ko sirf training data par fit kiya.

### **3. Modeling & Optimization**
* **Models Tested:** Logistic Regression, KNN, aur Decision Trees.
* **Hyperparameter Tuning:** `GridSearchCV` use karke KNN ki accuracy ko **78% se 84.74%** tak lekar gaye.

---

##  **Results Summary**
| Model | Base Accuracy | Optimized Accuracy |
| :--- | :--- | :--- |
| **KNN** | 78.5% | **84.74%** |
| Logistic Regression | 82.1% | 82.1% |
| Decision Tree | 75.0% | 77.2% |

---

##  **Future Improvements**
* More data samples (thousands of records) for 90%+ accuracy.
* Ensemble methods (Random Forest, XGBoost) ka istemal.
* Deep Learning (Neural Networks) implementation.

   


