# Data-Science-Project-AI-Job-Analysis
📊 AI Salary & Job Analysis — Exploratory Data Analysis (EDA)

This project explores AI & Data Science job salaries using pure Data Science tools (no machine learning).
The analysis is done using Pandas, NumPy, Matplotlib, and Seaborn and focuses on understanding how salary varies with:

Job titles

Experience levels

Company location

Employment type

Remote ratio

Year

The goal is to clean, visualize, and generate insights from the dataset.

🧠 Project Overview

This project includes:

✔️ Data Cleaning
✔️ Handling missing values
✔️ Data type corrections
✔️ Exploratory Data Analysis
✔️ Visualizations (scatterplots, bar charts, boxplots, pairplots)
✔️ Salary distribution analysis
✔️ Top-10 aggregations (cleaner visualizations)
✔️ Insights and conclusions

The dataset used contains attributes such as:

job_title

experience_level

company_location

employment_type

salary / salary_in_usd

remote_ratio

work_year

🔧 Technologies Used
Library	Purpose
Pandas	Data cleaning, manipulation, analysis
NumPy	Numerical operations
Matplotlib	Basic plots
Seaborn	Statistical visualizations
Jupyter Notebook	Interactive development
📥 How to Run This Project
1️⃣ Clone the repository
git clone https://github.com/<your-username>/<your-repo-name>.git
cd <your-repo-name>

2️⃣ Create and activate a virtual environment (optional but recommended)
python -m venv venv
# Windows
venv\Scripts\activate
# macOS / Linux
source venv/bin/activate

3️⃣ Install the dependencies
pip install -r requirements.txt

4️⃣ Run the Jupyter Notebook
jupyter notebook

📊 Visualizations Included

The analysis includes:

✔️ Salary distribution

Histogram

KDE plot

✔️ Salary vs Experience Level

Boxplot (clean)

Statistical summary

✔️ Top 10 Job Titles

Horizontal bar chart

Aggregated mean salary

✔️ Company Location Analysis

Salary comparison by country

Remote vs Onsite comparisons

✔️ Pairplot

To understand relationships between numerical features

✔️ Scatterplots

Salary vs Experience

Salary vs Remote Ratio

All visuals are resized, cleaned, and properly labeled for readability.

🧹 Data Cleaning Steps

Some of the key steps include:

Handling missing salary values

Standardizing experience levels (EN, MI, SE, EX)

Dropping invalid or duplicate records

Converting salary to salary_k (in thousands) for readability

Sorting and aggregating job titles (Top 10 to avoid clutter)

🔍 Key Insights from the Analysis

Here are some sample insights you can modify based on your results:

Senior-level roles (SE) earn the highest median salary.

Fully remote jobs show a tendency to pay higher compared to on-site roles.

The USA, Germany, and UK have the highest average salaries in the dataset.

Top-paying job titles include roles like "Machine Learning Engineer" and "Data Architect".

Experience level has a strong correlation with salary, but company location affects it significantly.

📌 Future Work

Since you haven’t learned machine learning yet, this project is focused on EDA.
But later you can extend this project with:

Salary prediction (Linear Regression / Random Forest)

Feature engineering

Automated dashboards using PowerBI/Tableau

Streamlit web app

📄 License

This project is licensed under the MIT License — you are free to use, modify, and distribute it.

🤝 Contributions

Pull requests are welcome!
If you’d like to improve visualizations, add new analyses, or optimize the notebook, feel free to open an issue.

⭐ Support

If you found this useful, please give the repo a star ⭐ on GitHub!
