# Global Data Science Salary Dashboard (2020–2025)

> An end-to-end Tableau dashboard project analyzing global job salaries in Data Science, AI, and Machine Learning using real-world data from Kaggle.

This project provides deep insights into how job titles, experience levels, remote work preferences, and geography impact salary trends from 2020 through 2025.

---

## Project Summary

This Tableau dashboard was created to help professionals, hiring managers, and students:
- Understand global compensation trends in the AI & Data field
- Compare salary ranges across experience levels and job titles
- Identify which countries and company sizes offer the highest pay
- Analyze the impact of remote work on salaries over the years

Using a structured, clean visualization design, I broke down complex salary data into interactive charts, maps, and timelines. This project demonstrates my ability to work with real-world datasets, extract insights, and present them through business-friendly dashboards.

---

## Dataset Overview

📁 File used: [`salaries.csv`](salaries.csv)  
📌 Source: [Kaggle – Salaries for Data Science Jobs](https://www.kaggle.com/datasets/adilshamim8/salaries-for-data-science-jobs)

The dataset includes **real salary data** reported between **2020 and 2025**.  
Each row represents a job in Data Science, AI, or Machine Learning.

**Key columns in the dataset:**

| Column Name         | Description                                                                 |
|---------------------|-----------------------------------------------------------------------------|
| `work_year`         | The year the salary was reported (2020 to 2025)                            |
| `experience_level`  | Level of seniority: EN (Entry), MI (Mid), SE (Senior), EX (Executive)      |
| `employment_type`   | Full-time (FT), Part-time (PT), Contract (CT), Freelance (FL)              |
| `job_title`         | Job role (e.g., Data Scientist, ML Engineer, AI Researcher)                |
| `salary_currency`   | Original currency of salary                                                 |
| `salary_in_usd`     | Salary converted to USD for easy comparison                                |
| `employee_residence`| Country where employee lives (ISO country codes)                           |
| `remote_ratio`      | % of remote work: 0 (On-site), 50 (Hybrid), 100 (Fully Remote)             |
| `company_location`  | Country where employer is headquartered                                    |
| `company_size`      | S (Small), M (Medium), L (Large)                                            |

The raw data was downloaded directly from Kaggle and used as-is without heavy preprocessing since Tableau is capable of handling well-structured CSV files directly.

---

## Visualizations & Insights

The final Tableau dashboard includes the following sections:

### 1️⃣ **Salary Trend Over Time**
- Line chart showing how average salaries changed from 2020 to 2025
- Helps visualize salary growth across the years post-COVID and during AI boom

### 2️⃣ **Top 10 Job Titles by Average Salary**
- Horizontal bar chart showing the most lucrative roles
- Example insights: AI Architects and Data Science Managers rank highest

### 3️⃣ **Salary by Experience Level**
- Stacked bar chart comparing salaries across EN, MI, SE, and EX
- Shows how moving up in seniority drastically affects compensation

### 4️⃣ **Remote vs On-Site Salary Comparison**
- Bar chart grouped by remote_ratio (0, 50, 100)
- Hybrid roles surprisingly show slightly lower salaries than full remote or on-site

### 5️⃣ **Salary by Country (Interactive Map)**
- Map showing average salaries by country
- Used color-coding based on average salary in USD
- Helpful to visualize geographical hotspots (e.g., USA, Switzerland)

### 6️⃣ **Salary by Company Size**
- S/M/L comparison across salary distributions
- Larger companies generally offer better pay and stability

---

## Dashboard Preview

### 💼 Top Job Titles by Salary
![Bar Chart](screenshots/chart1.png)

### 📈 Salary Trend Over Time
![Line Chart](screenshots/chart2.png)

> Want to see it live? 👉 [**View on Tableau Public**](#) *(https://public.tableau.com/app/profile/sai.sadhasivam.gopalakrishnan/viz/DataScienceSalaryDashboard20202025/DataScienceSalaryDashboard)*

---

##  Key Findings

- **Executives (EX)** earn up to **3× more** than entry-level roles
- **USA, Switzerland, and Germany** lead in average salaries
- **Fully Remote roles** earn slightly more than hybrid or on-site roles
- Global salaries saw a **~40% increase** from 2020 to 2025, driven by AI industry demand
- **Data Scientist** remains the most common job title in the dataset

---

## Tools & Technologies

| Tool        | Purpose                                   |
|-------------|-------------------------------------------|
| **Tableau Public** | Dashboard design, visualization, interactive filtering |
| **VS Code**        | README authoring, project structure |
| **Git & GitHub**   | Version control, portfolio publishing |
| **Kaggle**         | Real-world dataset source           |

---

## 🧾 Author

**Sai Sadhasivam**  
Aspiring Data Scientist | Tableau & Python Enthusiast  
📫 [LinkedIn](https://linkedin.com/in/saisadhasivam) 

> I believe in learning by doing — this project is part of my journey toward becoming a world-class data scientist.

---

## Tags

`Tableau` `Kaggle` `Data Science` `Dashboard` `AI` `Machine Learning`  
`Global Salary Analysis` `Remote Work` `Visualization` `Entry-Level Project`

