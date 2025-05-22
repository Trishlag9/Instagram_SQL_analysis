# 📊 Instagram Post Analytics — SQL Project

This project performs data analysis on Instagram post performance using SQL Server. It focuses on understanding user engagement, data quality, and identifying trends and outliers.

---

## 🗃️ Dataset

The data is stored in a table named `Instagram` inside a database called `MyDatabase`.

---

## 🔧 SQL Tasks Performed

### ✅ Database Setup
- Created and selected a database.
- Previewed the top 5 records.

### 📈 Summary Statistics
- Total number of posts
- Average impressions
- Maximum and minimum likes

### ⚠️ Missing Data Handling
- Identified null values in `Data_comment` and `Plays`
- Dropped `Data_comment` column due to all values being null

### 📊 Post Type Distribution
- Counted the frequency of each `Post_type`

### 💬 Engagement Metrics
- Calculated:
  - Likes per Impression (%)
  - Saves per Impression (%)
- Focused on top 5 performing posts

### 📆 Trend Over Time
- Extracted date from `Publish_time`
- Summarized total impressions and likes by date

### 🚨 Outlier Detection
- Flagged posts with impressions beyond ±2 standard deviations from the mean

## 🛠️ Tools Used

- SQL Server
- T-SQL (Transact-SQL)
## 📚 Concepts Covered

- Data profiling and cleansing  
- Aggregate metrics  
- Engagement rate analysis  
- Time series breakdown  
- Outlier detection using statistical logic

## ✅ How to Use

1. Import your Instagram data into SQL Server.
2. Use the provided SQL queries to explore and analyze the data.
3. Modify queries as needed for deeper insights.

