# Bank Account Fraud

------------------

## Description

In a large consumer bank, individuals can apply online for a bank account opening and, if granted, benefit from the banking services. Leveraging this system, fraudsters attempt to gain access to such services by identity theft or by creating a fictional individual. Once access to a new bank account is granted, the fraudster quickly takes advantage of the accompanying line of credit or uses the account to receive illicit payments. In this scenario, where the fraudster succeeds, the bank sustains all costs as there is no way of tracing the fraudster's true identity.

Using a dataset gathered from online bank account opening applications, the goal of this practical assignment is to provide informed and well-documented advice on which predictive modelling solution to use to detect fraudulent applications accurately.

Each instance (row) of the dataset represents an application described by 32 features. The label of each instance is stored in the"is\_fraud" target variable. A full description of the features that compose the dataset is available [here](./datasets/datasheet.pdf).  
  
## Tasks

Using the [train.csv](./datasets/train.csv) data set, you have a set of main tasks to accomplish as described next. Still, you are free to include other tasks to increase the value of your assignment.
  
### Task 1: Data Understanding and Preparation and Descriptive Analytics

This task involves summarizing and visualizing the data to provide valuable insights. Consider questions that could be interesting to check with the available data and provide answers using textual summaries or data visualization. Based on this analysis, you should also check if it is necessary to carry out any data clean-up and pre-processing steps. Additionally, you can apply clustering techniques if you find them helpful to provide valuable insights.

### Task 2: Predictive Modelling

From the available data, you should define the data set used for the classification task at hand. Different models should be considered, and the choice of the final model should be justified.

### Task 3: Kaggle Competition

Additionally, you should submit your solution for the [test.csv](./datasets/test.csv) data set to the [Kaggle Competition](https://www.kaggle.com/competitions/fraud-detection-cc4036-2223).

Note that the goal is not to overfit the test set data to achieve a good position in the public leaderboard. Your rank position in the private leaderboard will be accounted for in the final grade.  

## Tools

You can use R or Python. You can find material for dynamic reporting in R with markdown if you choose to use R. You can use the Colab Research Notebooks or Jupyter Notebooks if you decide to use Python.

## Deliverables

The practical assignment is mandatory, should be performed individually, and submitted on moodle with a compressed file containing the following items:

* slides for presentation (PDF format) focusing on the main issues of the project for a 10 minutes presentation; any additional information that cannot be presented in the 10 min slot can be included as annexes to the presentation;  

* the source of two ready-to-execute dynamic reports or notebooks with all the code necessary to reproduce the results you present for i) Task 1; and ii) Task 2, including the solution submitted to Kaggle - Task 3, i.e. it should be possible to replicate your predictions; any complementary files needed to execute your report (e.g. data files, data objects) should be submitted as well.

## Deadline

June 12st, 2023, 23:59

## Presentation Guidelines

* problem definition (1 slide)
* data understanding:  concise summary, focusing on the main findings (2 slides)
* data preparation: outline, focusing on the main operations  (2 slides)
* predictive modelling with experimental results (2 slides)
* conclusions, limitations and future work (1 slide)
* annexes

TOTAL: max 40 slides

## Grading

The grading of the practical assignment is distributed as follows:
  
* Task 1 (25%)
* Task 2 (25%)
* Task 3 (10%)
* Originality (15%)
* Presentation (25%) - **mandatory**

------------------

## Deliver

- Best submission in Kaggle: 0.84635
- Grade: 15

### Developer

* Name: André Miguel Faria da Silva
* N_mec: up201906559
* Site: <https://asilva.luxcorp.pt>
* Github: <https://github.com/user/mastersilvapt>
* Kaggle: <https://www.kaggle.com/mastersilvapt>

### Report

* [First Part Report](R/reportPart1.pdf)
* [Final Report](Python/report.ipynb)
* [Slides](presentation/slides.pdf)

### Stucture

* [correlation](correlations/) folder contains csv for feature to feature and feauture to target correlation values
* [datasets](datasets/) folder contains 2 csv, [Train](datasets/train.csv) dataset and [Test](datasets/test.csv) dataset
* [model](model/) folder contains information and parameters on the models
* [plots](plots/) folder contains features distribution separated in Non Fraud and Fraud
* [predictions](predictions/) folder contains the automatically saved predictions when a model was runned
* [Python](Python/) folder contains all the python code
* [R](R/) folder contains all the R code
