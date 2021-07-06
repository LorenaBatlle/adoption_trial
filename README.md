## Introduction

This project has the purpose of showing some of my hard and communication skills. It gives a big picture about how I achieve some insights; it is not looking for the best performance or a complete project process.


## Main problem goal

The main goal is to extract insights and predict if a user would become a paying customer or not at the end of a trial.

## Context

There is an app which offers a monthly subscription with one week trial period, at the end of which, the customer starts paying the subscription, unless they cancel.

The journey starts with installing the app on a user's device. When a user launches the app for the first time he needs to complete the onboarding info. Right after, a paywall is shown. This is where the app gives the chance to start a subscription with the mentioned 7 days trial period. After 7 days - and if they don’t cancel their subscription - they become paying customers and an invoice is recorded in the system.

The company is interested in knowing if a user would potentially convert into a customer after trial ends. Besides, knowing it as soon as possible in the trial period gives them some advantage to take other actions.


## Data provided

Users who started trial during December 2020.


## Project structure
The project has 3 main files numbered from 1 to 3; I recommend that order to read it. 

1-Generate_dataset: in this file I generate the dataset from two tables with the data (it is not in the project because of privacy reasons). Contains data analysis, some feature engineering and dummy transformations.
2-Decision_tree: in this file I generate a basic decision tree in order to:
  - validate the data, check if the main features could have future information.
  - get insights, considering a simple structure.
  - obtain a roc benchmark.
3-Train: in this file I train a potential model, as I said, not aiming for the best performance.

Finally, there is one more file with some common functions for general usage.

## Project dependencies
- python 3.0
- pandas
- sklearn
- numpy
- graphviz
- matplotlib
- xgboost
