# Performance Predictions with Machine Learning
# Introduction
The primary aim of this report is to contribute to the enhancement of students’ educational experiences using machine learning techniques. By developing machine learning models capable of accurately predicting students’ academic performance, this report aims to provide educators, administrators, and students with a proactive tool to identify potential challenges and implement early intervention methods.

# Model Development
## Dataset
The dataset used in this report was downloaded from Mendeley data repository. It contains the academic, demographic and socio-economic information of 12,411 engineering students at the Technological University of Bolívar (UTB). The dataset has 44 variables and includes a combination of both categorical and numerical variables. The academic component of the dataset presents the results of standardised national assessments developed by the Colombian Institute for the Evaluation of Education (ICFES). The standardised tests, popularly known as Saber Test are recorded at two different periods in a student’s life. Saber11 is taken during the final year or 11th grade of high school, and it consists of 5 tests: Mathematics, Critical Reading (CR_S11), English Language (ENG_S11), Natural Sciences and Citizenship Competencies. SaberPro is aimed at students in their final year of their professional engineering program. It assesses Critical Reading (CR_PRO), Quantitative Reasoning, English Language (ENG_PRO), Writing, Citizenship Competencies and Formulation of Engineering Projects (Mendoza-Mendoza, et al., 2023). These variables (final year PRO grades) will form the basis of the target variables to measure students’ academic performance. the Table 1 displays a brief description of the numerical variables while Table 2 describes the categorical variables of the dataset. 
All data preparation and prediction tasks are performed using Python because it has powerful libraries like Pandas, NumPy and Scikit-learn which are great for data manipulation, modelling and analysis tasks. Pandas is a great choice for data cleaning because it offers DataFrames that make it easy to handle missing values, outlier and duplicates in a dataset (W3 Schools, 2022). The dataset is uploaded in Jupyter notebook and read as a Python Pandas data frame to begin pre-processing and analysis tasks. 

![image](https://github.com/user-attachments/assets/72769a8e-cab4-4163-82f9-5e6f01643afd)



