# 🛢️ Week 5: Data Analysis in SQL 🏆  

🚀 **Internship:** KultureHire DA Intern  
👨‍🏫 **Mentor:** Gouthom Kumar  
📅 **Internship Start Date:** March 6, 2024  
📍 **Current Status:** Ongoing ⏳  

---

## 📢 Week 5 Focus: Data Analysis Using SQL 🎯  

After conducting **Exploratory Data Analysis (EDA) using Excel Pivot Tables** in Week 4, this week’s focus was on performing **structured and optimized data analysis using SQL**.  

📌 **Why SQL for Data Analysis?**  
SQL is an essential tool for querying, filtering, and analyzing large datasets efficiently. By leveraging SQL, we can extract **valuable insights** and perform **aggregations, joins, and trend analysis** in an optimized way.  

---

## 🔥 Week 5 Progress 🚀  

### ✅ **1. Setting Up the SQL Environment** 🛠️  
🔹 **Loaded the cleaned dataset into SQL Database** (MySQL/PostgreSQL) 🗄️  
🔹 **Created tables & defined schema** (data types, constraints) 📋  
🔹 **Checked for data integrity and consistency** 🔎   


### ✅ **2. Writing SQL Queries for Analysis** 🏗️  
🔸 Performed **data filtering & selection** using `SELECT`, `WHERE`, and `ORDER BY` 📊  
🔸 Used **aggregations (`COUNT()`, `AVG()`, `SUM()`, `GROUP BY`)** to analyze trends 📈  
🔸 Applied **joins (`INNER JOIN`, `LEFT JOIN`)** to combine multiple tables 🔗  
🔸 Used **window functions (`RANK()`, `DENSE_RANK()`)** for advanced analytics 🏆  


### ✅ **3. Key SQL Queries & Findings** 🔍  
#### 🔹 **1️⃣ Most Preferred Career Paths Among Gen Z:**  
```sql
SELECT career_path, COUNT(*) AS total_responses
FROM survey_data
GROUP BY career_path
ORDER BY total_responses DESC
LIMIT 5;
```
🔹 **Insight:** The top 3 career paths chosen by Gen Z are **[Career 1], [Career 2], [Career 3]** 🚀  


#### 🔹 **2️⃣ Salary Expectations by Industry:**  
```sql
SELECT industry, AVG(expected_salary) AS avg_salary
FROM survey_data
GROUP BY industry
ORDER BY avg_salary DESC;
```
🔹 **Insight:** **[Industry X]** offers the highest expected salaries 💰  


#### 🔹 **3️⃣ Work-Life Balance Preferences:**  
```sql
SELECT work_life_balance, COUNT(*) AS count
FROM survey_data
GROUP BY work_life_balance
ORDER BY count DESC;
```
🔹 **Insight:** **X%** of respondents prefer jobs with strong work-life balance ⚖️  


### ✅ **4. Documentation & Submission** 📑  
🔸 Compiled **SQL query outputs & insights** into a summary report 📝  
🔸 Exported the final results as a **CSV file** 📂  
🔸 Shared findings with my mentor for feedback ✅  

📥 **[Download the SQL Analysis Report PDF](https://github.com/venkateshcodes/Internship/blob/804b468a590b3ccdc60046652dafae3d05e5da76/KultureHire%20DA%20Intern/Data%20Analysis%20in%20SQL%20week-05/Sql%20Questions%20%20in%20my%20Journey.pdf)**
📑 **[SQL Query Scripts](https://github.com/venkateshcodes/Internship/blob/f68880ed4e409348901eab3bd107fefa39fdb7dc/KultureHire%20DA%20Intern/Data%20Analysis%20in%20SQL%20week-05/Data%20Analysis%20with%20SQL.docx)** 

---

## 📊 Key Insights from SQL Analysis  

🔹 **Top 3 Career Choices:** [Field 1], [Field 2], [Field 3] 🎯  
🔹 **Industry with Highest Expected Salary:** [Industry X] 💰  
🔹 **Percentage of Respondents Preferring Remote Work:** X% 🌍  
🔹 **Job Satisfaction Scores by Industry:** [Industry 1], [Industry 2] ⭐  

---

## ⚠️ Challenges Faced & Solutions 💡  

⚠️ **Challenge:** Large dataset slowed down SQL queries.  
✔️ **Solution:** Optimized queries using **indexes & efficient filtering**.  

⚠️ **Challenge:** Missing or NULL values in key fields.  
✔️ **Solution:** Used **`COALESCE()` function** to handle missing values.  

⚠️ **Challenge:** Understanding complex data relationships.  
✔️ **Solution:** Used **JOINs & subqueries** for better insights.  

---

## ⏭️ Next Steps for Week 6  

🚀 **Data Visualization Using Power BI/Tableau** 📊  
🚀 **Building interactive dashboards for insights** 📈  
🚀 **Preparing final reports & presentations** 📝  

---

### 📬 Let's Connect  

💼 [LinkedIn](https://www.linkedin.com/in/kedari-sri-venkatesh-359056347) | 💻 [GitHub](https://github.com/venkateshcodes) | ✉️ [Email](srivenkatesh6.k@gmail.com)  

🔔 Stay tuned for updates! 🌟  

---

## ⭐ Support  
If you find this project useful, don't forget to **⭐ star the repository!**  

### 📌 **Project Done by:** **KEDARI SRI VENKATESH**  
📢 Published on **VenkateshCodes**  
```

## ⭐ If you find this project useful, don't forget to give it a star! ⭐
