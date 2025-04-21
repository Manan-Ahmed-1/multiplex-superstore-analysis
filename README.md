# Multiplex Superstore Customer Analysis 📊

This project is a data analysis and regression modeling task based on "Multiplex Superstore" dataset. The goal is to clean, analyze, visualize, and model customer behavior and sales data.

## 🗂 Dataset Overview

- Two sheets:
  - `Customers`: 400 rows of unique customers with features like signup date, monthly spend, score, and age.
  - `Orders`: 1000+ rows of customer transactions including order details, categories, amount (in multiple currencies), and geographical data.

## 🧹 Data Cleaning Highlights

- Cleaned messy `Customer_ID` columns and converted to integers.
- Handled missing values in a **contextual** manner:
  - Filled city and country based on available matching info.
  - Converted multi-format dates to datetime objects.
  - Standardized currencies to GBP.
- Verified normality before applying imputation on numerical fields.

## 📈 Visualizations

- Age Group vs Product Category
- Monthly Spend across Cities and Countries
- Customer-wise Order Count and Total Spend
- Monthly Order Trends
- Score Analysis and Spending Patterns

## 🤖 Modeling

- **Linear Regression**:
  - Features: `Signup_Date` (as tenure) and `Monthly_Spend`
  - Target: `Score`
  - Achieved R² score of **0.95**, indicating strong predictive power.

## 🧰 Tools Used

- Python (Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn)
- Google Colab
- GitHub for version control and portfolio display

## 📥 How to Use

1. Clone or download the repository.
2. Open the `.ipynb` file in Jupyter or Google Colab.
3. Run each cell step-by-step to explore the analysis.

---

## 🧠 What I Learned

- Real-world data cleaning and preprocessing techniques
- Conditional missing value handling
- Creating visualizations that tell a story
- Building and evaluating regression models
- Documenting and sharing data projects professionally

---

## 🔗 Author

**Manan Ahmed**  
Data Analyst/Scientist 
📫 Connect: https://www.linkedin.com/in/manan-ahmed-73a793252/
