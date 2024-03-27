# Decision Tree Classification with Diabetes Dataset (CART)

This Python script applies decision tree classification model on the Diabetes dataset and performs various analyses and evaluations.

## Usage

1. First, install the necessary libraries for this code to run:


pip install pydotplus
pip install skompiler
pip install astor
pip install joblib

2. Create a data file named "diabetes.csv" in the same directory as the code and provide its contents.

3. Run the code. The code has been commented to explain each step sequentially and display the results.
4. . Examine the outputs of the code. These outputs include model performance, feature importances, decision tree visualization, and other analysis results.

## Requirements

This code requires Python 3 and the necessary libraries to be installed. Required libraries are specified in the "requirements.txt" file.

## Notes

- Default hyperparameters are used for the decision tree model. GridSearchCV can be used to optimize hyperparameters if desired.
- This script uses the holdout method to split the dataset into training and test sets. Cross-validation can be used for more advanced evaluation.

## License

This code is free to use, modify, and distribute. See the LICENSE file for licensing information.
