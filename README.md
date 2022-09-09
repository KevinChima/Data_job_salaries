# Data Science Job Salaries - EDA

## Introduction
Data science is an interdisciplinary field that uses scientific methods, processes, algorithms and systems to extract knowledge and insights from noisy, structured and unstructured data, and apply knowledge from data across a broad range of application domains. Applications of data science range from domains including Healthcare, Gaming, Recommendation Systems, Logistics, Fraud Detection, Internet Search, Targeted Advertising, Speech Recognition, Airline Route Planning and many more. In today's world where data is increasing exponentionally, there is an urgent need to hire good data scientists, to derieve meaningful information for that huge sources of data.

In this exploratory data analysis, we Analize a dataset which consists of salaries of various Data Scientists ranging between year 2020-2022 across various Job titles and distinct geographical regions. We aim at derieving some information about how the features relate or correlate with the salary

## About the Dataset
The dataset consists of 11 features with 606 candidate's salary estimated. The features used in the dataset are described below:
| Columns | description |
| :- | :- |
| **`work_year`**|	The year the salary was paid.
| **`experience_level`**|  The experience level in the job during the year with the following possible values: EN Entry-level/ Junior MI Mid-level / Intermediate SE Senior-level / Expert EX Executive-level / Director
| **`employment_type`**|  The type of employement for the role: PT Part-time FT Full-time CT Contract FL Freelance
| **`job_title`**|  The role worked in during the year.
| **`salary`**|  The total gross salary amount paid.
| **`salary_currency`**|  The currency of the salary paid as an ISO 4217 currency code.
| **`salaryinusd`**|  The salary in USD (FX rate divided by avg. USD rate for the respective year via fxdata.foorilla.com).
| **`employee_residence`**|  Employee's primary country of residence in during the work year as an ISO 3166 country code.
| **`remote_ratio`**|  The overall amount of work done remotely, possible values are as follows: 0 No remote work (less than 20%) 50 Partially remote 100 Fully remote (more than 80%)
| **`company_location`**|  The country of the employer's main office or contracting branch as an ISO 3166 country code.
| **`company_size`**|  The average number of people that worked for the company during the year: S less than 50 employees (small) M 50 to 250 employees (medium) L more than 250 employees (large)

## Analysis Summary
Performing Exploratory Data Analysis furnish me with these informations about Data Science related job salaries:

- Data Science is gaining traction and we see an upward trend between the year 2020 and 2022.
- medium and large company size offers more salary than small company.
- Generally, Irrespective of the company size, the more experienced one is the higher the salary.
- Remote jobs are more common and offers more salary than No-remote, and Hybrid jobs. This may be as a result of the pandemic. but we can't - ascertain that because the dataset contains no record before the pandemic
- Among the top 10 most common job titles Data Architect, Machine Learning Scienctist, Data Science Manager are the top 3 highest paid job roles.
- Among the top 10 most common job titles for Entry level Machine Learning Engineer, Research Scientist, and Business Data Analyst job roles offer more salary.

## Presentation
for the presentation, I focus on the relation between each of the independent variable and the target - salary (in USD). But before presenting the relationship between the some of the independent variables and salary, I started by showing the distribution of each of the independent variable - this is crucial to understand how the variables ralates to the target.

Afterwards, I introduce the categorical columns with respect to average salary. To start, I used the bar plot and violin plot to visualize the average and median salary with respect to the 3 company sizes - Small, Medium, and Large (as contained in the dataset). In most of the visualization, I use the bar plot to get the relationship between an independent variable and the mean target (salary). I made sure I used discrete color mapping when ploting discrete variable. And where different variables are plotted (in the case of multivariate plots), I ensure to chose a color map that clearly depict each of the category to foster a better understanding and readabitlity of the plots.