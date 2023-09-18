[![Install](https://github.com/nogibjj/HugoHu-Project-1/actions/workflows/install.yml/badge.svg)](https://github.com/nogibjj/HugoHu-Project-1/actions/workflows/install.yml)

[![Lint](https://github.com/nogibjj/HugoHu-Project-1/actions/workflows/lint.yml/badge.svg)](https://github.com/nogibjj/HugoHu-Project-1/actions/workflows/lint.yml)

[![Format](https://github.com/nogibjj/HugoHu-Project-1/actions/workflows/format.yml/badge.svg)](https://github.com/nogibjj/HugoHu-Project-1/actions/workflows/format.yml)

[![Test](https://github.com/nogibjj/HugoHu-Project-1/actions/workflows/test.yml/badge.svg)](https://github.com/nogibjj/HugoHu-Project-1/actions/workflows/test.yml)

## Project #1: Continuous Integration using GitHub Actions of Python Data Science Project

> © Yadong (Hugo) Hu 2023
> 
> This project was generated by this [Awesome Template](https://github.com/0HugoHu/IDS706-Python-Template)

<br />

**Duke IDS706 Individual Project 1 Requirements:**

The project structure must include the following files:
- Jupyter Notebook with:
  - Cells that perform descriptive statistics using Polars or Panda.
  - Tested by using nbval plugin for pytest
- Python Script performing the same descriptive statistics using Polars or Panda
- A lib.py file that shares the common code between the script and notebook
- Makefile with the following:
  - Run all tests (must test notebook and script and lib)
  - Formats code with Python black
  - Lints code with Ruff
  - Installs code via:  pip install -r requirements.txt
- A test_script.py to test script
- A test_lib.py to test library
- Pinned requirements.txt
- GitHub Actions performs all four Makefile commands with badges for each one in the README.md

<br />


## Project Description
This project uses ```Pandas``` library to read from a csv dataset and perform descriptive statistics on the dataset. 

It then uses ```matplotlib``` to plot the data and ```seaborn``` to visualize the data.

The data set has been taken from glassdoor and focuses on income for various job titles based on gender. As there have been many studies showcasing that women are paid less than men for the same job titles, this data set will be helpful in identifying the depth of the gender-based pay gap. The features of the data set are:
- Job Title
- Gender
- Age
- PerfEval
- Education
- Dept
- Seniority
- Base Pay
- Bonus

**The objective of this project is to analysis the influence of gender on the average base pay.**

<br />

## Demo

This section is included in ```Hugo-Project-1.ipynb```

### Pandas Descriptive Statistics
![](/.tutorial/demo1.png)

### Female Base Pay Distribution
![](/.tutorial/demo3.png)

### Male Base Pay Distribution
![](/.tutorial/demo2.png)

### Base Pay Difference on Gender
![](/.tutorial/demo4.png)

<br />

## Run

### Some Makefile Commands
```commandline
make clean
make install
make format
make lint
make test
make run
```
