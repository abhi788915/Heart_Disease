# Heart_Disease
 Project Report: Heart Disease Analysis Dashboard in Power BI
 Objective:
The aim of this project is to analyze heart disease data, visualize important trends, and present key insights using Power BI. The analysis focuses on understanding the distribution of heart disease in relation to factors like age, gender, cholesterol levels, and heart rate. We also track critical KPIs to provide a clear, data-driven narrative.

Data Overview:
The dataset consists of heart disease patient records with the following key attributes:

Age: Age of the patient.
Sex: Gender (0 = Female, 1 = Male).
cp: Chest pain type.
trestbps: Resting blood pressure (in mm Hg).
chol: Cholesterol level (mg/dl).
fbs: Fasting blood sugar (> 120 mg/dl).
restecg: Resting electrocardiographic results.
thalach: Maximum heart rate achieved.
exang: Exercise-induced angina (1 = Yes, 0 = No).
oldpeak: ST depression induced by exercise relative to rest.
slope: The slope of the peak exercise ST segment.
ca: Number of major vessels colored by fluoroscopy.
thal: Thalassemia (3 = Normal, 6 = Fixed Defect, 7 = Reversible Defect).
target: Target variable (1 = Heart Disease, 0 = No Heart Disease).
Key Features Added to the Data:
Sex Column Conversion:

The Sex column was converted into a more readable format:
0 = Female
1 = Male
Chest Pain Type (cp) Conversion:

The cp column was converted into descriptive categories:
0 = Typical Angina
1 = Atypical Angina
2 = Non-Anginal Pain
3 = Asymptomatic
Oldpeak Grouping:

The Oldpeak (ST Depression) values were grouped into categories:
0-1: "Mild Depression"
1-2: "Moderate Depression"
2+: "Severe Depression"
Age Group Creation:

Age ranges were created to group patients into categories:
30-40
40-50
50-60
60-70
70+
KPIs and Visualizations:
1. Key Performance Indicators (KPIs):
Average Age of Patients: Displayed the mean age of patients.
Average Cholesterol Level: Showed the average cholesterol level in the dataset.
Heart Disease Rate: Presented as a KPI card, showing the percentage of patients with heart disease (target = 1).
Maximum Heart Rate Achieved: Displayed the highest heart rate (thalach) recorded among patients.
Chest Pain Distribution: Visualized as a bar chart to show the frequency of different types of chest pain.
2. Gauge KPI:
Heart Disease Rate (Gauge): A gauge was used to track the percentage of patients with heart disease against a target or benchmark.
3. Interactive Slicers:
Age Group Slicer: Created age groups to filter visualizations by age range (30-40, 40-50, etc.).
Gender Slicer: Allowed filtering visualizations based on gender (Male/Female).
4. Visualizations:
Heart Disease Distribution by Age and Gender:

A clustered bar chart was created to visualize the heart disease distribution across age groups, split by gender (Male/Female).
It is color-coded to show patients with and without heart disease based on the target column.
Chest Pain Type by Gender:

A stacked column chart showing the distribution of different chest pain types (Typical Angina, Atypical Angina, etc.) across genders.
Oldpeak Distribution:

A column chart showing the distribution of ST Depression (Oldpeak) across the categories (Mild, Moderate, Severe) and comparing them for patients with and without heart disease.
Cholesterol Levels by Age Group:

A line chart to track average cholesterol levels across different age groups, helping to observe trends of cholesterol with age.
Insights:
Heart Disease Distribution: The highest occurrence of heart disease was observed in the age group 50-60, with males having a slightly higher prevalence of heart disease compared to females.
Cholesterol Trends: Higher cholesterol levels are more prevalent among patients in the 50-60 age group, with a slight decrease in older groups.
Chest Pain Analysis: Asymptomatic patients (Chest Pain Type 3) made up a significant portion of those diagnosed with heart disease.
Oldpeak ST Depression: Most patients experiencing Moderate Depression (Oldpeak between 1 and 2) tend to have a higher incidence of heart disease.
Conclusion:
The Heart Disease Analysis Dashboard successfully provides an interactive and comprehensive view of the dataset. With key insights like age-related trends in heart disease, the impact of cholesterol and heart rate, and gender-based comparisons, this dashboard can help healthcare professionals and analysts better understand the factors associated with heart disease.

Further exploration could include advanced predictive modeling or using additional datasets to expand the analysis.
