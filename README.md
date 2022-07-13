# Finding-Donors-For-CharityML

This goal of the project is to help a ficticious charity organization, called CharityML find people who are likely to donate. CharityML is then supposed to send emails to the people whose annual income is predicted to be more than 50K USD.

This project is part of Udacity's Machine Learning Cross-Skilling Nanodegree track sponsored by ITIDA.

## Tools Used:
- Python 3.7.11
- Jupyter Notebooks with VSCode
- Scikit-Learn
- NumPy
- Pandas
- Matplotlib

## Dataset
`census.csv`, contains demographic data about the potential donors.

## The Summary of the Process
- The project strats with preliminary wrangling, including data exploration an transformations such as one-hot encoding, normalization, ...etc.
- Next, three ML models were chosen, namely *Decision Tree*, *Support Vector Machine*, and *AdaBoost (with Decision Trees)*.
- After that, a training–prediction pipeline was built to help training and testing the three models.
- The *AdaBoost* Classifier model was chosen for tuning and improving due to its outstanding performance in terms of accuracy, F-score, and even the training time.

## Key results
The performance of the final model on testing data:
- Accuracy: 0.8375
- F-score: 0.6889

## How to View the Results
Open the [finding_donors.ipynb](https://github.com/Moaaz-Mahmoud/Finding-Donors-For-CharityML/blob/master/finding_donors.ipynb) on GitHub.
