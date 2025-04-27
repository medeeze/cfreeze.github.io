# cfreeze.github.io

Personal portfolio containing data science projects.

# [Project: Kaggle Home Credit Default Risk](https://github.com/medeeze/Kaggle_Home_Project)

Home Credit would like to provide customers with the ability to request loans despite 
having a lack of credit history. Without credit history, it is difficult to predict the likeliness 
of a given customer to pay off their debt which is a risk lenders usually avoid.

Creating a model that can accurately predict a customer’s likeliness of credit default. Trained a model using historical customer data given by Home Credit. This will be a supervised classification model that determines the probability of the target variable: credit default. Through the combination of calculating the significance of one variable and the relationship between multiple variables, a test set can be created to provide a probability of the target variable happening.

## Main Segments of the Project
* Prepare and clean datasets to improve model performance
* Analyze the relationships between the variables of multiple datasets with the target variable: credit default
* Train and test multiple methods through random forest, naive bayes, and logistic regression

## Personal Contribution To The Final Output
* Random forest model
* Logistic base model
* Code organization and comments
* Model results summaries

## Challenges Encountered
* Strategizing how to combine multiple datasets to create the highest performing model
* Effectively data cleaning datasets used for modeling
* Finding a way to take multiple approaches to modeling that are not as familiar such as: naive bayes and random forest

## Solution and Value
Our analysis found that certain demographic variables provide strong signals of default risk. We recommend leveraging these features in the model, while taking care to follow fair lending practices and assess for bias. In addition, we suggest using demographic insights to support customer segmentation, targeted interventions, and ongoing model monitoring. Since we found that demographics can help us predict loan default, we have to be aware of not using this information to become bias or discriminate against certain groups of people. 

The value of these models and solutions is to help Home Credit consitently classify customers who have a high risk of credit default. Finding the likeliness of a given customer to default will increase profit margin and decrease the occurance of losses.
These loan applicants often have limited information available. This supports the importance of creating a model that analyzes the relationship between the given variables and default. 

## Insights
While having a tool that can determine the likeliness of a customer default is very helpful, it is not something that can be relied on for every applicant. There are many scenarios where loan applicants will have very limited background information, credit history, or other variables that are not included in the dataset. Personal experience, knowledge, and judgment will continue to be important factors toward making the final decision the risk for a given customer.
