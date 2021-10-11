# IT-Salary-Europe-2020
The IT Salary Survey Europe has been taken from Kaggle and EDA has been performed on this dataset to get valuable insight from the data about the salary features in Europe for the year 2020 and find out insights on the relation amongst the features. This led to useful insights on salary, relation between gender and roles, relation between cities and salary and other dependencies between other features that help us get an overview of the corporate worker salaries and the various factors that influence it.

Exploratory Data Analysis has been performed on the dataset. Too many cleanings had to be performed for the dataset as it contained many missing, invalid datatypes and NULL values. After removing all the NaN values and correcting the data types, the correlation matrix of the dataset was calculated and strong correlation has been found between the features:
1. Age and Total Years of Experience

and Very Strong Correlation between the features:
1. 'Yearly bonus + stocks in EUR' and 'Annual brutto salary (without bonus and stocks) one year ago. Only answer if staying in the same country'.
2. 'Yearly bonus + stocks in EUR' and 'Annual bonus+stocks one year ago. Only answer if staying in same country'.
3.  'Annual bonus+stocks one year ago. Only answer if staying in same country' and 'Annual brutto salary (without bonus and stocks) one year ago. Only answer if staying in the same country'.

Again, Chi-Square Testing for Independency was performed on -
1. Gender & Position: Dependent on each other.
2. Gender & Seniority Level: Dependent on each other.
3. City & Yearly Bonus + Stocks in EUR: Dependent on each other.
4. Company Size & Covid 19 Reception in EUR: Dependent on each other.
5. Employment status & Main coding language: Dependent on each other.

Fom these findings it was concluded that in Europe, Gender bias may exist due to dependency found from Hypothesis testing by Chi-Square approach and depending on which city we live, our salaries will be determined. And during the times of COVID-19, the recession was directly proportional to the company size and our employment status is also defined by our coding language skills. 

Further work on finding more specific details including the coding languages and which cities provide higher salaries are to be worked upon.
Thank you for reading so far!
