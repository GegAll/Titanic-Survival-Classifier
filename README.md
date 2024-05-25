# Titanic-Survival-Classifier

This repository contains a machine learning project explained step by step aimed at predicting which passengers survived the Titanic disaster but mainly to show how a machine learning workflow for aclassification problem looks like. The dataset used in this project comes from the Kaggle competition: [Titanic - Machine Learning from Disaster](https://www.kaggle.com/competitions/titanic/data).

## Project Overview

This project involves creating a classification model to predict the survival of passengers on the Titanic. The model is built using various features of the passengers, such as gender, age, class, and other relevant information.

## Dataset Description

The dataset is split into two groups:

- **Training Set (`train.csv`)**: Used to build and train the machine learning models. The survival outcome (ground truth) is provided for each passenger.
- **Test Set (`test.csv`)**: Used to evaluate the performance of the model on unseen data. The survival outcome for each passenger is not provided, and the model is used to predict these outcomes.
- **Gender Submission (`gender_submission.csv`)**: An example submission file assuming that all female passengers survived.

### Features

1. `Survival`: Survival status (1 = Survived, 0 = Not Survived)
2. `Pclass`: Passenger class (1 = 1st, 2 = 2nd, 3 = 3rd)
3. `Sex`: Gender of the passenger
4. `Age`: Age of the passenger
5. `SibSp`: Number of siblings/spouses aboard the Titanic
6. `Parch`: Number of parents/children aboard the Titanic
7. `Ticket`: Ticket number
8. `Fare`: Passenger fare
9. `Cabin`: Cabin number
10. `Embarked`: Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)

### Additional Notes

- `Pclass` is a proxy for socio-economic status (SES):
  - 1st = Upper class
  - 2nd = Middle class
  - 3rd = Lower class
- `Age` can be fractional for ages less than 1. Estimated ages are in the form of `xx.5`.

## Implementation Details

The project includes the following steps:

1. **Data Preprocessing**: Handling missing values, encoding categorical variables, and feature scaling.
2. **Model Training**: Training various machine learning models to predict survival.
3. **Evaluation**: Assessing the performance of the models using metrics such as accuracy, precision, recall, and F1 score.
4. **Visualization**: Plotting the results and feature importance using heatmaps and other visual tools.

## How to Use

1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/titanic-survival-classifier.git
2. Navigate the project directory:
   ```sh
   cd titanic-survival-classifier
3. Install the required dependencies:
   ```sh
   pip install -r requirements.txt
4. Run the Jupyter notebook to train the model and generate predictions:
   ```sh
   jupyter notebook titanic_classifier.ipynb


## Repository Structure

* `titanic_classifier.ipynb`: The main Jupyter notebook containing the implementation of the classification model.
* `data/`: Directory containing the dataset files.
* `figures/`: Directory where generated plots and figures are saved.
* `requirements.txt`: List of required Python packages.

## License

This project is licensed under the MIT License. See the LICENSE file for details.

Feel free to replace `GegAll` with your actual GitHub username.

