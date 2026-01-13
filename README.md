# DATA-PIPELINE-DEVELOPMENT

**COMPANY**: CODTECH IT SOLUTIONS 

**NAME**: ANAM KAZI  

**INTERN ID**: CTIS0520  

**DOMAIN**: DATA SCIENCE  

**DURATION**: 4 WEEKS  

**INTERNSHIP PERIOD**: 18 DECEMBER 2025 - 15 JANUARY 2026  

**MENTOR**: NEELA SANTOSH KUMAR

# Employee Data Preprocessing and Transformation Project

This project focuses on cleaning, transforming, and preparing employee-related data for analytical and machine learning purposes. Real-world datasets are rarely perfect; they often contain missing values, inconsistent entries, mixed data types, and require standardization before they can be used effectively. This project demonstrates how to build a structured preprocessing pipeline using Python, Pandas, NumPy, and Scikit-Learn to convert raw employee data into a clean, standardized, and machine-learning-ready format.

The dataset used in this project includes important employee attributes such as Age, Salary, Experience, Gender, and Department. Some of these fields contain missing values, which provides a practical scenario for demonstrating effective data handling techniques. Through this project, the dataset is cleaned, transformed, and converted into meaningful numerical representations that can be readily used in data science workflows.

The preprocessing pipeline is designed in two major parts. The first part handles numerical features such as Age, Salary, and Experience. Missing values in these fields are handled using a mean imputation technique through Scikit-Learn’s SimpleImputer. After handling missing data, numerical features are scaled using StandardScaler to ensure that the data follows a standard normal distribution. This step is crucial because unscaled data can lead to biased machine learning models where certain features dominate due to larger numeric ranges.

The second part of the pipeline deals with categorical features including Gender and Department. Since machine learning models cannot directly understand textual categorical data, it must be converted into numerical format. This is achieved using OneHotEncoder, which converts each categorical value into binary columns representing different categories such as Gender_Female, Gender_Male, Department_IT, Department_HR, Department_Finance, and Department_Marketing. Before encoding, missing categorical values are handled using the most frequent value strategy to ensure consistency.

Both numerical and categorical preprocessing steps are combined efficiently using ColumnTransformer. This ensures that all required transformations are applied at once instead of performing manual repetitive steps. The processed data is then converted into both NumPy array and Pandas DataFrame formats, making it highly flexible for further use.

The project consists of four main files. The original dataset file data.csv contains raw employee information. The core Python script task1.py performs the complete preprocessing workflow including loading the dataset, applying transformations, generating feature names, and saving results. The output of the transformation is saved in two formats: processed_employee_data.csv, which provides a readable processed dataset, and processed_employee_data.npy, which stores the processed data in an efficient NumPy array format suitable for machine learning tasks.

The script prints the original dataset, transformation success messages, processed data shape, feature means for verification, and a preview of the transformed data. This ensures transparency and allows users to visually confirm successful preprocessing.

This project is highly valuable for learning and professional development. It reflects real-industry workflows followed in data analytics, data science, and artificial intelligence fields. Understanding preprocessing is essential because data quality directly impacts the accuracy of predictive models. By automating the transformation pipeline, this project saves time, ensures consistency, and prepares the dataset for future analysis, visualization, or machine learning model development.

#Output
![Image](https://github.com/user-attachments/assets/66276fd6-cabe-47e0-81ee-d686353be6a9)
![Image](https://github.com/user-attachments/assets/d505c3a1-a17f-4e5a-8441-374ab7ec2694)
