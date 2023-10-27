# Bank-Loan-Case-Study
Analyzing patterns in the data using Exploratory Data Analysis(EDA) and ensuring that capable applicants are not rejected.

## Table of content
- [Project description](#Project-description)
- [Data source](#Data-source)
- [Tools](#Tools)
- [Data analysis](#Data-analysis)
- [Conclusion](#Conclusion)


### Project description 
In this project, as a data analyst in a finance company, my task is to analyze the loan application data to address the challenges of customers with sufficient credit history defaulting on loans. Using the exploratory Data Analysis (EDA) I need to examine patterns to ensure qualified applicants are not wrongly rejected. The objective is to find the patterns guiding decisions on loan denial, and amount adjustments and finally improve the company’s approach to handling loan defaults. The project’s goal is to use EDA to understand how customers and loan attributes impact the likelihood of defaults and help the company make better decisions.

### Data source 
The dataset.csv is provided in two sets one is application data and the other is previous application data, also another sheet with column descriptions before that I cleaned and understood the data and made a dataset that was required for this project according to tasks.

### Tools
- MS Excel for data analysis [Click Here](https://docs.google.com/spreadsheets/d/1dWhx7j6PtFhp8ieUc82XpaOLH2xTE_bX/edit?usp=sharing&ouid=105843925605549140071&rtpof=true&sd=true) For Application Dataset, [Click Here](https://docs.google.com/spreadsheets/d/1h5fZKaOTzn6vuaCODbEFr6Y9F3xo2gGYUFYf0Oe5XGE/edit?usp=sharing) For Previous application dataset
- Tableau for Data visualization Task 1[Click Here](https://public.tableau.com/views/P_6BankLoanCS_1/Missing_Datapvs?:language=en-GB&:display_count=n&:origin=viz_share_link), Task 2[Click Here](https://public.tableau.com/views/P_6BankloanCS_2/Income?:language=en-GB&:display_count=n&:origin=viz_share_link), Task 3,4[Click Here](https://public.tableau.com/views/Project_6CS_34/TargetImbalance?:language=en-GB&:display_count=n&:origin=viz_share_link)
- MS PowerPoint for Data report [Click Here](https://docs.google.com/presentation/d/1CDVgmE9JSDknLjhn5gWgd4TmMorpm8UT/edit?usp=sharing&ouid=105843925605549140071&rtpof=true&sd=true)

### Data analysis
1.	Identify the missing data in the dataset and an appropriate method to deal with it

  	Application dataset
    ![image](https://github.com/esmdsuhail/Bank-Loan-Case-Study/assets/142283402/0bfc3b24-6aa5-4941-a312-6989280d6ac3)

  	 Previous application dataset
    ![Missing_Data(pvs)](https://github.com/esmdsuhail/Bank-Loan-Case-Study/assets/142283402/06aa57af-5f9a-4331-b6e7-6aa16eda03b0)


Almost 50% of dataset has the columns with more than 40% data missing which are deleted and the columns below it were imputed with mean and median for numerical columns.


2.  Detect and identify outliers in the dataset using Excel statistical functions and features, focusing on numerical variables.

    ![Screenshot (257)](https://github.com/esmdsuhail/Bank-Loan-Case-Study/assets/142283402/19339be8-b8eb-4897-88d9-b1d08cf579ef)

The above variables like INCOME, CHILDREN_CNT, FAM_MEM_CNT, and DAYS_EMPLYD, from the dataset, show the most outliers than the others.


3.  Determine the data imbalance in the loan application dataset and calculate the ratio of data imbalance.

    ![image](https://github.com/esmdsuhail/Bank-Loan-Case-Study/assets/142283402/1a5a7ecf-298e-4225-a286-8479db9d5b78)

The given dataset shows a significant class imbalance, with a ratio of approximately 1:11 between non-defaulters and defaulters. Such a skewed distribution indicates that the number of default clients is relatively small compared to non-default clients.


4.	Perform univariate analysis, and bivariate analysis using Excel functions and features.
UNIVARIATE ANALYSIS

    ![Screenshot (259)](https://github.com/esmdsuhail/Bank-Loan-Case-Study/assets/142283402/6cd09c57-591d-463b-a2ab-19955a46cda7)

    ![image](https://github.com/esmdsuhail/Bank-Loan-Case-Study/assets/142283402/a9af0a36-53e8-4a5e-8530-7292a038706b)

    ![image](https://github.com/esmdsuhail/Bank-Loan-Case-Study/assets/142283402/a6f773d9-3873-4c65-b444-83357cc1acaa)

This is to understand the distribution of individual variables, and segmented univariate analysis to compare variable distributions for different scenarios.


BIVARIATE ANALYSIS
   
   This bivariate analysis is to explore relationships between variables and the target variable

  ![image](https://github.com/esmdsuhail/Bank-Loan-Case-Study/assets/142283402/55cc6a71-5b4e-4388-a3ce-2d3811cb4846)

  ![Screenshot (260)](https://github.com/esmdsuhail/Bank-Loan-Case-Study/assets/142283402/00bd5a3e-3c44-4559-9507-440453f907d6)


5.  Segment the dataset based on different scenarios (e.g., clients with payment difficulties and all other cases) and identify the top correlations for each segmented data using Excel functions.

  Top 10 of TARGET ‘0'

  ![image](https://github.com/esmdsuhail/Bank-Loan-Case-Study/assets/142283402/881ddd4e-a4b2-45b6-940e-e17168c9a40b)

  Top 10 of TARGET ‘1’

  ![image](https://github.com/esmdsuhail/Bank-Loan-Case-Study/assets/142283402/8ea59124-24dd-43a3-ab27-168cc6c6c90b)

To perform this analysis, I have used the old technique by manually applying the formula to the columns but can also be performed by using the tool pack of data analysis in the ribbon tab


### Conclusion

The valuable insights provided by this project give us the factors influencing the loan default enabling the finance company to make data-driven decisions in the loan approval process. The combination of all tasks through EDA contributes to a comprehensive understanding of the dataset and the correlation analysis and visualization were the key tools for identifying the patterns and making informed business decisions.
