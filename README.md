# *Student Grade Prediction*
We have performed a set of regression and classification tasks on the dataset to predict the grades of students in secondary school subjects based on a number of academic and demographic factors.

## Problem Statement
The *__Student Grade Prediction__* project uses Machine learning algorithms to perform classification and regression tasks on student grades, other socio-economic factors and predict student performance in cumulative assessments. This can be used to perform a detailed analysis of student performance and based on the results of the analysis, appropriate steps can be taken to improve the odds around ensuring better perfomance of students in academics.

## About Dataset
The dataset contains student details. The data attributes include student grades, demographic, social and school related features) and it was collected by using school reports and questionnaires. Two datasets are merged containing the performance in two distinct subjects: Mathematics (mat) and Portuguese language (por). The two datasets were modelled under binary/five-level classification and regression tasks. 
The dataset contains the following features:

#### Features Information:

- school - student's school (binary: 'GP' - Gabriel Pereira or 'MS' - Mousinho da Silveira)
- sex - student's sex (binary: 'F' - female or 'M' - male)
- age - student's age (numeric: from 15 to 22)
- address - student's home address type (binary: 'U' - urban or 'R' - rural)
- famsize - family size (binary: 'LE3' - less or equal to 3 or 'GT3' - greater than 3)
- Pstatus - parent's cohabitation status (binary: 'T' - living together or 'A' - apart)
- Medu - mother's education (numeric: 0 - none, 1 - primary education (4th grade), 2 - 5th to 9th grade, 3 - secondary education or 4 - higher education)
- Fedu - father's education (numeric: 0 - none, 1 - primary education (4th grade), 2 - 5th to 9th grade, 3 - secondary education or 4 - higher education)
- Mjob - mother's job (nominal: 'teacher', 'health' care related, civil 'services' (e.g. administrative or police), 'at_home' or 'other')
- Fjob - father's job (nominal: 'teacher', 'health' care related, civil 'services' (e.g. administrative or police), 'at_home' or 'other')
- reason - reason to choose this school (nominal: close to 'home', school 'reputation', 'course' preference or 'other')
- guardian - student's guardian (nominal: 'mother', 'father' or 'other')
- traveltime - home to school travel time (numeric: 1 - 1 hour)
- studytime - weekly study time (numeric: 1 - 10 hours)
- failures - number of past class failures (numeric: n if 1<=n<3, else 4)
- schoolsup - extra educational support (binary: yes or no)
- famsup - family educational support (binary: yes or no)
- paid - extra paid classes within the course subject (Math or Portuguese) (binary: yes or no)
- activities - extra-curricular activities (binary: yes or no)
- nursery - attended nursery school (binary: yes or no)
- higher - wants to take higher education (binary: yes or no)
- internet - Internet access at home (binary: yes or no)
- famrel - quality of family relationships (numeric: from 1 - very bad to 5 - excellent)
- freetime - free time after school (numeric: from 1 - very low to 5 - very high)
- goout - going out with friends (numeric: from 1 - very low to 5 - very high)
- Dalc - workday alcohol consumption (numeric: from 1 - very low to 5 - very high)
- Walc - weekend alcohol consumption (numeric: from 1 - very low to 5 - very high)
- health - current health status (numeric: from 1 - very bad to 5 - very good)
- absences - number of school absences (numeric: from 0 to 93) these grades are related with the course subject, Math or Portuguese:
G1 - first subject grade (numeric: from 0 to 20)
G2 - second subject grade (numeric: from 0 to 20)

#### Target Information:
G3 - final grade (numeric: from 0 to 20, output target) 

Source of Dataset: *__Kaggle__*

## Tools Used
* Google Colab
* Jupyter Notebooks

## Libraries Used
* Matplotlib
* Seaborn
* Sk-learn
* Numpy

## About Algorithms
## *Linear Regression*
Linear regression is a linear approach to modelling the relationship between a scalar response and one or more explanatory variables (also known as dependent and independent variables). Linear regression is performed upon the data. It is used to predict the cumulative grade of the students when the input features are provided along with the progress of the students.

## *Logistic Regression*
Logistic regression is a statistical model that in its basic form uses a logistic function to model a binary dependent variable, although many more complex extensions exist. In regression analysis, logistic regression (or logit regression) is estimating the parameters of a logistic model (a form of binary regression).
Logistic regression is used to perform classification tasks upon the student dataset.

## *Decision Tree Regression*
Decision tree builds regression or classification models in the form of a tree structure. It breaks down a dataset into smaller and smaller subsets while at the same time an associated decision tree is incrementally developed. The final result is a tree with decision nodes and leaf nodes.
It is used to predict the cumulative grade of the students when the input features are provided along with the progress of the students. It is used to improvise upon the previous algorithms.



