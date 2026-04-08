# 🍽️ Zomato Restaurants Data Analysis (EDA)

##  Project Overview

This project performs **Exploratory Data Analysis (EDA)** on the Zomato Restaurants dataset to uncover insights about restaurant trends, customer preferences, and business factors affecting ratings.

The goal is to transform raw data into **actionable business insights** using Python-based data analysis tools.



##  Objectives

* Perform data cleaning and preprocessing
* Analyze restaurant distribution across cities
* Understand rating patterns
* Explore impact of pricing and online delivery
* Generate meaningful business insights

---

##  Tech Stack

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

---

##  Dataset

* Zomato Restaurants Dataset (CSV)
* Contains information about restaurants, cuisines, ratings, cost, and services

---

##  Key Analysis Performed

### 1. Data Cleaning

* Handled missing values
* Cleaned column names
* Removed irrelevant columns

### 2. Feature Engineering

* Extracted primary cuisine
* Converted categorical features (Yes/No → 0/1)

### 3. Exploratory Data Analysis

* Rating distribution
* Top cities with most restaurants
* Popular cuisines
* Cost vs rating analysis
* Online delivery impact
* Price range vs ratings

### 4. Advanced Analysis

* Grouped comparisons (mean ratings)
* Multi-variable analysis (price + delivery)
* Correlation heatmap

---

##  Key Insights

* Most restaurants have ratings between **2.5 and 4.0**
* **Mid-range restaurants** perform as well as or better than expensive ones
* **Online delivery** slightly improves customer engagement
* **Cost does not strongly influence ratings**
* Restaurant success depends on **multiple factors, not just price or service**

---

##  Business Recommendations

* Focus on **value-for-money pricing**
* Enable **online delivery** to improve reach
* Prioritize **customer experience over pricing strategy**
* Align offerings with **popular cuisines**

---

##  How to Run the Project

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/zomato-eda.git
   ```

2. Navigate to the project folder:

   ```bash
   cd zomato-eda
   ```

3. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

4. Run Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

---

##  Project Structure

```
zomato-eda/
│
├── zomato.csv
├── EDA_Zomato.ipynb
├── README.md
├── requirements.txt
```

---

##  Future Improvements

* Build dashboard using Streamlit / Power BI
* Add predictive modeling (rating prediction)
* Perform city-wise deep analysis

---

##  Author

Akash Upadhya

---

⭐ If you like this project, consider giving it a star!
