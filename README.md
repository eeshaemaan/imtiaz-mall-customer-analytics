# Imtiaz Mall Customer Analytics - Electronics Section

## Project Overview
This project analyzes customer behavior in the electronics section of Imtiaz Mall to address declining sales and improve customer retention.  

It covers the complete data science lifecycle — from data preprocessing and exploratory analysis to predictive modeling and customer segmentation.

---

## Business Objectives
- Identify factors contributing to customer churn  
- Segment customers for targeted marketing strategies  
- Predict future customer purchase behavior  
- Provide actionable recommendations for sales growth  

---

## Dataset
- Electronics retail dataset (`electronics.json`)  
- Includes:
  - Customer demographics  
  - Purchase history  
  - Product details  
  - Transaction dates  
  - Spending amounts  

---

## Project Workflow

### Data Preprocessing
- Handled missing values using appropriate imputation techniques  
- Detected and treated outliers  
- Cleaned inconsistencies in data formats  
- Feature engineering:
  - Average spending per purchase  
  - Purchase frequency per month  
  - Brand affinity score  
  - Product category preferences  
- Standardized numerical features  

---

### Exploratory Data Analysis (EDA)
- **Univariate Analysis:** Distribution of age, spending, frequency  
- **Bivariate Analysis:** Relationships between income, spending, and preferences  
- **Temporal Analysis:** Trends and seasonal patterns in customer behavior  

---

### Predictive Modeling

#### Linear Regression
- Predicted average spending per customer  
- Evaluated using:
  - Mean Absolute Error (MAE)  
  - Mean Squared Error (MSE)  
  - R² Score  

#### Decision Tree Classifier
- Predicted likelihood of customer purchase  
- Evaluated using:
  - Accuracy  
  - Precision  
  - Recall  
  - F1-Score  

---

### Customer Segmentation (K-Means Clustering)
- Applied K-Means to group customers based on behavior  
- Used Elbow Method to determine optimal clusters  
- Analyzed cluster characteristics:
  - Spending patterns  
  - Brand preferences  
  - Product categories  

---

## Technologies Used
- Python 3.8+  
- Pandas, NumPy  
- Matplotlib, Seaborn, Plotly  
- Scikit-learn  
- Jupyter Notebook  

---

## Key Results & Insights
- Identified multiple customer segments with distinct purchasing behaviors  
- Purchase frequency strongly influences overall spending  
- Product category preferences impact repeat purchases  
- Predictive models provide insights into future customer actions  

---

## Business Recommendations
- Target high-frequency customers with loyalty programs  
- Personalize marketing based on product preferences  
- Focus on high-performing product categories  
- Use predictive models for proactive customer retention  

---

## Future Improvements
- Implement advanced models (Random Forest, XGBoost)  
- Deploy as a real-time analytics dashboard  
- Integrate recommendation systems  
- Automate data pipelines  

---

## Author
**Eesha Emaan**  
