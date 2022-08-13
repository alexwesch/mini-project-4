# Mini-project IV

### [Assignment](assignment.md)

## Project/Goals
Predict whether a loan will be approved based on given parameters

## Hypothesis
Married and having dependants impoves chance of loan, because these variable are related to the age of the subject and old subjects are more likely to have assets and credit history. Check corrilations of these values
Size of loan appoved is related to size of income. Compare loans size and assests with scatterplot
Having a coapplicant improves chances of acceptence. Create categorical variable based on whether there is a coapplicant and check corrilation.


## EDA 
Assets and loan sizes are right skewed. 
Credit history was the most important factor in determining if a loan will be approved. Location was the second most important factor, with suburban being coorilated positively and rural negitively. 


## Process

### Removed rows with two or more missing variables. Removed rows missing credit history. Replaced missing variables based on values for Credit History and Location, with mean for loan ammount, median for loan term and mode for categorical variables
### Created total income feature combining Applicant and Coapplicant incomes. Created categorical value indicating if the loan application had a coapplicant. Log transformed total income and loan amount to remove skew
### Split data into x and y variables and training and test sets. Scaled x training and testing data. Used gridsearch with Logistic Regression and Random Forest Classifier to determine best model and parameters
### Selected Logistic Regression with best parameters from 

## Results/Demo
(fill in your model's performance, details about the API you created, and (optional) a link to an live demo)

## Challanges 
(discuss challenges you faced in the project)

## Future Goals
(what would you do if you had more time? are there any potential issues/biases with your model/use case?)