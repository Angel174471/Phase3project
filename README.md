# Phase 3 project


# Chicago Car Crash Data Analysis

![img](images/chicago cars 2.jpeg)

## Overview
This project focuses on analyzing [Chicago car crash data](https://data.cityofchicago.org/Transportation/Traffic-Crashes-Crashes/85ca-t3if) collected from 2015 to 2023 with the goal of enhancing vehicle safety and reducing traffic accidents. The analysis involves cleaning the data, converting it to numerical format, and employing various machine learning models for classification.

## Data
I utilized three datasets, [Passengers](https://data.cityofchicago.org/Transportation/Traffic-Crashes-People/u6pd-qa9d), [Vehicles](https://data.cityofchicago.org/Transportation/Traffic-Crashes-Vehicles/68nd-jvt3), and [Crashes](https://data.cityofchicago.org/Transportation/Traffic-Crashes-Crashes/85ca-t3if) containing information about car crashes, including details like primary contributors, weather conditions, road defects, and more. The data was preprocessed and transformed into a numerical format to facilitate machine learning.

## Modeling
I adopted an iterative modeling approach, beginning with a baseline model and progressively building more complex models. The following models were considered:
- Logistic Regression
- Decision Trees
- K-Nearest Neighbors
- Naive Bayes
- Bagged Trees

These models were iteratively improved based on prior model results, and each change was justified in the context of the problem. Evaluation metrics, including precision, recall, and F1-score, were used to gauge model performance. 

## Model Selection
After thorough evaluation, the Naive Bayes Model was chosen as the final model for predicting primary contributors to car crashes. This decision was based on its strong recall performance, which is crucial for real-world implications.

## Evaluation
The chosen model was evaluated using holdout test data and appropriate metrics. The evaluation not only considered metrics but also the real-world consequences of errors, making it suitable for solving the business problem. Further real-world testing is recommended to validate its effectiveness.

## Recommendations
Based on my analysis, I recommend focusing on addressing primary contributors to car crashes, particularly driver error. Safety equipment and traffic control devices should be promoted and maintained to reduce accidents. Attention to road defects is also vital for road safety.

## Conclusion
This project presents a data-driven approach to enhancing road safety by identifying primary contributors to car crashes. The selected Naive Bayes Model demonstrates promise, but real-world testing and continued monitoring are crucial for the stakeholders' goal of reducing traffic accidents.

Please note that further details and code can be found in the Jupyter notebooks provided in this repository.

