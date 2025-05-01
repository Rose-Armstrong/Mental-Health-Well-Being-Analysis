# Mental-Health-Well-Being-Analysis
 Excel Dashboard Project

📌 Overview:
This project presents an interactive dashboard analyzing the mental health and well-being of students using an open dataset from Kaggle. The goal is to identify patterns and risk factors related to depression, suicidal thoughts, and overall lifestyle behaviors among students.

🔧 Tools Used:

Microsoft Excel: Pivot Tables, Pivot Charts, Slicers

Data Cleaning: Excel formulas (e.g., IF(), SUBSTITUTE(),TRIM() )

Dataset: Student Depression Dataset – Kaggle

🧹 Data Cleaning & Preprocessing:

Fixed inconsistent city names and removed irrelevant entries (e.g., '3', 'city', educational qualifications).

Grouped Age into categories using nested IF() formulas.

Removed binary indicators and replaced them with Yes/No for readability (e.g., depression status).

Handled outliers in CGPA (e.g., removed 0) and grouped as Above Average / Below Average.

Removed incorrect or placeholder financial stress entries.

Cleaned up text fields using SUBSTITUTE() to remove unwanted characters (e.g., quotes).

Removed "Others" category from dietary habits for clarity.

📊 Dashboard Features:
Filters: Gender, City, CGPA Category

Visuals:

Depression vs Suicidal Thoughts (Pie Chart)

Suicidal Thoughts by Age Group

Financial Stress vs Depression

Depression vs Sleep and Eating Habits

Family History vs Depression

Easy comparison through interactive slicers.

🚀 How to Use:
Open the Excel file.
Use slicers to explore mental health trends across gender, cities, and CGPA categories.
Visualisations will auto-update with slicer input.
