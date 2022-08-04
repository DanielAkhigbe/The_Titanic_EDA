# The_Titanic_EDA
### Exploratory Data Analysis on the Titanic Dataset

### Summary
The Titanic ship, which met an unfortunate tragedy in 1912, is known as one of the most infamous shipwrecks in history.
The details of a subset of the passengers on board (891 to be exact) were used to create a Dataset for Exploratory Data Analysis and to build a Machine Learning model
that could find some correlation between the features/columns of the Dataset and the model could be used to predict the survival of other passengers that could have
been on board the ship.

### Dataset Origin
The Dataset was gotten from kaggle.com

### Workflow
EDA was carried out on the Dataset using Jupyter Notebooks.

A few Machine Learning models were created and evaluated to pick the best model amongst them.
These models were created based on hyperparameter tuning.
The sklearn module was used in the model creation, evaluation and selection.
Logistic Regression was used as the benchmark model and the Random Forest ensemble method was further applied.

The models were split into Train, Validation and Test sets and GridSearchCv was used to evaluate the models' performance.

The Random Forest model produced favourable results with a high accuracy and precision scores and the full details can be explored in the Jupyter Notebooks.
