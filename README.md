# 🎬 Netflix Movies & TV Shows Data Analysis using SQL

<p align="center">
  <img src="logo.png" alt="Netflix SQL Project Banner" width="100%">
</p>

<p align="center">
A complete SQL-based data analytics project that explores Netflix's content library to answer real-world business questions using PostgreSQL.
</p>

---

# 📖 Project Overview

The rapid growth of streaming platforms has generated enormous volumes of entertainment data. Organizations rely on data analytics to understand audience preferences, identify content trends, and make informed business decisions.

This project focuses on analyzing the Netflix Movies and TV Shows dataset using SQL. By applying various SQL concepts such as filtering, aggregation, joins, Common Table Expressions (CTEs), window functions, date functions, and string manipulation, this project extracts meaningful business insights from raw data.

Rather than simply querying the dataset, the project simulates real-world business scenarios that a Data Analyst may encounter while working with an OTT platform or media company.

---

# 🎯 Project Objectives

The main objectives of this project are to:

* Analyze the overall distribution of Movies and TV Shows.
* Explore content ratings across different categories.
* Identify trends based on release years.
* Discover countries contributing the highest amount of Netflix content.
* Analyze movie durations and TV show seasons.
* Examine genre-wise content distribution.
* Identify missing or incomplete records.
* Perform country-specific analysis for India.
* Practice solving business-oriented analytical problems using SQL.

---

# 📂 Dataset Information

**Dataset Name:** Netflix Movies & TV Shows

**Source:** Kaggle

The dataset contains metadata for thousands of Netflix titles and includes information such as:

* Show ID
* Content Type
* Title
* Director
* Cast Members
* Country
* Date Added
* Release Year
* Rating
* Duration
* Genre
* Description

This dataset is widely used for practicing SQL, data cleaning, and exploratory data analysis.

---

# 🛠️ Technologies Used

| Technology | Purpose             |
| ---------- | ------------------- |
| PostgreSQL | Database Management |
| SQL        | Data Analysis       |
| pgAdmin    | Query Execution     |
| Git        | Version Control     |
| GitHub     | Project Hosting     |

---

# 🗄️ Database Schema

The project stores the dataset in a single table named **netflix**.

Columns include:

* show_id
* type
* title
* director
* casts
* country
* date_added
* release_year
* rating
* duration
* listed_in
* description

This schema provides all the necessary information required to perform business analysis on Netflix's content library.

---

# 📊 Business Problems Solved

The following analytical questions were solved using SQL:

### 1. Movies vs TV Shows Distribution

Determine the total number of Movies and TV Shows available on Netflix.

---

### 2. Most Common Rating

Identify the rating that appears most frequently for Movies and TV Shows separately.

---

### 3. Movies Released in a Specific Year

Retrieve all movies released during a selected year.

---

### 4. Top Countries by Content

Identify the five countries that have produced the highest amount of Netflix content.

---

### 5. Longest Movie

Find the movie with the maximum runtime available in the dataset.

---

### 6. Recently Added Content

Retrieve all content added to Netflix during the last five years.

---

### 7. Movies Directed by Rajiv Chilaka

Find every title directed by Rajiv Chilaka.

---

### 8. TV Shows with More Than Five Seasons

Identify long-running television series.

---

### 9. Genre Distribution

Count the number of titles available under each genre.

---

### 10. India's Year-wise Content Analysis

Calculate India's yearly contribution and determine the top five years with the highest percentage of content releases.

---

### 11. Documentary Movies

Retrieve all titles categorized as documentaries.

---

### 12. Missing Director Information

Identify content records where the director field is unavailable.

---

### 13. Salman Khan Movies

Find all Salman Khan movies released during the last ten years.

---

### 14. Top Indian Actors

Identify actors appearing most frequently in Indian-produced Netflix content.

---

### 15. Content Classification

Categorize titles into different groups depending on whether their description contains keywords like **Kill** or **Violence**.

---

# 🧠 SQL Concepts Practiced

This project demonstrates practical implementation of:

* SELECT Statement
* WHERE Clause
* ORDER BY
* GROUP BY
* Aggregate Functions
* CASE WHEN
* DISTINCT
* Common Table Expressions (CTEs)
* Window Functions
* RANK()
* String Functions
* Date Functions
* Type Casting
* UNNEST()
* STRING_TO_ARRAY()
* Pattern Matching (LIKE & ILIKE)
* Nested Queries

---

# 📈 Key Insights

After analyzing the dataset, several interesting observations were identified:

* Netflix offers a significantly larger collection of Movies compared to TV Shows.
* TV-MA and TV-14 are among the most frequently assigned content ratings.
* The United States and India contribute a major share of Netflix's content.
* Drama and International Movies are among the most common genres.
* Some records contain missing director information, highlighting real-world data quality issues.
* India has shown continuous growth in content production across multiple years.
* Keyword-based categorization helps distinguish between general entertainment and potentially violent content.

---

# 🚀 Learning Outcomes

By completing this project, I gained practical experience in:

* Writing optimized SQL queries
* Performing business-focused data analysis
* Solving real-world analytical problems
* Working with large structured datasets
* Using PostgreSQL for data exploration
* Applying advanced SQL functions
* Converting raw data into actionable business insights

---

# 📁 Repository Structure

```text
Netflix_SQL_Project/
│
├── Dataset/
│   └── netflix_titles.csv
│
├── SQL Queries/
│   ├── Question_01.sql
│   ├── Question_02.sql
│   ├── ...
│   └── Question_15.sql
│
├── Screenshots/
│
├── logo.png
│
└── README.md
```

---

# ⭐ Project Highlights

✔ Real-world Business Problems

✔ SQL-Based Data Analytics

✔ Advanced PostgreSQL Queries

✔ Data Cleaning Techniques

✔ Window Functions & CTEs

✔ String Manipulation

✔ Date Operations

✔ Business Insight Generation

---

# 📌 Future Improvements

Possible enhancements for this project include:

* Developing an interactive Power BI dashboard.
* Creating Tableau visualizations.
* Performing Python-based Exploratory Data Analysis (EDA).
* Building predictive machine learning models.
* Automating report generation.
* Deploying the project as a web-based analytics dashboard.

---

# 🤝 Connect With Me

If you found this project helpful or have any suggestions, feel free to connect with me on GitHub or LinkedIn.

⭐ If you like this project, don't forget to give the repository a Star!
