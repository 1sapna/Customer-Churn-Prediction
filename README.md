# Customer Churn Prediction

## 📌 Project Overview
This project aims to predict customer churn for a subscription-based service using historical data. The dataset contains customer demographics, usage patterns, and subscription details. The goal is to develop a machine learning model that identifies customers likely to discontinue the service.

## 📂 Dataset
- The dataset includes customer details, subscription duration, usage behavior, and other demographic factors.
- Missing values are handled with appropriate imputation strategies.
- Features are preprocessed using encoding and scaling techniques.

## 🔧 Installation & Setup
1. **Clone the Repository**
   ```bash
   git clone https://github.com/yourusername/customer-churn-prediction.git
   cd customer-churn-prediction
   ```
2. **Install Dependencies**
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Notebook**
   Open customer_churn_prediction.ipynb and run the cells in order


## 🏗️ Project Workflow

### 1️⃣ Data Preprocessing
- Handling missing values using appropriate imputation strategies.
- Encoding categorical variables using **Label Encoding** and **One-Hot Encoding**.
- Feature scaling using **StandardScaler** for numerical features.
- Removing redundant or highly correlated features.

### 2️⃣ Exploratory Data Analysis (EDA)
- Visualizing the distribution of customer churn using **Seaborn** and **Matplotlib**.
- Analyzing feature correlations with a **heatmap**.
- Checking outliers using **boxplots**.
- Understanding customer behavior through **histograms, bar plots, and pair plots**.

### 3️⃣ Model Training & Evaluation
- Splitting the dataset into **training and testing sets**.
- Training different machine learning models, including:
  - **Random Forest Classifier**
  - **Logistic Regression**
  - **Gradient Boosting**
  - **Support Vector Machines (SVM)**
  - **Bernoulli NB Model**
  - **XGBoost Classifier**
  - **K-Nearest Neighbors (KNN)**
- Evaluating models using:
  - **Accuracy**
  - **Precision, Recall, and F1-score**
  - **Confusion Matrix**


### 4️⃣ 📊  Results & Insights
- The best-performing model(Random Forest Classifier)  achieves an accuracy of 86.7%.
- Key factors influencing churn:
  - Customers with low account balance are more likely to churn.
  - Inactive members are at a higher risk of leaving.
  - Customers with fewer products are more likely to churn.
- The model can help businesses identify at-risk customers and improve retention strategies.




### 5️⃣ 💾 Saving the Model 
- The trained Random Forest model is saved as model.pkl using Pickle.
- This allows for easy reuse without retraining.



