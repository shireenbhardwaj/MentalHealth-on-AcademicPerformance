# 📊 Student Mental Health Analysis: Impact on Academic Performance
Student Mental Health Analysis explores mental health trends among students using multiple survey datasets. It includes data cleaning, exploratory analysis in Jupyter notebooks, and a Power BI dashboard for visualization. The project aims to uncover insights to inform educational institutions and policymakers. 

## 📝 Project Overview
This project explores the prevalence of mental health disorders among students and their impact on academic productivity and achievement. By analyzing multiple datasets, we aim to provide insights into how mental health affects absenteeism, GPA, and overall academic performance.

### 🔍 **Key Research Questions:**
- How do mental health disorders impact academic performance, particularly in terms of absenteeism and presenteeism?
- What patterns exist between mental health conditions and GPA?
- How can educational institutions use data to identify and support students at risk?

## 📂 Data Sources
We utilized **both primary and secondary data sources** to enhance our analysis.
|Dataset|	Source|	Key Variables|	Purpose|
|:------:|:------:|:------:|:------:|
|Student Mental Health Data|	Kaggle|	GPA, Symptoms, Year of Study, Age|	Examines the link between mental health and academic performance|
|Global Student Mental Health|	Data.World (U.S. Dept. of Health & Human Services)	|Geographic location, Gender, Mental Health Indicators|	Visualized in Power BI to analyze trends across different regions|
|University Student Mental Health|	Borealis	|Age, Social Support Score, Emotional Regulation, Stress Scores	|Applied regression models to analyze predictors of mental health|
|Mental Health Survey (Primary Data)	|Custom Survey	|Self-reported stress, mental health symptoms, academic habits|	Identifies behavioral patterns affecting academic success|

### 🛠 Data Preprocessing & Quality Handling
- **Imputation of missing values** using statistical techniques
- **Data transformation** for uniformity across datasets
- **Outlier detection** & removal for cleaner analysis
- **Feature engineering** to extract meaningful insights

## 💻 Methods & Tools Used
### 🛠 Technologies
- **Python** (Pandas, NumPy, Matplotlib, Seaborn, Sci-kit Learn, SciPy)
- **Jupyter Notebooks** for data wrangling and exploratory analysis
- **Power BI** for interactive visualizations and dashboards
- **Regression Models** (Linear, Ridge, Random Forest) for trend analysis

### 🔬 Analytical Approaches
- **Data Cleaning & Transformation:** Handling missing data, normalizing values, and creating derived variables.
- **Exploratory Data Analysis (EDA):** Identifying trends and correlations between mental health symptoms and academic performance.
- **Statistical Modeling:** Applying regression techniques to predict the impact of mental health on student performance.
- **Dashboard Creation:** Designing an interactive Power BI dashboard to communicate findings visually.

## 📈 Key Findings
- Students experiencing multiple mental health issues (e.g., stress, anxiety, loneliness) showed lower GPA scores.
- Higher absenteeism correlated strongly with poor academic performance.
- International students exhibited higher levels of academic stress, possibly due to visa-related pressures.
- Negative perceptions around seeking mental health support were common among students with lower GPA.
- Students on the borderline of GPA requirements for visa status (F1: 3.0 GPA) reported the highest stress levels.
  
📌 **Conclusion:** Universities should implement targeted mental health interventions, personalized academic support, and initiatives to reduce stigma around mental health discussions.

## 📊 Power BI Dashboard
A Power BI dashboard was developed to provide interactive visualizations of our findings. It consists of two main sections:
- **Survey Data Insights:** How self-reported mental health symptoms correlate with academic performance.
  
![Page 1](https://github.com/user-attachments/assets/a937b24d-7a8d-43a0-9dc7-3c43111a048d)

- **Global Trends:** Analysis of student mental health patterns across different regions.
  
![Page 2](https://github.com/user-attachments/assets/c96bc279-7e4c-4d1a-a5be-c91273719d17)


## 🚀 Challenges & Learnings
### 🔴 Challenges
- Handling missing data and inconsistencies in public datasets
- Integrating multiple datasets with different structures
- Addressing low response rates in primary survey data
- Ensuring statistical validity of regression models

### ✅ Key Takeaways
- Data preprocessing is crucial for accurate analysis.
- Combining quantitative (regression) and qualitative (survey) approaches provided deeper insights.
- Visualization tools like Power BI help in making findings actionable and interpretable.

## 📌 Future Scope
- Expand dataset to include more diverse student populations for improved generalizability.
- Conduct a longitudinal study to track mental health trends over time.
- Develop an early warning system for universities to identify at-risk students based on behavioral patterns.
