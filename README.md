:honey_pot:

Using scikit-learn's gradient boost classifier to predict an individual's risk of developing diabetes.

When making predictions there are four possible outcomes: true positives, true negatives, false positives and false negatives. Of course it is best when a model can accurately predict as many true positives and true negatives, and minimal false positives and false negatives. So should I opt for a model that minimises false positives (predicting diabetes in a healthy person) or false negatives (predicting no diabetes in a person that does have diabetes)? Here I have conducted model selection and parameter tuning (via GridSearchCV) focused on finding the minimum number of false negatives.

General description and data are available on [kaggle](https://www.kaggle.com/uciml/pima-indians-diabetes-database).
