Salary Analysis using PySpark
📌 Project Overview

This project performs Salary Data Analysis using PySpark, Pandas, and Matplotlib.
The goal of the project is to analyze employee salary data and extract useful insights such as:

Average salary
Highest and lowest salaries
Salary distribution
Salary based on gender
Salary based on education level
Experience impact on salary
Employee statistics and KPIs

The project also includes multiple visualizations to better understand the dataset.

🚀 Technologies Used
Python
PySpark
Pandas
Matplotlib
📂 Dataset Features

The dataset contains information such as:

Age
Gender
Education Level
Job Title
Years of Experience
Salary
⚙️ Project Steps
1. Install PySpark
!pip install pyspark
2. Create Spark Session
spark = SparkSession.builder \
    .appName("SalaryAnalysis") \
    .getOrCreate()
3. Load Dataset
df = spark.read.csv(
    "/content/Salary Data.csv",
    header=True,
    inferSchema=True
)
4. Data Cleaning
Remove null values
Remove duplicate rows
Check missing values
5. Data Analysis

The project performs several analyses including:

Average Salary
Maximum Salary
Minimum Salary
Highest Paid Job Titles
Salary by Gender
Salary by Education Level
Experience vs Salary
Salary Distribution
Employees Count by Gender
Top Salaries
Salary by Age
Correlation Between Experience and Salary
Average Salary by Age Group
6. Data Visualization

Different charts are used including:

Bar Charts
Pie Charts
Line Charts
Histograms
📊 Example Visualizations
Salary by Gender
Compare average salaries between males and females.
Experience Impact on Salary
Analyze how years of experience affect salary.
Salary Distribution
Visualize salary frequency across employees.
📈 KPI Metrics

The project calculates important KPIs such as:

Total Employees
Total Job Titles
Average Experience
Average Salary
▶️ How to Run the Project
Clone the repository:
git clone <your-repository-link>
Open the project folder:
cd <repository-name>
Install required libraries:
pip install pyspark pandas matplotlib
Run the Python file:
python salaryanalysis.py
📌 Future Improvements
Build an interactive dashboard using Streamlit
Add machine learning salary prediction
Deploy the project online
Add more advanced visualizations
👩‍💻 Author

Developed by Rana Yasser ✨
