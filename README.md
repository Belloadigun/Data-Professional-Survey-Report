# Data-Professionals-Survey-Report
Exploratory data analysis of survey responses from data professionals. The project highlights key trends, insights, and visualizations related to roles, tools, and experiences in the data industry.

![business-data-analysis](https://github.com/user-attachments/assets/763a1d06-9358-4501-98e5-5f60d67a9bc2)

# 📊 Introduction
This project presents an exploratory data analysis (EDA) of survey responses collected from professionals in the data industry. The aim is to uncover insights into common tools, job roles, work experience, and trends within the field of data science and analytics. The analysis was conducted using Power BI, leveraging its powerful data modeling and visualization capabilities to create an interactive dashboard that showcases key patterns and findings. 
This project serves both as a learning experience in data visualization and a resource for those interested in the current landscape of the data profession.

# 🔍 Project Objectives
This project explores a dataset related to professionals in the data industry, aiming to uncover insights around career trends, preferences, and satisfaction. The key questions addressed include:
1. What is the average salary for each job title?
Analyzing how compensation varies across different roles in the data profession.
3. Which programming language is most favored, and by whom (job title)?
Identifying the most popular programming languages and which professionals prefer them the most.
4. How difficult is it to break into the data profession?
Examining responses related to career transitions and barriers to entry into data-related roles.
5. What is the satisfaction rate with work-life balance?
Measuring how content data professionals are with their work-life balance.
6. What is the satisfaction rate with salary?
Investigating how happy professionals are with their current compensation.

# 📊 Data Source
Tha data used in this project was sourced from Power BI - Final Project.xlsx

# 📊🧹 Data Cleaning Process
To meet the objectives of this project, the dataset underwent several transformation steps to prepare it for analysis;
1. All Columns between "Browser" and "Referrer" were deleted.
   ![Deleted Columns](https://github.com/user-attachments/assets/a4879de9-abeb-4cf4-b482-f9dffd64c99e)
2. The Column with title name "Which Title Best Fits your Current Role?" is splitted by Delimiter.
   ![Splitting Column](https://github.com/user-attachments/assets/d9e63ecb-a51f-4248-a472-463d132fa009)
3. The New Column generated after splitting was deleted.
   ![New Column after Splitting](https://github.com/user-attachments/assets/70306620-3f6e-4512-bacb-f5754dfe76f6)
4. The Column with title name "Favorite Programming Language" is splitted by Delimiter.
   ![Splitting Column 2](https://github.com/user-attachments/assets/62b8d7a2-8cd1-4bd0-a86b-b505a58cf20f)
5. The New Column generated after splitting was deleted.
6. The Column "Current Yearly Salary (in USD)" was duplicated.
   
   ![Duplicate column](https://github.com/user-attachments/assets/1ec5c0dd-d567-47ce-9377-8ba1d9550616)
8. The duplicate column by title "Current Yearly Salary (in USD)-Copy" was splitted by Digit to Non-Digit.
   ![Splitted Column 1](https://github.com/user-attachments/assets/23fcc2c8-8872-47a7-ba64-af835b665387)
9. Duplicated column with title "Current Yearly Salary (in USD)- Copy.3" was deleted.
10. "k","-" and "+" were replaced in "Current Yearly Salary (in USD)- Copy 2" Column with blanks and a numerical value.
    ![Replaced Value 1](https://github.com/user-attachments/assets/af994c93-d53d-4b1e-b8ea-0688e6005316)
11. A New Column "Average Salary" was added to the table.
12. Columns with title name "What Industry do you work in?" and "Which country do you live in?" were splitted by Delimiters.

# 📈 Visualization and Insights
![Power BI Dashboard](https://github.com/user-attachments/assets/72a2641a-5abd-4886-b378-02f5c3c283e4)

1. Canada appears to have the highest number of survey respondents.
2. There's a visible gap in pay among different roles, emphasizing specialization value.
3. Work-Life Balance scored 5.74/10, which is average but not excellent. Salary Satisfaction is 4.27/10, which is quite low.
4. Majority found it "Difficult" or "Very Difficult" to break into the data field.
5. Low votes for JavaScript and Java confirm their limited use in core data roles.

# ✅ Recommendations 
1. Given the difficulty in entering the field, organizations and educators should promote:
   a) Mentorship programs.
   b) Internship and bootcamp opportunities.
   c) More beginner-friendly content and community access.
2. Low happiness with salary suggests employers may need to:
   a) Reassess compensation structures.
   b) Offer clearer promotion pathways and benefits.
3. Work-life balance is average. Employers should consider:
   a) Flexible work arrangements.
   b) Mental health support initiatives in data roles.






