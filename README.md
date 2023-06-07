# Lending Club Case Study

## Goals of data analysis:  

``` 
Lending loans to ‘risky’ applicants is the largest source of financial loss
(called credit loss). The credit loss is the amount of money lost by the lender 
when the borrower refusesto pay or runs away with the money owed.  

The main objective is to be able to identify these risky loan applicants, 
then such loans can be reduced thereby cutting down the amount of credit loss. 
Identification of such applicants using EDA is the aim of this case study.   

Perform an analysis to understand the driving factors (or driver variables)
behind loan default, i.e.the variables which are strong indicators of default.  
The company can utilise this knowledge for its portfolio and risk assessment. 

```

### Step 1: Data Cleaning 1  

#### a) Considered the loan status, which are Fully paid and Charged Off.
#### b) Deleted all the columns which contains empty values or NA.
#### c) Removed the rows which contains empty cells.
#### d) For the better analysis grouped the emp_length 10+ Years to 10 & <1 Year to 1
#### e) Created two new columns ‘Year’, ‘Month’ from ‘issue_d’ date column.
#### f) Columns 'emp_length', 'int_rate’ habing data type as Object, type casted to numeric.
#### g)Used Sort function to sort the column ‘Grade’ for the better view.


### Step 2: Univariate Analysis
#### a) Count & percentage of Loan status between FullyPaid vs ChargedOff
#### b) Count of Customers experience
#### c) Category wise distributio of loans
#### d) House ownership of customers
#### e) Loans Issued in each year
#### f) Purpose of loan consideration
#### g) Distribution of loans across various grades

### Step 3: Bivaraiate/Multivariate Analysis
#### a) Differentiaion of Interest rates for each grade
#### b) comparion of fully paid & charged off between employee length and verification status
#### c) No. of Loans issued in each year and a month
#### f) Heatmap view

### Step 5: Results   


### Contributors
- Sai Krishna Somisetty
- Mrityunjaya Shukla







##### Developed as part of the Exloratory Data Analysis Module required for Post Graduate Diploma in Machine Learning and AI - IIIT,Bangalore.
