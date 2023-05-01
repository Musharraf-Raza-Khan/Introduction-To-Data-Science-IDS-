## ASSIGNMENT NO 1

## MUSHARRAF RAZA KHAN | 52024

**DO NOT COPY**

/--------------------------------\

### Question # 01

Write a Python function called `proportion_of_education` that calculates the proportion of children in the dataset who had a mother with different levels of education. The function should take no arguments and should return a dictionary containing the proportions in the form of:

```
{"less than high school":0.2,
"high school":0.4,
"more than high school but not college":0.2,
"college":0.2}
```
## Skills Needed & Knowledge Required
To solve this task, you will need to have a basic understanding of the following:
- Python programming language
- Data manipulation and analysis using pandas library
- Basic statistical analysis and calculation of proportions

Specifically, you should know how to:
- Load a dataset using pandas
- Subset data based on specific conditions
- Perform basic data manipulation tasks such as filtering and aggregation
- Calculate proportions using basic arithmetic operations and/or pandas functions
- Create a dictionary in Python

## Explaination of the statement

The task requires writing a Python function called `proportion_of_education` that reads in a dataset containing information about children's health and their mothers' education levels. The function should calculate the proportion of children in the dataset who had a mother with different levels of education and return a dictionary containing the proportions for each level of education.

The function should take no arguments and should read the dataset from a file or URL. The dataset contains information about children's health, including whether or not they had chickenpox, the number of chickenpox vaccine doses they received, and whether or not they were breastfed as infants. Additionally, the dataset includes information about the mothers' education levels, categorized as "less than high school," "high school," "more than high school but not college," and "college."

To solve this task, the function needs to count the number of children in each education level and calculate the proportion of children for each level. The function should then return a dictionary containing the proportions for each education level, with the education level as the key and the proportion as the value.

For example, the returned dictionary should be in the form:
```
{"less than high school":0.2,
"high school":0.4,
"more than high school but not college":0.2,
"college":0.2}
```
This means that 20% of children in the dataset had a mother with less than a high school education, 40% had a mother with a high school education, 20% had a mother with more than a high school but not college education, and 20% had a mother with a college education.

/--------------------------------\

### Question  # 02

Explore the relationship between being fed breastmilk as a child and getting a seasonal influenza vaccine from a healthcare provider. Write a function that returns a tuple of the average number of influenza vaccines for those children who received breastmilk as a child and those who did not, in the form:

```
(2.5, 0.1)
```
## Skills Needed & Knowledge Required 

To solve this question, you will need the following skills and knowledge:

- Basic understanding of Python programming language
- Familiarity with data analysis and manipulation using pandas library in Python
- Ability to read and understand a dataset in CSV format
- Understanding of basic statistical concepts such as mean and correlation
- Ability to write functions in Python
- Ability to extract and filter data from a pandas DataFrame based on certain conditions

You will also need access to the given dataset and knowledge on how to load it into a pandas DataFrame in Python.

## Explaination of the statement

The task is to analyze the relationship between receiving breastmilk as a child and getting a seasonal influenza vaccine from a healthcare provider, and return the average number of influenza vaccines for children who received breastmilk and those who did not. 

The expected output is a tuple of two numbers: the first number represents the average number of influenza vaccines for children who received breastmilk, and the second number represents the average number of influenza vaccines for children who did not receive breastmilk. 

For example, the output (2.5, 0.1) means that on average, children who received breastmilk as a child had 2.5 influenza vaccines from a healthcare provider, while children who did not receive breastmilk had only 0.1 influenza vaccine from a healthcare provider.

/--------------------------------\


### Question # 03

Investigate if there is a link between vaccine effectiveness and sex of the child by calculating the ratio of the number of children who contracted chickenpox but were vaccinated against it (at least one varicella dose) versus those who were vaccinated but did not contract chickenpox. The function should return a dictionary containing the results by sex in the form:

```
{"male":0.2,
"female":0.4}
```
## Explaination of the statement
This task involves analyzing a dataset to investigate if there is any correlation between vaccine effectiveness and the sex of the child. The function `chickenpox_by_sex()` should be implemented to calculate the ratio of the number of children who contracted chickenpox despite being vaccinated (at least one varicella dose) versus those who were vaccinated but did not contract chickenpox, and return the results by sex. 

The function should return a dictionary containing the results by sex in the form {"male":0.2, "female":0.4}. This means that for example, if the ratio of male children who contracted chickenpox despite being vaccinated is 0.2, and the ratio of female children who contracted chickenpox despite being vaccinated is 0.4, the function should return a dictionary {"male":0.2, "female":0.4}. 

To complete this task, one should have knowledge of Python programming language, data manipulation, and basic statistical analysis. Familiarity with Pandas library is also necessary to read and manipulate the dataset. Additionally, knowledge of statistical concepts such as correlation, ratios, and probability is essential to interpret and analyze the results obtained.


## Skills Needed & Knowledge Required
To solve this problem, the following skills and knowledge are required:
- Basic understanding of Python programming language
- Knowledge of data manipulation using pandas library in Python
- Knowledge of basic statistical concepts such as correlation, p-value, and ratio
- Familiarity with data analysis and data visualization using Python
- Understanding of dictionary data structure in Python

/--------------------------------\

### Question # 04

Determine if there is a correlation between having had the chickenpox and the number of chickenpox vaccine doses given (varicella). The function should return the correlation coefficient and p-value in the form of a tuple. Interpretation of the correlation coefficient and p-value is also provided in the question description.

## Skills Needed & Knowledge Required
- To complete this task, one would need a good understanding of statistical concepts such as correlation and p-values, as well as knowledge of Python programming language and data analysis libraries such as pandas and numpy. Additionally, knowledge of statistical analysis tools such as scipy and statsmodels would also be helpful.

## Explaination of the statement
The task is to write a Python function that analyzes the relationship between having had the chickenpox and the number of chickenpox vaccine doses given (varicella). The function should return the correlation coefficient and p-value in the form of a tuple.

The correlation coefficient measures the strength and direction of the relationship between two variables, with a value between -1 and 1. A positive correlation coefficient indicates a positive relationship, meaning that as one variable increases, the other also tends to increase. A negative correlation coefficient indicates a negative relationship, meaning that as one variable increases, the other tends to decrease. A correlation coefficient of 0 indicates no relationship between the two variables.

The p-value is the probability of observing a correlation coefficient as extreme or more extreme than the one calculated, assuming that there is no true correlation between the variables in the population. A small p-value (typically less than 0.05) indicates that the correlation is statistically significant, meaning that the observed relationship between the variables is unlikely to be due to chance.

**THE END**

/--------------------------------\



















