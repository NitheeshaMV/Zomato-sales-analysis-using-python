 # Zomato Sales Analysis

## 📌 Project Overview
This project analyzes **Zomato sales data** to derive meaningful insights into restaurant types, sales trends, pricing distribution, and correlations between different features. The dataset undergoes **data preprocessing, exploratory data analysis (EDA), and visualization** using Python.

## 📊 Dataset Description
The dataset is sourced from **Zomato sales records** and contains the following columns:
| Column Name      | Description |
|-----------------|-------------|
| `date`          | Date of the transaction |
| `restaurant_type` | Type of restaurant |
| `sales`         | Total sales amount |
| `rating`        | Customer rating |
| `city`          | City where the restaurant is located |
| `cost_for_two`  | Average cost for two people |

## 🛠 Data Preprocessing
- Removed **duplicates** and **missing values**
- Converted `date` column to **datetime format**
- Standardized numerical values

## 📈 Exploratory Data Analysis
### 📌 Restaurant Type Distribution
- Count plot to visualize the **number of restaurants by type**.

### 📌 Sales Trend Over Time
- Line graph to analyze **sales fluctuations over time**.

### 📌 Rating Distribution
- Histogram to understand the **distribution of restaurant ratings**.

### 📌 Cost for Two Analysis
- Bar graph to compare **average cost for two** across different cities.
- Box plot to analyze **cost variations** across cities.

### 📌 Feature Correlation
- Heatmap to identify **relationships between different numerical variables**.

## 📊 Results & Insights
- The majority of restaurants belong to a specific **popular category**.
- Sales exhibit **seasonal trends**, peaking at certain times.
- Higher-rated restaurants tend to have **higher costs for two**.
- Some cities show **significantly higher average costs** than others.

## 🔧 Technologies Used
- **Python**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Seaborn**



