# Banking-Loan-Defaulter-Analysis


## Project Objective

The primary objective of the project is to understand the characteristics and patterns of loan defaulters within a given dataset. 
By performing exploratory data analysis, I aim to uncover insights that can assist in identifying key factors influencing loan default and segmenting customers accordingly.

## Data Source

The dataset used in this analysis is sourced from Kaggle. It contains [brief description of the dataset, e.g., information about borrowers, loan amounts, repayment history, etc.].

## Tools and Libraries

- **Python**: The entire analysis is conducted using Python programming language.
- **Pandas**: Used for data manipulation and cleaning.
- **Matplotlib and Seaborn**: Employed for data visualization.
- **NumPy**: Utilized for numerical operations.
- **Jupyter Notebooks**: The analysis is documented and presented in Jupyter Notebooks for better clarity and interactivity.

## Project Workflow

### 1. Data Loading and Inspection

- Load the dataset into a Pandas DataFrame.
- Inspect the structure of the dataset, check for missing values, and understand the basic statistics.

### 2. Data Cleaning

- Handle missing values and outliers appropriately.
- Address any data inconsistencies or discrepancies.

### 3. Exploratory Data Analysis

#### 3.1 Univariate Analysis

- Examine the distribution of individual variables such as loan amount, income, and repayment status.
- Generate summary statistics and visualizations to better understand the data.

#### 3.2 Bivariate Analysis

- Investigate relationships between pairs of variables.
- Explore correlations and dependencies that may be indicative of loan default.

#### 3.3 Segmentation Analysis

- Segment the dataset based on relevant criteria (e.g., income levels, loan amounts).
- Analyze default rates within each segment.

### 4. Data Visualization

- Create visualizations to effectively communicate key findings and insights.
- Utilize plots, charts, and graphs to represent patterns and trends.

### 5. Conclusion and Recommendations

- Summarize key insights and findings from the analysis.
- Provide recommendations for mitigating loan default risks based on the identified patterns.



## Conclusion drawn from the analysis:

* Most of the customers have taken cash loans and customers who have taken cash loans are less likely to default

## CODE_GENDER : 
* Most of the loans have been taken by females and  the default rate for females is just ~7% which is safer and lesser than males.

## NAME_TYPE_SUITE : 
* Unaccompanied people had taken most of the loans and the default rate is ~8.5% which is still okay.
 
## NAME_INCOME_TYPE : 
 * The safest segments are working, commercial associates, and pensioners.

## NAME_EDUCATION_TYPE : 
* Higher education is the safest segment to give the loan with a default rate of less than 5%
 
## NAME_FAMILY_STATUS - 
* Married people are safe to target, default rate is 8%.

## NAME_HOUSING_TYPE - 
* People having house/apartment are safe to give the loan with a default rate of ~8%

# OCCUPATION_TYPE - 
* Low-skill laborers and drivers are the highest defaulters.
* Accountants are less defaulters.
* Core staff, Managers, and Laborers are safer to target with a default rate of <= 7.5 to 10%

## ORGANIZATION_TYPE - 
* Transport type 3 highest defaulter.
* Others, Business Entity Type 3, Self Employed are good to go with a default rate of around 10 %

## =======Univariate Numeric Variables Analysis========
>> Most of the loans were given for the goods price ranging between 0 to 1 ml
>> Most of the loans were given for the credit amount of 0 to 1 ml
>> Most of the customers are paying annuity of 0 to 50 K
>> Most of the customers have income between 0 to 1 ml

## =============Bivariate Analysis==================
>> AMT_CREDIT and AMT_GOODS_PRICE are linearly correlated, if the AMT_CREDIT increases the defaulters are decreasing
>> People having income less than or equal to 1 ml, are more like to take loans out of those who are taking loans of less than 1.5 million, could turn out to be defaulters. we can target income below 1 million and loan maount greater than 1.5 million
>> People having children 1 to less than 5 are safer to give a loan
>> People who can pay the annuity of 100K are more like to get the loan and that's up to less than 2ml (safer segment)

### ============Analysis on merged data==============
 
>> For the repairing purpose customers had applied mostly prev. and the same purpose has the most number of cancelations
>> Most of the app. which were prev. either canceled or refused 80-90% of them are repayer in the current data
>> offers that were unused prev. now have the maximum number of defaulters despite having high income band customers

### Final Conclusion/Insights

* The bank should target the customers
  >> Having low income i.e. below 1 ml
  >> working in Others, Business Entity Type 3, Self Employed  org. type
  >> Working as Accountants, Core staff, Managers, and Laborers 
  >> Having a house/apartment and are married and having children not more than 5
  >> Highly educated
  >> Preferably female

  >> * Unaccompanied people can be safer -  the default rate is ~8.5%

### Amount segment recommended -
  * The credit amount should not be more than 1 ml.
  * Annuity can be made of 50K (depending on the eligibility).
  * Income bracket could be below 1 ml.
  *  80-90% of the customers who were prev. canceled/refused, are repayers. The bank can do the analysis and can consider giving loans to these segments.

# ====================precautions===============
  >> org. Transport type 3 should be avoided
  >> Low-skill laborers and drivers  should be avoided
  >> offers prev. unused and high-income customers should be avoided


