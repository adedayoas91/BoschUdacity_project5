# Predict Customer Churn

## Project Aim: 
 **To Predict Customer Churn** of Bosch-Udacity Ai Accelerator Program (DevOps Engineer Nanodegree). 

## Description
> For this task, a pre-trained machine learning model is provided in the `churn_notebook.ipynb`. The goal is then to create a library and a test file that takes into account best software release practices.

The `churn_notebook.ipynb` is written in python version 3 (3.6 or higher should run it just fine). This can be checked and run in a iPython environment with a jupyter notebook.

## Other files and data description
File overview and data are in the root directory. All files are also included in this directory 

## Running Files
How do you run your files? What should happen when you run your files?

One easy way to run the files is by running ```python churn_library``` in the terminal. 

Running the Test file `churn_script_logging_and_tests.py` can be done using

```pytest churn_script_logging_and_tests.py```

we excetued the steps below

Collectes the different test of the churn library functions
Runs these test.
Saves the log message into ./logs/churn_library_test.log



## Clean code results

This version of our code yield the following result using pylint and autopep8 commands

```
pylint churn_library.py
....
Your code has been rated at 9.30/10
```

```
pylint churn_script_logging_and_tests.py
....
Your code has been rated at 7.77/10

