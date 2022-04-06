# Lending-Club-Case-Study

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)


## General Information

- Background of the Project 

This project is about Consumer finance company which specialises in lending various types of loans to urban customers. When the company receives a loan application, the company has to make a decision for loan approval based on the applicant’s profile.

This company is the largest online loan marketplace, facilitating personal loans, business loans, and financing of medical procedures. Borrowers can easily access lower interest rate loans through a fast online interface. 

- What is the business probem that your project is trying to solve?

The aim is to identify patterns which indicate if a person is likely to default, which may be used for taking actions such as denying the loan, reducing the amount of loan, lending (to risky applicants) at a higher interest rate, etc.

- What is the dataset that is being used?

The data given below contains the information about past loan applicants and whether they ‘defaulted’ or not. how consumer attributes and loan attributes influence the tendency of default.

## Technologies Used
Approch :
Data Cleanning
Data Understanding
Data transformation
Univariate Analysis
Bivariate Analysis

Technogies : Python ( Juypyter Notebook ) and its libraries : NumPy, pandas, Matplotlib, seaborn etc., Git/GitHub, Microsoft office.

## Conclusions
#### 1.So for us only important factors are Fully paid and charged off for comparison
#### Fully paid : 83%
##### Charged off : 14.2%

#### It is clear that as sub grade decreases, then the chances of loan getting charged off increases. 
#### Lending club should examine more information from borrowers before issuing loans to Low grade (G to A)

##### This endorses the previous assumption for home ownership, that having loan adds to liability, which the user with higher int rate doesn't able to pay his loan back and does gets Charged OFF

#### Only for 0 experience the charged off percentage is more than 20, for the rest it is increasing slowly with experience (maybe as less experience people are bachelors thus less responsibility, and more experience are with family)

#### Lending club should reduce the high interest loans for 60 months tenure, they are prone to loan default

#### Charged off tends to increase when dti increases

#### lower the enquires higher are the chances of payment

#### For revol_acc > 8515 i.e. the median, the charged off is higher by 5%

#### Clearly shows that having total_acc between 0 and 20, increases the chances of Charged Off

