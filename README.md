# 🎓 Student Performance Data Analysis using Python

## 📌 Project Overview
This project is an end-to-end **Data Analytics Project** built using Python.  
The objective of this project is to analyze student performance data, clean and transform the dataset, perform Exploratory Data Analysis (EDA), and generate meaningful insights using visualizations.

The project demonstrates practical usage of:
- **Pandas** for data manipulation
- **NumPy** for numerical operations
- **Matplotlib** and **Seaborn** for data visualization

This project is beginner-friendly and suitable for showcasing on a resume or GitHub portfolio.

---

# 📂 Dataset Information
The dataset contains information related to students such as:
- Gender
- Parent Education Level
- Parent Marital Status
- Ethnic Group
- Math Score
- Reading Score
- Writing Score
- Other demographic details

Dataset Source: Kaggle

---

# 🛠️ Technologies Used

| Technology | Purpose |
|------------|----------|
| Python | Programming Language |
| Pandas | Data Cleaning & Analysis |
| NumPy | Numerical Computation |
| Matplotlib | Data Visualization |
| Seaborn | Statistical Visualization |
| Jupyter Notebook | Development Environment |

---

# 📦 Installation

Install the required libraries using pip:

```bash
pip install numpy pandas matplotlib seaborn

🚀 Project Workflow
1️⃣ Data Import
Imported dataset using Pandas
Loaded CSV file into DataFrame
import pandas as pd

df = pd.read_csv("students.csv")
2️⃣ Data Exploration

Performed initial exploration using:

df.head()
df.info()
df.describe()
df.isnull().sum()

This helped understand:

Data types
Missing values
Dataset structure
Statistical summaries
3️⃣ Data Cleaning

Steps performed:

Removed unnecessary columns
Fixed inconsistent string values
Checked for null values
Corrected formatting issues

Example:

df['weekly study hours'] = df['weekly study hours'].str.replace('5th October', '5 to 10')
4️⃣ Exploratory Data Analysis (EDA)
📊 Gender Distribution

Used Seaborn countplot to visualize gender distribution.

📈 Parent Education vs Student Scores
Grouped data based on parent education
Calculated average math, reading, and writing scores
Visualized using heatmap
📉 Parent Marital Status Analysis

Analyzed whether marital status affects student performance.

📦 Boxplots for Outlier Detection

Used boxplots to detect:

Outliers
Score distribution
Variability in student scores
🥧 Ethnic Group Distribution

Created pie charts and countplots to visualize ethnic group percentages.

📷 Sample Visualizations
Count Plots
Heatmaps
Pie Charts
Boxplots

These visualizations help in understanding:

Student performance trends
Demographic impact
Score distributions
Relationships between variables
🔍 Key Insights

✅ Female students slightly outnumber male students.

✅ Parent education level has a strong impact on student scores.

✅ Parent marital status has very little impact on performance.

✅ Math scores showed greater variability and more outliers.

✅ Group C had the highest student population among ethnic groups.

📚 Learning Outcomes

Through this project, I learned:

Real-world data cleaning techniques
Exploratory Data Analysis (EDA)
Data visualization best practices
Grouping and aggregation using Pandas
Drawing insights from datasets
Creating resume-worthy analytics projects
📁 Project Structure
📦 Student-Performance-Analysis
 ┣ 📂 dataset
 ┃ ┗ 📄 students.csv
 ┣ 📂 images
 ┃ ┗ 📄 charts.png
 ┣ 📄 analysis.ipynb
 ┣ 📄 README.md
 ┗ 📄 requirements.txt
▶️ How to Run the Project
Clone the repository
git clone https://github.com/your-username/student-performance-analysis.git
Navigate to project folder
cd student-performance-analysis
Open Jupyter Notebook
jupyter notebook
Run analysis.ipynb
🌟 Future Improvements
Add Machine Learning models for score prediction
Create interactive dashboards using Power BI or Tableau
Deploy project using Streamlit
Perform deeper statistical analysis
🤝 Contributing

Contributions are welcome. Feel free to fork this repository and improve the project.

📬 Contact

If you liked this project, feel free to connect with me on GitHub and LinkedIn.

⭐ Don't Forget to Star the Repository!

If you found this project helpful, give it a ⭐ on GitHub.
