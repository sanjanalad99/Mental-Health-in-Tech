
Mental Health in Tech Survey Analysis
This project aims to analyze mental health data in the tech industry using the Mental Health in Tech Survey dataset. The analysis utilizes Python's Pandas library for data manipulation and Matplotlib, Seaborn, and hvPlot for data visualization.

Dataset Overview
The dataset contains information on various attributes including age, gender, country, employment status, family history of mental health issues, treatment received, and more.

Data Cleaning: Missing Values
Initially, we identified missing values in several columns including "state", "self_employed", "work_interfere", and "comments". After assessing the impact of missing values, we decided to drop the "state" and "comments" columns and fill missing values in "self_employed" and "work_interfere" columns with their respective modes.

Univariate Analysis
We conducted univariate analysis to explore individual attributes such as country, age, employment status, family history, remote work, and more. Key insights include:

The United States, the United Kingdom, and Canada have the highest number of mental health cases in the tech industry.
Individuals aged between 25-40 are more susceptible to mental health issues.
Most affected individuals are employees working in-office rather than remotely and are employed by tech companies.
Bivariate & Multivariate Analysis
Further analysis involved examining relationships between attributes and identifying similarities. We converted categorical variables to numerical for correlation analysis.

Notable findings include a strong correlation between seeking help, wellness programs, and benefits provided by employers for mental health support.

Conclusion
The analysis sheds light on the prevalence of mental health issues in the tech industry and provides insights for employers to consider implementing supportive measures. This project demonstrates the importance of data-driven approaches in addressing mental health challenges in the workplace.




